<template>
  <section class="fifth_div">



      <h2>Advisors</h2>
      <hr class="">



      <div class="container">
          <div class="row">
              <div class="col-md-3">
                  <img src="../assets/rajat-goel.jpeg">
                  <h3>Mr. Rajat Goel</h3>
                  <p>
                      <a href="" target="_blank">
                          <i class="fa fa-linkedin-square"></i>
                      </a>
                  </p>
              </div>
              <div class="col-md-3">
                  <img src="../assets/jayne-shaw.jpeg">
                  <h3>Ms. Jayne Shaw</h3>
                  <p>
                      <a href="" target="_blank">
                          <i class="fa fa-linkedin-square"></i>
                      </a>
                  </p>
              </div>
              <div class="col-md-3">
                  <img src="../assets/sushma-rajagopalan.jpeg">
                  <h3 class="teammate">Ms. Sushma Rajagopalan</h3>
                  <p>
                      <a href="" target="_blank">
                          <i class="fa fa-linkedin-square"></i>
                      </a>
                  </p>
              </div>
              <div class="col-md-3">
                  <img src="../assets/rajat-goel.jpeg">
                  <h3>Dr. Mark Holterman</h3>
                  <p>
                      <a href="" target="_blank">
                          <i class="fa fa-linkedin-square"></i>
                      </a>
                  </p>
              </div>
          </div>
      </div>
  </section>

</template>

<script >
export default {
  name: 'Advisors'

}

</script>
<style scoped>
.fifth_div img {
    width: 120px;
    height: 120px;
    object-fit: cover;
}
.fifth_div h3{
    font-size: 22px;
    padding-top: 11px;
    max-width: 200px;
    margin: auto;
}
.fifth_div hr{
    max-width: 50px;
    border-width: 3px;
    border-color: #f05f40;
}
.fifth_div h2{
    font-weight: 300;
}
.fifth_div::before{
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    display: block;
    width: 100%;
    height: 100%;
    background-image: url(../assets/interview.jpg);
    background-position: center center;
    background-size: cover;
    opacity: 0.2;
}
.fifth_div{
    text-align: center;
    position: relative;
    padding: 49px 0px;

}

</style>
