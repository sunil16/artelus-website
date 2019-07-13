<template>
  <section class="second_div">
    <h2>Mission</h2>
    <hr class="hr_line">
    <div class="container">
      <p>
        Mine and cultivate existing medical archives using computational techniques seeking patterns that can help doctors with disease diagnosis, prognosis, and treatment.</p>
      <p>
        Team with technology firms Health care organizations to access medical data in order to provide timely, doctor assisted solutions utilizing technologies such as portable devices, cloud computing, and deep learning</p>
      <p> To create and predict Early Warning Systems for preventing fatal diseases and ailments
      </p>
    </div>

  </section>
</template>

<script type="text/javascript">
export default {
  name: 'Mission',

}
</script>
<style scoped>

section.second_div {
  position: relative;
  padding-top: 32px;
}

.second_div::before {
  content: "";
  background-image: url(../assets/bg-2.jpg);
  opacity: 0.1;
  position: absolute;
  width: 100%;
  display: block;
  top: 0;
  height: 100vh;
}

.second_div .container {
  padding: 0px 121px;
}

.second_div p {
  font-size: 20px;
  color: #f05f40;
  text-align: -webkit-left;
  line-height: 32px
}

.second_div hr {
  background: #f05f40;
}

.hr_line {
  max-width: 50px;
  border-width: 4px;
  background: #fff;
}
</style>
