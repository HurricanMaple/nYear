<template>
  <div class="about">
    <div>
      <h3>这是一个使用vuejs构建的网页</h3>
      <br>

      <p>本质是 2021 年底制作 Scratch 项目「嗨跨年！」使用 Vue.js 的重置版</p>
      <br>
      
      <footer>(c) 2022 飓枫.  <a href="https://fiee.wtdown.top"> 博客</a> </footer>
    </div>
  </div>
</template>

<style>
  footer {
    color: #bbb;
    font-size: 12px;
  }

  .about {
    display: flex;
    padding: 32px;
    justify-items: center;
    justify-content: center;
  }

  @media (min-width: 1024px) {
    .about {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-items: center;
      justify-content: center;
    }
  }
</style>
