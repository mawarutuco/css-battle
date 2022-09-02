```html
<div class="left hollow-circle"></div>
<div class="bridge"></div>
<div class="right hollow-circle"></div>
<div class="top circle-mask"></div>
<div class="bottom circle-mask"></div>
<div class="top circle"></div>
<div class="bottom circle"></div>
<style>
  .circle {
    background: #f5bb9c;
    width: 60px;
    height: 60px;
    border-radius: 100%;
  }

  .circle-mask {
    background: #09042a;
    width: 80px;
    height: 80px;
    border-radius: 100%;
  }

  .hollow-circle {
    background: #e78481;
    width: 80px;
    height: 80px;
    border-radius: 100%;
    -webkit-mask: radial-gradient(circle at 40px, #0000 30px, red 0px);
  }

  .top {
    position: absolute;
    transform: translate(-50%, -50%);
    left: 200px;
    top: 97.5px;
  }

  .bottom {
    position: absolute;
    transform: translate(-50%, -50%);
    left: 200px;
    top: 202.5px;
  }

  .left {
    position: absolute;
    transform: translate(-50%, -50%);
    left: 140px;
    top: 150px;
  }

  .right {
    position: absolute;
    transform: translate(-50%, -50%);
    left: 260px;
    top: 150px;
  }

  .bridge {
    width: 50px;
    height: 45px;
    background: #e78481;
    position: absolute;
    transform: translate(-50%, -50%);
    left: 200px;
    top: 150px;
  }

  body {
    background: #09042a;
  }
</style>
```
