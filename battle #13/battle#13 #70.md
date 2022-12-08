```html

<div class='face'></div>
<div class='nostrils'></div>
<div class='eyes'></div>
<style>
  .eyes,.eyes::before{
    width: 50px;
    height: 50px;
    background:radial-gradient(ellipse at center,
    #293462 0%, #293462 15%,
    #FFF1C1 15%, #FFF1C1 45%,
    #FE5F55 45%, #FE5F55 100%);
    border-radius:50%;
  }
  .eyes{
    top:85;
    left:210;
  }
  .eyes::before{
    content:'';
    left:-70;
  }
  .nostrils,.nostrils::before{
    width: 10px;
    height: 10px;
    background:#293462;
    border-radius:50%;
  }
  .nostrils{
    top:160;
    left:205;
  }
  .nostrils::before{
    content:'';
    left:-20;
  }
  .face {
    width: 150px;
    height: 100px;
    background: #A64942;
    top:110;
    left:125;
    border-radius:60px;
    overflow:hidden;
  }
  .face::before{
    content:'';
    background:#FE5F55;
    width: 500px;
    height: 500px;
    border-radius:50%;
    top:-430;
    left:-175;
  }
  .face,.nostrils,.eyes,::before{
    position:absolute;
  }
  body{
    background:#293462;
  }
</style>

```