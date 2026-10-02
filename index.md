---
layout: default
title: rstudio::conf
description: Talks, workshops, and source materials from rstudio::conf 2017 and 2018.
samwiki: true
---

<div class="sw-lede" markdown="1">
<div class="sw-lede-copy" markdown="1">

## The conference materials

This is where we will store all of the materials for rstudio::conf! The tree is the 2017 conference in Orlando and the 2018 conference in San Diego. Each talk or workshop is a folder named for the session and the speaker, holding the deck that was given and, when the author checked it in, the R Markdown, notebook, or script that produced it.

The files are the ordinary artifacts of those years of RStudio talks. HTML decks were built with reveal.js, R Notebooks, and R Markdown HTML documents, so the `.html` file is the talk and the `.Rmd` beside it is what you knit to rebuild it. PDF decks are the export the speaker committed. A notebook published as `.nb.html` keeps its source behind the Code menu: download the `.Rmd` from there before you re-run the examples.

Some folders do not contain the slides, because the speaker published them on their own site and the README only records the link. Yihui Xie's sessions on R Markdown internals, extensions, and blogdown point at slides.yihui.name. Jenny Bryan's Happy Git and GitHub session points at happygitwithr.com. Bhaskar Karambelkar's leaflet workshop points at the deck and the repository he used to generate it. Those outbound links are the materials for those sessions.

