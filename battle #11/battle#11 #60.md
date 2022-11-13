```html

<div class='one'></div>
<div class='two'></div>
<div class='one'></div>
<div class='two'></div>
<style>
  .one{
    background:repeating-linear-gradient(
      45deg,
      #191919,#191919 25%,
      #4F77FF 25%, #4F77FF 50%
    );
  }
  .two{
    background:repeating-linear-gradient(
      -45deg,
      #191919,#191919 25%,
      #4F77FF 25%, #4F77FF 50%
    );
  }
  div{
    width:50px;
    height:150px;
  }
  body{
    background:#191919;
    display:flex;
    justify-content:center;
    align-items:center;
  }
</style>

```