```html

<div class='trumpet'></div>
<div class='sound-wave'></div>
<style>
  .sound-wave,.sound-wave::before,.sound-wave::after,.trumpet,.trumpet::after{
    position:absolute;
    top:50%;
    transform:translate(0,-50%);
  }
  .trumpet{
    width: 50px;
    height: 50px;
    background:#5DBCF9;
    border-radius:10px 0 0 10px;
    left:75;
  }
  .trumpet::after{
    content:'';
    width: 40px;
    height: 40px;
    border:solid 80px;
    border-color:#0000 #5DBCF9 #0000 #0000;
    transform:translate(-38%,-50%);
  }
  .sound-wave,.sound-wave::before,.sound-wave::after{
    border:#5DBCF9 10px;
    border-style:solid solid solid none;
    border-radius:0 200px 200px 0;
  }
  .sound-wave {
    width: 65px;
    height: 130px;
    left:225;
  }
  .sound-wave::before {
    content:'';
    width: 40px;
    height: 80px;
  }
  .sound-wave::after {
    content:'';
    width: 90px;
    height: 180px;
  }
  body{
    background:#191919;
  }
</style>

```