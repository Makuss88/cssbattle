 ![picture](img/7.png)
 ```
 <div a> <div b> <div c>

<style>
  body {
    margin: auto;
    background: #0B2429;
    display: flex;
  	align-items: center;
  }
  
  div {
    width: 150px;
    height: 150px;
    border-radius: 100px 0; 
  }

  div[a] {
    background: #1A4341;
  	transform:translate(75px, 0px);    
  }
  
  div[b] {
    background: #998235;
	  transform:translate(50px, 0px);    
  }
  
  div[c] {
	  background: #F3AC3C;
    transform:translate(50px, 0px);    
  }
</style>
