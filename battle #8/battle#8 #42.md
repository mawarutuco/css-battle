```html

<div class='face'>
  <div class='hair'></div>
  <div class='hair'></div>
  <div class='eye'></div>
  <div class='eye'></div>
  <div class='month'></div>
</div>
<style>
  .hair{
    width: 100px;
    height: 100px;
    background: #FFF1C1;
    border-radius:100px;
    margin:-50px 00px 20px 0px;  
  }
  .month{
    width: 40px;
    height: 10px;
    background: #FFF1C1;
    border-radius:100px;
    margin:0 50px;
  }
  .eye{
    width: 60px;
    height: 60px;
    background: #FFF1C1;
    border-radius:100px;
  }
  .face {
    width: 200px;
    height: 200px;
    background: #FE5F55;
    border-radius:100px 100px 50px 50px;
    position:absolute;
    transform:translate(-50%,-50%);
    top:50%;
    left:50%;
    display:flex;
    justify-content:space-around;
    flex-wrap:wrap;
    overflow:hidden;
  }
    body{
    background:#293462;
  }
</style>


```
