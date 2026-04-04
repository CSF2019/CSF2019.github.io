---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently pursuing a doctor’s degree at the School of Computer Science, Zhejiang University (2022-present). I am affiliated with the [State Key Laboratory of CAD & CG](http://www.cad.zju.edu.cn/), where I am supervised by Prof. [Qiang Zou](https://qiang-zou.github.io/) . Prior to this, I completed my undergraduate studies at Jiangnan University(2015-2019), and experienced one and a half year at the School of Ocean, Zhejiang University(2020-2022), as a master student.

 My research interests include but are not limited to geometric modeling, implicit neural representations, generative AI, and parallel computing. Currently, I’m working on lattice structure modeling, including automatic design, compression, generation and editing.

Publications
======
<style>
/* 每个论文条目容器 */
.publication-item {
    display: flex;           /* 使用flex布局实现图片和文字并排 */
    gap: 20px;              /* 图片和右侧内容之间的间距 */
    margin-bottom: 3rem;    /* 条目之间的较大间距 */
    align-items: flex-start; /* 顶部对齐，避免拉伸 */
}

/* 图片容器 */
.publication-item .image {
    flex: 0 0 150px;        /* 固定图片宽度为150px（可根据需要调整） */
}

.publication-item .image img {
    width: 100%;            /* 图片填满容器宽度 */
    height: auto;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

/* 右侧文字和链接容器 */
.publication-item .content {
    flex: 1;                /* 占据剩余空间 */
}

/* 论文标题/作者行 */
.publication-item .citation {
    margin: 0 0 8px 0;
    line-height: 1.4;
}

/* 链接区域 */
.publication-item .links {
    margin-top: 5px;
}

.publication-item .links a {
    margin-right: 12px;
    text-decoration: none;
    border-bottom: 1px solid #0366d6;
}

/* 响应式：当屏幕过窄时，改为上下堆叠 */
@media (max-width: 600px) {
    .publication-item {
        flex-direction: column;
        gap: 10px;
    }
    .publication-item .image {
        flex-basis: auto;
        max-width: 200px;
    }
}
</style>

<!-- 第一个论文条目 -->
<div class="publication-item">
    <div class="image">
        <a href="/images/gallery/paper1.png">
            <img src="/images/gallery/paper1.png" alt="论文1配图">
        </a>
    </div>
    <div class="content">
        <div class="citation">
            Sifan Chen, Guoyue Luo, Yuan Kong*, Qiang Zou*, 
            "A Quasi-Optimal Shape Design Method for Lattice Structure Construction", 
            <em>ASME Trans. JMD</em> (2025)
        </div>
        <div class="links">
            <a href="https://doi.org/10.1115/1.4068955">Paper</a>
            <a href="https://github.com/Qiang-Zou/LatticeConstruction">Code</a>
        </div>
    </div>
</div>

<!-- 第二个论文条目 -->
<div class="publication-item">
    <div class="image">
        <a href="/images/gallery/paper2.png">
            <img src="/images/gallery/paper2.png" alt="论文2配图">
        </a>
    </div>
    <div class="content">
        <div class="citation">
            Qiang Zou*, Yunzhu Gao, Guoyue Luo, Sifan Chen, 
            "Meta-meshing and triangulating lattice structures at a large scale", 
            <em>Computer-Aided Design</em> (2024)
        </div>
        <div class="links">
            <a href="https://doi.org/10.1016/j.cad.2024.103732">Paper</a>
            <a href="https://github.com/Qiang-Zou/MetaMesh">Code</a>
        </div>
    </div>
</div>

<!-- 继续添加更多条目... -->

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
