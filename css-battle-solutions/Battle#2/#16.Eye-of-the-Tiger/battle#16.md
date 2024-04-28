<div class="diamond">
  <div class="circle-one"></div>
  <div class="circle-two"></div>
  <div class="circle-three"></div>

  </div>
  
<style>
body{
  display: flex;
  justify-content: center;
  align-items: center;
  background: #0B2429; 
  margin: 0;
}

  .diamond{
    position: relative;
    height:200px;
    width: 200px;
    background: #998235;
    transform: rotate(45deg);
    border-top-left-radius: 50%;
    border-bottom-right-radius: 50%;
  }
  .circle-one{
    position: absolute;
    margin: 10px;
    width: 180px;
    height: 180px;
    border-radius: 50%;
    z-index: 1;
    background: #0B2429;
  }

  .circle-two{
    position: absolute;
    margin: 30px;
    height: 140px;
    width: 140px;
    z-index: 2;
    border-radius: 50%;
    background: #F3AC3C;
    
  }

  .circle-three{
    position: absolute;
    background: #0B2429;
    width: 50px;
    height: 50px;
    margin: 75px;
    z-index: 3;
    border-radius: 50%;
  }
</style>

<!-- OBJECTIVE -->
<!-- Write HTML/CSS in this editor and replicate the given target image in the least code possible. What you write here, renders as it is -->

<!-- SCORING -->
<!-- The score is calculated based on the number of characters you use (this comment included :P) and how close you replicate the image. Read the FAQS (https://cssbattle.dev/faqs) for more info. -->

<!-- IMPORTANT: remove the comments before submitting -->