Two 2018 decks sit in the year folder rather than in a subdirectory: JD Long's "The Unreasonable Effectiveness of Empathy" and Emily Riederer's tidycf talk, which turns a cash-flow analysis on its side. The 2018 note also points at [Petr Simecek's index](https://github.com/simecek/RStudioConf2018Slides) of that year's talks and training sessions.

Across both years the same tools keep coming back. R Markdown is covered as a system you can extend, as eight outputs from one file (notebook, HTML, xaringan, blogdown, GitHub document, PDF, Shiny, and bookdown), and as parameterized reports and multilingual notebooks that call SQL, bash, and Python. Shiny shows up as dashboards, `renderUI` and `insertUI`, shinytest, and a load test of how an app behaves as users and cores increase. Modeling sessions include tidyverse modeling, competitive modeling of outcomes, ciTools intervals, and deploying TensorFlow models.

- Open the PDF or HTML in the session folder to read the talk as it was delivered.
- Knit the companion `.Rmd` in RStudio when you want to regenerate the deck or the report.
- For an R Notebook (`.nb.html`), use the Code menu and download the `.Rmd` before you re-run it.
- Read the session README when the slides live on the speaker's site instead of in this repository.
- Sean Lopp's 2017 dashboard examples need a Weather Underground API key in `utils.R` before they will run locally.
- The 2018 Shiny scaling folder has the slides and the analysis scripts (`analyse.R`, `results.R`, `beep.R`). The full playback logs are in [shinyloadtest-results](https://github.com/slopp/shinyloadtest-results).

</div>
<aside class="sw-find" markdown="1">

## What you’ll find

- **2017, Orlando** — 21 session folders, from the tidyverse and R Markdown to Shiny, Spark, leaflet, and the IDE.
- **2018, San Diego** — 18 session folders and two root PDFs, including parameterized reports, shinytest, and R Markdown's eight outputs.
- **Decks in the tree** — HTML, PDF, R Markdown, and notebooks committed with the talk.
- **Decks on a speaker site** — folders whose README links out, and that link is the material.
- **2018 index** — Petr Simecek's list of talks and training sessions, linked from the year note.

</aside>
</div>

<div class="sw-catalog-bar">
  <div class="sw-toolbar">
    <label class="sw-search" for="sw-q">Find a session
      <input id="sw-q" type="search" placeholder="Speaker, year, tool, or title" autocomplete="off">
    </label>
    <p class="sw-result" id="sw-count" aria-live="polite"></p>
  </div>
  <nav class="sw-jumps" aria-label="Years">
    <a href="#y2017">2017</a>
    <a href="#y2018">2018</a>
  </nav>
</div>

<section class="sw-section" id="y2017">
  <div class="sw-section-head">
    <h2>2017 · Orlando <span class="sw-pill">21 sessions</span></h2>
    <p>Twenty-one folders from the Orlando conference. A few of them only store the link to a deck the speaker already hosted.</p>
  </div>
  <div class="sw-grid">
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="https://slides.yihui.name/2017-rstudio-conf-rmarkdown-Yihui-Xie.html" target="_blank" rel="noopener">Advanced R Markdown</a></h3>
    <span class="sw-lang">Link</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">Two-part deck on R Markdown internals and examples of extensions. The slides are published at slides.yihui.name; this folder records the link.</p>
  <p class="sw-meta">Yihui Xie</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="https://slides.yihui.name/2017-rstudio-conf-rmarkdown-Yihui-Xie.html" target="_blank" rel="noopener">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/Advanced%20R%20Markdown%20-%20Yihui%20Xie">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/Competitive_Modeling_of_Outcomes_for_Prediction_Max_Kuhn/Slides.pdf">Competitive Modeling of Outcomes for Prediction</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">Slide deck, checked in as Slides.pdf.</p>
  <p class="sw-meta">Max Kuhn</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/Competitive_Modeling_of_Outcomes_for_Prediction_Max_Kuhn/Slides.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/Competitive_Modeling_of_Outcomes_for_Prediction_Max_Kuhn">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="https://slides.yihui.name/2017-rstudio-conf-ext-rmd-Yihui-Xie.html" target="_blank" rel="noopener">Customizing and Extending R Markdown</a></h3>
    <span class="sw-lang">Link</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">How to customize and extend R Markdown. The deck is on slides.yihui.name.</p>
  <p class="sw-meta">Yihui Xie</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="https://slides.yihui.name/2017-rstudio-conf-ext-rmd-Yihui-Xie.html" target="_blank" rel="noopener">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/Customizing%20and%20Extending%20R%20Markdown%20-%20Yihui%20Xie">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/Database_Best_Practices-Jim_Hester/2017_01_13-RStudio_conf-Database_Best_Practices.html">Database Best Practices</a></h3>
    <span class="sw-lang">HTML</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">HTML slides plus SQL-examples.Rmd and the rendered notebook SQL-examples.nb.html.</p>
  <p class="sw-meta">Jim Hester</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/Database_Best_Practices-Jim_Hester/2017_01_13-RStudio_conf-Database_Best_Practices.html">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/Database_Best_Practices-Jim_Hester">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/Dynamic_Shiny_Interfaces_with_renderUI_and_insertUI-Barbara_Borges_Ribeiro/Dynamic%20Shiny%20interfaces%20with%20insertUI%20and%20renderUI.pdf">Dynamic Shiny Interfaces</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">PDF slides on building Shiny interfaces with renderUI and insertUI.</p>
  <p class="sw-meta">Barbara Borges Ribeiro</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/Dynamic_Shiny_Interfaces_with_renderUI_and_insertUI-Barbara_Borges_Ribeiro/Dynamic%20Shiny%20interfaces%20with%20insertUI%20and%20renderUI.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/Dynamic_Shiny_Interfaces_with_renderUI_and_insertUI-Barbara_Borges_Ribeiro">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/Easy_Dashboards_RMD-Sean_Lopp/presentation.html">Easy Dashboards with R Markdown</a></h3>
    <span class="sw-lang">HTML</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">presentation.html is the deck. The R Markdown dashboards need a Weather Underground API key in utils.R before they run locally.</p>
  <p class="sw-meta">Sean Lopp</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/Easy_Dashboards_RMD-Sean_Lopp/presentation.html">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/Easy_Dashboards_RMD-Sean_Lopp">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="http://happygitwithr.com" target="_blank" rel="noopener">Happy Git and GitHub for the useR</a></h3>
    <span class="sw-lang">Link</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">The session points at the Happy Git and GitHub for the useR book rather than a slide file in this folder.</p>
  <p class="sw-meta">Jenny Bryan</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="http://happygitwithr.com" target="_blank" rel="noopener">Book</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/Happy_Git_and_GitHub-Jenny_Bryan">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/Happy_R_Users_Purrr-Charlotte_Wickham/slides.pdf">Happy R Users, purrr</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">Slide deck for the purrr workshop, checked in as slides.pdf.</p>
  <p class="sw-meta">Charlotte Wickham</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/Happy_R_Users_Purrr-Charlotte_Wickham/slides.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/Happy_R_Users_Purrr-Charlotte_Wickham">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/Lightning_Talks/bsplus_Tools_for_Bootstrap_JavaScript_Components-Ian_Lyttle.pdf">Lightning Talks</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">Three short decks: bsplus (Ian Lyttle), Business Intelligence with R (Elaine McVey), and ggedit (Jonathan Sidi, PDF and Rmd).</p>
  <p class="sw-meta">Several speakers</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/Lightning_Talks/bsplus_Tools_for_Bootstrap_JavaScript_Components-Ian_Lyttle.pdf">bsplus</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/Lightning_Talks">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/List_Columns-Jenny_Bryan/2017-01_rstudio-conf-bryan-list-columns.pdf">List Columns</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">Putting square pegs in round holes: list-columns in a data frame. PDF in the folder, with a pointer to the purrr tutorial.</p>
  <p class="sw-meta">Jenny Bryan</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/List_Columns-Jenny_Bryan/2017-01_rstudio-conf-bryan-list-columns.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/List_Columns-Jenny_Bryan">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="https://slides.yihui.name/2017-rstudio-conf-blogdown-Yihui-Xie.html" target="_blank" rel="noopener">Making Websites with R Markdown</a></h3>
    <span class="sw-lang">Link</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">blogdown talk. The slides are at slides.yihui.name.</p>
  <p class="sw-meta">Yihui Xie</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="https://slides.yihui.name/2017-rstudio-conf-blogdown-Yihui-Xie.html" target="_blank" rel="noopener">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/Making%20Websites%20with%20R%20Markdown%20-%20Yihui%20Xie">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="https://bhaskarvk.github.io/leaflet-talk-rstudioconf-2017/RstudioConf2017.html#1" target="_blank" rel="noopener">Mapping in R with Leaflet</a></h3>
    <span class="sw-lang">Link</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">Slides and the code that generates them live in the speaker's leaflet-talk repository, linked from the README here.</p>
  <p class="sw-meta">Bhaskar Karambelkar</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="https://bhaskarvk.github.io/leaflet-talk-rstudioconf-2017/RstudioConf2017.html#1" target="_blank" rel="noopener">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/Mapping_in_R_with_Leaflet-Bhaskar_Karambelkar">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/Opinionated_Analysis_Development-Hilary_Parker/2017-01-14-rstudio-conf-170114193522.pdf">Opinionated Analysis Development</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">PDF slide deck for the talk.</p>
  <p class="sw-meta">Hilary Parker</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/Opinionated_Analysis_Development-Hilary_Parker/2017-01-14-rstudio-conf-170114193522.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/Opinionated_Analysis_Development-Hilary_Parker">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/Profiling-Winston_Chang/Profiling.pdf">Profiling</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">Profiling.pdf is the deck. Profiling.Rmd is the source.</p>
  <p class="sw-meta">Winston Chang</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/Profiling-Winston_Chang/Profiling.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/Profiling-Winston_Chang">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/push-button-publishing-with-rstudio-connect-Jeff_Allen/rstudio%20connect.pdf">Push-button Publishing with RStudio Connect</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">PDF slides on publishing with RStudio Connect.</p>
  <p class="sw-meta">Jeff Allen</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/push-button-publishing-with-rstudio-connect-Jeff_Allen/rstudio%20connect.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/push-button-publishing-with-rstudio-connect-Jeff_Allen">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/R_and_Spark_Javier_Luraschi/analyzing-4-billion-tags-with-r-and-spark.html">R and Spark</a></h3>
    <span class="sw-lang">HTML</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">Analyzing 4 billion tags with R and Spark: HTML slides, the R Markdown source, and the notebook.</p>
  <p class="sw-meta">Javier Luraschi</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/R_and_Spark_Javier_Luraschi/analyzing-4-billion-tags-with-r-and-spark.html">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/R_and_Spark_Javier_Luraschi">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/R_Notebook_Workflows-Jonathan_McPherson/r-notebook-workflows.html">R Notebook Workflows</a></h3>
    <span class="sw-lang">HTML</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">HTML slides and r-notebook-example, both as Rmd and as a rendered notebook.</p>
  <p class="sw-meta">Jonathan McPherson</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/R_Notebook_Workflows-Jonathan_McPherson/r-notebook-workflows.html">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/R_Notebook_Workflows-Jonathan_McPherson">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/RStudio_Server_Pro_PowerTools-Jonathan_McPherson/rsp-power-tools.html">RStudio Server Pro Power Tools</a></h3>
    <span class="sw-lang">HTML</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">HTML slides rendered from rsp-power-tools.Rmd. Also published on RPubs.</p>
  <p class="sw-meta">Jonathan McPherson</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/RStudio_Server_Pro_PowerTools-Jonathan_McPherson/rsp-power-tools.html">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/RStudio_Server_Pro_PowerTools-Jonathan_McPherson">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/The_Tidyverse-Hadley_Wickham/tidyverse.pdf">The Tidyverse</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">PDF slide deck, tidyverse.pdf.</p>
  <p class="sw-meta">Hadley Wickham</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/The_Tidyverse-Hadley_Wickham/tidyverse.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/The_Tidyverse-Hadley_Wickham">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/Web_APIs_R_Amanda_Gadrow/WebAPIsInR.html">Using Web APIs in R</a></h3>
    <span class="sw-lang">HTML</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">Slides plus httr scripts: OMDb and SWAPI, Twitter with OAuth 1.0, and GitHub with OAuth 2.0.</p>
  <p class="sw-meta">Amanda Gadrow</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/Web_APIs_R_Amanda_Gadrow/WebAPIsInR.html">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/Web_APIs_R_Amanda_Gadrow">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2017/What%27s%20New%20with%20the%20IDE%20--%20Kevin%20Ushey/slides.html">What's New in the RStudio IDE</a></h3>
    <span class="sw-lang">HTML</span>
  </div>
  <p class="sw-badge">2017</p>
  <p class="sw-desc">slides.html is the gif-heavy deck. slides.Rmd is the source.</p>
  <p class="sw-meta">Kevin Ushey</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2017/What%27s%20New%20with%20the%20IDE%20--%20Kevin%20Ushey/slides.html">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2017/What%27s%20New%20with%20the%20IDE%20--%20Kevin%20Ushey">Source</a>
  </div>
</article>
  </div>
</section>

<section class="sw-section" id="y2018">
  <div class="sw-section-head">
    <h2>2018 · San Diego <span class="sw-pill">20 sessions</span></h2>
    <p>Eighteen folders plus two PDFs that were committed at the year root. Mine Çetinkaya-Rundel's eight-ways examples include a rendered bookdown book.</p>
  </div>
  <div class="sw-grid">
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/Agile_Data_Science--Elaine_McVey/Agile%20Data%20Science%20McVey.pdf">Agile Data Science</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">PDF slide deck for the talk.</p>
  <p class="sw-meta">Elaine McVey</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/Agile_Data_Science--Elaine_McVey/Agile%20Data%20Science%20McVey.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/Agile_Data_Science--Elaine_McVey">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/ciTools_model_inference--Matthew_Avery/ciTools-rstudio-conf-2018.pdf">ciTools Model Inference</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">PDF slides on model inference with ciTools.</p>
  <p class="sw-meta">Matthew Avery</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/ciTools_model_inference--Matthew_Avery/ciTools-rstudio-conf-2018.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/ciTools_model_inference--Matthew_Avery">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/contributing_to_the_tidyverse-Mara_Averick/tverse_contributing_rstudioconf.pdf">Contributing to the Tidyverse</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">PDF slide deck on contributing to the tidyverse.</p>
  <p class="sw-meta">Mara Averick</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/contributing_to_the_tidyverse-Mara_Averick/tverse_contributing_rstudioconf.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/contributing_to_the_tidyverse-Mara_Averick">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/Debugging_in_RStudio--Amanda_Gadrow/RStudio_Debugging_Cheatsheet.pdf">Debugging in RStudio</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">One-page RStudio debugging cheatsheet.</p>
  <p class="sw-meta">Amanda Gadrow</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/Debugging_in_RStudio--Amanda_Gadrow/RStudio_Debugging_Cheatsheet.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/Debugging_in_RStudio--Amanda_Gadrow">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/Deploying_TensorFlow_Models--Javier%20Luraschi/deploy-tensorflow-models-walkthrough.nb.html">Deploying TensorFlow Models</a></h3>
    <span class="sw-lang">Notebook</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">Walkthrough notebook and the tfdeploy R Markdown, with the rendered HTML beside the sources.</p>
  <p class="sw-meta">Javier Luraschi</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/Deploying_TensorFlow_Models--Javier%20Luraschi/deploy-tensorflow-models-walkthrough.nb.html">Notebook</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/Deploying_TensorFlow_Models--Javier%20Luraschi">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/Fruit_For_Thought--Aron_Atkins/Fruit_For_Thought--Aron_Atkins.pdf">Fruit for Thought</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">Parameterized R Markdown reports (the Macoun apple demos), PDF slides, HTML slides, and speaker notes built with pandoc.</p>
  <p class="sw-meta">Aron Atkins</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/Fruit_For_Thought--Aron_Atkins/Fruit_For_Thought--Aron_Atkins.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/Fruit_For_Thought--Aron_Atkins">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/Modeling_in_the_Tidyverse--Max_Kuhn/Modeling_in_the_Tidyverse.html">Modeling in the Tidyverse</a></h3>
    <span class="sw-lang">HTML</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">HTML slides and a PDF export of the same deck.</p>
  <p class="sw-meta">Max Kuhn</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/Modeling_in_the_Tidyverse--Max_Kuhn/Modeling_in_the_Tidyverse.html">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/Modeling_in_the_Tidyverse--Max_Kuhn">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/ModernDive_Something_Blue-Chester_Ismay/2018-02-03_ismay.pdf">ModernDive, Something Blue</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">PDF slide deck from the ModernDive session.</p>
  <p class="sw-meta">Chester Ismay</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/ModernDive_Something_Blue-Chester_Ismay/2018-02-03_ismay.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/ModernDive_Something_Blue-Chester_Ismay">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/Multilingual_Rmarkdown--Aaron_Berg/0_presentation.html">Multilingual R Markdown</a></h3>
    <span class="sw-lang">HTML</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">Presentation plus notebooks for SQL three ways, bash with R, and R with Python. Download the Rmd from the notebook Code menu to re-run them.</p>
  <p class="sw-meta">Aaron Berg</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/Multilingual_Rmarkdown--Aaron_Berg/0_presentation.html">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/Multilingual_Rmarkdown--Aaron_Berg">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/Phrasing-Mara_Averick/phrasing_rstudioconf.pdf">Phrasing</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">PDF slide deck.</p>
  <p class="sw-meta">Mara Averick</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/Phrasing-Mara_Averick/phrasing_rstudioconf.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/Phrasing-Mara_Averick">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/R_Markdown_Eight_Ways--Mine_Cetinkaya_Rundel/rstudioconf-2018-rmd-eight-ways.pdf">R Markdown: Eight Ways</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">One document, eight outputs: notebook, HTML, xaringan, blogdown, GitHub document, PDF, Shiny, and bookdown. The examples are in numbered folders next to the PDF.</p>
  <p class="sw-meta">Mine Çetinkaya-Rundel</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/R_Markdown_Eight_Ways--Mine_Cetinkaya_Rundel/rstudioconf-2018-rmd-eight-ways.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/R_Markdown_Eight_Ways--Mine_Cetinkaya_Rundel">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/RStudio_Pro_1.1_Features--Jonathan_McPherson/rsp11-features.html">RStudio Pro 1.1 Features</a></h3>
    <span class="sw-lang">HTML</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">reveal.js deck rendered from rsp11-features.Rmd, including the DiagrammeR figures under gv/.</p>
  <p class="sw-meta">Jonathan McPherson</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/RStudio_Pro_1.1_Features--Jonathan_McPherson/rsp11-features.html">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/RStudio_Pro_1.1_Features--Jonathan_McPherson">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/Rstudio_%20unreasonable%20empathy.pdf">The Unreasonable Effectiveness of Empathy</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">PDF kept at the 2018 root: the killer skill for a technical career, as given by JD Long.</p>
  <p class="sw-meta">JD Long</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/Rstudio_%20unreasonable%20empathy.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/Scaling_Shiny_Sean_Lopp/slides.pdf">Scaling Shiny</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">slides.pdf plus the load-test scripts (analyse.R, results.R, beep.R). The full playback logs are in slopp/shinyloadtest-results.</p>
  <p class="sw-meta">Sean Lopp</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/Scaling_Shiny_Sean_Lopp/slides.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/Scaling_Shiny_Sean_Lopp">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/Shinytest-Winston_Chang/2018-02-02-RStudioConf-shinytest.pdf">shinytest</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">PDF slides on testing Shiny applications with shinytest.</p>
  <p class="sw-meta">Winston Chang</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/Shinytest-Winston_Chang/2018-02-02-RStudioConf-shinytest.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/Shinytest-Winston_Chang">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/Stop_Worrying_Love_The_Firewall--Ian_Lyttle/Stop_Worrying_Love_The_Firewall--Ian_Lyttle.pdf">Stop Worrying and Love the Firewall</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">PDF slide deck.</p>
  <p class="sw-meta">Ian Lyttle</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/Stop_Worrying_Love_The_Firewall--Ian_Lyttle/Stop_Worrying_Love_The_Firewall--Ian_Lyttle.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/Stop_Worrying_Love_The_Firewall--Ian_Lyttle">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/Storytelling_with_R-Olga_Pierce/Storytelling_with_R-Olga_Pierce.pdf">Storytelling with R</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">PDF slide deck.</p>
  <p class="sw-meta">Olga Pierce</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/Storytelling_with_R-Olga_Pierce/Storytelling_with_R-Olga_Pierce.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/Storytelling_with_R-Olga_Pierce">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/TeachTidyverse-DavidRobinson/TeachTidyverse-DavidRobinson.pdf">Teach the Tidyverse</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">PDF slide deck on teaching the tidyverse.</p>
  <p class="sw-meta">David Robinson</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/TeachTidyverse-DavidRobinson/TeachTidyverse-DavidRobinson.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/TeachTidyverse-DavidRobinson">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/The_R_admin_is_rad--Nathan_Stephens/R-Admin-2018.pdf">The R Admin is Rad</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">PDF slide deck on administering R.</p>
  <p class="sw-meta">Nathan Stephens</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/The_R_admin_is_rad--Nathan_Stephens/R-Admin-2018.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018/The_R_admin_is_rad--Nathan_Stephens">Source</a>
  </div>
</article>
<article class="sw-card">
  <div class="sw-card-top">
    <h3 class="sw-name"><a href="2018/tidycf_Riederer_rstudio.pdf">tidycf</a></h3>
    <span class="sw-lang">PDF</span>
  </div>
  <p class="sw-badge">2018</p>
  <p class="sw-desc">PDF kept at the 2018 root: turning analysis on its head by turning cash flows on their side.</p>
  <p class="sw-meta">Emily Riederer</p>
  <div class="sw-actions">
    <a class="sw-btn sw-btn-live" href="2018/tidycf_Riederer_rstudio.pdf">Slides</a>
    <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/rstudio-conf/tree/master/2018">Source</a>
  </div>
</article>
  </div>
</section>

<p class="sw-empty" id="sw-empty" hidden>No session matches that search.</p>

<script>
(function () {
  var input = document.getElementById("sw-q");
  var count = document.getElementById("sw-count");
  var empty = document.getElementById("sw-empty");
  if (!input) return;
  var cards = Array.prototype.slice.call(document.querySelectorAll(".sw-card"));
  var sections = Array.prototype.slice.call(document.querySelectorAll(".sw-section"));
  function apply() {
    var q = input.value.trim().toLowerCase();
    var n = 0;
    cards.forEach(function (card) {
      var show = !q || card.textContent.toLowerCase().indexOf(q) !== -1;
      card.hidden = !show;
      if (show) n += 1;
    });
    sections.forEach(function (section) {
      section.hidden = !section.querySelector(".sw-card:not([hidden])");
    });
    count.textContent = n + (n === 1 ? " session" : " sessions");
    empty.hidden = n !== 0;
  }
  input.addEventListener("input", apply);
  apply();
})();
</script>
