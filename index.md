---
layout: default
title: 高振源
---

<!-- ─────────────── 个人简介（ABOUT） ─────────────────────────────────── -->
<section id="about">
  <div class="intro">
    <img src="tx.png" alt="高振源 头像" class="avatar">

    <h1>你好，我是高振源</h1>
    <p>中南大学计算机科学学生 │ AIGC & 机器学习爱好者</p>

    <!-- 技能徽章（Badges） -->
    <div class="badges">
      <img class="badge" src="https://img.shields.io/badge/Python-3670A0?logo=python&logoColor=white" alt="Python">
      <img class="badge" src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white" alt="PyTorch">
      <img class="badge" src="https://img.shields.io/badge/LightGBM-00A2FF?logo=lightgbm&logoColor=white" alt="LightGBM">
      <img class="badge" src="https://img.shields.io/badge/Jekyll-CC0000?logo=jekyll&logoColor=white" alt="Jekyll">
    </div>

    <!-- 访客统计徽章 -->
    <p>
      ![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=your-username.your-username.github.io)
    </p>
  </div>
</section>

---

<!-- ─────────────── 项目展示（PROJECTS） ─────────────────────────────────── -->
<section id="projects">
  <h2>项目</h2>

  <div class="project-card">
    <h3>Zero-shot 双域图像风格迁移算法</h3>
    <p>基于预训练扩散模型，设计两阶段风格注入与自适应调节器，实现抽象与具体风格的动态平衡。</p>
    <ul>
      <li>技术栈：Python、PyTorch、Stable Diffusion、CLIP</li>
      <li>🔗 <a href="https://github.com/your-username/zero-shot-style-transfer" target="_blank">项目链接</a></li>
    </ul>
    <img src="assets/images/tx.png" alt="风格迁移演示" width="300">
  </div>

  <div class="project-card">
    <h3>贷款违约预测 Stacking 模型</h3>
    <p>基于 LightGBM、XGBoost 与 CatBoost 进行多模型融合，并使用 Logistic 回归作为元学习器，实现高精度预测。</p>
    <ul>
      <li>技术栈：Python、LightGBM、XGBoost、CatBoost、scikit-learn</li>
      <li>🔗 <a href="https://github.com/your-username/loan-default-stacking" target="_blank">项目链接</a></li>
    </ul>
    <img src="assets/images/tx.png" alt="Stacking 模型演示" width="300">
  </div>

  <!-- 动态 Trending 列表（每晚自动更新） -->
  <div class="trending">
    <h3>今日 GitHub 趋势仓库 (每日更新)</h3>
    {% include trending.md %}
  </div>
</section>

---

<!-- ─────────────── 博客（BLOG） ────────────────────────────────────────────── -->
<section id="blog">
  <h2>博客</h2>
  <ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>（{{ post.date | date: "%Y-%m-%d" }}）</small>
    </li>
  {% endfor %}
  </ul>
  <p><a href="/blog">查看更多博文 →</a></p>
</section>

---

<!-- ─────────────── 联系方式（CONTACT） ─────────────────────────────────── -->
<section id="contact">
  <h2>联系方式</h2>
  <ul>
    <li>📧 邮箱：<a href="mailto:gaozhenyuan38@gmail.com">gaozhenyuan38@gmail.com</a></li>
    <li>🌐 GitHub：<a href="https://github.com/your-username" target="_blank">github.com/your-username</a></li>
    <li>🖥️ 个人博客：<a href="https://your-blog.com" target="_blank">your-blog.com</a></li>
  </ul>
</section>
