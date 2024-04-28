<div class="circle"></div>
<div class="circle"></div>
<div class="center"></div>
<style>
  body{
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0;
    background: #09042A;
  }
  .circle{
    height: 150px;
    width: 150px;
    border-radius: 50%;
    background: #7B3F61;
  }
  .circle:first-child{
    margin-right: -50px;
  }
 .circle:nth-child(2){
   background: #E78481;
 }
  .center{
    position: absolute;
    background: #09042A;
    width: 80px;
    height: 80px;
    transform: rotate(45deg);
    border-top-right-radius: 75px;
    border-bottom-left-radius: 75px;
  }
 
</style>

