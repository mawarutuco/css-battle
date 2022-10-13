```html

<div class='line line1'></div>
<div class='line line2'></div>
<div class='line line3'></div>
<div class='plate'>
    <div class='hole hole1'></div>
    <div class='hole hole2'></div>
    <div class='hole hole3'></div>
</div>
    
<style>
  .line3 {
    top:65px;
    left:203px;
    transform:rotate(120deg)
  }
  .line2 {
    top:55px;
    left:203px;
    transform:rotate(60deg)
  }
  .line1 {
    top:140px;
    left:50%;
  }
  .line {
    width: 10px;
    height: 180px;
    border-radius:10px;
  }
  .hole3 {
    width: 20px;
    height: 20px;
    top:75px;
    left:50px;
  }
  .hole2 {
    width: 10px;
    height: 10px;
    top:25px;
    left:75px;
  }
  .hole1 {
    width: 30px;
    height: 30px;
    top:35px;
    left:35px;
  }
  .hole {
    background: #998235;
  }
  .plate {
    width: 100px;
    height: 100px;
    top:50%;
    left:50%;
  }
  div{
    position:absolute;
    transform:translate(-50%,-50%);
    border-radius:100%;
    background: #F3AC3C;
  }
  body{
    background:#1A4341;
  }
</style>

```