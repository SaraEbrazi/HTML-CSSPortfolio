<div class='circle'></div>
<div class='container'>
<div class='circle-one'></div>
<div class='container-one'></div>
<div class='circle-one'></div>
</div>
<div class='circle'></div>
<style>
body{
  display: grid;
  place-items: center;
  align-content: center;
  background: #09042A; 
  grid-auto-rows: 53px;
}
  .circle{
    width: 60px;
    height: 60px;
    border-radius: 100%;
    background-color: #F5BB9C;
    z-index: 1;
      border: 10px solid #09042A;   
  }
  .container-one{
    height: 60px;
    width: 60px;
    background-color: #E78481;
  }
  .circle-one{
    width: 60px;
    height: 60px;
    border-radius: 100%;
    background-color: #09042A;
    border: 10px solid #E78481;
    margin-inline: -10px;
  }
  .container{
    display: flex;
    align-items: center;
    justify-content: center;
  }


  

 

