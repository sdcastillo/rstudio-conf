# rstudio-conf

This is where we will store all of the materials for rstudio::conf! The tree is the 2017 conference in Orlando and the 2018 conference in San Diego. Each talk or workshop is a folder named for the session and the speaker, holding the deck that was given and, when the author checked it in, the R Markdown, notebook, or script that produced it.

The files are the ordinary artifacts of those years of RStudio talks. HTML decks were built with reveal.js, R Notebooks, and R Markdown HTML documents, so the `.html` file is the talk and the `.Rmd` beside it is what you knit to rebuild it. PDF decks are the export the speaker committed. A notebook published as `.nb.html` keeps its source behind the Code menu: download the `.Rmd` from there before you re-run the examples.

Some folders do not contain the slides, because the speaker published them on their own site and the README only records the link. Yihui Xie's sessions on R Markdown internals, extensions, and blogdown point at slides.yihui.name. Jenny Bryan's Happy Git and GitHub session points at happygitwithr.com. Bhaskar Karambelkar's leaflet workshop points at the deck and the repository he used to generate it. Those outbound links are the materials for those sessions.

Two 2018 decks sit in the year folder rather than in a subdirectory: JD Long's [The Unreasonable Effectiveness of Empathy](<2018/Rstudio_ unreasonable empathy.pdf>) and Emily Riederer's [tidycf](2018/tidycf_Riederer_rstudio.pdf) talk, which turns a cash-flow analysis on its side. The [2018 note](2018/README.md) also points at [Petr Simecek's index](https://github.com/simecek/RStudioConf2018Slides) of that year's talks and training sessions.

Across both years the same tools keep coming back. R Markdown is covered as a system you can extend, as eight outputs from one file (notebook, HTML, xaringan, blogdown, GitHub document, PDF, Shiny, and bookdown), and as parameterized reports and multilingual notebooks that call SQL, bash, and Python. Shiny shows up as dashboards, `renderUI` and `insertUI`, shinytest, and a load test of how an app behaves as users and cores increase. Modeling sessions include tidyverse modeling, competitive modeling of outcomes, ciTools intervals, and deploying TensorFlow models.

- Open the PDF or HTML in the session folder to read the talk as it was delivered.
- Knit the companion `.Rmd` in RStudio when you want to regenerate the deck or the report.
- For an R Notebook (`.nb.html`), use the Code menu and download the `.Rmd` before you re-run it.
- Read the session README when the slides live on the speaker's site instead of in this repository.
- Sean Lopp's 2017 dashboard examples need a Weather Underground API key in `utils.R` before they will run locally.
- The 2018 Shiny scaling folder has the slides and the analysis scripts (`analyse.R`, `results.R`, `beep.R`). The full playback logs are in [shinyloadtest-results](https://github.com/slopp/shinyloadtest-results).

## 2017 · Orlando

- [Advanced R Markdown](<2017/Advanced R Markdown - Yihui Xie>) — Yihui Xie. Two-part deck on R Markdown internals and examples of extensions. The slides are published at slides.yihui.name; this folder records the link.
- [Competitive Modeling of Outcomes for Prediction](<2017/Competitive_Modeling_of_Outcomes_for_Prediction_Max_Kuhn/Slides.pdf>) — Max Kuhn. Slide deck, checked in as Slides.pdf.
- [Customizing and Extending R Markdown](<2017/Customizing and Extending R Markdown - Yihui Xie>) — Yihui Xie. How to customize and extend R Markdown. The deck is on slides.yihui.name.
- [Database Best Practices](<2017/Database_Best_Practices-Jim_Hester/2017_01_13-RStudio_conf-Database_Best_Practices.html>) — Jim Hester. HTML slides plus SQL-examples.Rmd and the rendered notebook SQL-examples.nb.html.
- [Dynamic Shiny Interfaces](<2017/Dynamic_Shiny_Interfaces_with_renderUI_and_insertUI-Barbara_Borges_Ribeiro/Dynamic Shiny interfaces with insertUI and renderUI.pdf>) — Barbara Borges Ribeiro. PDF slides on building Shiny interfaces with renderUI and insertUI.
- [Easy Dashboards with R Markdown](<2017/Easy_Dashboards_RMD-Sean_Lopp/presentation.html>) — Sean Lopp. presentation.html is the deck. The R Markdown dashboards need a Weather Underground API key in utils.R before they run locally.
- [Happy Git and GitHub for the useR](<2017/Happy_Git_and_GitHub-Jenny_Bryan>) — Jenny Bryan. The session points at the Happy Git and GitHub for the useR book rather than a slide file in this folder.
- [Happy R Users, purrr](<2017/Happy_R_Users_Purrr-Charlotte_Wickham/slides.pdf>) — Charlotte Wickham. Slide deck for the purrr workshop, checked in as slides.pdf.
- [Lightning Talks](<2017/Lightning_Talks/bsplus_Tools_for_Bootstrap_JavaScript_Components-Ian_Lyttle.pdf>) — Several speakers. Three short decks: bsplus (Ian Lyttle), Business Intelligence with R (Elaine McVey), and ggedit (Jonathan Sidi, PDF and Rmd).
- [List Columns](<2017/List_Columns-Jenny_Bryan/2017-01_rstudio-conf-bryan-list-columns.pdf>) — Jenny Bryan. Putting square pegs in round holes: list-columns in a data frame. PDF in the folder, with a pointer to the purrr tutorial.
- [Making Websites with R Markdown](<2017/Making Websites with R Markdown - Yihui Xie>) — Yihui Xie. blogdown talk. The slides are at slides.yihui.name.
- [Mapping in R with Leaflet](<2017/Mapping_in_R_with_Leaflet-Bhaskar_Karambelkar>) — Bhaskar Karambelkar. Slides and the code that generates them live in the speaker's leaflet-talk repository, linked from the README here.
- [Opinionated Analysis Development](<2017/Opinionated_Analysis_Development-Hilary_Parker/2017-01-14-rstudio-conf-170114193522.pdf>) — Hilary Parker. PDF slide deck for the talk.
- [Profiling](<2017/Profiling-Winston_Chang/Profiling.pdf>) — Winston Chang. Profiling.pdf is the deck. Profiling.Rmd is the source.
- [Push-button Publishing with RStudio Connect](<2017/push-button-publishing-with-rstudio-connect-Jeff_Allen/rstudio connect.pdf>) — Jeff Allen. PDF slides on publishing with RStudio Connect.
- [R and Spark](<2017/R_and_Spark_Javier_Luraschi/analyzing-4-billion-tags-with-r-and-spark.html>) — Javier Luraschi. Analyzing 4 billion tags with R and Spark: HTML slides, the R Markdown source, and the notebook.
- [R Notebook Workflows](<2017/R_Notebook_Workflows-Jonathan_McPherson/r-notebook-workflows.html>) — Jonathan McPherson. HTML slides and r-notebook-example, both as Rmd and as a rendered notebook.
- [RStudio Server Pro Power Tools](<2017/RStudio_Server_Pro_PowerTools-Jonathan_McPherson/rsp-power-tools.html>) — Jonathan McPherson. HTML slides rendered from rsp-power-tools.Rmd. Also published on RPubs.
- [The Tidyverse](<2017/The_Tidyverse-Hadley_Wickham/tidyverse.pdf>) — Hadley Wickham. PDF slide deck, tidyverse.pdf.
- [Using Web APIs in R](<2017/Web_APIs_R_Amanda_Gadrow/WebAPIsInR.html>) — Amanda Gadrow. Slides plus httr scripts: OMDb and SWAPI, Twitter with OAuth 1.0, and GitHub with OAuth 2.0.
- [What's New in the RStudio IDE](<2017/What's New with the IDE -- Kevin Ushey/slides.html>) — Kevin Ushey. slides.html is the gif-heavy deck. slides.Rmd is the source.

## 2018 · San Diego

- [Agile Data Science](<2018/Agile_Data_Science--Elaine_McVey/Agile Data Science McVey.pdf>) — Elaine McVey. PDF slide deck for the talk.
- [ciTools Model Inference](<2018/ciTools_model_inference--Matthew_Avery/ciTools-rstudio-conf-2018.pdf>) — Matthew Avery. PDF slides on model inference with ciTools.
- [Contributing to the Tidyverse](<2018/contributing_to_the_tidyverse-Mara_Averick/tverse_contributing_rstudioconf.pdf>) — Mara Averick. PDF slide deck on contributing to the tidyverse.
- [Debugging in RStudio](<2018/Debugging_in_RStudio--Amanda_Gadrow/RStudio_Debugging_Cheatsheet.pdf>) — Amanda Gadrow. One-page RStudio debugging cheatsheet.
- [Deploying TensorFlow Models](<2018/Deploying_TensorFlow_Models--Javier Luraschi/deploy-tensorflow-models-walkthrough.nb.html>) — Javier Luraschi. Walkthrough notebook and the tfdeploy R Markdown, with the rendered HTML beside the sources.
- [Fruit for Thought](<2018/Fruit_For_Thought--Aron_Atkins/Fruit_For_Thought--Aron_Atkins.pdf>) — Aron Atkins. Parameterized R Markdown reports (the Macoun apple demos), PDF slides, HTML slides, and speaker notes built with pandoc.
- [Modeling in the Tidyverse](<2018/Modeling_in_the_Tidyverse--Max_Kuhn/Modeling_in_the_Tidyverse.html>) — Max Kuhn. HTML slides and a PDF export of the same deck.
- [ModernDive, Something Blue](<2018/ModernDive_Something_Blue-Chester_Ismay/2018-02-03_ismay.pdf>) — Chester Ismay. PDF slide deck from the ModernDive session.
- [Multilingual R Markdown](<2018/Multilingual_Rmarkdown--Aaron_Berg/0_presentation.html>) — Aaron Berg. Presentation plus notebooks for SQL three ways, bash with R, and R with Python. Download the Rmd from the notebook Code menu to re-run them.
- [Phrasing](<2018/Phrasing-Mara_Averick/phrasing_rstudioconf.pdf>) — Mara Averick. PDF slide deck.
- [R Markdown: Eight Ways](<2018/R_Markdown_Eight_Ways--Mine_Cetinkaya_Rundel/rstudioconf-2018-rmd-eight-ways.pdf>) — Mine Çetinkaya-Rundel. One document, eight outputs: notebook, HTML, xaringan, blogdown, GitHub document, PDF, Shiny, and bookdown. The examples are in numbered folders next to the PDF.
- [RStudio Pro 1.1 Features](<2018/RStudio_Pro_1.1_Features--Jonathan_McPherson/rsp11-features.html>) — Jonathan McPherson. reveal.js deck rendered from rsp11-features.Rmd, including the DiagrammeR figures under gv/.
- [The Unreasonable Effectiveness of Empathy](<2018/Rstudio_ unreasonable empathy.pdf>) — JD Long. PDF kept at the 2018 root: the killer skill for a technical career, as given by JD Long.
- [Scaling Shiny](<2018/Scaling_Shiny_Sean_Lopp/slides.pdf>) — Sean Lopp. slides.pdf plus the load-test scripts (analyse.R, results.R, beep.R). The full playback logs are in slopp/shinyloadtest-results.
- [shinytest](<2018/Shinytest-Winston_Chang/2018-02-02-RStudioConf-shinytest.pdf>) — Winston Chang. PDF slides on testing Shiny applications with shinytest.
- [Stop Worrying and Love the Firewall](<2018/Stop_Worrying_Love_The_Firewall--Ian_Lyttle/Stop_Worrying_Love_The_Firewall--Ian_Lyttle.pdf>) — Ian Lyttle. PDF slide deck.
- [Storytelling with R](<2018/Storytelling_with_R-Olga_Pierce/Storytelling_with_R-Olga_Pierce.pdf>) — Olga Pierce. PDF slide deck.
- [Teach the Tidyverse](<2018/TeachTidyverse-DavidRobinson/TeachTidyverse-DavidRobinson.pdf>) — David Robinson. PDF slide deck on teaching the tidyverse.
- [The R Admin is Rad](<2018/The_R_admin_is_rad--Nathan_Stephens/R-Admin-2018.pdf>) — Nathan Stephens. PDF slide deck on administering R.
- [tidycf](<2018/tidycf_Riederer_rstudio.pdf>) — Emily Riederer. PDF kept at the 2018 root: turning analysis on its head by turning cash flows on their side.
