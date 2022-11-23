```html

<div class='up'></div>
<div class='down'></div>
<style>
  .up,.up::after,.down,.down::after{
    width:0;
    height:0;
    border-style:solid;
    position:absolute;
  }
  .up,.up::after {
    border-width:0px 75px 130px  75px;
  }
  .up {
    border-color:#FF6D00 #0000 ;
    left:190;
  }
  .up::after {
    content:'';
    border-color:#FD4602 #0000 ;
    left:-95;
  }

  .up,.down{
    top:85;
  }
  
  .down,.down::after {
    border-width:130px 75px 0px 75px;
  }
  .down {
    border-color:#FD4602 #0000 ;
    left:80;
  }
  .down::after {
    content:'';
    border-color:#FF6D00 #0000 ;
    top:-130;
    left:-95;
  }
  body{
    background:#F2F2B6;
  }
</style>

```
