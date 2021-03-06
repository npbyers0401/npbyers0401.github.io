---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

## Grant-Funded Projects

### <span style="color: red;">OnTheBooks: Jim Crow and the Algorithms of Resistance</span>

[*OnTheBooks*](https://onthebooks.lib.unc.edu/) is a [collections as data](https://collectionsasdata.github.io/part2whole/) and machine learning project of the University of North Carolina at Chapel Hill Libraries with the goal of discovering Jim Crow and racially-based legislation signed into law in North Carolina between Reconstruction and the Civil Rights Movement (1865-1967). The project has been funded by the [Andrew W. Mellon Foundation](https://mellon.org/) as part of the first cohort for [Collections as Data: Part to Whole](https://collectionsasdata.github.io/part2whole/) and the [ARL Venture Fund](https://www.arl.org/news/arl-launches-venture-fund-to-support-research-and-development-in-member-libraries-proposals-due-february-28/). The major project deliverables include:

1. A publicly accessible, plain-text corpus of North Carolina Session Laws from 1865-1967 for general legal and historical research, and a list of racially-biased laws discovered.
2. A public git repository containing general scripts, open source software, and documentation for the benefit of future collections as data projects.
3. A short white paper describing our methods and workflows for accurate, large-scale OCR text conversion and text analysis for future teams seeking to create large-scale digital corpora and/or experiment with data-driven discovery.
4. A website for educators and researchers interested in Southern and African American History that lists and contextualizes North Carolina segregation laws we uncover from the Jim Crow era (1865/66 - 1967).

As a Documentation and Content Developer, my role in the project includes cleaning and processing of the corpus, creation of project scripts and workflows, preparation of visual materials for presentations, and the development of Jupyter-based documentation for project code.

**Topics:** Machine Learning, Digital Archives, Text Mining, North Carolina History, Jim Crow and Racism in the United States

**Tools:** Python, Jupyter, Git/GitHub

**Date:** 2020 (Ongoing)

**Links:** [Project Website](https://onthebooks.lib.unc.edu/), [XML Law Files](https://cdr.lib.unc.edu/concern/data_sets/hx11xm948?locale=en), [White Paper](https://doi.org/10.17615/hvz4-sr14), [Code and Documentation](https://github.com/UNC-Libraries-data/OnTheBooks)

## Master's Project

### <span style="color: red;">ECfAIR: A Semi-Supervised Classification Method for Email Collections</span>

ECfAIR - (**E** mail **C** lassification **f** or **A** rchival and **I** nstitutional **R** epositories)

For my master's paper I plan to build a tool to evaluate a semi-supervised "ensemble" classification method for use with large email collections. If successful, this method could be integrated into existing digital archives systems for the appraisal of email collections.

**Topics:** Machine Learning, Digital Archives, Text Mining

**Tools:** Python (Scikit Learn)

**Date:** 2019-2020 (Ongoing)

**Links:** [Project Proposal](https://npbyers0401.github.io/files/ProposalFinal.pdf)


## Side Projects

### <span style="color: red;">bibrepbuilder</span>

A Python-based tool for compiling multi-publication bibliometric reports using Web of Science (WoS) data

This tool was designed to produce short, descriptive bibliometric reports for sets of scholarly publications. It mimics some of the functionality of the Web of Science web interface but allows for easier manipulation and use of data and charts. The tool was designed to give researchers an accessible starting point for understanding the reach and impact of their publications or those of their team or organization. Alternatively, the tool can be used by librarians producing reports for patrons within their institution.

The software accepts as input a single WoS file and uses several Clarivate APIs to compile an Excel report.

**Topics:** Bibliometrics

**Tools:** Python (pandas, tkinter, xlsxwriter)

**Date:** 2019-2020

**Links:** (Currently proprietary)

### <span style="color: red;">artrepbuilder</span>

An Excel template for compiling single-publication bibliometric reports using Web of Science (WoS) data

This software consists of a macro-enabled Microsoft Excel workbook and an accompanying PowerPoint template. It allows one to download two WoS datasets and to automatically generate an Excel-based datafile as well as a basic PowerPoint report. The tool is designed to produce a report for a single publication (article, book chapter, conference presentation, etc.).

The software accepts as input two WoS files and uses several macros to compile a datafile and accompanying report.

**Topics:** Bibliometrics

**Tools:** Microsoft VBA, Microsoft Excel, Microsoft PowerPoint

**Date:** 2019

**Links:** (Currently proprietary)

## Class Projects

### <span style="color: red;">NASA's China Ban: A Predictive Bibliometric Analysis</span>

Term project for INLS 625 - Information Analytics

For this project I attempted to discern what effect, if any, a 2011 Congressional act prohibiting NASA scientists from collaborating bilaterally with Chinese scientists had on the research output of either group. I used citation data from Web of Science to build models that classified publications according to their title and abstract content. I found considerable differences between the two bodies of research, but was unable to make any firm conclusions because of incomplete data.

**Topics:** Machine Learning, Predictive Analytics, Text Mining

**Tools:** LightSIDE, WEKA, R (bibliometrix), Microsoft Excel

**Date:** Fall 2019

**Links:** [Final Report](https://npbyers0401.github.io/files/625ProjectReport.pdf)

### <span style="color: red;">Predicting Wine Scores Based on Review Content</span>

Term project for INLS 613 - Text Mining

For this project my group built and tested models to predict the score of a wine based on the contents of its review. To do so we used a subset of a dataset consisting of ~130,000 wine reviews scraped from winemag.com. We found that the written component of each review proved more predictive than features like price or place of origin, indicating a high degree of credibility on the part of the reviewers.

**Topics:** Machine Learning, Predictive Analytics, Text Mining

**Tools:** WEKA, LightSIDE, Python, R (ggplot), Microsoft Excel

**Date:** Spring 2019

**Links:** [Final Report](https://npbyers0401.github.io/files/613ProjectReport.pdf)

### <span style="color: red;">Adult Obesity in the United States - a Visualization Dashboard</span>

Midterm project for INLS 541 - Information Visualization

For this project I cleaned and prepared a real-world set of county-level health data for the years 2010-2019. The graphics illustrate obesity trends across space and time as well as the relationships between obesity and other health-related metrics.

**Topics:** Data Visualization

**Tools:** Tableau, Microsoft Excel

**Date:** Spring 2020

**Links:** [Tableau Dashboard](https://public.tableau.com/profile/npbyers#!/vizhome/AdultObesityintheUS_15854094045130/FinalDashboard2)

### <span style="color: red;">UNC BeAM (Be A Makerspace) Laser Cutters: Four Check System Analysis</span>

Term project for INLS 582 - Systems Analysis

For this project my team conducted a thorough analysis of the check-in and queue system for the university makerspace's laser cutters. We conducted interviews with students and staff and created an array of models to identify areas for improvement. Many of our recommendations were adopted by BeAM following our project submission.

**Topics:** Systems Analysis, Project Management

**Tools:** -

**Date:** Spring 2019

**Links:** [Final Report](https://npbyers0401.github.io/files/LaserCutter_FinalSpec.pdf)

### <span style="color: red;">Simulated IMLS Grant Proposal: "Digital Archives of Medical History"</span>

Term project for INLS 752 - Digital Curation

This project had my team create a simulated proposal for the IMLS National Leadership Grants for Libraries program. We created a hypothetical organization ("The Digital Archive of Medical History DAMH") that proposed to digitize and create an online presence for a hypothetical collection ("The Dorothea Dix Hospital Online Collection").

**Topics:** Digital Archives, Grant Proposals

**Tools:** -

**Date:** Fall 2019

**Links:** [Proposal Submission](https://npbyers0401.github.io/files/GrantProject_752.pdf)

## Undergraduate Honors Thesis

### <span style="color: red;">The Big E and the Mighty T: Ship Memorials in American War Memory</span>

Honors Thesis completed to satisfy the requirements of both the Plan II Honors Program and the History Honors Program at the University of Texas at Austin

For this thesis I conducted primary source research at five separate archives in Austin, Texas and Washington, DC. I analyzed the memorialization efforts surrounding two American warships, the USS Texas and the USS Enterprise, in the days following the conclusion of the Second World War. I found that the success of one effort and failure of the other resulted from differences in messaging and organization. Ultimately, each scenario reflects more on its own historical context than the historical events being memorialized.

**Topics:** American History, Memorialization

**Tools:** -

**Date:** 2015-2016

**Links:** [Thesis Submission Document](https://npbyers0401.github.io/files/ByersSignedThesis2016H.pdf)
