<template>
  <section class="tenth_div">
    <div class="container">
          <h2 class="section-heading text-center">Publications</h2>
          <hr >
      <div class="row">
        <div class="col-lg-12">
          <ol start="1">
            <li>
              <h6>
                Towards Ophthalmologist Level Accurate Deep Learning System for OCT Screening and Diagnosis
              </h6>
              <p >
                <b>Authors:</b> Mrinal Haloi
              </p>
              <p>
                <b>Abstract:</b> In this work, we propose an advanced AI based grading system for OCT images. The proposed system is a very deep fully convolutional attentive classification network trained with end to end advanced transfer learning with online random augmentation. It uses quasi random augmentation that outputs confidence values for diseases prevalence during inference. Its a fully automated retinal OCT analysis A…
              </p>

                <button class="btn btn-primary">Download</button>

            </li>
            <li>
                <h6>
                  Towards Ophthalmologist Level Accurate Deep Learning System for OCT Screening and Diagnosis
                </h6>
                <p >
                  <span >Authors:</span> Mrinal Haloi
                </p>
                <p>
                  <span>Abstract</span>Abstract: In this work, we propose an advanced AI based grading system for OCT images. The proposed system is a very deep fully convolutional attentive classification network trained with end to end advanced transfer learning with online random augmentation. It uses quasi random augmentation that outputs confidence values for diseases prevalence during inference. Its a fully automated retinal OCT analysis A…
                </p>

                  <button class="btn btn-primary">Download</button>

              </li>
              <li>
                <h6>
                  Towards Ophthalmologist Level Accurate Deep Learning System for OCT Screening and Diagnosis
                </h6>
                <p >
                  <span >Authors:</span> Mrinal Haloi
                </p>
                <p>
                  <span>Abstract</span>Abstract: In this work, we propose an advanced AI based grading system for OCT images. The proposed system is a very deep fully convolutional attentive classification network trained with end to end advanced transfer learning with online random augmentation. It uses quasi random augmentation that outputs confidence values for diseases prevalence during inference. Its a fully automated retinal OCT analysis A…
                </p>

                  <button class="btn btn-primary">Download</button>

              </li>
              <li>
                <h6>
                  Towards Ophthalmologist Level Accurate Deep Learning System for OCT Screening and Diagnosis
                </h6>
                <p >
                  <span >Authors:</span> Mrinal Haloi
                </p>
                <p>
                  <span>Abstract</span>Abstract: In this work, we propose an advanced AI based grading system for OCT images. The proposed system is a very deep fully convolutional attentive classification network trained with end to end advanced transfer learning with online random augmentation. It uses quasi random augmentation that outputs confidence values for diseases prevalence during inference. Its a fully automated retinal OCT analysis A…
                </p>

                  <button class="btn btn-primary">Download</button>

              </li>
              <li>
                <h6>
                  Towards Ophthalmologist Level Accurate Deep Learning System for OCT Screening and Diagnosis
                </h6>
                <p >
                  <span >Authors:</span> Mrinal Haloi
                </p>
                <p>
                  <span>Abstract</span>Abstract: In this work, we propose an advanced AI based grading system for OCT images. The proposed system is a very deep fully convolutional attentive classification network trained with end to end advanced transfer learning with online random augmentation. It uses quasi random augmentation that outputs confidence values for diseases prevalence during inference. Its a fully automated retinal OCT analysis A…
                </p>

                  <button class="btn btn-primary">Download</button>

              </li>
              <li>
                <h6>
                  Towards Ophthalmologist Level Accurate Deep Learning System for OCT Screening and Diagnosis
                </h6>
                <p >
                  <span >Authors:</span> Mrinal Haloi
                </p>
                <p>
                  <span>Abstract</span>Abstract: In this work, we propose an advanced AI based grading system for OCT images. The proposed system is a very deep fully convolutional attentive classification network trained with end to end advanced transfer learning with online random augmentation. It uses quasi random augmentation that outputs confidence values for diseases prevalence during inference. Its a fully automated retinal OCT analysis A…
                </p>

                  <button class="btn btn-primary">Download</button>

              </li>
          </ol>
          <div class="modal fade" id="download_paper_modal" tabindex="-1" role="dialog" aria-labelledby="downloadLabel">
            <div class="modal-dialog modal-lg" role="document">
              <div class="modal-content">
                <div class="modal-header">
                  <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                  <h2 class="modal-title" id="downloadLabel">Downlaod Paper</h2>
                </div>
                <div class="modal-body">
                  <div class="row">
                    <div class="col-md-5">
                      <input type="email" class="form-control" id="paper_download_email" placeholder="Please enter email first.">
                      <input type="hidden" id="paper_code_download">
                      <a href="" id="download_paper_now" class="d-none" target="_blank">Download</a>
                    </div>
                    <div class="col-md-7">
                      <button class="btn btn-primary" onclick="download_paper()">Download</button>
                    </div>
                    <div class="col-md-12 d-none text-danger" id="download_wrong_email_msg">
                      Wrong Email, please enter correct email id.
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Publication'
}
</script>
<style scoped>
.tenth_div h6{
    font-size: 24px;
    font-weight: bold;
}
.tenth_div .btn {
    color: #fff;
    background-color: #f05f40;
    border: 1px solid #f05f40;
    border-radius: 30px;
    padding: 4px 14px;
    font-size: 15px;
    font-weight: 700;
}
.tenth_div ol li{
    padding-bottom: 20px;
}
.tenth_div hr{
    max-width: 50px;
    border-width: 3px;
    border-color: #000;
}

.tenth_div .container{
  text-align: left;
}

</style>
