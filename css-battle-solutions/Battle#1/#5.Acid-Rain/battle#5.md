<div class="wrapper">
  <div class="c c-1"></div>
  <div class="c c-2"></div>
  <div class="c c-3"></div>
</div>
<style>
  body {
    background: #0B2429;
  }
  .wrapper{
    display: flex;
    height: 240px;
    margin: 30px auto;
  }
  .c{
    width: 120px;
    height: 120px;
    background: #F3AC3C;
    border-radius: 50%;
    border-top-right-radius: 0%;
    margin-left: -60px;
  }
  .c-1{
    align-self: flex-end;
    z-index: 3;
    margin-left: 72px;
  }
  .c-2{ 
    background: #998235;
    margin-top:60px;
    z-index: 2
  }
  .c-3{
    border-top-right-radius: 50%;
  }
</style>

