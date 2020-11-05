<div a> <div b> <div c>

<style>
  body {
    margin: auto;
    background: #0B2429;
    display: flex;
  	align-items: center;
  	padding-left: 140px;
  }
  
  div {
    width: 120px;
    height: 120px;
    background: #F3AC3C;
    border-radius: 60px 0 60px 60px; 
  }
  
  div[a] {
    border-radius: 50%; 
    transform: translate(60px, -60px); 
  	}
  
  div[b] {
    background: #998235;
    transform: translate(-60px, 60px); 
  }
  
  div[c] {
    transform: translate(-60px,60px);
  }
  
  
</style>
