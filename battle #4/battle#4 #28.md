```html
<div class="container">
  <div class="circle green"></div>
  <div class="half-circle-top yellow"></div>
  <div class="half-circle-top green"></div>
  <div class="circle yellow"></div>
</div>
<div class="container">
  <div class="half-circle-bottom yellow"></div>
  <div class="circle green"></div>
  <div class="circle yellow"></div>
  <div class="half-circle-bottom green"></div>
</div>
<style>
  .half-circle-bottom {
    width: 50px;
    height: 50px;
    border-radius: 0 0 100px 100px;
  }
  .half-circle-top {
    width: 50px;
    height: 50px;
    border-radius: 100px 100px 0 0;
  }
  .circle {
    width: 50px;
    height: 50px;
    border-radius: 50%;
  }
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .green {
    background: #998235;
  }
  .yellow {
    background: #f3ac3c;
  }
  div {
    margin: 5px 10px 5px 10px;
  }
  body {
    background: #1a4341;
    display: flex;
    justify-content: center;
    flex-direction: column;
    height: 100%;
    margin: 0;
  }
</style>
```
