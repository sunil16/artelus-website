<template>


    <section class="fourth_div">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <h2 class="section-heading text-center">Products</h2>
            <hr class="primary">
          </div>
        </div>
      </div>
      <div class="container" style="margin-top: 32px;">
        <div class="row">
          <div class="col-md-4 product">
            <h4 class="text-center" data-toggle="modal" data-target="#pro_sushruta">Sushruta</h4>
          </div>
          <div class="col-md-4 product">
            <h4 class="text-center" data-toggle="modal" data-target="#pro_hansanet">Hansanet</h4>
          </div>
          <div class="col-md-4 product">
            <h4 class="text-center" data-toggle="modal" data-target="#pro_nimi">Nimi</h4>
          </div>
        </div>
      </div>
      <div class="container" style="margin-top: 60px;">
        <div class="row">
          <div class="col-lg-12">
            <h2 class="section-heading text-center">Product Pipeline</h2>
            <hr class="primary">
          </div>
          <div class="col-lg-12">
            <ul class="pipeline-list">
              <!-- <li>Diabetic Retinopathy Detection System – In Market</li> -->
              <li>Chest X-rays for TB Detection – Validation</li>
              <li>Lung Cancer Detection – Data gathering</li>
              <li>Solve IVF problems using medical images and artificial intelligence- R&amp;D</li>
              <li>Breast Cancer Detection – Data gathering</li>
              <li>Multiple Sclerosis Serial Reading – Data gathering</li>
            </ul>
          </div>
        </div>
      </div>

    </section>

</template>

<script >
export default {
  name: 'Product'

}

</script>
<style >
.fourth_div{
  position: relative;
  height: 100vh;
}
.fourth_div:after {
  content: '';
      display: block;
      width: 100%;
      height: 100%;
      position: absolute;
      top: 0;
      left: 0;
      background-image:url(../assets/neurons.jpg);
      background-size: cover;
      background-position: center center;
      opacity: 0.2;
      z-index: -1;
}
.fourth_div h4{
  font-size: 20px;
    font-weight: 600;
    cursor: pointer;
    display: inline-block;
    width: 200px;
    background-color: #F05F40;
    padding: 12px;
    color: #fff;
}
.fourth_div ul{
  list-style-type: none;
text-align: left;
line-height: 33px;

}
.fourth_div {
  padding-top: 30px;
}
.fourth_div ul hr{
  max-width: 50px;
border-color: #f05f40;
border-width: 3px;
}

.fourth_div ul li{
  font-size: 18px;
margin-bottom: 12px;
}
.fa-linkedin-square{
      color: #e27459;
}
</style>
