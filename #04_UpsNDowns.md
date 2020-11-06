 ![picture](img/4.png)
 ```
<div a></div> <div b></div> <div a></div>
  
<style>
  body {
    background: #62306D;
    display: flex;
	  justify-content: center;
    align-items: center;
  }
  
  div {
    width: 100px;
    height: 100px;
    background: #F7EC7D;
  }

  div[a] {
    border-radius: 0 0 100px 100px;
    margin-top: 100px;
  }
  
  div[b] {
    border-radius: 100px 100px 0 0 ;
    margin-bottom: 100px;
  }
</style>
