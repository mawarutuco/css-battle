```html

<div class="bat-body"></div>
<div class="bat-head"></div>
<div class="wing-outer1"></div>
<div class="wing-outer2"></div>
<style>
  .wing-outer2::before,.wing-outer2::after{
    content:' ';
    width:200px;
    height:200px;
    background:#191919;
    border-radius:50%;
    position: absolute;
    top:160;
  }
  .wing-outer2::before{
    left:40;
  }
  .wing-outer2::after{
    right:40;
  }
  .wing-outer1::before,.wing-outer1::after{
    content:' ';
    width:95px;
    height:95px;
    background:#191919;
    border-radius:50%;
    position: absolute;
    top:100;
  }
  .wing-outer1::before{
    left:30;
  }
  .wing-outer1::after{
    right:30;
  }
  .bat-body{
    width:250px;
    height:80px;
    background:#F2AD43;
    position: absolute;
    left:70;
    top:100;
  }
  .bat-body::before{
    content:'';
    width:80px;
    height:30px;
    background:#191919;
    border-radius:0 0 10px 10px ;
    position: absolute;
    left:90;
  }
  .bat-head{
    width:20px;
    height:20px;
    background:#F2AD43;
    position: absolute;
    left:190;
    top:110;
  }
  .bat-head::before,.bat-head::after{
    content:'';
    width:10px;
    height:10px;
    border-radius:50%;
    background:#F2AD43;
    position: absolute;
    top:-5;
  }
  .bat-head::before{
    left:-5;
  }
  .bat-head::after{
    right:-5;
  }
  body{
    background:#191919;
  }
</style>

```