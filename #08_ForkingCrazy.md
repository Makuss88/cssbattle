 ![picture](8.png)
 ```
<div class="top">
  <div class="a"></div>
  <div class="b"></div>
  <div class="a"></div>
  <div class="b"></div>
  <div class="a"></div>
  <div class="b"></div>
  <div class="a"></div>
</div>
<div class='middle'></div>
<div class='bottom'></div>
<style>
  body {
    background: #6592CF;
    margin: 0;
  }
  
  .top {
  	display: flex;  
    justify-content: center;
    padding-top: 50px
  }
  
  .a, .b {
    width: 20px;
    border-radius: 20px;
  }
  
  .a {
    height: 140px;
 	  background: #060F55; 
  }
  
  .b {
  	height: 110px;
    background: #6592CF; 
  }
  
  .middle {
    width: 140px;
    height: 140px;
    margin: -80px auto;
    border-radius: 50%;
    background: #060F55;
  }
  
  .bottom {
   	margin: -80px auto;
    width: 20px;
    height: 150px;
  	background: #060F55;
  }  
</style>
