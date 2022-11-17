```html

<div class='main'>
  <div class='arc'></div>
</div>
<div class='semicircle left'></div>
<div class='semicircle right'></div>
<style>
  .semicircle {
    width: 20px;
    height: 10px;
    border-radius:20px 20px 0 0 ;
    background:#FFF58F;
    position:absolute;
    top:140;
  }
  .right{
     right:140;
  }
  .left{
     left:140;
  }
  .arc {
    width: 80px;
    height: 40px;
    border-radius:0 0 80px 80px;
    border: solid #FFF58F;
    border-width:0 20 20 20;
    margin:50 -10;
  }
  .main {
    width: 100px;
    height: 100px;
    background: #E08027;
    border-radius:50%;
    border:30px solid #824B20;
    margin:70 auto;
  }
  body{
    background:#191919;
  }
</style>

```