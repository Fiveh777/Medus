<template>
  <div class="footer content">
    <div class="container">
    	<div class="row">
    		<div class="col-md-5 box-left">
    			<img src="../assets/images/Group606.svg">
    			<p>Nexme is an on demand real estate platform that delivers instant access to homes and full-service, professional real estate agents. All at the click of a button.</p>
    			<ul>
    				<li>
    					<img src="../assets/images/facebook-logo-button.svg">
    				</li>
    				<li>
    					<img src="../assets/images/twitter-logo-button.svg">
    				</li>
    				<li>
    					<img src="../assets/images/instagram-logo.svg">
    				</li>
    				<li>
    					<img src="../assets/images/linkedin.svg">
    				</li>
    			</ul>
    			<p>Privacy Policy | Terms of Use 
    			<br>
    			© nexme 2019</p>
    		</div>
    		<div class="col-md-7 box-right">
    			<div class="row">
    				<div class="col-md-4">
    					<h3>Features</h3>
    					<ul>
    						<li>
    							<a href="">Buy</a>
    							</li>
    							<li>
    							<a href="">Sell</a>
    							</li>
    							<li>
    							<a href="">Mortgage</a>
    						</li>
    					</ul>
    				</div>
    				<div class="col-md-4">
    					<h3>Partners</h3>
    					<ul>
    						<li>
    							<a href="">Agent</a>
							</li>
							<li>
    							<a href="">Lender</a>
							</li>
							<li>
    							<a href="">Builder</a>
    						</li>
    					</ul>
    				</div>
    				<div class="col-md-4">
    					<h3>Company</h3>
    					<ul>
    						<li>
    							<a href="">About Nexme</a>
							</li>
							<li>
    							<a href="">Blog</a>
							</li>
							<li>
    							<a href="">Careers</a>
							</li>
							<li>
    							<a href="">Corporate Partners Program</a>
							</li>
							<li>
    							<a href="">Press</a>
							</li>
							<li>
    							<a href="">contact@nexme.com</a>
							</li>
							<li>
    							<a href="">1-800-390-8801 (6am-7pm PT) (6am-7pm PT)</a>
    						</li>
    					</ul>
    				</div>
    			</div>
    		</div>
    	</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CompFooter',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer {
    background: #123B41;
    padding: 50px 0 150px;
}
.footer .box-left p{
    color: #FFFFFF;
    opacity: 0.6;
    font-weight: 300;
    font-stretch: normal;
    font-size: 12px;
    line-height: 25px;
    margin-top: 30px;
    margin-bottom: 30px;
}
.footer .box-left ul{
	display: flex;
}
.footer .box-left ul li{
	margin-right: 15px;
}
.footer .box-right h3 {
	position: relative;
    color: #FFFFFF;
    opacity: 0.6;
    margin: 0;
    font-weight: 600;
    font-size: 15px;
    margin-bottom: 55px;
}
.footer .box-right h3:before {
	content: '';
    position: absolute;
    width: 24px;
    height: 0px;
    border: 2px solid #FDE76C;
    top: 28px;
    left: 0;
}
.footer .box-right ul li{
	margin-bottom: 13px;
}
.footer .box-right ul li a{
	color: #FFFFFF;
    opacity: 0.6;
    font-size: 14px;
}
@media (max-width: 991px){
    .footer {
        padding: 50px 0 50px;
    }
    .footer .box-left p {
        font-size: 16px;
    }
    .footer .box-right ul li a {
        font-size: 16px;
    }
    .footer .box-right h3 {
        font-size: 18px;
        margin-bottom: 30px;
        margin-top: 30px;
    }
}
</style>
