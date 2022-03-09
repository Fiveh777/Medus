<template>
  <div class="customers content">
  	<div class="container">
  		<h2>Why do customers love Nexme?</h2>
    	<ul class="box-items">
    		<li class="item">
    			<div class="box-img">
    				<img src="../assets/images/Group14277.svg">
    			</div>
    			<div class="box-text">
    				<h3>Instant access</h3>
    				<p>Nexme makes it easy for homebuyers to connect with local, qualified agents like you.</p>
    			</div>
    		</li>
    		<li class="item">
    			<div class="box-img">
    				<img src="../assets/images/Group14714.svg">
    			</div>
    			<div class="box-text">
    				<h3>Make an offer right away</h3>
    				<p>Homebuyers make offers through the app, streamlining the process for both themselves and the agents that serve them.</p>
    			</div>
    		</li>
    		<li class="item">
    			<div class="box-img">
    				<img src="../assets/images/Group13158.svg">
    			</div>
    			<div class="box-text">
    				<h3>50% commission savings</h3>
    				<p>Everyone wants to save money. That’s why more people want to buy and sell on Nexme rather than other traditional real estate firms.</p>
    			</div>
    		</li>
    	</ul>
  	</div>
    
  </div>
</template>

<script>
export default {
  name: 'CompWhyDoCustomers',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.customers {
	padding: 50px 0;
	background: #F7F7F7;
}
.customers h2 {
    font-size: 50px;
    color: #57C1A6;
    font-weight: 600;
    text-align: center;
    margin: 0;
}
.customers .box-items {
    margin-top: 40px;
    position: relative;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
    grid-column-gap: 40px;
    display: grid;
    grid-row-gap: 30px;
    padding: 0;
}
.customers .box-items li{
	grid-column-start: span 4;
    grid-column-end: span 4;
    padding: 30px 20px;
    text-align: center;
}
.customers .box-items li .box-img img{
	height: 137px;
}
.customers .box-items li .box-text h3{
	font-size: 22px;
    font-weight: 600;
    margin: 25px 0 20px;
    color: #525252;
}
.customers .box-items li .box-text p{
	color: #A0A0A0;
    font-size: 16px;
    line-height: 30px;
}
@media (max-width: 1024px){
    .customers .box-items li {
        grid-column-start: span 6;
        grid-column-end: span 6;
    }
}
@media (max-width: 991px){
    .customers h2 {
        font-size: 40px;
    }
}
@media (max-width: 610px){
    .customers .box-items li {
        grid-column-start: span 12;
        grid-column-end: span 12;
        box-shadow: 0px 3px 6px #00000029;
        border-radius: 15px;
        grid-row-gap: 20px;
        background-color: #fff;
    }
    .customers .box-items {
        grid-column-gap: 15px;
    }
}
</style>
