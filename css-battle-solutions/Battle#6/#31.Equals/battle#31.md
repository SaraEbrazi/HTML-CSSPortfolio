<div class="halfcircle"></div>
<div class="halfcircle"></div>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    background: #AA445F;
     }
  .halfcircle{
    position: relative;
    height: 200px;
    width: 100px;
    margin-left: -150px;
    border-top-left-radius: 100px;
    border-bottom-left-radius: 100px;
    background: #F7EC7D;
  }
  .halfcircle:first-child{
    position: absolute;
    margin-left: 150px;
    background: #E38F66;
    transform: rotate(180deg);
  }
</style>