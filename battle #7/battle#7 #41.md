```html

<div class='c'>
<div class='half'><div class='hole'></div></div>
<div class='half r'><div class='hole2'></div></div>

</div>
<style>

  .hole2{
    width: 50px;
    height: 50px;
    background: #293462;
    border-radius:0 40px 0 0;
    position:absolute;
    bottom:-10px;
  }
  .hole{
    width: 50px;
    height: 50px;
    background: #293462;
    border-radius:0 40px 0 0;
    position:absolute;
    bottom:70px;
  }
 
  .half {
    width: 50px;
    height: 140px;
    background: #FE5F55;
    border-radius:0 40px 0 0;
    display:relative;
     -webkit-mask: radial-gradient(circle at 30px 75px, #0000 15px, red 0); 
  }
  .r {
    transform:rotateY(180deg);
  }
  .c{
    display:flex;
    justify-content:center;
    align-items:center;
    height:100%;
  }
  body{
    background:#293462;
  }
</style>


```
