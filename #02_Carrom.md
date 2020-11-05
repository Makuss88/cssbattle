![picture](2.png)
```
<p a>
<p b>
<p c>
<p d>
<style>
  * {
    background: #62374e;
    margin: 0px;
  }
  
  p {
    width:50px;
    height: 50px;
    background: #fdc57b;
    position: absolute;
  }
  
  p[a], p[b] {
    top:50px;
  }
  
  p[b], p[c]{
    right:50px;
  } 
  
  p[c], p[d] {
    bottom:50px;  
  }
  
  p[d], p[a] {
    left: 50px;  
  }
  
</style>
```
