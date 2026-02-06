# 📊 Data Science Resources Index

This document provides a selection of links to useful resources for various aspects of data science, organized by topic. 

> **Note:** This is a living document and will be updated periodically. It currently focuses on resources collected in recent years, though some have not yet been personally tested.

---

## 📍 Table of Contents
* [💻 Software and Applications](#-software-packages)
    * [🐍 Python](#-python)
    * [📈 R](#-r)
    * [📊 Stata](#-stata)
    * [☁️ Git](#️-git)
    * [🔢 Excel](#-excel)
    * [📄 Latex](#-latex)
* [🔍 Analysis Tools](#-analysis-tools)
    * [🌍 Google Earth Engine](#-google-earth-engine)
    * [🤖 Machine Learning](#-machine-learning)
    * [🕷️ Web Scraping](#️-web-scraping)
    * [🗺️ Geospatial](#-geospatial)
    * [🐘 Big Data](#-big-data)
    * [🧠 Generative AI/LLMs](#-generative-aillms)
    * [📖 Text Analysis/NLP](#-text-analysisnlp)
    * [➕ Other Analysis Tools](#-other-analysis-tools)
* [⚖️ Causal Inference](#-causal-inference)
    * [🔗 General Causal Inference](#-general-causal-inference)
    * [🧮 Specific Econometric Methods](#-specific-econometric-methods)
* [📚 Other Resources](#-other-resources)
    * [💾 Data Sources](#-data-sources)
    * [🔬 Research Resources](#-research-resources)
    * [📝 Survey Implementation](#-survey-implementation)
    * [🌟 Additional Resources](#-additional-resources)

---

## 💻 Software Packages

### 🐍 Python
* **Sean Higgins Python Guide:** [skhiggins/Python_guide](https://github.com/skhiggins/Python_guide)
    * Topics: Style, packages, structure/organization, graphing, and reproducibility.
* **Python Causal Inference Handbook:** [python-causality-handbook](https://github.com/matheusfacure/python-causality-handbook).
* **UC Berkeley Python Practice:** [python.berkeley.edu](https://python.berkeley.edu/).
* **UC Berkeley D-Lab Resources:**
    * [Python Workshops Main Page](https://dlab-berkeley.github.io/dlab-workshops/python.html)
    * [General Python Resources](https://github.com/dlab-berkeley/python-berkeley)
    * [Python Fundamentals](https://github.com/dlab-berkeley/Python-Fundamentals)
    * [Python Data Wrangling](https://github.com/dlab-berkeley/Python-Data-Wrangling)
    * [Intermediate Python (Legacy)](https://github.com/dlab-berkeley/Python-Intermediate-Legacy)
    * [Python Data Visualization](https://github.com/dlab-berkeley/Python-Data-Visualization)
    * [Python for Everything](https://github.com/dlab-berkeley/python-for-everything)
* **Coding for Economists (Arthur Turrell):** [aeturrell.github.io/intro](https://aeturrell.github.io/coding-for-economists/intro.html)
    * Topics: Getting started, working with data, code style, data viz, workflow, econometrics, data types, text analysis, machine learning, geospatial, math, and transitioning from other languages.
* **Python for Data Science:** [python4DS/welcome](https://aeturrell.github.io/python4DS/welcome.html)
    * Topics: Basics, visualization, working with data types, and programming.
* **Awesome Geospatial Python:** [sacridini/Awesome-Geospatial](https://github.com/sacridini/Awesome-Geospatial?tab=readme-ov-file#python).
* **Gabor Bekes Resources:**
    * [Coding for Data Analysis with Python](https://github.com/gabors-data-analysis/da-coding-python): Basics, pandas, graphs, data exploration, functions, regression, datetime, time sessions, spatial viz, cross-validation, lasso, random forest, and classification.
    * [Setting up your Data Science Environment](https://github.com/gabors-data-analysis/setting-up-your-data-science-environment)
    * [How to set up your computer for Python](https://gabors-data-analysis.com/howto-python/)
* **Jeremy DNM Python Setup & Intro:**
    * [Geospatial Setup](https://github.com/jdnmiguel/Code-corner/blob/main/geospatial.md)
    * [Applied ML Setup](https://github.com/jdnmiguel/Applied-ML/blob/main/Code/0_setup.md)
    * [Python Intro Notebook](https://github.com/jdnmiguel/Applied-ML/blob/main/Code/1_python.ipynb)
* **DataCamp Career Track:** [Data Scientist with Python](https://app.datacamp.com/learn/career-tracks/data-scientist-with-python?version=5).
* **NYU Resources:**
    * [Python Data Bootcamp Book](https://nyudatabootcamp.gitbook.io/thebook/)
    * [Intro to Python for Science](https://physics.nyu.edu/pine/pymanual/html/pymanMaster.html)
* **Jupyter Notebooks:** [Tutorial for Beginners (DataQuest)](https://www.dataquest.io/blog/jupyter-notebook-tutorial/).

[🔝 Back to Top](#-table-of-contents)

---

### 📈 R
* **R Introductions and Setup:** [Introduction to R for Geospatial Data](https://datacarpentry.github.io/r-intro-geospatial/).
* **Data Science for Economists (Grant McDermott):** [uo-ec607/lectures](https://github.com/uo-ec607/lectures).
* **UC Berkeley D-Lab R Workshops:**
    * [D-Lab R Workshops Main Page](https://dlab-berkeley.github.io/dlab-workshops/R.html)
    * [R Push-In (4.5 hour intro)](https://github.com/dlab-berkeley/R-Push-Ins)
    * [R Basics for Haas (1.5 hours)](https://github.com/dlab-berkeley/R-Haas-Workshop)
    * [Fast R (2 hours)](https://github.com/dlab-berkeley/Fast-R)
    * [R for Data Science](https://github.com/dlab-berkeley/R-for-Data-Science)
    * [R Fundamentals](https://github.com/dlab-berkeley/R-Fundamentals)
    * [R Causal Inference](https://github.com/dlab-berkeley/R-Causal-Inference)
    * [R Data Visualization](https://github.com/dlab-berkeley/R-Data-Visualization)
    * [R Data Wrangling](https://github.com/dlab-berkeley/R-Data-Wrangling)
    * [R Functional Programming](https://github.com/dlab-berkeley/R-Functional-Programming)
    * [Advanced Data Wrangling (Legacy)](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R-legacy)
    * [Reproducible Project Management in R](https://github.com/dlab-berkeley/efficient-reproducible-project-management-in-R)
    * [RStudio Project Management](https://github.com/dlab-berkeley/RStudio-Project-Management)
* **DIME Analytics R Visual Library:** [r-econ-visual-library](https://worldbank.github.io/r-econ-visual-library/) — Excellent code examples for economic data visualization.
* **Fect Package:** [Fixed Effects Counterfactual Estimators](https://yiqingxu.org/packages/fect/fect.html) — Includes pre-trends and placebo tests.
* **Sean Higgins R Guide:** [skhiggins/R_guide](https://github.com/skhiggins/R_guide)
    * Topics: Style, packages, organization, graphing, reproducibility, and version control.
* **Awesome Geospatial R:** [sacridini/Awesome-Geospatial](https://github.com/sacridini/Awesome-Geospatial?tab=readme-ov-file#r).
* **Stata to R Guide:** [stata2r.github.io](https://stata2r.github.io/) — Essential for transitioning between languages.
* **Gabor Bekes Resources:**
    * [Coding for Data Analysis with R](https://github.com/gabors-data-analysis/da-coding-rstats): Basics, exploration, Markdown, ggplot, loops, functions, regression, ML (Lasso, Random Forest).
    * [How to set up your computer for R](https://gabors-data-analysis.com/howto-r/).
* **CMSA Camp (Sports Data Science):** [2021 Materials](https://www.stat.cmu.edu/cmsac/sure/2021/materials/)
    * Topics: Viz, clustering, PCA, splines, and supervised learning.
* **Reproducible Pipelines for Social Science:** [ddekadt/MY560](https://github.com/ddekadt/MY560_reproducible_pipelines_R).
* **Simon Ejdemyr R Tutorials:** [Basics Guide](https://sejdemyr.github.io/r-tutorials/basics/).
* **R for Data Science:** [Wickham and Grolemund (Free Book)](https://r4ds.had.co.nz/).
* **R Markdown:** [Getting Started Webinar (RStudio)](https://www.rstudio.com/resources/webinars/getting-started-with-r-markdown/).
* **DIME Descriptive Data Analysis:** [OSF Project](https://osf.io/7jbfg/).
* **Data Communication with R:** [Nick CH-K Slides](https://github.com/NickCH-K/DataCommSlides).
* **Advanced Data Analytics in Econ (MSU):** [Course Materials](https://github.com/msu-econ-data-analytics/course-materials)
    * Topics: Acquisition, cleaning, big data, geospatial, and ML classification.
* **PhD Econometrics in R:** [Ed Rubin's Class Notes](https://github.com/edrubin/EC607S24).

[🔝 Back to Top](#-table-of-contents)

---

### 📊 Stata
* **Programming in Stata (Official Manual):** [User's Guide Section 18 (PDF)](https://www.stata.com/manuals14/u18.pdf)
    * Topics: Macros, arguments, scalars/matrices, temporary objects, and ado files.
* **Stata Cheatsheets:** [GeoCenter Training Portfolio](https://geocenter.github.io/StataTraining/portfolio/01_resource/).
* **DIME Wiki Guides:**
    * [Data Cleaning](https://dimewiki.worldbank.org/Data_Cleaning)
    * [Data Analysis](https://dimewiki.worldbank.org/Data_Analysis)
* **The Stata Guide (Asjad Naqvi):**
    * [Main GitHub Repository](https://github.com/asjadnaqvi/The-Stata-Guide)
    * [Visualization Packages](https://medium.com/the-stata-guide/welcome-to-the-stata-guide-12adf81ec3d)
    * [Stata to LaTeX Guide](https://medium.com/the-stata-guide/the-stata-to-latex-guide-6e7ed5622856)
    * [Stata Maps](https://medium.com/the-stata-guide/tagged/maps)
    * [Programming (Mata, MLE, Regex)](https://medium.com/the-stata-guide/the-stata-programming-guide-776e93148efd)
    * [Awesome Stata Tips Collection](https://medium.com/the-stata-guide/the-awesome-stata-tips-collection-6805afdedffa)
    * [Workflow Guide](https://medium.com/the-stata-guide/the-stata-workflow-guide-52418ce35006)
    * [Stata and GitHub Integration](https://medium.com/the-stata-guide/stata-and-github-integration-8c87ddf9784a)
* **D-Lab Stata Fundamentals:** [Stata-Fundamentals](https://github.com/dlab-berkeley/Stata-Fundamentals).
* **Sean Higgins Stata Guide:** [skhiggins/Stata_guide](https://github.com/skhiggins/Stata_guide)
    * Topics: Style, packages, organization, and reproducibility.
* **Julian Reif Stata Coding Guide:** [julianreif.com/guide/](https://julianreif.com/guide/).
* **Gabor Bekes Resources:**
    * [Intro to Data Analysis in Stata](https://github.com/gabors-data-analysis/da-coding-stata): Do-files, reshaping, loops, regression, and visualization.
    * [How to set up your computer for Stata](https://gabors-data-analysis.com/howto-stata/).
* **Data Carpentry:** [Economics with Stata](https://datacarpentry.org/stata-economics/).
* **Princeton University (Oscar Torres-Reyna):**
    * [Getting Started in Data Analysis (PDF)](https://www.princeton.edu/~otorres/StataTutorial.pdf)
    * [DDS Online Stata Tutorial](https://www.princeton.edu/~otorres/Stata/)
* **Introduction to Stata:** [Alexander Lembcke's MRes Notes (PDF)](https://personal.lse.ac.uk/lembcke/ecStata/2010/MResStataNotesOct2010PartA.pdf).
* **UCLA Statistical Consulting:** [Stata Learning Modules](https://stats.idre.ucla.edu/stata/modules/).
* **J-PAL Research Resources:** [Data Cleaning and Management in Stata](https://www.povertyactionlab.org/resource/data-cleaning-and-management).
* **Performance Optimization:** [reghdfe 10x faster using Julia (Statalist)](https://www.statalist.org/forums/forum/general-stata-discussion/general/1735303-reghdfe-10x-faster).
* **Stata visualization:**
   * [Official Stata Publication-Quality Graphics](https://www.stata.com/features/publication-quality-graphics/).
   * [Making Coefficient Plots in Stata (John Kane)](https://medium.com/the-stata-gallery/making-regression-coefficient-plots-in-stata-7b100feac0cb).
   * [Better Stata Graphs Tips (Nicholas Davis)](https://www.nicholastdavis.com/wp-content/uploads/2018/12/davis_better_graphs.pdf).
   * [DIME Analytics Visual Library](https://worldbank.github.io/stata-visual-library/) — Extensive code and examples for economic visualizations.
   * [The Stata Visualizations Gallery](https://medium.com/the-stata-gallery).

[🔝 Back to Top](#-table-of-contents)

---

### ☁️ Git
* **UC Berkeley D-Lab Git Workshops:**
    * [Bash-Git Training](https://github.com/dlab-berkeley/Bash-Git) — Introduction to the command line and version control.
    * [Git Fundamentals](https://github.com/dlab-berkeley/git-fundamentals).
* **Data Science for Economists (Grant McDermott):** [uo-ec607/lectures](https://github.com/uo-ec607/lectures) — Includes dedicated sections on version control for research.
* **GitHub Tutorial:** [Video Walkthrough](https://youtu.be/krDQk5ZzP8U) — A "how-to" for getting started with the GitHub interface.
* **Git for Economists:** [A Practical Guide (Medium)](https://medium.com/codex/git-for-economists-a-practical-guide-7d10faf4224f).

[🔝 Back to Top](#-table-of-contents)

---

### 🔢 Excel
* **UC Berkeley D-Lab Excel Resources:**
    * [Excel Fundamentals](https://github.com/dlab-berkeley/Excel-Fundamentals)
    * [Visualization in Excel](https://github.com/dlab-berkeley/visualization-in-Excel)
    * [Basics of Excel](https://github.com/dlab-berkeley/Basics-of-Excel)

[🔝 Back to Top](#-table-of-contents)

---

### 📄 Latex
* **D-Lab LaTeX Fundamentals:** [LaTeX-Fundamentals](https://github.com/dlab-berkeley/LaTeX-Fundamentals).
* **Stata Table Integration:** [Jorg Weber's Guide to estout](https://www.jwe.cc/2012/03/stata-latex-tables-estout/) — How to generate and integrate Stata tables into LaTeX.
* **LaTeX Templates (Kyle Butts):** [kylebutts/latex-templates](https://github.com/kylebutts/latex-templates) — Templates for articles, slides, and referee responses.
* **ESOC Predoc Training:** [LaTeX Notes](https://github.com/esoclabprinceton/ESOC-Predoc-Training) — Useful for research assistants and pre-docs.
* **Beamer Tips:** [Paul GP's Beamer Tips](https://paulgp.github.io/2018/04/30/beamer-tips.html) — Best practices for creating presentation slides.

[🔝 Back to Top](#-table-of-contents)

---

## 🔍 Analysis Tools

### 🌍 Google Earth Engine
* **Getting Started:**
    * [Official GEE Get Started Guide](https://developers.google.com/earth-engine/guides/getstarted)
    * [End-to-End GEE (Spatial Thoughts)](https://courses.spatialthoughts.com/end-to-end-gee.html)
    * [GEE API Quickstart](https://developers.google.com/earth-engine/reference/Quickstart)
* **Awesome GEE:** [opengeos/Awesome-GEE](https://github.com/opengeos/Awesome-GEE) — A curated list of GEE resources.
* **UC Berkeley ARE Guide:** [Google Earth Engine Resources](https://docs.google.com/document/d/1xoHSCS6HfNsewkhnadLXC-wgjLzwTMvvjsoAc_9iRWM/edit?tab=t.0#heading=h.tfe5u1dx8lqr).
* **Awesome Geospatial GEE:** [sacridini/Awesome-Geospatial](https://github.com/sacridini/Awesome-Geospatial?tab=readme-ov-file#google-earth-engine).
* **D-Lab Blog:** [Big Datasets, Small Code Chunks, and Why I Use GEE](https://dlab.berkeley.edu/news/big-datasets-small-code-chunks-and-why-i-use-google-earth-engine).

[🔝 Back to Top](#-table-of-contents)

---

### 🤖 Machine Learning
* **General Resources:**
    * [D-Lab ML Working Group](https://github.com/dlab-berkeley/MachineLearningWG) — Resources in R and Python.
    * [Awesome Geospatial Deep Learning](https://github.com/sacridini/Awesome-Geospatial?tab=readme-ov-file#deep-learning).
    * [Mixtape Sessions: Machine Learning](https://github.com/Mixtape-Sessions/Machine-Learning/).
    * **Gabor Bekes Prediction & ML Case Studies:** code in R, Python, and Stata
       * [Overview](https://gabors-data-analysis.com/chapters/#part-iii-prediction)
       * [Data/Code Repository](https://github.com/gabors-data-analysis/da_case_studies).
       * Topics: Lasso, Big Data, Regression Trees, Random Forest, Boosting, and Classification.

#### 📈 R Specific ML
* **Ed Rubin's Class Notes:**
    * [Prediction and ML in Econ](https://github.com/edrubin/EC524S24).
    * [PhD Econometrics](https://github.com/edrubin/EC607S24): Inference, resampling, randomization, bootstrap, and "ML in one lecture."
* **UC Berkeley D-Lab R ML:**
    * [Machine Learning in R](https://github.com/dlab-berkeley/Machine-Learning-in-R) / [Alternative Repository](https://github.com/dlab-berkeley/R-Machine-Learning).
    * [Deep Learning in R](https://github.com/dlab-berkeley/R-Deep-Learning).
    * [Unsupervised Learning in R](https://github.com/dlab-berkeley/Unsupervised-Learning-in-R).
* **Gabor Bekes (R):** [da-coding-rstats](https://github.com/gabors-data-analysis/da-coding-rstats)
    * Topics: Regression, Spatial Viz, Cross-validation, Lasso, Random Forest, and Classification.
* **CMSA Camp (Sports Data):** [SURE 2021 Materials](https://www.stat.cmu.edu/cmsac/sure/2021/materials/)
    * Topics: Clustering, PCA, Splines, and Supervised Learning.
* **MSU Advanced Data Analytics:** [Course Materials](https://github.com/msu-econ-data-analytics/course-materials)
    * Topics: Prediction, Databases/Big Data, and ML Classification.
* **Paul Goldsmith-Pinkham:** [Applied Empirical Methods PhD Course](https://github.com/paulgp/applied-methods-phd) — Sections on ML in R.

#### 🐍 Python Specific ML
* **UC Berkeley D-Lab Python ML:**
    * [Machine Learning in Python](https://github.com/dlab-berkeley/python-machine-learning).
    * [Python Deep Learning](https://github.com/dlab-berkeley/Python-Deep-Learning).
    * [ML Intro (DS Discovery)](https://github.com/dlab-berkeley/Python-Machine-Learning-DS-Discovery).
    * [ML Fundamentals](https://github.com/dlab-berkeley/Python-Machine-Learning-Fundamentals).
    * [Fairness and Bias in ML (fairML)](https://github.com/dlab-berkeley/fairML).
    * [Artificial Neural Network (ANN) Fundamentals](https://github.com/dlab-berkeley/ANN-Fundamentals).
* **Coding for Economists (Arthur Turrell):** [Machine Learning Intro](https://aeturrell.github.io/coding-for-economists/ml-intro.html).
* **Gabor Bekes (Python):** [da-coding-python](https://github.com/gabors-data-analysis/da-coding-python)
    * Topics: Regression, Spatial Viz, Cross-validation, Lasso, Random Forest, and Classification.
* **Jeremy DNM:** [Applied ML for Economists](https://github.com/jdnmiguel/Applied-ML).

[🔝 Back to Top](#-table-of-contents)

---

### 🕷️ Web Scraping
* **General Guides:**
    * [Guide to Data Crawling (Claussen and Peukert)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3403799) — Academic paper on best practices and methods.
* **📈 R Specific Scraping:**
    * [William Marble's Guide to Webscraping in R](https://github.com/wpmarble/webscraping).
    * [Data Science for Economists (Grant McDermott)](https://github.com/uo-ec607/lectures) — Dedicated scraping modules.
    * [Collecting Data from the Web with R (Rochelle Terman)](https://plsc-31101.github.io/course/collecting-data-from-the-web.html#web-apis).
* **🐍 Python Specific Scraping:**
    * [Sean Higgins Python Tools](https://github.com/skhiggins/PythonTools) — Practical scraping code.
    * **UC Berkeley D-Lab Python Scraping:**
        * [Python Web APIs](https://github.com/dlab-berkeley/Python-Web-APIs)
        * [Python Web Scraping Fundamentals](https://github.com/dlab-berkeley/Python-Web-Scraping)
        * [Web Scraping Examples & Raw API Calls](https://github.com/dlab-berkeley/web-scraping-examples)
        * [Python Data from the Web](https://github.com/dlab-berkeley/python-data-from-web)

[🔝 Back to Top](#-table-of-contents)

---

### 🗺️ Geospatial
* **General Resources:**
    * [Geospatial Innovation Facility (GIF) UC Berkeley](http://gif.berkeley.edu/support/workshops.html) — Training and workshops.
    * [Awesome Geospatial](https://github.com/sacridini/Awesome-Geospatial) — Massive index of tools and links.
        * [Awesome Geospatial Data Sources](https://github.com/sacridini/Awesome-Geospatial?tab=readme-ov-file#data-sources).
    * [Spatial Edge](https://www.spatialedge.co/) — Datasets, tips, and research tutorials.
    * [Geographic Data Science (Pietro Stefani)](https://pietrostefani.github.io/gds/).
    * [Digital Earth Africa Learning Platform](https://learn.digitalearthafrica.org/).
* **📈 R Specific Geospatial:**
    * [Spatial Analysis in R with sf (Jacob Gellman)](https://jacobgellman.github.io/files/eco-data-sci-sf.html).
    * [Geocomputation with R](https://r.geocompx.org/) — Comprehensive online book.
    * [Geospatial Data Carpentry (UW Madison)](https://uw-madison-datascience.github.io/2019-07-11-uwmadison-dc/).
    * **UC Berkeley D-Lab R Geo:**
        * [R Geospatial Fundamentals](https://github.com/dlab-berkeley/R-Geospatial-Fundamentals)
        * [Geocoding in R](https://github.com/dlab-berkeley/Geocoding-in-R)
        * [Geospatial Fundamentals (sp legacy)](https://github.com/dlab-berkeley/Geospatial-Fundamentals-in-R-sp)
    * [Data Science for Economists (Grant McDermott)](https://github.com/uo-ec607/lectures).
    * [R as GIS for Economists (Taro Mieno)](https://tmieno2.github.io/R-as-GIS-for-Economists-Quarto/).
* **🐍 Python Specific Geospatial:**
    * [PyQGIS 101 (Anita Graser)](https://anitagraser.com/pyqgis-101-introduction-to-qgis-python-programming-for-non-programmers/) — Using Python within QGIS.
    * [D-Lab Python Geospatial Fundamentals](https://github.com/dlab-berkeley/Python-Geospatial-Fundamentals).
    * [Coding for Economists: Geo-intro (Arthur Turrell)](https://aeturrell.github.io/coding-for-economists/geo-intro.html).
    * [GIS Methods (Hohmann and Chiovelli)](https://github.com/sebastianhohmann/gis_course).
    * [Introduction to GIS Programming in Python (Qiusheng Wu)](https://gispro.gishub.org/)
        * [Main Repository](https://github.com/giswqs/intro-gispro/tree/main).

[🔝 Back to Top](#-table-of-contents)

---

### 🐘 Big Data
* **Big Data in Economics (Raj Chetty):** [opportunityinsights.org/course](https://opportunityinsights.org/course/)
    * Topics: Equality of opportunity, education, health, environment, and criminal justice.
    * Methods: Regression, causal inference, quasi-experimental methods, and machine learning.
* **Gabor Bekes Data Exploration & Big Data:**
    * [Case Studies (R, Python, Stata)](https://gabors-data-analysis.com/casestudies/part-I/)
    * [Book Overview](https://gabors-data-analysis.com/chapters/)
    * [Data and Code Repository](https://github.com/gabors-data-analysis/da_case_studies)
* **Big Data in Development (Josh Blumenstock):** [iSchool BDD (Python)](https://sites.ischool.berkeley.edu/bdd/)
    * [Blog Summary by Leila Njee Bugha](https://medium.com/@dlab-berkeley/using-big-data-for-development-economics-97aacf975f01).
* **Data in Macro Development (STEG Lectures):** [Virtual Course Materials](https://steg.cepr.org/events/virtual-course-data-macro-development)
    * Topics: Dev accounting, LSMS, multinational production, international trade, public finance, night lights, cell phone data, climate/weather, and time use data.
* **Advanced Data Analytics in Econ (MSU):** [course-materials](https://github.com/msu-econ-data-analytics/course-materials)
    * Topics: Data acquisition, workflows, databases, big data, and ML classification.

[🔝 Back to Top](#-table-of-contents)

---

### 🧠 Generative AI/LLMs
* **Research & Literature Tools:**
    * [Storm (Stanford)](https://storm.genie.stanford.edu) — Generating research articles with references to published sources.
    * [Undermind AI (MIT)](https://www.undermind.ai/) — Advanced discovery for literature reviews.
* **UC Berkeley D-Lab AI Workshops:**
    * [D-Lab AI Workshop Main Page](https://dlab-berkeley.github.io/dlab-workshops/ai.html)
    * [Intro to LLMs for Exploratory Research](https://github.com/dlab-berkeley/LLMs-Exploratory-Research)
    * [ChatGPT Prompt Engineering](https://github.com/dlab-berkeley/prompt-engineering)
* **Generative AI for Econ Research (Anton Korinek):** [genaiforecon.org](https://www.genaiforecon.org/index.html).
* **AI in Research and Teaching (Paul GP):** [Practical Guide](https://paulgp.github.io/2024/06/24/llm_talk.html)
    * Topics: VS Code and Copilot, Chat LLMs, Midjourney images, and running LLMs locally.

[🔝 Back to Top](#-table-of-contents)

---

### 📖 Text Analysis/NLP
* **UC Berkeley D-Lab Python Resources:**
    * [Python Text Analysis](https://github.com/dlab-berkeley/Python-Text-Analysis).
    * [Text Analysis for Digital Humanities](https://github.com/dlab-berkeley/DH-Text-Analysis).
    * [Natural Language Processing Part 2](https://github.com/dlab-berkeley/Natural-Language-Processing-Part-Two-DS-Discovery/tree/main).
    * [TextXD Python Text Analysis](https://github.com/dlab-berkeley/TextXD-Python-Text-Analysis).
    * [Data Science & Social Justice (NLP and ML)](https://github.com/dlab-berkeley/Data-Science-Social-Justice-2022/).
    * [Computational Text Analysis (Legacy 2017)](https://github.com/dlab-berkeley/Computational-Text-Analysis-2017).
    * [Computational Text Analysis Working Group](https://dlabctawg.github.io/).
* **Coding for Economists (Arthur Turrell):** [Text Analysis in Python](https://aeturrell.github.io/coding-for-economists/text-intro.html).
* **DataCamp Skill Track:** [Natural Language Processing in Python](https://app.datacamp.com/learn/skill-tracks/natural-language-processing-in-python).
* **Speech and Language Processing:** [Jurafsky & Martin Textbook (3rd ed. draft)](https://web.stanford.edu/~jurafsky/slp3/).
* **Computational Text Analysis & Social Media Research using R:** [justinchuntingho/R-Text-Analysis](https://github.com/justinchuntingho/Introduction-to-Computational-Text-Analysis-and-Social-Media-Research-using-R).


[🔝 Back to Top](#-table-of-contents)

---

### ➕ Other Analysis Tools
* **Parallel Programming & Cloud Computing:** [Grant McDermott's Lectures](https://github.com/uo-ec607/lectures)
    * Topics: R parallel programming, Docker, Google Compute Engine, and Spark.
* **Workflow and Project Management:**
    * [Data Science for Economists (Grant McDermott)](https://github.com/uo-ec607/lectures).
    * [DIME Analytics Coding Best Practices](https://dimewiki.worldbank.org/wiki/Coding_practices).
    * [DIME Wiki Data Management](https://dimewiki.worldbank.org/Data_Management).
    * [Stata Coding Guide (Julian Reif)](https://julianreif.com/guide/).
    * [Applied Tips for Applied Micro RAs (PDF)](https://www.dropbox.com/scl/fi/0vc9ar0gfauad8xjdanux/Applied-Tips-for-Applied-Micro-RAs.pdf?rlkey=9asv8tcqv20j67dcn6t0txpp2&e=1&dl=0).
    * [ESOC Predoc Training: Research Production Notes](https://github.com/esoclabprinceton/ESOC-Predoc-Training).
* **Databases and SQL:** [Grant McDermott's Database Modules](https://github.com/uo-ec607/lectures)
    * Topics: SQL and Google BigQuery.

[🔝 Back to Top](#-table-of-contents)

---

## ⚖️ Causal Inference

### ⚖️ Causal Inference

#### 🔗 General Causal Inference
* **Causal Mixtape (Scott Cunningham):** [Online Book](https://mixtape.scunning.com/index.html) and [GitHub Sessions](https://github.com/Mixtape-Sessions).
* **Econometrics Discussions (Chloe East):** [chloeneast.com/metrics-discussions](https://www.chloeneast.com/metrics-discussions.html).
* **The Effect (Nick Huntington-Klein):** [theeffectbook.net](https://theeffectbook.net/) — An introduction to research design and causality.
* **ARE 212 Materials (Ethan Ligon):** [ligon/ARE212_Materials](https://github.com/ligon/ARE212_Materials)
    * Topics: Multiple equation models, causality vs. correlation, identification, IV, GMM, resampling, and bootstrap.
* **Applied Empirical Methods (Paul Goldsmith-Pinkham):** [PhD Course in R](https://github.com/paulgp/applied-methods-phd).
* **Statistical Tools for Causal Inference (Sylvain Chabé-Ferret):** [STCI Online Textbook (R)](https://chabefer.github.io/STCI/).
* **Applied Econometrics Course Notes (Kyrill Borusyak):** [borusyak/are213](https://github.com/borusyak/are213).

[🔝 Back to Top](#-table-of-contents)

---

#### 🧮 Specific Econometric Methods
* **Regression Discontinuity:** [rdpackages.github.io](https://rdpackages.github.io/replication/) — Replication code and software packages.
* **Difference-in-Differences (DiD):**
    * [Asjad Naqvi's DiD Guide](https://asjadnaqvi.github.io/DiD/): Comparison of packages across Stata, R, Python, and Julia.
    * [HonestDiD (Stata)](https://github.com/mcaceresb/stata-honestdid).
    * [Pedro Sant'Anna's DiD Checklist](https://causalinf.substack.com/p/pedros-diff-in-diff-checklist-step).
* **Replication Databases:** [Dropbox Folder](https://www.dropbox.com/scl/fo/0ohwq294bknhn7hdoa7yf/ALV36_DEERdTz_XoCJPEyhc?rlkey=k9zv22k4jnco7zydfok4cvtfc&e=1&dl=0) — Databases of replicable papers organized by method.
* **Fixed Effects Models:** [Josh Blumenstock's Lecture Notes (PDF)](http://www.jblumenstock.com/files/courses/econ174/FEModels.pdf).
* **Power Analysis:** [UCLA Statistical Consulting Seminar](https://stats.idre.ucla.edu/other/mult-pkg/seminars/intro-power/).
* **Non-Standard Errors & Clustering:**
    * [World Bank Blog: New Wisdom on Clustering](https://blogs.worldbank.org/impactevaluations/when-should-you-cluster-standard-errors-new-wisdom-econometrics-oracle).
    * [LOST Stats: Non-standard Errors Guide](https://lost-stats.github.io/Model_Estimation/Statistical_Inference/Nonstandard_Errors/nonstandard_errors.html).

[🔝 Back to Top](#-table-of-contents)

---

## 📚 Other Resources

### 💾 Data Sources

* **Macro Development Data (STEG Lectures):** [STEG Virtual Course](https://steg.cepr.org/events/virtual-course-data-macro-development)
    * Topics: Dev accounting, LSMS, ag data, trade, night lights, cell phone data, climate, and time use data.
* **J-PAL / IPA Resources:**
    * [J-PAL/IPA Dataverse](https://dataverse.harvard.edu/dataverse/DFEEP?widget=dataverse%40harvard).
    * [Catalog of Administrative Datasets](https://www.povertyactionlab.org/catalog-administrative-data-sets).
* **IPUMS International:** [Harmonized International Census Data](https://www.ipums.org/projects/ipums-international).
* **3ie Remote Sensing:** [Remote Sensing Inventory](https://www.3ieimpact.org/resources/remote-sensing-inventory).
* **World Bank Data Portals:**
    * [Microdata Catalog](https://microdata.worldbank.org/index.php/catalog/?page=1&ps=15).
    * [General Data Catalog](https://datacatalog.worldbank.org/home).
    * [Open Data Portal](https://data.worldbank.org/).
    * [Climate Change Knowledge Portal](https://climateknowledgeportal.worldbank.org/index.php/explore).
    * [Space2Stats](https://worldbank.github.io/DECAT_Space2Stats/readme.html).
* **LSMS (Living Standards Measurement Study) Libraries:**
    * [Harmonized LSMS-ISA (World Bank)](https://github.com/lsms-worldbank/LSMS-ISA-harmonised-dataset-on-agricultural-productivity-and-welfare).
    * [Harmonized LSMS-HFPS (World Bank)](https://github.com/lsms-worldbank/HFPS_harmonization_working).
    * [Harmonized LSMS-ISA (EPAR)](https://github.com/EvansSchoolPolicyAnalysisAndResearch/LSMS-Data-Dissemination).
    * [LSMS_Library (Ethan Ligon)](https://github.com/ligon/LSMS_Library): All LSMS-type datasets and documentation in DVC format.
* **Aggregators & Repositories:**
    * [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets?tab=readme-ov-file).
    * [Digital Earth Africa](https://digitalearthafrica.org/en_za/): Map platform and dataset access for remotely-sensed data in Africa.
    * [The SHRUG (India)](https://www.devdatalab.org/shrug): High-resolution data for India.
    * [Data-basis (Brazil)](https://data-basis.org/en): Aggregated public datasets with a focus on Brazil.

[🔝 Back to Top](#-table-of-contents)

---

### 🔬 Research Resources
* **J-PAL Evaluation Resources:** *
    * [Research Resources](https://www.povertyactionlab.org/research-resources?view=toc)
    * [Resources for Randomized Evaluations](https://www.povertyactionlab.org/research-resources?view=toc#choose-a-view) — Comprehensive guides on RCT design and implementation.
    * [Handbook on Using Administrative Data](https://admindatahandbook.mit.edu/book/v1.1/index.html).
    * Other resources: Health care evaluation toolkit, Guide for early career researchers
* **Literature Search & Access:**
    * [Ungated Research](https://ungated.research.bowdoin.edu/) — Access to selected papers from top economics journals.
    * [Connected Papers](https://www.connectedpapers.com/) — Visual tool to find related papers by topic or citation networks.
    * [EconLit Pipeline (Paul Goldsmith-Pinkham)](https://paulgp.com/econlit-pipeline/index.html) — Full-text search for top economics journals and NBER working papers.

[🔝 Back to Top](#-table-of-contents)

---

### 📝 Survey Implementation
* **DIME Wiki SurveyCTO:**
   * [Programming Practices](https://dimewiki.worldbank.org/SurveyCTO_Programming).
   * [Coding Practices](https://dimewiki.worldbank.org/index.php?title=SurveyCTO_Coding_Practices&redirect=no).
   * [Additional Topics](https://dimewiki.worldbank.org/SurveyCTO_Additional_Topics)
* **Qualtrics Fundamentals:** [D-Lab Workshop](https://dlab-berkeley.github.io/dlab-workshops/workshop/qualtrics-fundamentals).

[🔝 Back to Top](#-table-of-contents)

---

### 🌟 Additional Resources
* **Events & Media:**
    * [Economics Conferences Spreadsheet (Anne Burton and Barton Willage](https://docs.google.com/spreadsheets/d/1MNeXLKiwQA4MK3cZ3Hr1WWXZTReh3rKQU_yfTKnu-hg/htmlview?urp=gmail_link#) — Crowdsourced list of upcoming econ conferences.
    * [Econmoics journals with short paper options (David Evans)](https://docs.google.com/spreadsheets/d/19eOOIIIRitfCOcsFbGHQseiVSg35sNyxATCIcE-G5h0/htmlview).
    * [Econimate](https://www.youtube.com/c/econimate/playlists) — Educational videos illustrating various economic topics.
    * [VoxDev: Where to Find Dev Econ Media](https://voxdev.org/topic/where-find-development-economics-resources-newsletters-articles-podcasts-videos) — Curated list of newsletters, podcasts, and articles.
* **Training & Tools:**
    * [MIT/J-PAL DEDP MicroMasters](https://micromasters.mit.edu/dedp) — Professional credentials in Data, Economics, and Development Policy.
    * [Zotero Tutorial](https://www.youtube.com/watch?v=HBynXko1wUU) — Video guide for using the reference management tool.
    * [Research Project Cookie Cutter (Arthur Turrell)](https://github.com/aeturrell/cookiecutter-research-project) — Template code to standardize and jumpstart your research project structure.

[🔝 Back to Top](#-table-of-contents)
