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

<!-- 第三个论文条目 -->
<div class="publication-item">
    <div class="image">
        <a href="/images/gallery/paper3.png">
            <img src="/images/gallery/paper3.png" alt="论文3配图">
        </a>
    </div>
    <div class="content">
        <div class="citation">
            Yaonaiming Zhao, Qiang Zou*, Guoyue Luo, Jiayu Wu, Sifan Chen, Depeng Gao, Minghao Xuan, Fuyu Wang, 
            "TPMS2STEP: error-controlled and C2 continuity-preserving translation of TPMS models to STEP files based on constrained-PIA",  
            <em>Computer-Aided Design</em> (2024)
        </div>
        <div class="links">
            <a href="https://doi.org/10.1016/j.cad.2024.103726">Paper</a>
            <a href="https://github.com/Qiang-Zou/TPMS2STEP">Code</a>
        </div>
    </div>
</div>

<!-- 继续添加更多条目... -->

Skills
======
1. Familiar with C/C++, Python, CUDA programing, Pytorch framework
1. Familiar with mesh processing techniques, heuristic algorithms, diffusion models, InstantNGP, QAT
1. Getting familiar with 3DGS, 3DGS Compression 
1. Familiar with CAD tools like NX, meshlab 

