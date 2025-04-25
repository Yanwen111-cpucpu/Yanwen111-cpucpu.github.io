---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm currently a Master student from  [The Department of Mechanical Engineering](https://me.berkeley.edu/) at [UC Berkeley](https://www.berkeley.edu/). Robotics bimanual manipulation, data collection interface are two fields I'm working on. I'm fortunate to cooperate with PhDs and postdocs in [MSC Lab](https://msc.berkeley.edu/) led by [Prof.Masayoshi Tomizuka](https://me.berkeley.edu/people/masayoshi-tomizuka/).

Before my journey at Berkeley, I received my Bachelor's degree from [School of Mechanical and Engineering](https://me.sjtu.edu.cn/), Qian Xuesen Class at [Shanghai Jiaotong University](https://www.sjtu.edu.cn/). After graduation, I was pursuing a Master's degree in Finance from [SAIF](https://www.saif.sjtu.edu.cn/) at Shanghai Jiaotong University and then dropped out.

I also interned in [Grasp Lab at Zhejiang University](https://grasplab2022.github.io/) and robotics startup [Maxinsghts](https://www.maxinsights.ai/).

I spent most of time doing these:
======
### 🤖 Dual-arm Robot Grasping

Here is a demo of a bimanual robot performing a bottle cap twisting task:

![Dual-arm Task](images/dual_arm_twist.gif)

---

### 📦 Few-shot Sim2Real with Force-feedback Teleop Interfeace

We designed a GELLO-based robotics teleop decive with a torque-enabled scroll wheel as end effector, collecting most of data in Sim of 3-level rendering.
It turns out that high-fidelity rendering improves success rate in final deployment, and force-feedback speeds up the demonstration process.
<div class="flex-container">
  <div class="left-image">
    <img src="/images/sim_collection.gif" width="45%" alt="左侧动图">
  </div>
  <div class="right-column">
    <img src="/images/render1.gif" width="45%" alt="右上动图">
    <img src="/images/render2.gif" width="45%" alt="右中动图">
    <img src="/images/render3.gif" width="45%" alt="右下动图">
  </div>
</div>



Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
