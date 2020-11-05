 ![picture](12.png)
 ```
<div class='a'> </div>
<div class='c'> </div>
<div class='b'> </div>

<style>  
  body {
    margin: 0;
    background: #F5D6B4;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  div {
    width: 60px;
    height: 30px;
    border: 20px solid #D86F45;
    border-top:none;
    border-radius: 0 0 60px 060px;
    margin-top: 50px;
  }
  
  .a::before, .b::before {
    content: '';
    width: 20px;
    height: 10px;
    background: #D86F45;
    position: absolute;
    top: 140px;
    left: 70px;
    border-radius: 10px 10px 0 0;
  } 
  
  .b::before {
    left: 310px;    
  }
  
  .c {
    border: 20px solid #D86F45;
    border-bottom: none;
    border-radius: 60px 60px 0 0;  
    margin: 0 -20px 50px;
  }  
</style>
