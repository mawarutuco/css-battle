```html


  <div class='col'>
      <div class='head-l'></div>
      <div class='neck-t yellow'></div>
      <div class='neck-b yellow'></div>
      <div class='body'>
        <div class='row'>
          <div class='mark green'></div>
          <div class='mark yellow'></div>
        </div>
      </div>
  </div>
  <div class='col absolute flex-end'>
      <div class='head-r'></div>
      <div class='head-b'></div>
      <div class='circle green'></div>
      <div class='circle green'></div>
  </div>

<style>
  .green {
    background:#998235;
  }
  .yellow {
    background:#F3AC3C;
  }
  .circle {
    width: 20px;
    height: 20px;
    border-radius:100%;
    margin-top:10px;
  }
  .mark {
    width: 50px;
    height: 50px;
    border-radius:100%;
    margin-top:-30px;
  }
  .head-b {
    width: 20px;
    height: 20px;
    background:#F3AC3C;
    border-radius: 0 0 20px 20px ;
  }
  .head-r {
    width: 50px;
    height: 20px;
    background:#F3AC3C;
    border-radius: 0 10px 0 0 ;
  }
  .head-l {
    width: 100px;
    height: 20px;
    background:#F3AC3C;
    border-radius:10px 0 0 10px ;
  }
  .neck-t {
    width: 20px;
    height: 20px;
  }
  .neck-b {
    width: 50px;
    height: 20px;
    border-radius:10px 10px 0 0 ;
  }
  .body {
    width: 100px;
    height: 140px;
    background: linear-gradient(#F3AC3C 40%,#998235 0%);
    border-radius:20px
  }
  .row{
    display:flex;
    height:100%;
    justify-content:center;
    align-items:center;
  }
  .col{
    display:flex;
    height:100%;
    justify-content:center;
    align-items:center;
    flex-direction:column;
  }
  .flex-end{
    align-items:flex-end;
  }
  .absolute{
    position:absolute;
    top:-50px;
    right:100px;
  }
  body{
    background:#1A4341;
  }
</style>


```