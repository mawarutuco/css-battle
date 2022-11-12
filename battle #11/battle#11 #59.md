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
    background: linear-gradient( 
      #4F77FF 0%,#4F77FF 20%,
      #191919 20% ,#191919 26%,
      #4F77FF 26%,#4F77FF 47%,
      #191919 47% ,#191919 53%,
      #4F77FF 53%,#4F77FF 73%,
      #191919 73% ,#191919 80% ,
      #4F77FF 80% ,#4F77FF 100% 
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