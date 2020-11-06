![picture](img/20.png)
```
<div class="a">
	<div class="h b"></div>
	<div class="h c"></div>
	<div class="h d"></div>
	<div class="h e"></div>
	<div class="i f"></div>
	<div class="i g"></div>
</div>
<style>
  body {
    margin: 0;
    background: #62306D;
    display:flex;
  	justify-content:center;
  	align-items:center;
  }
  
  .a {
    width: 200px;
    height: 100px;
    background: linear-gradient(90deg, #F7EC7D 70%, #E38F66 70%);  
    display:flex;
  	justify-content:center;
  	align-items:center;
  }
  
  .h {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background: #62306D;
  }
  
  .i {
    width: 20px;
    height: 20px;
    border-radius: 50%;
    background: #62306D;
  }
  
  .b {
    transform: translate(-20px, -50px); 
  }
  
  .c {
    transform: translate(-60px, 50px); 
  }
  
  .d {
    transform: translate(100px, -50px); 
  }
  
  .e {
    transform: translate(60px, 50px); 
  }

  .f {
 	 transform: translate(-30px, -50px); 
  }
  
  .g {
 	 transform: translate(-50px, 50px); 
  }
</style>