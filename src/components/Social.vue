<template>
  <section class="elevin_div">
    <h2>Social</h2>
    <hr>
    <div class="container">
        <div class="row">
          <div class="col-md-6">
            <div class="video_sec">
              <iframe width="1280" height="340px" src="https://www.youtube.com/embed/x9SGSotikw4" frameborder="0" allow="accelerometer; autoplay;" allowfullscreen></iframe>
            </div>
          </div>
          <div class="col-md-6">
            <div class="video_sec">
              <iframe  width="1280" height="340px" src="https://www.youtube.com/embed/XI21j9qPU5w" frameborder="0" allow="accelerometer; autoplay; "  allowfullscreen></iframe>
            </div>
          </div>
        </div>
      </div>

  </section>
  </template>

  <script>
  export default {
    name: 'Social'
  }
  </script>
  <style scoped>
  section.elevin_div {
      padding-bottom: 30px;
  }
  .elevin_div .video_sec{
      position: relative;
      padding-top: 35px;
      overflow: hidden;
      margin-bottom: 30px;
      height: 300px;
  }
  .elevin_div .video_sec iframe, .elevin_div .video_sec iframe video{
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
  }
  .elevin_div hr{
    max-width: 50px;
    border-width: 3px;
    border-color: #f05f40;
  }
  </style>
