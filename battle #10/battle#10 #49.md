```html

<div class='container'>
  <div class='root'></div>
  <div class='home'>
      <div class='line lineAndDoor'></div>
      <div class='door lineAndDoor'></div>
  </div>
</div>
<style>
  .lineAndDoor{
    position:absolute;
    transform:translate(-50%);
    left:50%;
    background:#EEB850;
  }
  .door{
    width:50px;
    height:50px;
    border-radius:10px 10px 0 0;
    bottom:0
  }
  .line{
    width:100px;
    height:10px;
    border-radius:10px;
    top:-5px;
  }
  .root {
    border-style:solid;
    border-color:#0000 #0000 #243D83 #0000;
    border-width:0 100px 100px 100px;
  }
  .home {
    width: 150px;
    height: 100px;
    background: #243D83;
    border-radius:0 0 10px 10px;
    position:relative;
  }
  .container{
    display:flex;
    justify-content:center;
    align-items:center;
    height:100%;
    flex-direction:column;
  }
  body{
    background:#6592CF;
  }
</style>

```
