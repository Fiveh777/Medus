<template>
  <div class="partner-network content">
    <div class="container">
    	<h2>An agent partner network of agents from 10+ firms</h2>
    	<ul class="box-items clearfix">
    		<li>
    			<img src="../assets/images/Century21.png"> 
    		</li>
    		<li>
    			<img src="../assets/images/BerkshireHathaway.png"> 
    		</li>
    		<li>
    			<img src="../assets/images/Remax.png"> 
    		</li>
    		<li>
    			<img src="../assets/images/JohnLScott.png"> 
    		</li>
    		<li>
    			<img src="../assets/images/kellerwilliams.png"> 
    		</li>
    		<li>
    			<img src="../assets/images/Windermere.png"> 
    		</li>
    		<li>
    			<img src="../assets/images/ColdwellBanker.png"> 
    		</li>
    		<li>
    			<img src="../assets/images/expRealty.png"> 
    		</li>
    	</ul>
    	<p>Nexme is a network of agent partners who operate independently. Real estate agents who sign up to the Nexme platform are licensed through their current real estate firms. Nexme does not hire real estate agents.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CompPartnerNetwork',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.partner-network {
	text-align: center;
	padding: 50px 0;
}
.partner-network h2 {
    color: #1A545D;
    font-weight: 600;
    font-size: 30px;
}
.partner-network p {
    color: #A0A0A0;
    font-weight: 400;
    font-size: 14px;
}
.partner-network .box-items {
   	margin: 40px 0;
}
.partner-network .box-items li{
	width: calc(12.5% - 50px);
    float: left;
    margin: 0 25px;
}
.partner-network .box-items li img {
    height: 98px;
    object-fit: contain;
    width: 100%;
}
.partner-network .box-items li p {
    line-height: 27px;
    color: #A0A0A0;
    font-size: 14px;
}
@media (max-width: 1024px){
    .partner-network .box-items li {
        width: calc(25% - 50px);
    }
    .partner-network h2 {
        font-size: 50px;
    }
}
@media (max-width: 991px){
    .partner-network .box-items {
        margin: 30px 0;
    }
    .partner-network h2 {
        font-size: 40px;
    }
    .partner-network p {
        font-size: 16px;
    }
}
@media (max-width: 610px){
    .partner-network .box-items li {
        width: calc(50% - 50px);
    }
}
</style>
