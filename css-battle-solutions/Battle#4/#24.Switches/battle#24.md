<div class="container">
  <div class="circle bg-yellow left-circle z-1"></div>
  <div class="circle bg-yellow right-circle z-1"></div>
  <div class="cylindrical bg-brown left-cylindrical"></div>
  <div class="cylindrical bg-copper right-cylindrical"></div>
</div>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  .container {
    width: 100vw;
    height: 100vh;
    background: #62306d;
    position: relative;
  }
  .circle {
    width: 100px;
    height: 100px;
    border-radius: 50%;
  }
  .cylindrical {
    width: 150px;
    height: 100px;
    border-radius: 100px;
  }
  .bg-yellow {
    background: #f7ec7d;
  }
  .bg-brown {
    background: #aa445f;
  }
  .bg-copper {
    background: #e38f66;
  }
  .z-1 {
    z-index: 1;
  }
  .left-circle,
  .right-circle,
  .left-cylindrical,
  .right-cylindrical {
    position: absolute;
    top: 50%;
    left: 50%;
  }
  .left-circle {
    transform: translate(calc(-50% - 70px), -50%);
  }
  .right-circle {
    transform: translate(calc(-50% + 70px), -50%);
  }
  .left-cylindrical {
    transform: translate(calc(-50% - 70px), calc(-50% - 25px)) rotate(90deg);
  }
  .right-cylindrical {
    transform: translate(calc(-50% + 70px), calc(-50% + 25px)) rotate(90deg);
  }
</style>