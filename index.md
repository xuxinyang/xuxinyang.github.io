---
layout: default
---

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@500&display=swap" rel="stylesheet">

<!-- Animate.css -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>

<!-- Bootstrap -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- 自定义样式 -->
<style>
  body {
    font-family: 'Quicksand', sans-serif;
    background: linear-gradient(to right, #f0f9ff, #d9f9ff);
    padding-top: 50px;
  }
  h1 {
    color: #007ACC;
    text-align: center;
    margin-bottom: 30px;
  }
  .lead {
    text-align: center;
    font-size: 1.3em;
    color: #333;
    margin-bottom: 40px;
  }
  .card-title {
    color: #007ACC;
  }
</style>

<!-- 欢迎标题 -->
<div class="animate__animated animate__fadeInDown">
  <h1>👋 欢迎来到我的 GitHub Pages 网站</h1>
</div>

<p class="lead animate__animated animate__fadeInUp">
  这是一个使用 Jekyll + Markdown + Animate.css 构建的漂亮站点！
</p>

<!-- 卡片展示 -->
<div class="container">
  <div class="row g-4">
    <div class="col-md-4">
      <div class="card shadow-sm animate__animated animate__zoomIn">
        <div class="card-body">
          <h5 class="card-title">✨ 关于我</h5>
          <p class="card-text">这里可以写你的简介、背景或兴趣爱好。</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card shadow-sm animate__animated animate__zoomIn animate__delay-1s">
        <div class="card-body">
          <h5 class="card-title">💼 我的项目</h5>
          <p class="card-text">展示你做过的项目、网站或作品集链接。</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card shadow-sm animate__animated animate__zoomIn animate__delay-2s">
        <div class="card-body">
          <h5 class="card-title">📬 联系方式</h5>
          <p class="card-text">留下你的邮箱、GitHub、微信公众号等。</p>
        </div>
      </div>
    </div>
  </div>
</div>
