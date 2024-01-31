---
permalink: /
title: "Longkun's Homepage"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**Dr. Guo** is a Professor with the School of Mathematics and Statistics, Fuzhou University, since 2019. He received B.S. and Ph.D. degrees in Computer Science from the University of Science and Technology of China (USTC) in 2005 and 2011, respectively. He did his postdocs at The University of Adelaide.
He has published more than 100 academic papers in reputable journals/conferences such as IEEE TMC, IEEE TC,  Algorithmica, IEEE TPDS, IEEE ICDCS, AAAI, IJCAI, and ACM SPAA.

Research Interesting
======
Efficient algorithm design; Computational complexity analysis for optimization problems in data science; high-performance computing systems and networks

Getting started
======
- **Longkun Guo**, Chaoqi Jia, Kewen Liao,  Zhigang Lu, Minhui Xue: Efficient Constrained $k$-Center Clustering with Background Knowledge, *[In Proceedings of the 38th AAAI Conference on Artificial Intelligence (AAAI-24)](https://aaai.org/aaai-conference/)*, AAAI, Vancouver, Canada, pp. TBA.
  (Top-2 Conference in Artificial Intelligence)
- Pei Yao (Supervised student), **Longkun Guo***, Peng Li, Jiawei Lin: Optimal Algorithm for Min-Max Line Barrier Coverage with Mobile Sensors on 2-Dimensional Plane. *[Comput. Networks](https://dblp.uni-trier.de/db/journals/cn/cn228.html#YaoGLL23)* 228: 109717 (2023) 
- **Longkun Guo**, Wenjie Zou, Chenchen Wu, Dachuan Xu, Ding-Zhu Du: MinSum Movement of Barrier and Target Coverage using Sink-based Mobile Sensors on the Plane. *[ICDCS 2021](https://dblp.uni-trier.de/db/conf/icdcs/icdcs2021.html#GuoZWXD21)*: 696-706  
- **Longkun Guo**, Yunyun Deng, Kewen Liao, Qiang He, Timos Sellis, Zheshan Hu: A Fast Algorithm for Optimally Finding Partially Disjoint Shortest Paths. *[IJCAI 2018](https://dblp.uni-trier.de/db/conf/ijcai/ijcai2018.html#GuoDLHSH18)*: 1456-1462 PDF 
- **Longkun Guo**, Hong Shen: Efficient Approximation Algorithms for the Bounded Flexible Scheduling Problem in Clouds. *[IEEE Trans. Parallel Distributed Syst](https://dblp.uni-trier.de/db/journals/tpds/tpds28.html#GuoS17)*. 28(12): 3511-3520 (2017) 
- **Longkun Guo**, Hong Shen, Wenxing Zhu: Efficient Approximation Algorithms for Multi-Antennae Largest Weight Data Retrieval. *[IEEE Trans. Mob. Comput](https://dblp.uni-trier.de/db/journals/tmc/tmc16.html#GuoSZ17)*. 16(12): 3320-3333 (2017) 

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
