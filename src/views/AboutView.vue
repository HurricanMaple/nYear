<template>
  <div class="about">
    <div>
      <h3>这是一个使用vuejs构建的网页</h3>
      <br>

      <p>本质是 2022 年底制作 Scratch 项目「嗨新年！」使用 Vue.js 构建</p>
      <br>
      
      <footer>(c) 2022 飓枫.  <a href="https://fiee.wtdown.top"> 博客</a> </footer>
      <!-- require APlayer -->

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/aplayer/dist/APlayer.min.css">

<script src="https://cdn.jsdelivr.net/npm/aplayer/dist/APlayer.min.js"></script>

<!-- require MetingJS -->

<script src="https://cdn.jsdelivr.net/npm/meting@2/dist/Meting.min.js"></script>

<meting-js

    server="netease"

    type="playlist"

    id="7633921136">

</meting-js>        

<div style="text-align: center">

    <p style="float:center;height:20px;line-height:20px;margin: 10px 0px 10px 0px;color:#737373;">Copyright © 2022 飓枫

<script async src="https://npm.elemecdn.com/penndu@1.0.0/bsz.js"></script>
        <span id="busuanzi_container_site_pv">本站总访问量<span id="busuanzi_value_site_pv"></span>次</span>
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
