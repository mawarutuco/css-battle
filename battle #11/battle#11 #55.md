```html

<div class='top top_bottom'></div>
<div class='bottom top_bottom'></div>
<div class='left left_right'></div>
<div class='right left_right'></div>
<style>
  .left_right{
    width: 100px;
    height: 50px;
    background: #F9E492;
  }
  .right {
    border-radius:0 0 50px 50px ;
  }
  .left {
    border-radius:50px 50px 0 0;
    transform:translate(-100%,-100%);
  }
  .top_bottom{
    width: 50px;
    height: 100px;
    background: #4F77FF;
  }
  .bottom {
    border-radius:50px 0 0 50px;
    transform:translate(-100%,0);
  }
  .top {
    border-radius:0 50px 50px 0;
    transform:translate(0,-100%);
  }
  div{
    position:absolute;
    top:50%;
    left:50%;
  }
  body{
    background:#191919;
  }
</style>

```