```html
<div class="left triangle"></div>
<div class="big-circle middle"></div>
<div class="middle-circle middle"></div>
<div class="small-circle middle"></div>
<div class="right triangle"></div>
<style>
  body {
    background: #0b2429;
  }

  .middle {
    position: absolute;
    top: 150px;
    left: 200px;
    transform: translate(-50%, -50%);
    height: 100%;
  }

  .left {
    border-width: 60px 60px 60px 0px;
    border-color: transparent #998235 transparent transparent;
    position: absolute;
    top: 90px;
    left: 59px;
  }

  .right {
    border-width: 60px 0px 60px 60px;
    border-color: transparent transparent transparent #998235;
    position: absolute;
    top: 90px;
    right: 59px;
  }

  .triangle {
    width: 0px;
    height: 0px;
    border-style: solid;
  }

  .big-circle {
    width: 200px;
    height: 200px;
    background: #998235;
    border-radius: 50%;
    z-index: 1;
  }

  .middle-circle {
    width: 180px;
    height: 180px;
    background: #0b2429;
    border-radius: 50%;
    z-index: 2;
  }

  .small-circle {
    width: 140px;
    height: 140px;
    background: #f3ac3c;
    border-radius: 50%;
    -webkit-mask: radial-gradient(circle at center center, #0000 25px, red 0);
    z-index: 3;
  }
</style>
```
