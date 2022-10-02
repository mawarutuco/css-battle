```html
<div class="big-circle"></div>
<div class="yellow right-top"></div>
<div class="yellow left-bottom"></div>

<style>
  .left-bottom {
    border-radius: 0 0 0 140px;
    bottom: 80px;
    right: 50%;
    -webkit-mask: radial-gradient(circle at right top, #0000 40px, red 0);
  }
  .right-top {
    border-radius: 0 140px 0 0;
    top: 80px;
    left: 50%;
    -webkit-mask: radial-gradient(circle at left bottom, #0000 40px, red 0);
  }
  .yellow {
    width: 70px;
    height: 70px;
    background: #f7ec7d;
  }
  .big-circle {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    background: #aa445f;
    transform: translate(-50%, -50%);
    top: 50%;
    left: 50%;
  }
  div {
    position: absolute;
  }
  body {
    background: #e38f66;
  }
</style>
```
