---
layout: default
title: 算法与编程笔记
---

<!-- 字体 & 动效 & 样式库 -->
<link href="https://fonts.googleapis.com/css2?family=Fira+Code&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- 自定义样式 -->
<style>
  body {
    font-family: 'Fira Code', monospace;
    background: #fdfdfd;
    padding: 40px 20px;
  }
  h1, h2 {
    text-align: center;
    color: #2c3e50;
  }
  .section-title {
    margin-top: 50px;
    margin-bottom: 20px;
    border-bottom: 2px solid #ccc;
    display: inline-block;
    padding-bottom: 5px;
  }
  .card-title {
    font-weight: bold;
    color: #0077cc;
  }
  .card-text {
    font-size: 0.95em;
  }
</style>

<!-- 欢迎标题 -->
<div class="text-center animate__animated animate__fadeInDown">
  <h1>📘 算法与编程学习笔记</h1>
  <p class="lead">记录算法题解、编程语言知识、实用技巧</p>
</div>

<!-- 专栏部分 -->
<div class="container mt-5">
  <h2 class="section-title">📚 专栏目录</h2>
  <div class="row g-4">

    <div class="col-md-4">
      <div class="card shadow-sm animate__animated animate__fadeInUp">
        <div class="card-body">
          <h5 class="card-title">🧮 算法基础</h5>
          <p class="card-text">包括排序、递归、动态规划、贪心等经典算法总结。</p>
          <a href="#算法" class="btn btn-sm btn-outline-primary">查看内容</a>
        </div>
      </div>
    </div>

    <div class="col-md-4">
      <div class="card shadow-sm animate__animated animate__fadeInUp animate__delay-1s">
        <div class="card-body">
          <h5 class="card-title">💡 题目题解</h5>
          <p class="card-text">整理各类算法题的思路分析与代码实现（Leetcode/蓝桥杯等）。</p>
          <a href="#题解" class="btn btn-sm btn-outline-primary">查看内容</a>
        </div>
      </div>
    </div>

    <div class="col-md-4">
      <div class="card shadow-sm animate__animated animate__fadeInUp animate__delay-2s">
        <div class="card-body">
          <h5 class="card-title">⚙️ 编程语言</h5>
          <p class="card-text">总结 C++、Python、JavaScript 等语言的常用语法和技巧。</p>
          <a href="#语言" class="btn btn-sm btn-outline-primary">查看内容</a>
        </div>
      </div>
    </div>

  </div>
</div>

<!-- 内容占位符：你可以在这里写 Markdown 文章或链接 -->

---

## 🧮 算法基础 {#算法}

- [x] 快速排序与归并排序讲解
- [x] 背包九讲整理（01背包、完全背包、多重背包等）
- [x] 图论基础：DFS/BFS、最短路、并查集

👉 更多内容持续更新中...

---

## 💡 题目题解 {#题解}

- ✅ Leetcode 经典题整理
- ✅ 蓝桥杯刷题记录
- ✅ 动态规划实战题解（含思路 + 状态转移 + 优化）

📝 每篇题解使用 Markdown 编写，图文并茂！

---

## ⚙️ 编程语言 {#语言}

### C++ 常用写法

```cpp
for (int i = 0; i < n; ++i) {
  cout << a[i] << " ";
}
```

### python 语法简明笔记
```python
nums = [1, 2, 3]
print([x**2 for x in nums if x % 2 == 0])
```