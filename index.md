<!-- index.md -->
---
layout: default
title: 高振源
---

<div align="center">
  <img src="tx.png" alt="Avatar" width="200" style="border-radius: 50%;">
  <h1>你好，我是高振源</h1>
  <p>计算机科学学生 │ AIGC & 机器学习爱好者</p>
</div>

---

## 关于我

我是一名中南大学计算机学院学生，热衷于人工智能、深度学习与算法研究。  
喜欢探索前沿技术，积极参与各类竞赛与科研项目，擅长将理论与实践相结合。

---

## 技能与技术

- **编程语言**：Python、C++、Java  
- **机器学习/深度学习**：TensorFlow、PyTorch、LightGBM、XGBoost、CatBoost  
- **前端开发**：HTML、CSS、JavaScript  
- **工具与平台**：Git、GitHub、Jupyter Notebook、Linux  

---

## 项目展示

### Zero-shot 双域图像风格迁移算法
基于预训练扩散模型，设计两阶段风格注入与自适应调节器，实现抽象与具体风格的动态平衡，显著提升迁移质量并减少内容泄露。  
- 技术栈：Python、PyTorch、Stable Diffusion、CLIP  
- 关键亮点：  
  - 两阶段注入：先保留内容结构，再逐步引入风格特征  
  - 自适应调节：借助多模态模型动态控制风格强度  
- [项目链接](https://github.com/your-username/zero-shot-style-transfer)

---

### 贷款违约预测 Stacking 模型
基于 LightGBM、XGBoost 与 CatBoost 进行多模型融合，并使用 Logistic 回归作为元学习器，实现高精度预测。  
- 技术栈：Python、LightGBM、XGBoost、CatBoost、scikit-learn  
- 关键亮点：  
  - 多层次特征工程：数值特征转换、时间特征提取、缺失值指示器  
  - 5 折交叉验证 & OOF（Out-of-Fold）构造二层训练集  
- [项目链接](https://github.com/your-username/loan-default-stacking)

---

## 联系方式

- 📧 邮箱：gaozhenyuan38@gmail.com  
- 🌐 GitHub：[github.com/your-username](https://github.com/your-username)  
- 🖥️ 个人博客：[your-blog.com](https://your-blog.com)（可选）

---

> **提示**：  
> 1. 把上述文件放到仓库根目录下，确保 `tx.png` 与这两个文件在同一目录。  
> 2. 根据需要，将 `your-username` 替换为你的 GitHub 用户名，将 URL、项目链接等替换成真实地址。  
> 3. 如果想自定义更多样式，可以切换主题（如 `jekyll-theme-cayman` → `jekyll-theme-midnight` 等），或者在仓库中新建 `_sass`、`assets/css` 等文件自定义 CSS。  

完成后，推送到名为 `your-username.github.io` 的仓库，GitHub 会自动触发 Jekyll 构建，你的个人主页就能在 `https://your-username.github.io` 访问了。
