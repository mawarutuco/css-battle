```html
<div class='container'>
  <div class='ticket'></div>
  <div class='hole top'></div>
  <div class='hole bottom'></div>
</div>
<style>
  .ticket {
    width: 200px;
    height: 100px;
    background:linear-gradient(90deg,#F7EC7D 70%,#E38F66 30%);
  -webkit-mask: radial-gradient(circle at 20px 20px, #0000 20px, red 0) -20px -20px; 
  }

.hole{
  width: 20px;
    height: 20px;
  border-radius:100%;
    background:#62306D;
  position:absolute;
left:230px;
}
  .top{
      top:90px;
  }
  .bottom{
      bottom:90px;
  }
.container{
  display:flex;
    justify-content:center;
    align-items:center;
  height:100%;
}
  body{
    background:#62306D;
  }

</style>
```