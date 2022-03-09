<template>
  <div class="client-info content">
    <div class="container">
    	<div class="row">
    		<div class="box-text col-md-6 col-sm-6 col-xs-12">
	    		<h3>Tom | <span>Nexme agent partner</span></h3>
	    		<p>“Nexme has connected me with homebuyers and sellers that I may have never met. It eliminates the upfront work, allows me to move quickly through the process of meeting them and providing my local expertise and insight, which is what I do best. It’s a win for me.”</p>
	    	</div>
	    	<div class="box-img col-md-6 col-sm-6 col-xs-12">
	    		<img src="../assets/images/AdobeStock_79055934.png" class="img-people"> 
	    		<img src="../assets/images/Path27809.svg" class="img-icon"> 
	    	</div>
    	</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CompClientInfo',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.client-info {
    background: #57C1A6;
}
.client-info .row{
	display: flex;
}
.client-info .box-img {
    position: relative;
}
.client-info .box-img .img-people{
    position: absolute;
    top: -38px;
    left: 25%;
    z-index: 1;
        height: calc(100% + 38px);
}
.client-info .box-img .img-icon{
    position: absolute;
    top: -38px;
    right: 0;
}
.client-info .box-text {
    margin-top: 93px;
    margin-bottom: 69px;
}
.client-info .box-text h3 {
    color: #FFFFFF;
    font-weight: 600;
    font-size: 22px;
    line-height: 24px;
    margin-top: 0;
    margin-bottom: 20px;
}
.client-info .box-text h3 span {
    color: #FFFFFFB2;
    font-weight: 400;
    font-size: 22px;
    line-height: 24px;
}
.client-info .box-text p {
    letter-spacing: 0px;
    color: #FFFFFF;
    font-size: 22px;
    line-height: 44px;
}
@media (max-width: 991px){
    .client-info .box-img .img-people {
        left: 0;
    }
    .client-info .box-img .img-icon{
        display: none;
    }
    .client-info .box-text p {
        font-size: 16px;
    }
    .client-info .box-text {
        margin-top: 50px;
        margin-bottom: 50px;
    }
}
@media (max-width: 767px){
    .client-info .box-img .img-people {
        position: inherit;
        top: 0;
        width: 100%;
        max-height: 400px;
        object-fit: contain;
    }
    
    .client-info .row {
         display: inherit; 
    }
}
</style>
