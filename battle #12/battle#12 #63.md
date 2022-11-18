```html

<div class='lt'></div>
<div class='rt'></div>
<div class='rb'></div>
<div class='lb'></div>
<div class='squre'></div>
<style>
  .lb {
    border-radius:50px 0  50px 50px ;
  }
  .rb {
    border-radius:0 50px 50px 50px ;
  }
  .rt {
    border-radius:50px 50px 50px 0 ;
  }
  .lt {
    border-radius:50px 50px 0 50px;
  }
  .rt,.rb{
    right:105px;
  }
  .lb,.rb{
    bottom:55px;
  }
  .lt,.lb{
    left:105px;
  }
  .lt,.rt{
    top:55px;
  }
  .squre{
    left:165;
    top:115;
  }
  .lt,.rt,.rb,.lb,.squre{
    width: 50px;
    height: 50px;
    background: #191919;
    border:10px solid #5DBCF9;
    position:absolute;
  }
  body{
    background:#191919;
  }
</style>

```