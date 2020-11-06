![picture](img/19.png)

```
<div class="a"></div>
<div class="b c"></div>
<div class="b"></div>

<style>
  body {
    margin: 0;
    display: flex;
    justify-content: center;   
  	align-items: center;
    background: #0B2429;
  }
  
  .a {
    width: 100px;
    height: 100px;
   	background: #F3AC3C; 
	  transform: translateY(35px) rotate(45deg);
  }
  
  .b {
    width: 72px;
    height: 70px;
   	position: absolute;
    background: #1A4341;
    transform: skew(0deg, 45deg) translate(35px, -70px);
  } 
  
  .c {
    width: 70px;
    background: #998235;
    transform: skew(0deg, -45deg) translate(-35px, -70px);
  }
</style>