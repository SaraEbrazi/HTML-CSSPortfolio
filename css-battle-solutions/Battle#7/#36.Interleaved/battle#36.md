<div class="rect"></div>
<div class="rect"></div>
<div class="rect"></div>
<div class="rect"></div>
<div class="rect"></div>

<style>
  body{
    display: flex;
    margin: 0 12.5px;
    background: #1A4341;
    justify-content: space-around;
  }
  .rect:nth-child(2n+1) {
   width: 50px;
    height: 200px;
    margin-top: 100px;
    border-top-right-radius: 50px;
    border-top-left-radius: 50px;
    background: #F3AC3C;
  }
  .rect:nth-child(2n){
     width: 50px;
    height: 200px;
    border-bottom-right-radius: 50px;
    border-bottom-left-radius: 50px;
    background: #998235;
    
  }
</style>
