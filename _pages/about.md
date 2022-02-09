---
permalink: /
title: "Hey! I'm Junchen."
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
About me
======
I am a graduate student from Boston University majored in Computer Science. Having a good understanding of both application and theory, I have a great interest in software development as well as data engineering. As a cs major student, I am on the track of data-centric computing from which I take Distributed System, Stream System, DB architecture as well as OOD design and graduate algorithm. Familiar with Java, C++, and Go, I can be a great team member and write efficient code. 

Before my master's study, I completed a 6-month internship with Renliwo Network, where I honed my full-stack development skills. Ideally, I would like to continue to specialize in software engineering in the area including web app dev., data infra. engineering and system engineering.

Recent work
======  

BCNC | Asian Impact & Equity (In progess)
------
*About BCNC: Since 1969, Boston Chinatown Neighborhood Center (BCNC) 
has been a vital presence in Greater Boston and beyond, empowering Asians and new immigrants to build healthy families, achieve greater economic success, 
and contribute to thriving communities.*

There is a lack of access and understanding around Asian data around 
the social determinants and outcomes of health. 
Partly it is due to the Model Minority Myth as well as the challenge of 
the diversity of who makes up the category "Asian" and "Asian American." 
Over the last 12 to 18 months during the COVID pandemic as well as the 
increase in attention to Black Lives Matter and racial equity, 
focus and data on the impact of racism and inequity has been limited. 
Article after article about education, health, 
economics focused on some communities of color while leaving out or 
not considering Asian data. With there being the widest range of income 
inequality in the Asian community, the issue is complex.

I have a vision of making Asian data using the recent Census, 
American Community Survey data, and other resources more 
available to nonprofits, organizers, policy makers, elected officials, 
academics, and average citizens. The MetroWest Foundation's Initiative 
"Impact MetroWest'' was my inspiration for the creation of a website that 
allows for one to easily access and "slice and dice" the data so for 
example, one can drill down to the needs of different parts of the Asian diaspora. Vietnamese immigrants 
and Chinese Immigrants are different from Taiwanese immigrants.


Adaptive checkpointing in Apache Flink (In progess)
------
Design, implement, and evaluate an adaptive checkpointing mechanism that will automatically adjust the checkpoint interval based on:  
   (i) system metrics  
   (ii) user-defined constraints  

Online Education Web App(In progess)
------
*Paticipate in Harvard Innovation Labs As Venture*


A Fault-Tolerant key/value Storage System(In progess)
------
1. Implement Raft, a replicated state machine protocol
2. Build a key/value service on top of Raft
3. Shard service over multiple replicated state machines for higher performance

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
