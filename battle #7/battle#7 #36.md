```html
<div class='container'>
    <div class='yellow'></div>
    <div class='green'></div>
    <div class='yellow'></div>
    <div class='green'></div>
    <div class='yellow'></div>
</div>
<style>
  .green {
    background: #998235;
    border-radius:0 0 50px 50px;
  }
  .yellow {
    background: #F3AC3C;
    border-radius:50px 50px 0 0;
    margin:100px 0 0 0;
  }
  .container{
    display:flex;
    width:95%;
    justify-content:space-around;
    margin:0 0 0 10px;
  }
  div{
     width: 50px;
    height: 200px;
  }
  body {
    background: #1A4341;
    margin:0px;
  }
</style>
```
