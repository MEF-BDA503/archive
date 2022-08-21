
# Student and Group Work

You can access code and reports of students and project groups from their **Progress Journals**.

- [Progress Journals](pj21_list)


# Course Essentials

- [Projects](projects)
- [Project Guidelines](project_guidelines)

# Week 7 (Dec 15, 2021)

**Guest Lecture** [Tamer Emre](https://www.linkedin.com/in/tamer-emre/) Director of Market Operations at [EPİAŞ/EXIST](https://epias.com.tr/)

Presentations!

# Week 6 (Dec 1, 2021)

- [reticulate Lecture Notes](reticulate_notes)
- [reticulate Official Page](https://rstudio.github.io/reticulate)
- [golem Official Page](https://thinkr-open.github.io/golem/)
- [Docker Official Page](https://www.docker.com/)
  - [Docker 101](https://www.docker.com/101-tutorial)

# Week 5 (Nov 17, 2021)

**Guest Lecture** [Ecem Korkmaz Gelal](https://www.linkedin.com/in/ecemkorkmaz/) Co-Founder & CEO at [TalentGrid](https://talentgrid.io/)

- [rvest Mini Tutorial](https://boun-ie48a.github.io/files/rvest_mini_tutorial.html)

  - Voluntary Exercise: Try the exercises at the end of the rvest mini tutorial.

- [Joins tutorial](https://stat545.com/join-cheatsheet.html)
  - [Mini live lecture](https://boun-ie48a.github.io/files/joins_tutorial_live_lecture.html)
- [Mini tutorial on pivot longer/wider](https://boun-ie48a.github.io/files/short_tutorial_on_pivot_wider_longer.html)
- Voluntary Exercise data: ATP World Tour 2017 Tennis data ([RData](https://mef-bda503.github.io/archive/fall20/files/atp_tennis_data_2017.RData/atp_tennis_data_2017.RData)) ([Source](https://github.com/serve-and-volley/atp-world-tour-tennis-data/)) ([Example analysis](https://pjournal.github.io/mef03-karaahmetlid/ATP2017.html))
  - Voluntary exercise ([see the desired outputs on dummy data](https://boun-ie48a.github.io/files/tennis_exercise_output.png))
    1. Create a matrix (or data frame) of "top 20" (top winners by quantity) players with the number matches among themselves as the value. Plot a heatmap of this matrix.
    2. Create a matrix (or data frame) of top 20 players with win percentages (rows are winners).
    3. Do the same for top 5 countries.

# Week 4 (Nov 3, 2021)

Guest lecture by [Kemal Davaslıoğlu](https://www.linkedin.com/in/kdavasli/), Senior Research Scientist at [Intelligent Automation](https://www.i-a-i.com/).

- This week we will learn about `shiny` to create interactive dashboards on web browsers ([official tutorial](https://shiny.rstudio.com/tutorial/)). Also see the [Shiny Cheatsheet](https://shiny.rstudio.com/images/shiny-cheatsheet.pdf) from RStudio. (Bonus: Check <https://shinyapps.io> to deploy your shiny apps)
  - [Extra tutorial on R Shiny (Turkish)](https://acikenerji.github.io/R-shiny/)
  - [Mastering Shiny](https://mastering-shiny.org/)
  - [How to deploy to shinyapps.io](https://shiny.rstudio.com/articles/shinyapps.html)
- Shiny in-class exercise [starter code](https://gist.github.com/berkorbay/5793188b7ebfe013ce64703179f9aa01).
- Example run code from a Shiny application `shiny::runGitHub("BOUN-IE48A/boun-ie48a.github.io",subdir="files/shinyExample/")`
- Bonus: You may look at [shinydashboard](https://rstudio.github.io/shinydashboard/) for dashboard web apps.
- Bonus: You may look at [shinyMobile](https://rinterface.github.io/shinyMobile/) for mobile optimized web apps.

**Group Assignment (Deadline Nov 17, 18:30)**

Create a Shiny app using the Izmir's Fish Market data (see previous week's in-class example). Use your imagination but keep it simple enough. Upload it to shinyapps.io and give a link from your Group Progress Journal.

# Week 3 (Oct 20, 2021)

Guest lecture by [Gizem Gür](https://www.linkedin.com/in/gizemgur/), Co-Founder & Senior System Architect of [Sufle](https://www.sufle.io/).

- [Introduction to ggplot2](https://pjournal.github.io/files/ggplot2_renewable.html)
  - Extra Material: [Introduction to ggplot2 with election data](https://pjournal.github.io/files/ggplot2_elections.html)
  - Extra Material: [Introduction to ggplot2 with weather data](https://mef-bda503.github.io/archive/fall18/files/ggplot2_lecture.html)

**In-Class Exercise (Bonus)** (Due Date: ~~Oct 20~~ postponed to Oct 25, 2021 21:30) This exercise will provide up to 5% bonus to your final grades. Prepare a report which analyzes Izmir's Fish Market prices. Your report should not be long but it should tell a good story. You are expected to use your dplyr & ggplot2 skills and present an HTML output generated by RMarkdown. **It is highly recommended that you do the Datacamp or relevant reading before the lecture.** For more information [click here](https://acikveri.bizizmir.com/en/dataset/balik-hal-fiyatlari/resource/022e9a4d-b184-495f-8dc2-734fb07e350c)

- [Download Data Set](https://openfiles.izmir.bel.tr/100160/docs/balik_hal_fiyatlari.csv). Please inspect the data set before you start coding. You will see some titles and explanations after the data (this is the raw export).
- You can use `read_csv` command of the `readr` package.
- Your report should include an introduction with max 2-3 bullet points about your findings (e.g. "Fish prices are most volatile for BARBUN and AHTAPOT and average min-max price spread is 5% of the mid price."). Support your findings with one, or at most two visualizations. Have a brief conclusion part.
- Reports not linked from your Progress Journals will not be graded.
- Bonus deadline is strict. But you are welcome to put your analysis to your Progress Journals afterwards. They will be taken into account to determine your letter grades regardless of the bonus.

**Netflix Assignment (Deadline Nov 3, 18:30)**

- You are going to analyze Netflix shows with a given dataset.
- Gather Netflix data from [this link](https://github.com/ygterl/EDA-Netflix-2020-in-R/raw/master/netflix_titles.csv).
- Refer to Yigit Erol's [Medium post](https://medium.com/deep-learning-turkiye/exploration-of-netflix-2020-dataset-in-r-markdown-eda-b202bbaec4a) and [Github repository](https://github.com/ygterl/EDA-Netflix-2020-in-R/). It is an RMarkdown project and Rmd files and his analyses might help you.
- Prepare your own analysis. It might be about a single genre, distribution and benchmark of genres, ratings, durations, or anything else that you think is creative and analytical. (Pro tip: End your analysis with some show suggestions to make it more interesting.)
- Post the RMarkdown HTML output and upload it to your Progress Journal. (You need to give a link on your PJ to your assignment, otherwise it won’t be evaluated.) Add a reference link to Yigit's work.

# Week 2 (Oct 6, 2021)

- [Introduction to dplyr v1.0.0](https://pjournal.github.io/files/dplyr_renewable.html)
  - Extra Material: [Introduction to dplyr with election data](https://pjournal.github.io/files/dplyr_elections.html)
  - Extra Material (in Turkish): [R ile Veri Analizi 101](https://acikenerji.github.io/verianalizi101/)

# Week 1 (Sep 22, 2021)

- [Introduction to BDA503](files/introduction/)
- **RMarkdown Assignment (Deadline Oct 6, 18:30):** Prepare an RMarkdown document. Introduce yourself in one paragraph (Your name surname, your work, your data interests and how you (plan to) use data science skills in your current/future work). Plus, add your Linkedin account link. Watch some UseR-2021 videos ([Main Link](https://user2021.r-project.org/) - [Recordings Link](https://user2021.r-project.org/recordings/)) and write one of them down on your RMarkdown document. Find 3 R posts relevant to your interests and describe them. Get the html output and put it in your progress journal repository. Provide link from your Progress Journal page. Click for ([Example 1](https://pjournal.github.io/mef03-OzgeBegde/RMarkdown_Homework.html)) and [Example 2](https://pjournal.github.io/boun01-canaytore/assignment1_rmarkdown).
- Form teams of 4-5 and prepare for major projects (we will discuss in week 2).

- [GitHub Desktop](https://desktop.github.com/)
- [Cheat Sheet Heaven](https://www.rstudio.com/resources/cheatsheets/)
- [Introduction to R](https://pjournal.github.io/docs/r_intro/2109/) - Brief Presentation
- Introduction to R ([html](https://pjournal.github.io/files/01_R_Basics.html) \| [pdf](https://pjournal.github.io/files/01_R_Basics.pdf))
- [R Fundamentals Exercises](https://pjournal.github.io/files/R_fundamentals_exercises.html)

# Week 0

- Some light reading about the previous years. ([Read on Blog](https://medium.com/@berk.orbay/how-to-teach-an-awesome-data-analysis-course-922f5e5651c0))
- Some light reading about instructor's view on R. ([Read on Blog](https://medium.com/yes-r-can/why-r-stats-is-the-best-2c09d77de25b))
- Some light reading about Progress Journals of previous years. ([Read on Blog](https://medium.com/berk-orbay/student-data-analysis-projects-with-r-729a8529d5a8))

This course benefits from **DataCamp for the Classroom** program. See details [here](https://www.datacamp.com/groups/education).

## Course Archive

- [2020](archive/fall20) - [2019](archive/fall19) - [2018](archive/fall18) - [2017](archive/fall17)
- [See all previous similar courses from here](https://berkorbay.github.io/courses/)
- [Student projects](https://medium.com/berk-orbay/student-data-analysis-projects-with-r-729a8529d5a8)

# Miscellaneous

## Data Sets for Prospective Projects

- YÖK

[https://yokatlas.yok.gov.tr/](https://yokatlas.yok.gov.tr/)
[https://istatistik.yok.gov.tr/](https://istatistik.yok.gov.tr/)

- ÖSYS

[http://www.osym.gov.tr/TR,6552/sureli-yayinlar.html](http://www.osym.gov.tr/TR,6552/sureli-yayinlar.html)

- EPİAŞ

[https://seffaflik.epias.com.tr/transparency/](https://seffaflik.epias.com.tr/transparency/)

- SPK

[http://www.spk.gov.tr/indexcont.aspx?action=showpage&showmenu=yes&menuid=9&pid=0&subid=1&submenuheader=0](http://www.spk.gov.tr/indexcont.aspx?action=showpage&showmenu=yes&menuid=9&pid=0&subid=1&submenuheader=0)

- Merkez Bankası - CBRT

[http://evds.tcmb.gov.tr/](http://evds.tcmb.gov.tr/)

- Emeklilik Gözetim Merkezi

[http://www.egm.org.tr/?pid=351](http://www.egm.org.tr/?pid=351)

- TURKSTAT - TUIK

[http://www.tuik.gov.tr/Start.do](http://www.tuik.gov.tr/Start.do)

[http://www.tuik.gov.tr/takvim/tkvim.zul?submenuheader=0#tb1](http://www.tuik.gov.tr/takvim/tkvim.zul?submenuheader=0#tb1)

## Extra Materials

For audiovisual learners, some webinars [here](https://www.rstudio.com/resources/webinars/).

### dplyr

- [Official dplyr tutorial](https://cran.r-project.org/web/packages/dplyr/vignettes/dplyr.html)
- [dplyr join functions](http://stat545.com/bit001_dplyr-cheatsheet.html)
- [dplyr join functions official tutorial](https://cran.r-project.org/web/packages/dplyr/vignettes/two-table.html)
- [dplyr Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/data-transformation.pdf)

### ggplot2

- [ggplot2 Tidyverse Page](http://ggplot2.tidyverse.org/)
- [R4DS Book - Data Visualization](http://r4ds.had.co.nz/data-visualisation.html)
- [ggplot2 Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/data-visualization-2.1.pdf)
- [ggplot2 Gallery](http://www.r-graph-gallery.com/portfolio/ggplot2-package/)

### RMarkdown

- [Introduction to RMarkdown - Official](http://rmarkdown.rstudio.com/lesson-1.html)
- [R4DS Book - Communication](http://r4ds.had.co.nz/communicate-intro.html)
- [DataCamp - Authoring R Markdown Reports Free Part](https://www.datacamp.com/courses/reporting-with-r-markdown)
- [RMarkdown Cheat Sheet](https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference-guide.png)

### Shiny

- [Shiny Tutorial](https://shiny.rstudio.com/tutorial/)
- [ShinyJS](https://deanattali.com/shinyjs/)
- [flexdashboard](http://rmarkdown.rstudio.com/flexdashboard/)
- [Shinyapps.io - Publish Your Shiny Products](http://shinyapps.io/)
- [htmlwidgets](http://www.htmlwidgets.org/)

### RStudio

- [RStudio - Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf)

## External Good Resources About R and Data Science

- [Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/book.html)
- [R for Data Science](http://r4ds.had.co.nz/)
- [R'a Hızlı Giriş (Türkçe)](https://r338.github.io/ab-2017/dokumanlar/RHizliGiris.pdf)
- [The Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/)
- [Advanced R](http://adv-r.had.co.nz/)
- [Bookdown Compilation](https://bookdown.org/)
- [Akademik Bilişim 2017 - R ile Veri Analizi Dersi](https://r338.github.io/ab-2017/)
- [BOUN-FE 522](https://github.com/berkorbay/fe522)
- [Learn X in Y Minutes - R](https://learnxinyminutes.com/docs/r/)
- [dplyr vignettes](https://cran.r-project.org/web/packages/dplyr/vignettes/dplyr.html)
- [ggplot2 workshop](http://tutorials.iq.harvard.edu/R/Rgraphics/Rgraphics.html)
- [RStudio Cheat Sheets (Base R, dplyr, ggplot2, RMarkdown etc.)](https://www.rstudio.com/resources/cheatsheets/)
- [R Reference Cards](https://cran.r-project.org/doc/contrib/Short-refcard.pdf)
- [data.table Cheat Sheet](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/datatable_Cheat_Sheet_R.pdf)