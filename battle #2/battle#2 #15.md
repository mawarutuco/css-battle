```html
<div class="circle left position"></div>
<div class="circle right position"></div>
<style>

body{
background:#09042A;
}

.circle {
width: 150px;
height: 150px;
border-radius: 50%;
}

.position{
position: absolute;
transform:translate(-50%,-50%);
top:50%;
}

.left {
background: #7B3F61;
left:150px;
-webkit-mask: radial-gradient(circle at 175px, #0000 75px, red 0) 0px;
}

.right {
background: #E78481;
left:250px;
-webkit-mask: radial-gradient(circle at -25px, #0000 75px, red 0) 0px;
}

</style>
```