<template>

  <section class="sixt_div">
   <div class="container">
       <div class="row">
           <div class="col-lg-12">
               <h2 class="section-heading text-center">We're Hiring</h2>
               <hr class="primary">
               <p class="text-center cont900">
                   Great products are made by great teams and great teams are made of great individuals. We prefer
                   to associate ourselves with people who are passionate about what they do, since that is how we
                   are. We work to make a difference in the world with our work. Are you such a person too? Here
                   are the openings we have currently- if you think you fit the bill, go ahead and apply!
                   You can either send your resumes to contact@artelus.com or use the Apply button below.

               </p>
           </div>
       </div>
   </div>
   <div class="container  text-center">
       <div class="row">
           <div class="col-md-12">
               <table class="career-table">
                   <thead>
                       <tr>
                           <td>Open Positions</td>
                           <td>Job Description</td>
                           <td>Apply</td>
                       </tr>
                   </thead>
                   <tbody>
                       <tr>
                           <td>Python Developer</td>
                           <td><a href="" class="btn btn-primary">View JD</a></td>
                           <td><a href="" class="btn btn-primary">Apply</a></td>
                       </tr>
                       <tr>
                           <td>Angular Developer</td>
                           <td><a href="" target="_blank" class="btn btn-primary">View JD</a></td>
                           <td><a href="" class="btn btn-primary">Apply</a></td>
                       </tr>
                       <tr>
                           <td>UI / UX Developer</td>
                           <td><a class="btn btn-primary">View JD</a></td>
                           <td><a class="btn btn-primary ">Apply</a></td>
                       </tr>
                       <tr>
                           <td>Android Developer</td>
                           <td><a class="btn btn-primary">View JD</a></td>
                           <td><a class="btn btn-primary">Apply</a></td>
                       </tr>
                       <tr>
                           <td>Python Tech Lead</td>
                           <td><a href="" target="_blank" class="btn btn-primary">View JD</a></td>
                           <td><a href="" class="btn btn-primary">Apply</a></td>
                       </tr>
                       <tr>
                           <td>Data Scientist</td>
                           <td><a href="" target="_blank" class="btn btn-primary">View JD</a></td>
                           <td><a href="" data-job="Data Scientist" data-toggle="modal" data-target="#jobApplyPop"
                                   data-backdrop="static" class="btn btn-primary japply">Apply</a></td>
                       </tr>
                       <tr>
                           <td>DevOps Engineer</td>
                           <td><a href="downloads/job-profiles/devops-engineer.pdf" target="_blank"
                                   class="btn btn-primary">View JD</a></td>
                           <td><a href="javascript:void(0)" data-job="DevOps Engineer" data-toggle="modal"
                                   data-target="#jobApplyPop" data-backdrop="static"
                                   class="btn btn-primary japply">Apply</a></td>
                       </tr>
                       <tr>
                           <td>Software Test Engineer</td>
                           <td><a href="downloads/job-profiles/software-test-engineer.pdf" target="_blank"
                                   class="btn btn-primary">View JD</a></td>
                           <td><a href="javascript:void(0)" data-job="Software Test Engineer" data-toggle="modal"
                                   data-target="#jobApplyPop" data-backdrop="static"
                                   class="btn btn-primary japply">Apply</a></td>
                       </tr>
                       <tr>
                           <td>Technical Architect</td>
                           <td><a href="downloads/job-profiles/technical-architect.pdf" target="_blank"
                                   class="btn btn-primary">View JD</a></td>
                           <td><a href="javascript:void(0)" data-job="Technical Architect" data-toggle="modal"
                                   data-target="#jobApplyPop" data-backdrop="static"
                                   class="btn btn-primary japply">Apply</a></td>
                       </tr>
                       <tr>
                           <td>Quality Assurance Manager</td>
                           <td><a href="downloads/job-profiles/quality-assurance-manager.pdf" target="_blank"
                                   class="btn btn-primary">View JD</a></td>
                           <td><a href="javascript:void(0)" data-job="Quality Assurance Manager"
                                   data-toggle="modal" data-target="#jobApplyPop" data-backdrop="static"
                                   class="btn btn-primary japply">Apply</a></td>
                       </tr>


                   </tbody>
               </table>
           </div>
       </div>
   </div>
</section>
</template>

<script>
export default {
  name: 'Hiring'
}
</script>
<style >
.sixt_div table{
    width: 100%;
    margin: auto;
    max-width: 779px;
}
.sixt_div table thead tr td{
    background-color: #f05f40;
    color: #fff;
    font-size: 16px;
    padding: 7px 0
}
.sixt_div table tr td .btn{
    background-color: #f05f40;
    border: 1px solid #f05f40;
    border-radius: 30px;
    font-size: 12px;
    font-weight: 700;
    padding: 5px 20px;
    color: #fff;
    text-transform: uppercase;

}
.sixt_div table tr{
    border-bottom: 1px solid red;
}
.sixt_div table tr td{
    padding: 6px 0px;
}
.sixt_div p{
    max-width: 900px;
    margin: auto;
    padding-bottom: 15px;
}
.sixt_div::before{
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
.sixt_div, .sevent_div{
    height: 109vh;
    position: relative;
    padding-top: 15px;
}
.sixt_div hr{
    max-width: 50px;
    border-width: 3px;
    border-color: #f05f40;
}
</style>
