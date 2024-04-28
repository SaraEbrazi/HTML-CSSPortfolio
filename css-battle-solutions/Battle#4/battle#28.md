<div class="container">
  <div class="a" c></div>
  <div class="b" d></div>
  <div class="b" c></div>
  <div class="a" d></div>
</div>
<div class="container">
   <div class="b" d e></div>
   <div class="a" c></div>
  <div class="a" d></div>
  <div class="b" c e></div>
</div>
<style>
   body{margin-block: 80px;display: grid;place-items: center;background: #1A4341;}
  .container{display: flex;justify-content: space-between;height: 50px;width: 260px;}
  .a{width: 50px;height: 50px ;border-radius: 100%;}
  .b{width: 50px;height: 50px ;border-top-right-radius: 50px;border-top-left-radius: 50px;}
  [c]{background: #998235;}
  [d]{background: #F3AC3C;}
  [e]{transform: rotateX(180deg);}
</style>
