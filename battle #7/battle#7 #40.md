```html

<div class='circle'></div>
<div class='rectangle r1'></div>
<div class='rectangle r2'></div>
<style>
  .r2{
    background:#6592CF;
    left:150px;
  }
  .r1{
    background:#243D83;
    left:100px;
  }
  .rectangle{
    width: 50px;
    height: 100px;
    top:50px;
  }
  .circle {
    width: 200px;
    height: 200px;
    background: radial-gradient(ellipse at center,
    #6592CF 0%, #6592CF 35%,
    #243D83 35%, #243D83 100%);
    border-radius:50%;
    transform:translate(-50%,-50%);
    top:50%;
    left:50%;
  }
  div{
    position:absolute;
  }
  body{
    background:#6592CF;
  }
</style>

```
