```html
<div class="left">
  <div class="small"></div>
</div>
<div class="right"></div>

<style>
  .small {
    width: 30px;
    height: 30px;
    background: #0b2429;
    border-radius: 100%;
    transform: translate(-25%, -150%);
  }
  .right {
    width: 100px;
    height: 100px;
    background: #f3ac3c;
    border-radius: 0 100px 0 0;
    transform: translate(0, -100%);
  }
  .left {
    width: 75px;
    height: 150px;
    background: #998235;
    border-radius: 100px 0 0 100px;
    transform: translate(-100%, -50%);
  }
  div {
    position: absolute;
    left: 50%;
    top: 50%;
  }
  body {
    background: #1a4341;
  }
</style>
```
