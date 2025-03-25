---
permalink: /
title: "Education Background"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Lyuye Zhang is a final-year PhD candidate. He completed his undergraduate studies at Harbin Engineering University, China in 2016, earning a Bachelor's degree. In 2018, he furthered his academic pursuits by obtaining a Master of Engineering degree from Nanyang Technological University, Singapore. Currently, he is engaged in a doctoral program at the School of Computer and Science Engineering at **Nanyang Technological University**, where he is under the esteemed guidance of Professor [Yang Liu](https://personal.ntu.edu.sg/yangliu/).

Research Interests
======
My primary research interests revolve around the domains of Software Security and Maintenance, encompassing various aspects such as Open Source Security, Software Supply Chain Security, Open Source Governance, and Software Evolution Analysis.

News
======
* Mar 2025: Our paper "Drop the Golden Apples: Identifying Third-Party Reuse by DB-Less Software Composition Analysis" was accepted by **FSE-IVR 2025**.
* Jan 2025: Our paper "LLMs Meet Library Evolution: Evaluating Deprecated API Usage in LLM-based Code Completion" was accepted by **ICSE 2025**.
* May 2024: My short paper "Vulnerability Root Cause Function Locating For Java Vulnerabilities" was accepted by **ICSE 2024** Student Competition Track.
* Dec 2023: Our paper "Empirical Analysis of Vulnerabilities Life Cycle in Golang Ecosystem" was accepted by **ICSE 2024**.
* August 2023: Our paper "Software Composition Analysis for Vulnerability Detection: An Empirical Study on Java Projects" was accepted by **FSE2023**.
* July 2023: Our paper "Mitigating Persistence of Open-Source Vulnerabilities in Maven Ecosystem" was accepted by **ASE2023**.
* February 2023: Our paper "Compatible Remediation on Vulnerabilities from Third-Party Libraries for Java Projects" received the **ACM SIGSOFT Distinguished Paper Award at ICSE2023**!
* December 2022: Our paper "Compatible Remediation on Vulnerabilities from Third-Party Libraries for Java Projects" was accepted by **ICSE2023**.
* December 2022: Our paper "OSSFP: Precise and Scalable C/C++ Third-Party Library Detection using Fingerprinting Functions" was accepted by **ICSE2023**.
* October 2022: Our paper "Has My Release Disobeyed Semantic Versioning? Static Detection Based on Semantic Differencing" received the **ACM SIGSOFT Distinguished Paper Award at ASE2022**.
* July 2022: Our paper "Has My Release Disobeyed Semantic Versioning? Static Detection Based on Semantic Differencing for Java" was accepted by **ASE2022**!

Services
======
* APSEC 2024 PC.
* ACSAC 2024 PC.
* Internetware 2024 PC.
* MSR2024 Junior PC.
* CCS2023 AEC.


<!-- 
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
