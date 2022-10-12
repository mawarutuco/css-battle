```html

<div class='circle'>
  <div class='mountain left'></div>
  <div class='mountain right'></div>
</div>

<style>
  .right{
    border-width:0 90px 90px 90px;   
    top:130px;
    right:80px;
  }
  .left{
    border-width:0 180px 180px 180px;   
    top:60px;
    right:-120px;
  }
  .mountain {
    width: 0px;
    height: 0px;
    border-style:solid;
    border-color:#0000 #0000 #FE5F55 #0000;
    position:absolute;
  }
  .circle {
    width: 200px;
    height: 200px;
    background: #FFF1C1;
    border-radius:100%;
    position:absolute;
    transform:translate(-50%,-50%);
    top:50%;
    left:50%;
    overflow:hidden;
  }
  body{
    background:#293462;
  }
</style>

```
