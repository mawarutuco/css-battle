```html

<div class='yellow'></div>
<div class='green'></div>
<style>
  .yellow {
    width: 250px;
    height: 250px;
    background: linear-gradient( 
      #0000 0% ,#0000 30%,
      #F3AC3C 30% ,#F3AC3C 38%,
      #0000 38% ,#0000 46%,
      #F3AC3C 46% ,#F3AC3C 54%,
      #0000 54% ,#0000 62%,
      #F3AC3C 62% ,#F3AC3C 70%,
      #0000  70%,#0000  100%);
    border-radius:50%;
  }
  .green {
    width: 200px;
    height: 200px;
    background: linear-gradient( #998235 0% ,#998235 15%,#0000 15% ,#0000 85%,#998235  85%,#998235  100%);
    border-radius:50%;
  }
  div{
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-50%,-50%);
  }
   body{
    background:#1A4341;
  }
</style>

```
