```html

<div class='bee'></div>
<div class='circle l'></div>
<div class='circle r'></div>
<style>
  .r{
    right:-300px;
  }
  .circle{
    width: 300px;
    height: 300px;
    background:#1A4341;
    border-radius:50%;
  }
  .l{
    left:0px;
  }
  .bee {
    width: 300px;
    height: 180px;
    background: linear-gradient(
      #F3AC3C 0%,#F3AC3C 11%,
      #0000 11%,#0000 22%,
      #F3AC3C 22%,#F3AC3C 33%,
      #0000 33%,#0000 44%,
      #F3AC3C 44%,#F3AC3C 56%,
      #0000 56%,#0000 67%,
      #F3AC3C 67%,#F3AC3C 78%,
      #0000 78%,#0000 89%,
      #F3AC3C 89%,#F3AC3C 100%
    );
    transform:translate(-50%,-50%);
    left:50%;
  }
  div{
    position:absolute;
    transform:translate(-50%,-50%);
    top:50%;
  }
  body{
    background:#1A4341;
  }
</style>


```
