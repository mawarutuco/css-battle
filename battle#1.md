```html
<div class="right-top"></div>
<div class="right-bottom"></div>
<div class="left-top"></div>
<div class="left-bottom"></div>

<style>
  body{
    background: #62374e;
  }
  
  div {
    width: 50px;
    height: 50px;
    background: #fdc57b;
    position:absolute;
  }
  
  .right-top{
    right:50px;
    top:50px; 
  }
  
      .right-bottom{
    right:50px;
    bottom:50px; 
  }
  
    .left-top{
    left:50px;
    top:50px; 
  }
  
      .left-bottom{
    left:50px;
    bottom:50px; 
  }
  
</style>


//----升級↓-----


<div class='big-big-box'>
<div class='big-box'>
<div class="box"></div>
<div class="box"></div>
</div>

<div class='big-box'>
<div class="box"></div>
<div class="box"></div>
</div>
</div>

<style>
  body{
    background: #62374e;
  /*瀏覽器預設會有間距*/
    margin:0px;
      padding:0px;
  }
  
  .big-big-box{
        display:flex;
 	flex-direction:column;
    justify-content:space-between;
    height:100%;
  }
  
  .big-box{
    display:flex;
 	flex-direction:row;
    justify-content:space-between;
    margin:50px 50px;
  }
  
  .box {
    width: 50px;
    height: 50px;
    background: #fdc57b;
  }
  
  
</style>
