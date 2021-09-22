---
permalink: /
title: " "
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently an associate professor with College of Computer and Information at Hohai University, China. I received B.Eng. and M.Eng. degrees from Beijing Jiaotong University, Beijing, China, in 2005 and 2007, respectively, and Ph.D. degree from Nanyang Technological University, Singapore, in 2014. I have published more than 20 papers on image/video coding, image/video communication and resource allocation, including IEEE Trans. on Circuits and Systems for Video Technology, IEEE Trans. on Wireless Communications, IEEE Trans. on on Mobile Computing, Signal Processing: Image Communication. My research interests include image/video coding, image/video communication, immersive videos, visual perception and applications, etc.

Pulication
======
**Selected Journal papers**
1.	Kun Zhu, Lujiu Li, Yuanyuan Xu*, Tong Zhang, Lu Zhou, "Multi-Connection Based Scalable Video Streaming in UDNs: A Multi-Agent Multi-Armed Bandit Approach," IEEE Transactions on Wireless Communications, Early access, 2021.
1.	Kun Zhu, Yuanyuan Xu*, Jun Qian, and Dusit Niyato, "Revenue Optimal Auction For Resource Allocation in Wireless Virtualization: A Deep Learning Approach," IEEE Transactions on Mobile Computing, Sept. 2020. 
1.	Yuanyuan Xu, “Predictive Side Decoding for Human-Centered Multiple Description Image Coding”, EURASIP Journal on Wireless Communications and Networking, no. 93, May 2020.
1.	Yuanyuan Xu, Kun Zhu*, “Cost Sensitive Learning Based HEVC Screen Content Intra Coding for Mobile Devices”, Mobile Networks and Applications, vol. 25, pp.2471-2481, June 2020.
1.	Yuanyuan Xu, Kun Zhu*, and Shan Li, “Hierarchical Combinatorial Auction in Computing Resource Allocation for Mobile Blockchain”, Wireless Communications and Mobile Computing, vol. 2020, Aug 2020.
1.	Yuanyuan Xu*, Shan Li and Yixuan Zhang, “Privacy-Aware Service Subscription in People-Centric Sensing: A Combinatorial Auction Approach”, Computers, Materials & Continua, vol. 61, no.1, pp.129-139, Oct. 2019.
1.	Xiang Zhang*, Ce Zhu, Honggang Wu, Zhi Liu, and Yuangyuan Xu, “An imbalance compensation framework for background subtraction,” IEEE Transactions on Multimedia, vol. 19, no. 11. pp. 2425-2438, Nov. 2017. 
1.	Yuanyuan Xu*, Ce Zhu, Lu Yu, “Multipath Routing of Multiple Description Coded Images in Wireless Networks,” Journal of Computer Science and Technology, vol.29, issue 4, pp.576-588, July 2014.
1.	Yuanyuan Xu, Ce Zhu*, “End-to-End Rate-Distortion Optimized Description Generation for H.264 Multiple Description Video Coding,” IEEE Trans. on Circuits and Systems for Video Technology, vol.23, no.9, pp.1523-1536, Sept. 2013.
1.	Yuanyuan Xu, Ce Zhu*, “Multi-description Multipath Video Streaming in Wireless Ad Hoc Networks”, Signal Processing: Image Communication, vol. 27, no. 8, pp. 836-848, 2012.
1.	Yuanyuan Xu, Ce Zhu*, Wenjun Zeng, Xuejun Li, “Multiple Description Coded Video Streaming in Peer-to-peer Networks”, Signal Processing: Image Communication, vol. 27, no. 5, pp. 419–429, 2012.



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
