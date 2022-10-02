```html

<div class='row-middle'>

  <div class='col-middle'>

    <div class='square-xs black'></div>

  <div class='left-half-circle yellow col-middle'>
    <div class='left-mask black'></div>
    </div>

  </div>

  	<div class='square-m black circle row-middle'>
      	<div class='square-xs black-red circle'></div>
     </div>

  <div class='col-middle'>

  <div class='right-half-circle yellow col-flex-end'>
    <div class='right-mask black'></div>
    </div>

    <div class='square-xs black'></div>
  </div>

  </div>


  <div class='square-lg yellow circle absolute-middle'></div>

</div>
<style>

  body{
    background:#191210;
  }

  .absolute-middle{
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-50%,-50%);
    z-index:-1;
  }

  .left-half-circle{
    width: 100px;
    height: 50px;
    border-radius:0 0 200px 200px;
  }

    .left-mask{
    width: 60px;
    height: 30px;
    border-radius:0 0 60px 60px;
  }

    .right-half-circle{
    width: 100px;
    height: 50px;
    border-radius:200px 200px 0 0 ;
  }

   .right-mask{
    width: 60px;
    height: 30px;
    border-radius:200px 200px 0 0 ;
  }

  .row-middle{
    display:flex;
    justify-content:center;
    align-items:center;
    height:100%;
  }

    .col-middle{
    display:flex;
    flex-direction:column;
    align-items:center;
    justify-content:flex-start;
  }

      .col-flex-end{
    display:flex;
    flex-direction:column;
    align-items:center;
    justify-content:flex-end;
  }

  .yellow{
    background:#ECA03D;
  }

  .black-red{
    background:#84271C;
  }

  .black{
    background:#191210;
  }

  .square-lg {
    width: 140px;
    height: 140px;
  }

   .square-m {
    width: 100px;
    height: 100px;
  }

    .square-s {
    width: 60px;
    height: 60px;
  }

  .square-xs {
    width: 50px;
    height: 50px;
  }

  .circle{
    border-radius:50%;
  }


</style>

```
