```html

<div class='figers '>
  <div class='figer'></div>
  <div class='long-figer'></div>
  <div class='figer'></div>
  <div class='short-figer'></div>
</div>
<div class='hand1'></div>
<div class='hand2'></div>
  <div class='big-figer'></div>
<style>
  .figer {
    height: 45px;
    border-radius:10px;
  }
  .big-figer {
    height: 63px;
    border-radius:15px;
    border:#F9E492 5px solid;
    top:105px;
    left:150px;
    transform:rotate(60deg);
  }
  .long-figer {
    height: 55px;
    border-radius:10px;
  }
  .short-figer {
    height: 35px;
    border-radius:10px;
  }
  .figers {
    width: 100px;
    height:40px;
    display:flex;
    justify-content:space-around;
    align-items:flex-end;
    top:115px;
    margin-left:2px;
  }
  .hand1 {
    width: 100px;
    height: 40px;
    top:158px;
  }
  .hand2 {
    width: 50px;
    height: 45px;
    top:200px;
  }
  .hand1,.hand2,.big-figer,.figers{
    position:absolute;
  }
  .hand1,.hand2,.figers{
    transform:translate(-50%,-50%);
    left:50%;
  }
  .hand1,.hand2{
    border-radius:0 0 10px 10px;
    background: #191919;
  }
  .figer,.big-figer,.long-figer,.short-figer{
    width: 20px;
    background: #191919;
  }
  body{
    background:#F9E492;
  }
</style>


```
