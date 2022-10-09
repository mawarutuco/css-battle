```html

<div class='left left-outer outer'>
  <div class='left left-inner inner'></div>
</div>
<div class='right-outer outer right'>
  <div class='right-inner inner right'></div>
</div>
<style>
  .inner {
    width: 40px; 
    height: 180px;
    background:#6592CF;
  }
  .right-inner {
     transform:translate(50%,-50%);
  }
  .left-inner {
     transform:translate(0,-50%);
  }
  .right-outer {
    right:29%;
  }
  .left-outer {
    left:44%;
  }
  .right {
    border-radius: 80px 0 0 80px ;
  }
  .left {
    border-radius: 0 80px 80px  0;
  }
  .outer{
    width: 60px; 
    height: 240px;
    background:#243D83;
    transform:translate(-50%,-50%);
  }
  div{
    position:absolute;
    top:50%;
  }
  body{
    background:#6592CF;
  }
</style>

```
