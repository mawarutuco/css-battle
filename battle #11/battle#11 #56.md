```html

<div class='container d-flex justify-center'>
  <div class='top blue d-flex justify-center'>
    <div class='eye black'></div>
    <div class='eye black'></div>
  </div>
  <div class='bottom blue d-flex justify-center'>
    <div class='teeth black'></div>
    <div class='teeth black'></div>
    <div class='teeth black'></div>
  </div>
  <div class='nose black'></div>
</div>
<style>
  .black{
    background: #191919;
  }
  .blue{
    background: #4F77FF;
  }
  .container{
    flex-direction:column;
    height:100%;
    align-items:center;
  }
  .teeth {
    width: 10px;
    height: 10px;
    border-radius:50% 50% 0 0;
    margin:0 2px;
  }
  .nose {
    width: 20px;
    height: 20px;
    border-radius:50%;
    position:absolute;
    top:176px;
  }
  .eye {
    width: 40px;
    height: 40px;
    border-radius:50%;
    margin:0 5px 7px;
  }
  .top {
    width: 120px;
    height: 100px;
    border-radius:60px 60px 10px 10px;
    align-items:end;
  }
  .bottom {
    width: 80px;
    height: 30px;
    border-radius:0 0 20px 20px;
    align-items:end;
  }
  .justify-center{
    justify-content:center;
  }
  .d-flex{
    display:flex;
  }
  body{
    background:#191919;
  }
</style>

```
