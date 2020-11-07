![picture](img/21.png)

<div c> 
  <div a></div>
  <div b></div>
</div>
   
<div d> 
  <div a e></div>
  <div b f></div>
</div>
      
<style>

  body {
    margin: 0;
    background: #222;
  }
  
  div[c] {
    transform: rotate(45deg);
  	position: absolute;
    top: 62px;
    left: 195px;
    }
  
  div[a], div[b] {
    position: absolute;
    background: #F2994A;
    width: 30px;
    height: 100px;
  	border-radius: 0 0 0 10px;  
  }
  
  div[b] {
    top: 70px;
    width: 80px;
    height: 30px;
	  border-radius: 0 5px 0 10px;    
  }
  
  div[d] {
    transform: rotate(-135deg);
  	position: absolute;
    bottom: 63px;
    right: 196px;
  }
  
  div[e], div[f] {
    background: #2D9CDB;
  }
</style>
