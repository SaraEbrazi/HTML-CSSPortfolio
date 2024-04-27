<div class="rect"></div>
  <div class="diamond-one"></div>
<div class="diamond-two"></div>
<div class="circle"></div>

<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
     margin: 0;
    background: #222730;
  }
  .rect{
    width: 400px;
    height: 150px;
    background: #4CAAB3;
    
  }

  .diamond-one{
    position: absolute;
    width:250px;
    height: 250px;
    background: #222730;
    transform: rotate(45deg);
  }
  .diamond-two{
    position: absolute;
    width: 150px;
    height: 150px;
    background: #4CAAB3;
    transform: rotate(45deg)
  }
  .circle{
    position: absolute;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: #393E46;
  }
</style>

