```html

<div class='window'>
  <div class='sum'></div>
  <div class='left'></div>
  <div class='right'></div>
</div>
<style>
  .right {
    background: #824B20;
    left:150px;
  }
  .left {
    background: #E08027;
  }
  .sum {
    width:60px;
    height:60px;
    background: #FFF58F;
    left:50%;
    top:60%;
  }
  .right,.left{
    width:200px;
    height:200px;
    top:200px;
  }
  .right,.left,.sum{
    border-radius:50%;
    position:absolute;
    transform:translate(-50%,-50%);
  }
  .window {
    width: 150px;
    height: 200px;
    background: #F2AD43;
    border-radius:80px 80px 20px 20px;
    margin:50px auto;
    overflow:hidden;
    position:relative;
  }
  body{
    background:#191919;
  }
</style>

```