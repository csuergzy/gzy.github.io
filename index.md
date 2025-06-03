---
layout: default
title: "高振源的个人主页"
---

<!--========================================
  简介（Intro）区 → #intro
=========================================-->
<section id="intro">
  <h2 class="section-title">简介</h2>
  <div class="intro-content">
    <!-- 头像：请将 tx.png 放在仓库根目录（和 index.md 同级） -->
    <img src="tx.png" alt="高振源头像" class="profile-pic" />
    <h3>高振源</h3>
    <p>中南大学计算机科学学生 | AIGC &amp; 机器学习爱好者</p>

    <!-- 技术徽章（Badge）示例，可按需增删 -->
    <div class="badges">
      <img class="badge" src="https://img.shields.io/badge/-Python-3572A5?logo=python&logoColor=white" alt="Python" />
      <img class="badge" src="https://img.shields.io/badge/-PyTorch-ee4c2c?logo=pytorch&logoColor=white" alt="PyTorch" />
      <img class="badge" src="https://img.shields.io/badge/-Jekyll-D00?logo=jekyll&logoColor=white" alt="Jekyll" />
      <img class="badge" src="https://img.shields.io/badge/-Git-181717?logo=git&logoColor=white" alt="Git" />
    </div>
  </div>
</section>

<!--========================================
  项目（Projects）区 → #projects
=========================================-->
<section id="projects">
  <h2 class="section-title">项目</h2>

  <!-- 项目卡片 1 -->
  <div class="project-card">
    <div class="project-title">Zero-shot 双域图像风格迁移算法</div>
    <p>
      基于预训练扩散模型，设计两阶段风格注入与自适应调节器，
      实现抽象与具体风格的动态平衡，并在多个数据集上显著优于
      传统方法。  
    </p>
    <p><strong>技术栈：</strong>Python / PyTorch / Stable Diffusion / CLIP</p>
    <p>
      <a href="https://github.com/your-username/zero-shot-style-transfer" target="_blank">项目链接 ▶</a>
    </p>
  </div>

  <!-- 项目卡片 2 -->
  <div class="project-card">
    <div class="project-title">贷款违约预测 Stacking 模型</div>
    <p>
      基于 LightGBM、XGBoost 与 CatBoost 的多模型融合，并使用
      Logistic 回归作为元学习器，实现高精度预测。包括全面的
      特征工程、5 折交叉验证与 OOF 构造。  
    </p>
    <p><strong>技术栈：</strong>Python / LightGBM / XGBoost / CatBoost / scikit-learn</p>
    <p>
      <a href="https://github.com/your-username/loan-default-stacking" target="_blank">项目链接 ▶</a>
    </p>
  </div>

  <!-- 根据需要，可继续添加更多 project-card -->
</section>

<!--========================================
  博客（Blog）区 → #blog
=========================================-->
<section id="blog">
  <h2 class="section-title">博客</h2>
  <ul class="blog-list">
    <!-- 使用 Jekyll 的循环列出最新 5 篇文章 -->
    {% for post in site.posts limit:5 %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <small>（{{ post.date | date: "%Y-%m-%d" }}）</small>
      </li>
    {% endfor %}
  </ul>
  <p style="text-align: center;">
    <a href="/blog" style="font-weight: 500; color: var(--link-color);">查看全部博客文章 ▶</a>
  </p>
</section>

<!--========================================
  联系方式（Contact）区 → #contact
=========================================-->
<section id="contact">
  <h2 class="section-title">联系方式</h2>
  <ul class="contact-list">
    <li>📧 邮箱：<a href="mailto:gaozhenyuan38@gmail.com">gaozhenyuan38@gmail.com</a></li>
    <li>🐙 GitHub：<a href="https://github.com/your-username" target="_blank">github.com/your-username</a></li>
    <li>📝 博客：<a href="https://your-blog.com" target="_blank">your-blog.com</a></li>
  </ul>
</section>
