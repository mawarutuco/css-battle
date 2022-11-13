```html

<div class='circle'>
  <div class='middle-line'></div>
</div>
<div class='circle-line left-line'></div>
<div class='circle-line right-line'></div>

<style>
  .circle {
    width: 150px;
    height: 150px;
    background: repeating-linear-gradient( 
      #4F77FF ,#4F77FF 30px,
      #191919 30px ,#191919 40px
    );
    border-radius:50%;
    left:50%;
  }
  .circle-line{
    width: 200px;
    height: 200px;
    border-radius:50%;
    border:#191919 solid 10px;
  }
  .right-line{
    left:135px
  }
  .left-line{
    left:265px
  }
  .middle-line{
    width: 10px;
    height: 300px;
    background:#191919;
    left:50%;
  }
  div{
    transform:translate(-50%,-50%);
    position:absolute;
    top:50%;
  }
  body{
    background:#191919;
  }
</style>

```