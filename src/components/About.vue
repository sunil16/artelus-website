<template>
<section class="third_div">
  <h2>About</h2>
  <hr class="hr_line">
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <p>We are working in the Deep Learning space to solve healthcare problems. We seek to make products, which would complement the knowledge and assist the clinician in making faster and accurate diagnosis.</p>
        <p>We are leveraging the cutting edge technologies like Deep Learning and artificial intelligence to increase the capacity of healthcare providers enabling them to offer higher quality care without over burdening the system.</p>
        <p>Solutions using Deep Learning Algorithms have a higher rate of accuracy and early detection can save lives.</p>
        <p>Artelus R&amp;D team constantly strives to innovate new ways of developing accurate primary screening solution. Our team is working on developing primary screening tools to detect TB, Breast cancer and Lung cancer. We are also working in diagnostic
          solutions that would assist the doctors in accurate diagnosis for faster treatment by providing a comprehensive reporting of anomalies detected during primary screening process.</p>
        <p>Our products offer primary screening solutions for problems that are inevitably going to strike, and preempt them from getting worse. Identifying people with diseases at early stage can help them avoid disease complications and expensive treatments.
          In many cases, screening can help people avoid onset of disease altogether. We are taking health care experience beyond the boundaries of hospitals and specialized clinics.</p>
        <p>This will have the natural outcome of reducing cost, improving health and making the world a happy and healthy place to live in.</p>
      </div>
      <div class="col-md-6">
        <div class="youtube-video-container">
          <video width="560" height="315" controls="">
                                                      <source src="img/artelus_video.mp4" type="video/mp4">
                                                      Your browser does not support the video.
                                                  </video>
        </div>
        <div class="youtube-video-container">
          <iframe width="560" height="315" src="https://www.youtube.com/embed/vyjuutk3JvE?rel=0&amp;showinfo=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen=""></iframe>
        </div>
      </div>


    </div>


  </div>

</section>
</template>

<script>
export default {
  name: 'About'
}
</script>
<style scoped>


.third_div {
  position: relative;
  padding-top: 305px;
  padding-bottom: 50px;
}

.third_div .container {
  padding-top: 30px;
}

.third_div .container p {
  text-align: left;

}

.third_div hr {
      border-color: #f05f40;
}

.hr_line {
  max-width: 50px;
  border-width: 4px;
  background: #f05f40 !importants;
}
</style>
