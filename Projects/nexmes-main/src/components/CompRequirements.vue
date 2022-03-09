<template>
  <div class="requirements content">
    <div class="container">
    	<div class="row">
    		<div class="col-md-6 col-sm-6 col-xs-12 box-img">
    			<img src="../assets/images/MaskGroup158.png">
    		</div>
    		<div class="col-md-6 col-sm-6 col-xs-12 box-text">
    			<h2>Our Agent Requirements</h2>
    			<ul>
    				<li>
    					<img src="../assets/images/Group13466.svg">
    					<p>Age 21+</p>
    				</li>
    				<li>
    					<img src="../assets/images/unlock_icon.svg">
    					<p>2+ years experience</p>
    				</li>
    				<li>
    					<img src="../assets/images/forsale.svg">
    					<p>10+ sales as the listing agent</p>
    				</li>
    			</ul>
    			<p>We do not hire agents, Nexme partner agents are licensed by their own firm. Partner agents agree to give 50% of their commission back</p>
    		</div>
    	</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Requirements',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.requirements{
	padding: 67px 0 50px;
	background: #1A545D
}
.requirements .box-img img{
	max-width: 88%;
}
.requirements .box-text h2{
	color: #fff;
	font-size: 50px;
	font-weight: 600;
	margin: 0;
}
.requirements .box-text p{
	font-size: 18px;
	color: #fff;
	opacity: 0.9;
	margin-bottom: 0;
}
.requirements .box-text ul{
	margin-top: 58px;
	margin-bottom: 40px;
}
.requirements .box-text ul li{
    display: flex;
    align-items: center;
    margin-bottom: 25px;
}
.requirements .box-text ul li img{
	max-width: 50px;
	margin-right: 40px;
}
@media (max-width: 1024px){
    .requirements .box-text h2 {
        font-size: 25px;
    }
    .requirements .box-text ul {
        margin-top: 15px;
        margin-bottom: 15px;
    }
    .requirements .box-text ul li {
        margin-bottom: 10px;
    }
    .requirements .box-text ul li img {
        max-width: 35px;
        margin-right: 20px;
    }
}
@media (max-width: 991px){
    .requirements .box-text p {
        font-size: 16px;
    }
    .requirements[data-v-f8a03c22] {
        padding: 50px 0 ;
        background: #1A545D;
    }
}
@media (max-width: 767px){
    .requirements .box-img img {
        max-width: 100%;
        width: 100%;
    }
    .requirements .box-text{
        margin-top: 30px;
    }
}
</style>
