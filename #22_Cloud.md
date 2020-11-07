![picture](img/22.png)
```
<div a></div>
<div b></div>
<div c></div>
  
<style>
  body {
    margin: 0;
    background: #F5D6B4;
  	display: flex;
    justify-content: center;    
  }
  
  div {
    position: absolute;
    background: #D86F45;
  }
  
  div[a] {
    width: 200px;
    height: 50px;
    border-radius: 0 25px 25px 50px;
    top: 165px;
  }
  
  div[b], div[c] {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    top: 115px;
    left: 100px;
  }
  
  div[c] {
    top: 85px;
    left: 180px;
  }
</style>
