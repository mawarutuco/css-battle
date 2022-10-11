```html

<div class='line-row'></div>
<div class='big squre'></div>
<div class='small squre'></div>
<div class='line-col'></div>

<style>
  .line-row{
    width: 270px;
    height: 30px;
    background:#998235;
    top:80%
  }
  .line-col{
    width: 30px;
    height: 100%;
    background:#F3AC3C;
  }
  .squre{
    border-style: solid;
    border-width: 0px 30px 30px 30px;
  }
  .small {
    width: 90px;
    height: 120px;
    border-color: #0000 #998235 #998235 #998235;
  }
  .big {
    width: 210px;
    height: 180px;
    border-color: #0000 #F3AC3C #F3AC3C #F3AC3C;
  }
  div{
    position:absolute;
    transform:translate(-50%);
    left:50%;
  }
  body{
    background:#1A4341;
    margin:0;
  }
</style>

```
