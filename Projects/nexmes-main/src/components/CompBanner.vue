<template>
  <div class="banner content">
  	<div class="container">
  		<div class="box-title">
	    	<h2>Partner with Nexme</h2>
	    	<p>Scale your business with less effort. No more buying zip codes. Help us help our homebuyers and sellers with your 5 star service.</p>
	    </div>
	    <ul class="box-items">
    		<li class="item">
    			<div class="box-img">
    				<img src="../assets/images/Forsalesign.svg">
    			</div>
    			<div class="box-text">
    				<h3>Join for free</h3>
    				<p>There are no upfront costs or referral fees to join our partner agent network.</p>
    				<div class="box-link">
    					<a href="">Partner with us</a>
    				</div>
    			</div>
    		</li>
    		<li class="item">
    			<div class="box-img">
    				<img src="../assets/images/Group14701.svg">
    			</div>
    			<div class="box-text">
    				<h3>Access to active users</h3>
    				<p>Our active homebuyers and sellers want to talk to you! Get connected with them instantly and guide them in their journey.</p>
    			</div>
    		</li>
    		<li class="item">
    			<div class="box-img">
    				<img src="../assets/images/Group12998.svg">
    			</div>
    			<div class="box-text">
    				<h3>Easy to use platform</h3>
    				<p>Keep track of all your activity with our easy to use dashboard. Tour, interview, offer, and sale data in one place.</p>
    			</div>
    		</li>
    		<li class="item">
    			<div class="box-img">
    				<img src="../assets/images/Group14698.svg">
    			</div>
    			<div class="box-text">
    				<h3>24/7 support</h3>
    				<p>Reach out to us whenever you need, for whatever you need. We’re there for you so you can be there for any prospective homebuyers and sellers.</p>
    			</div>
    		</li>
    	</ul>
  	</div>
    
  </div>
</template>

<script>
export default {
  name: 'Banner',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.banner {
    padding: 140px 0 109px;
    background: transparent url("../assets/images/Background.svg") 0% 0% no-repeat padding-box;
    background-size: cover;
}
.banner .box-title {
    text-align: center;
    color: #fff;
    max-width: 840px;
    margin: 0 auto;
}
.banner .box-title h2 {
    font-size: 73px;
    font-weight: 600;
    margin-bottom: 30px;
    margin-top: 0;
}
.banner .box-title p{
	font-size: 22px;
}
.banner .box-items {
    margin-top: 90px;
    position: relative;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
    grid-column-gap: 15px;
    display: grid;
    grid-row-gap: 30px;
    padding: 0;
}
.banner .box-items li{
	background: #FFFFFF;
	box-shadow: 0px 3px 6px #00000029;
	border-radius: 15px;
	grid-column-start: span 3;
    grid-column-end: span 3;
    padding: 40px 20px;
        text-align: center;
}
.banner .box-items li .box-img img{
	    height: 168px;
}
.banner .box-items li .box-text h3{
	    font-size: 22px;
    font-weight: 600;
    margin: 20px 0;
}
.banner .box-items li .box-text p{
	color: #A0A0A0;
    font-size: 16px;
    line-height: 30px;
}
.banner .box-items li .box-text .box-link{
    margin-top: 25px;
    display: inline-block;
}
.banner .box-items li .box-text .box-link a{
	color: #393939;
    font-size: 16px;
    padding: 16px 25px;
    background: #FDE76C;
    width: 174px;
    margin: 0 auto;
    box-shadow: 0px 3px 6px #0000001A;
    border-radius: 33px;
}
@media (max-width: 1366px){
	.banner .box-items li .box-text h3{
	    min-height: 48px;
	}
}
@media (max-width: 1024px){
    .banner .box-items li .box-text h3{
        min-height: 48px;
    }
    .banner .box-items li[data-v-1cc567cb] {
        grid-column-start: span 6;
        grid-column-end: span 6;
    }
    .banner .box-items li .box-text h3{
        min-height: inherit;
    }
    .banner .box-title h2 {
        font-size: 50px;
    }
}
@media (max-width: 991px){
    .banner {
        padding: 140px 0 50px;
    }
    .banner .box-title h2 {
        font-size: 40px;
    }
    .banner .box-title p {
        font-size: 16px;
    }
}
@media (max-width: 610px){
    .banner .box-items li[data-v-1cc567cb] {
        grid-column-start: span 12;
        grid-column-end: span 12;
    }
}
</style>
