<div class="container">
  <div class="triangle one"></div>
  <div class="triangle two"></div>
  <div class="triangle three"></div>
  <div class="triangle four"></div>
</div>
<style>
    * {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
  }
   .container {
    width: 100%;
    height: 100%;
    background: #F2F2B6;
    position: relative;
  }
  .triangle {
    width: 0;
    height: 0;
    position: absolute;
    top: 50%;
    left: 50%;
  }
  .one {
    border-top: 130px solid #FF6D00;
    border-left: 75px solid transparent;
    border-right: 75px solid transparent;
    transform: translate(calc(-50% + -65px), calc(-50% + 0px)) rotate(-360deg);
    z-index: 1;
  }
   .two {
    border-top: 130px solid #FD4602;
    border-left: 75px solid transparent;
    border-right: 75px solid transparent;
    transform: translate(calc(-50% + -45px), calc(-50% + 0px)) rotate(-360deg);
    z-index: 0;
  }
  .three{
    border-bottom: 130px solid #FD4602;
    border-left: 75px solid transparent;
    border-right: 75px solid transparent;
    transform: translate(calc(-50% + 45px),calc(-50% + 0px)) ;
    z-index: 1;
  }
  .four{
    border-bottom: 130px solid #FF6D00;
    border-left: 75px solid transparent;
    border-right: 75px solid transparent;
    transform: translate(calc(-50% + 65px),calc(-50% + 0px));
  }
</style>