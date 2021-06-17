<template>
<div class="everything">
      <div class="card" style="width: 18rem;">
  <img class="card-img-top" src="../assets/logo.png" >
  <div class="card-body">
      <div class="line"></div>
    <h5 class="card-title">Sticker</h5>
    <p class="card-text">Minor details of item</p>
    <div class="center">
    <div class="buttons d-flex flex-row">
      <button class="btn btn-success cart-button px-5">Add to cart </button>
    </div>
</div>
  </div> 
</div>
  <div class="card" style="width: 18rem;">
  <img class="card-img-top" src="../assets/hat.jpg" >
  <div class="card-body">
      <div class="line"></div>
    <h5 class="card-title">Hat</h5>
    <p class="card-text">Minor details of item</p>
        <div class="buttons d-flex flex-row">
      <button class="btn btn-success cart-button px-5">Add to cart </button>
    </div>
  </div> 
</div>
  <div class="card" style="width: 18rem;">
  <img class="card-img-top" src="../assets/wallet.png" >
  <div class="card-body">
      <div class="line"></div>
    <h5 class="card-title">Wallet</h5>
    <p class="card-text">Minor details of item</p>
        <div class="buttons d-flex flex-row">
      <button class="btn btn-success cart-button px-5">Add to cart </button>
    </div>
  </div> 
</div>

  <div class="card" style="width: 18rem;">
  <img class="card-img-top" src="../assets/shirt.jpg" >
  <div class="card-body">
      <div class="line"></div>
    <h5 class="card-title">Shirt</h5>
    <p class="card-text">Minor details of item</p>
        <div class="buttons d-flex flex-row">
      <button class="btn btn-success cart-button px-5">Add to cart </button>
    </div>
  </div> 
</div>
      <div class="card" style="width: 18rem;">
  <img class="card-img-top" src="../assets/jacket.jpg" >
  <div class="card-body">
      <div class="line"></div>
    <h5 class="card-title">Jacket</h5>
    <p class="card-text">Minor details of item</p>
        <div class="buttons d-flex flex-row">
      <button class="btn btn-success cart-button px-5">Add to cart </button>
    </div>
    
  </div> 
</div>
      <div class="card" style="width: 18rem;">
  <img class="card-img-top" src="../assets/hoodie.jpg" >
  <div class="card-body">
      <div class="line"></div>
    <h5 class="card-title">Hoodie</h5>
    <p class="card-text">Minor details of item</p>
        <div class="buttons d-flex flex-row">
      <button class="btn btn-success cart-button px-5">Add to cart </button>
    </div>
  </div> 
</div>
      <div class="card" style="width: 18rem;">
  <img class="card-img-top" src="../assets/bottle.jpg" >
  <div class="card-body">
      <div class="line"></div>
    <h5 class="card-title">Bottle</h5>
    <p class="card-text">Minor details of item</p>
        <div class="buttons d-flex flex-row">
      <button class="btn btn-success cart-button px-5">Add to cart </button>
    </div>
  </div> 
</div>

</div>

</template>

<script>
export default {

}
</script>

<style scoped>
.everything {
  margin-right: 0px;
  margin-left: auto;
}
.card {
    margin-top: 1%;
    margin-left: 8%;
    margin-right: 8%;
    padding: 0 25px 0 25px;
    cursor: pointer;
    float: left;
    height: 360px;
    
}
.card-img-top {
  height: auto;
}
.line{
    border-top: 1px solid grey;
    padding: 0 0 10px 0;
}
img{
  max-height: 250px;
  max-width: 300px;
  min-height: 210px;
  min-width: 200px;
}
button{
  margin-left: 12px;
}
</style>