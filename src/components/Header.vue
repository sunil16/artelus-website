<template >
<div>
  <nav id="nav" class="navbar navbar-inverse" data-spy="affix" data-offset-top="197" navbar-fixed-top :class="{ 'nav-change' : true == scrolled}">
    <div class="container-fluid">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
                          <span class="sr-only">Toggle navigation</span>
                          <span class="icon-bar"></span>
                          <span class="icon-bar"></span>
                          <span class="icon-bar"></span>
                      </button>
        <a class="navbar-brand page-scroll" href="#page-top"><img src="../assets/logo.png" style="margin-top:-21px;margin-left:-15px;margin-right:-20px;" height="75" width="75"></a>
        <a class="navbar-brand page-scroll" style="font-size:13px;" href="#page-top">Artificial Learning Systems</a>
      </div>

      <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
        <ul class="nav navbar-nav navbar-right">
          <li class="active"><a class="page-scroll" href="#page-top">Home</a></li>
          <li class=""><a class="page-scroll" href="#vision">Vision</a></li>
          <li class=""><a class="page-scroll" href="#mission">Mission</a></li>
          <li class=""><a class="page-scroll" href="#about">About</a></li>
          <li class=""><a class="page-scroll" href="#product">Products</a></li>
          <li class=""><a class="page-scroll" href="#advisor">Advisors</a></li>
          <li class=""><a class="page-scroll" href="#career">Careers</a></li>
          <li class=""><a class="page-scroll" href="#team">Team</a></li>
          <li class=""><a class="page-scroll" href="#media">In the news</a></li>
          <li class=""><a class="page-scroll" href="#publication">Publications</a></li>
          <li class=""><a class="page-scroll" href="#social">Social</a></li>
          <li class=""><a class="page-scroll" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <div class="header-container" id="page-top" style="background-color: RGBA(0, 170, 168, 1); color:#fff; height:200px;">

    <div class="container top_sec">
      <div class="scm-text col-xs-12 col-sm-4 col-md-4 col-lg-4" style="height: 101px;">
        <a href="">Number of patients Screened</a>
        <div class="inner-counter count statistics patients">61601</div>
        <div class="statistics-loader  mt-10px hidden">
          <i class="fa fa-refresh fa-2x fa-spin"></i>
        </div>
      </div>
      <div class="scm-text col-xs-12 col-sm-4 col-md-4 col-lg-4" style="height: 101px;">
        <a href="">Number of saved eyes</a>
        <div class="inner-counter count statistics saved">14448</div>
        <div class="statistics-loader  mt-10px hidden">
          <i class="fa fa-refresh fa-2x fa-spin"></i>
        </div>
      </div>
      <div class="scm-text col-xs-12 col-sm-4 col-md-4 col-lg-4" style="height: 101px;">
        <a href="">Number of locations</a>
        <div class="inner-counter count statistics locations">365</div>
        <div class="statistics-loader  mt-10px hidden">
          <i class="fa fa-refresh fa-2x fa-spin"></i>
        </div>
        <div class="inner-counter" style="font-size: 10px;">40 fixed locations</div>
      </div>

    </div>
  </div>
  <Vision id="vision" />
  <Mission id="mission" />
  <About id="about" />
  <Product id="product" />
  <Advisore id="advisor" />
  <Hiring id="career" />
  <Team id="team" />
  <InTheNews id="media" />
  <Publication id="publication" />
  <Social id="social" />
  <Contact id="contact" />
  <Footer id="footer" />

</div>
</template>
<script>
import Vision from './Vision.vue'
import Mission from './Mission.vue'
import About from './About.vue'
import Product from './Product.vue'
import Advisore from './Advisore.vue'
import Team from './Team.vue'
import InTheNews from './InTheNews.vue'
import Publication from './Publication.vue'
import Social from './Social.vue'
import Contact from './Contact.vue'
import Hiring from './Hiring'
import Footer from './Footer'

export default {
  name: 'Header',
  components: {
    Vision,
    Mission,
    About,
    Product,
    Advisore,
    Team,
    InTheNews,
    Publication,
    Social,
    Contact,
    Hiring,
    Footer
  },
  data() {
    return {
      activeItem: 'home',
      scrolled: false
    }
  },
  methods: {
    isActive: function(menuItem) {
      return this.activeItem === menuItem
    },
    setActive: function(menuItem) {
      this.activeItem = menuItem // no need for Vue.set()
    },
    handleScroll() {
      this.scrolled = window.scrollY > 80;
    }
  },
  created() {
    window.addEventListener('scroll', this.handleScroll);
  },
  destroyed() {
    window.removeEventListener('scroll', this.handleScroll);
  }

}
</script>

<style>
.header-container {
  background-image: url(../assets/main-bg-large.jpg);
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
  height: auto;
  min-height: 420px;
}

.affix {
  top: 0;
  width: 100%;
  z-index: 9999 !important;
}

.navbar {
  margin-bottom: 0px;
  position: fixed;
  width: 100%;
  top: 0;
  background-color: transparent;
  z-index: 999999 !important;
}

.affix~.container-fluid {
  position: relative;
  top: 50px;
}

.nav-change {
  background-color: #fff;
}

.nav {
  padding-top: 45px;

}

.nav>li.active>a,
.nav>li.active>a:focus {
  color: #FFF !important;
  background-color: #f05f40 !important;
}

.scm-text {
  text-align: center;
  box-shadow: 7px 6px 7px rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  width: 30%;
  background: #333;
  overflow: hidden;
  padding: 10px;
  min-height: 30px;
  margin: 5px 10px;
  opacity: 1;
  font-size: 16px;
}

.top_sec {
  padding-top: 179px;
  width: 979px !important;

}

.navbar-inverse {

  border-color: #a59cad;
  border: none;
  border-bottom: 0.5px solid #a59cad;
}
</style>
