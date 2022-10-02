```html
<div class="bottom"></div>
<div class="middle"></div>
<div class="top"></div>
<style>
  .bottom {
    top: 150px;
    border-color: #0000 #0000 #00a79d #0000;
  }
  .middle {
    top: 100px;
    border-color: #0000 #0000 #f5c181 #0000;
  }
  .top {
    top: 50px;
    border-color: #0000 #0000 #ffeecf #0000;
  }
  div {
    width: 0px;
    height: 0px;
    border-style: solid;
    border-width: 0 125px 100px 125px;
    position: absolute;
    left: 50%;
    transform: translate(-50%, 0);
  }
  body {
    background: #007065;
  }
</style>
```
