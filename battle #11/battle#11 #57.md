```html

<div class='square'>
  <div class='circle-l left top'></div>
  <div class='circle-l right top'></div>
  <div class='circle-l left bottom'></div>
  <div class='circle-l right bottom'></div>
  <div class='circle-m left top'></div>
  <div class='circle-m right top'></div>
  <div class='circle-m left bottom'></div>
  <div class='circle-m right bottom'></div>
  <div class='circle-s left top'></div>
  <div class='circle-s right top'></div>
  <div class='circle-s left bottom'></div>
  <div class='circle-s right bottom'></div>
</div>
<style>
  .square {
    width: 110px;
    height: 110px;
    position:relative;
    margin:95px auto;
    position:relative;
  }
  .circle-s{
    width: 30px;
    height: 30px;
  }
  .circle-m{
    background:#F9E492;
    width: 45px;
    height: 45px;
  }
  .circle-l{
    background:#191919;
    width: 60px;
    height: 60px;
  }
  .square,.circle-s{
     background: #4F77FF;
  }
  .circle-l,.circle-m,.circle-s{
    border-radius:50%;
    position:absolute;
  }
  .top{
    top:-20px;
  }
  .left{
    left:-20px;
  }
  .bottom{
    bottom:-20px;
  }
  .right{
    right:-20px;
  }
  body{
    background:#191919;
  }
</style>

```