<template>
  <div class="greetings">
    <h1 class="t-color">nYear</h1>
    <h3>
      当新的一年将至，何必出外受寒，宅在家跨年岂不美哉？<br>
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-family: consolas, 'Shippori Mincho', monospace;
  font-weight: 800;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.t-color {
  display: inline-block;
  position: relative;
  text-shadow: 0 0 8px #AA3344CC;
}

.t-color:before {
  background-color: #AA334444;
  border-radius: 999px;
  color: #AA334466;
  content: '';
  padding: 25px;
  position: absolute;
  z-index: -1;

  width: 100px;
  height: 100px;

  top: -32px;
  left: -12px;
}

.t-color:after {
  background-color: #AA334411;
  color: #AA334466;
  content: '新年快乐';
  font-size: 24px;
  line-height: 0.8;
  padding: 0 8px;
  position: absolute;
  text-shadow: none;
  z-index: -1;

  bottom: -2px;
  right: -32px;
}

/* 手機端 */
.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
