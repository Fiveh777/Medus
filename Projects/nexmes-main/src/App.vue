<template>
  <div id="app">
      <CompHeader />
      <CompMenu />
      <CompBanner />
      <CompRequirements />
      <CompHowDoesNexmeWork />
      <CompWhyDoCustomers />
      <CompInTheRoom />
      <CompPartnerNetwork />
      <CompClientInfo />
      <CompAddress />
      <CompDownloadApp />
      <CompFooter />
  </div>
</template>

<script>
import CompHeader from './components/CompHeader.vue';
import CompBanner from './components/CompBanner.vue';
import CompRequirements from './components/CompRequirements.vue';
import CompHowDoesNexmeWork from './components/CompHowDoesNexmeWork.vue';
import CompMenu from './components/CompMenu.vue';
import CompWhyDoCustomers from './components/CompWhyDoCustomers.vue';
import CompInTheRoom from './components/CompInTheRoom.vue';
import CompPartnerNetwork from './components/CompPartnerNetwork.vue';
import CompClientInfo from './components/CompClientInfo.vue';
import CompAddress from './components/CompAddress.vue';
import CompDownloadApp from './components/CompDownloadApp.vue';
import CompFooter from './components/CompFooter.vue';
export default {
  name: 'App',
  components: {
    CompHeader,
    CompBanner,
    CompRequirements,
    CompHowDoesNexmeWork,
    CompMenu,
    CompWhyDoCustomers,
    CompInTheRoom,
	CompPartnerNetwork,
	CompClientInfo,
	CompAddress,
	CompDownloadApp,
	CompFooter
  },
  mounted () {
	  $(".header .box-nav .button-nav").click(function () {
	      $(".nav-right").toggleClass("active");
	      return false;
	  });
	  $(".nav-right .header-nav-right .icon-close i").click(function () {
	      $(".nav-right").removeClass("active");
	  });
    $(".content").click(function () {
        $(".nav-right").removeClass("active");
    });
  	$(window).scroll(function() {    
  	    var scroll = $(window).scrollTop();
  	    if (scroll >= 109) {
  	        $(".header").addClass("darkHeader");
  	    }
  	    else{
  	    	$(".header").removeClass("darkHeader");
  	    }
		}); 
  }
}
</script>

<style>
body, h1, h2, h3, h4, h5, h6, p, a, span{
	font-family: 'Montserrat', sans-serif;
}
ul {
    padding: 0;
    margin: 0;
    list-style-type: none;
}
@media (min-width: 1440px){
	body .container {
	    width: 75%;
	}
}
@media (max-width: 441px){
  .content h2{
    font-size: 30px !important;
  }
}
</style>
