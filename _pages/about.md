---
permalink: /
title: "About me"
excerpt: "I am a doctoral candidate at the University of Oxford specialising in social stratification, mobility and computational social science."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a doctoral candidate at [Nuffield College](https://www.nuffield.ox.ac.uk/), University of Oxford. I specialise in social and educational inequalities, gender disparity, cross-border policy diffusion, the political economy of development, and mental health. While my research primarily focuses on low- and middle-income countries, I have also experience conducting research on the UK and US. Besides, my regional expertise includes South Asia and sub-Saharan Africa. 

Publications
======
Hossain, Mobarak. (2021). &quot;Does Greater Community Involvement Mean More Parent-Teacher Interaction? Evidence from Seven Developing Countries.&quot; <i>International Journal of Educational Development, 83</i>, 102378. [https://doi.org/10.1016/j.ijedudev.2021.102378](https://doi.org/10.1016/j.ijedudev.2021.102378)\
\
Hossain, Mobarak. (2021). &quot;Gender Differences in Experiencing Coronavirus-Triggered Economic Hardship: Evidence from Four Developing Countries.&quot; <i>Research in Social Stratification and Mobility, 71</i>, 100555. [https://doi.org/10.1016/j.rssm.2020.100555](https://doi.org/10.1016/j.rssm.2020.100555)\
\
Hossain, Mobarak. (2021). &quot;Unequal Experience of COVID-Induced Remote Schooling in Four Developing Countries.&quot; <i>International Journal of Educational Development, 85</i>, 102446. [https://doi.org/10.1016/j.ijedudev.2021.102446 ](https://doi.org/10.1016/j.ijedudev.2021.102446 )

Under review
======
Diffusing Decentralisation Reforms Across Educational Systems in Low- and Middle-Income Countries: The Case of the World Bank, 1965-2020.\
****Abstract****\
The education sector in low- and middle-income countries (LMICs) has experienced a surge of neoliberal reforms over the past few decades primarily led by the World Bank (WB). A subtle form of ‘privatisation’, these reforms have often included attempts to ‘decrease standardisation’ or ‘de-standardise’ educational responsibilities and policies to local governments and schools. This is the first study to investigate WB’s efforts to de-standardise educational systems worldwide using 99 historical and present LMICs. We find that about 63 percent of WB projects in primary and secondary education have focused on doing so. De-standardisation attempts have taken place across boundaries through two different channels: (i) devolving educational responsibilities to sub-national entities and (ii) schools. The growth of sub-national level de-standardisation has slowed down since the mid-1990s to early 2000s while it is still on the rise at the school level starting from the late 1980s. We argue this could be led by a global emphasis on school-based intervention, an urge for aid effectiveness and better results, and the priority to spread democratic values in micro-social units. Our results give important evidence of how homogeneous strategies of supranational organisations spread through heterogeneous educational systems of nation-states because of aid dependency.\
\
Diffusing Decentralisation Reforms Across Educational Systems in Low- and Middle-Income Countries: The Case of the World Bank, 1965-2020.\
***Abstract***\
The Linkage between School Autonomy and Inequality in Achievement in 69 Countries: Does Development Level Matter?\
\


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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
