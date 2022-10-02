```html
<div class="eye left"></div>
<div class="eye right"></div>
<div class="mouth"></div>

<style>
  div {
    width: 120px;
    height: 60px;
    position: absolute;
  }
  .mouth {
    border-radius: 0 0 60px 60px;
    background: #060f55;
    -webkit-mask: radial-gradient(circle at top, #0000 40px, red 0);
    bottom: 40px;
    left: 140px;
  }
  .eye {
    border-radius: 60px 60px 0 0;
    background: #060f55;
    -webkit-mask: radial-gradient(circle at bottom, #0000 40px, red 0);
    top: 40px;
  }
  .left {
    left: 40px;
  }
  .right {
    right: 40px;
  }
  body {
    background: #6592cf;
  }
</style>
```
