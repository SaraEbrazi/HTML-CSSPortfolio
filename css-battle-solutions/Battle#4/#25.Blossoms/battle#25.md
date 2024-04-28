<div class="con">
  <div class="a"></div>
  <div class="b"></div>
</div>
<div class="con" c>
    <div class="a"></div>
  <div class="b"></div>
</div>

<style>
  body {
    display: flex;
    margin-inline: 100px;
    justify-content: space-around;
    align-items: center;
    background: #998235;
  }
  .con{
    display: grid;
    width: 80px;
    height: 180px;
  }
  .a{
    
    width: 80px;
    height: 100px;
    border-top-right-radius: 50px;
    border-bottom-left-radius: 50px;
    background: #1A4341;
  }
  .b{
    margin-block: 20px;
    width: 80px;
    height: 60px;
    border-top-right-radius: 50px;
    border-bottom-left-radius: 50px;
    background: #F3AC3C;
  }
  [c]{
    transform: rotateX(180deg);
  }
</style>
