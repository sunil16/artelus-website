<template>
  <section class="sevent_div">



    <h2 class="section-heading text-center">Our Team</h2>
    <hr class="">


    <div class=" container text-center">
        <div class="row">
            <div class="col-md-4 ">
                <h3 class="teammate">Pradeep Walia</h3>
                <small class="team-pos">Co-Founder and Director</small>
                <p class="team-links"><a href="https://www.linkedin.com/in/pradeepwalia" target="_blank"><i
                            class="fa fa-linkedin-square"></i></a></p>
            </div>
            <div class="col-md-4 ">
                <h3 class="teammate">Raja Rajeshwari</h3>
                <small class="team-pos">Co-Founder and Director</small>
                <p class="team-links"><a href="https://in.linkedin.com/in/rajarajeshwari-k-16a22310"
                        target="_blank"><i class="fa fa-linkedin-square"></i></a></p>
            </div>
            <div class="col-md-4 ">
                <h3 class="teammate">Lalit Pant</h3>
                <small class="team-pos">Co-Founder</small>
                <p class="team-links"><a href="https://www.linkedin.com/in/lalit-pant-9461331" target="_blank"><i
                            class="fa fa-linkedin-square"></i></a></p>
            </div>
            <div class="col-md-4 ">
                <h3 class="teammate">Vish Durga</h3>
                <small class="team-pos">Co-Founder</small>
                <p class="team-links"><a href="https://www.linkedin.com/in/vdurga" target="_blank"><i
                            class="fa fa-linkedin-square"></i></a></p>
            </div>
            <div class="col-md-4 ">
                <h3 class="teammate">Mrinal Haloi</h3>
                <small class="team-pos">Head of Artificial Intelligence</small>
                <p class="team-links"><a href="https://www.linkedin.com/in/mrinalhaloi" target="_blank"><i
                            class="fa fa-linkedin-square"></i></a></p>
            </div>
            <div class="col-md-4 ">
                <h3 class="teammate">Raja Rajalakshmi K</h3>
                <small class="team-pos">Data scientist and Integration Lead</small>
                <p class="team-links"><a href="https://www.linkedin.com/in/rajarajalakshmi-k-25b82a2b/"
                        target="_blank"><i class="fa fa-linkedin-square"></i></a></p>
            </div>
            <div class="col-md-4 ">
                <h3 class="teammate">Rahul Arya</h3>
                <small class="team-pos">Software Developer</small>
                <p class="team-links"><a href="https://www.linkedin.com/in/ralien" target="_blank"><i
                            class="fa fa-linkedin-square"></i></a></p>
            </div>
            <div class="col-md-4 ">
                <h3 class="teammate">Sandeep Gajjam</h3>
                <small class="team-pos">Software Engineer</small>
                <p class="team-links"><a href="https://www.linkedin.com/in/" target="_blank"><i
                            class="fa fa-linkedin-square"></i></a></p>
            </div>
        </div>
    </div>
</section>
</template>

<script>
export default {
  name: 'Team'
}
</script>
<style scoped>
.sevent_div::before{
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    display: block;
    width: 100%;
    height: 100%;
    background-image: url(../assets/team.jpg);
    background-position: center center;
    background-size: cover;
    opacity: 0.2;
}
.sevent_div{
    height: 100vh;
    position: relative;
    padding-top: 25px;
}
.sevent_div h3{
    font-size: 24px;
    font-weight: 400;

}
.sevent_div hr{
    max-width: 50px;
    border-width: 3px;
    border-color: #f05f40;
}
.sevent_div .row>div{
    padding-bottom: 25px;
}
.sevent_div{
    height: 109vh;
    position: relative;
    padding-top: 15px;
}
.fa-linkedin-square{
      color: #e27459;
}
</style>
