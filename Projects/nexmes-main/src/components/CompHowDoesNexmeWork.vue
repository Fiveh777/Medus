<template>
  <div class="howdoes content">
  	<div class="container">
  		<div class="row">
			<div class="col-md-6 col-sm-12 col-xs-12 box-diagram">
				<h2>How does Nexme work?</h2>
				<div class="diagram-items">
					<div class="line-diagram"></div>
					<div class="box-items clearfix">
						<div class="content-item item-left">
							<div class="box-icon">
								<div class="box-img">
									<img src="../assets/images/noun_apply_2714905.svg">
								</div>
							</div>
							<div class="box-text">
								<h3>Apply to join Nexme</h3>
								<p>Joining is free.</p>
								<div class="box-link">
									<a href="">Partner with us</a>
								</div>
							</div>
						</div>
						<div class="content-item item-right">
							<div class="box-icon">
								<div class="box-img">
									<img src="../assets/images/Check_icon.svg">
								</div>
							</div>
							<div class="box-text">
								<h3>Get accepted as an agent</h3>
								<p>Once accepted, nothing changes for you except that Nexme sends you active leads.</p>
							</div>
						</div>
						<div class="content-item item-left">
							<div class="box-icon">
								<div class="box-img">
									<img src="../assets/images/noun_notification_1078232.svg">
								</div>
							</div>
							<div class="box-text">
								<h3>Receive requests</h3>
								<p>Users will request instant tours, scheduled tours, or seller interviews.</p>
							</div>
						</div>
						<div class="content-item item-right">
							<div class="box-icon">
								<div class="box-img">
									<img src="../assets/images/house_selected.svg">
								</div>
							</div>
							<div class="box-text">
								<h3>Represent the buyer</h3>
								<p>You represent the buyer just as you normally would, helping them find the perfect home.</p>
							</div>
						</div>
						<div class="content-item item-left">
							<div class="box-icon">
								<div class="box-img">
									<img src="../assets/images/noun_pay_3211158.svg">
								</div>
							</div>
							<div class="box-text">
								<h3>Make an offer</h3>
								<p>Help the buyer put together and submit a legal offer.</p>
							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="col-md-6 col-sm-12 col-xs-12 box-img">
				<img src="../assets/images/Handholdingphone.svg">
			</div>
		</div>
  	</div>
  </div>
</template>

<script>
export default {
  name: 'HowDoesNexmeWork',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.howdoes {
	padding-top: 50px;
}
.howdoes .box-diagram {
	margin-bottom: 75px;
}
.howdoes .box-img img{
	max-width: 100%;
	float: right;
}
.howdoes .box-diagram h2{
	color: #57C1A6;
	font-size: 50px;
	font-weight: 600;
	margin: 0;
	text-align: center;
}
.howdoes .box-diagram .diagram-items {
	position: relative;
	height: 522px;
	margin: 75px 0;
}
.howdoes .box-diagram .diagram-items .line-diagram[data-v-1006b620] {
    position: absolute;
    left: 50%;
    top: 0;
    height: 100%;
    border: 2px solid #E2E2E2;
    transform: translateX(-50%);
}
.howdoes .box-diagram .diagram-items .box-items {

}
.howdoes .box-diagram .diagram-items .box-items .content-item {
	width: 50%;
}
.howdoes .box-diagram .diagram-items .box-items .content-item:nth-child(1){
	    position: absolute;
    left: 0px;
    top: 0px;
}
.howdoes .box-diagram .diagram-items .box-items .content-item:nth-child(2){
	    position: absolute;
    right: 0px;
    top: 25%;
}
.howdoes .box-diagram .diagram-items .box-items .content-item:nth-child(3){
	    position: absolute;
    left: 0px;
    top: 50%;
}
.howdoes .box-diagram .diagram-items .box-items .content-item:nth-child(4){
	    position: absolute;
    right: 0px;
    top: 75%;
}
.howdoes .box-diagram .diagram-items .box-items .content-item:nth-child(5){
	    position: absolute;
    left: 0px;
    top: 100%;
}
.howdoes .box-diagram .diagram-items .box-items .content-item.item-left{
	text-align: right;
	float: left;
	    clear: left;
}
.howdoes .box-diagram .diagram-items .box-items .content-item.item-right{
	text-align: left;
	float: right;
	    clear: right;
}
.howdoes .box-diagram .diagram-items .box-items .content-item .box-icon {
    
}
.howdoes .box-diagram .diagram-items .box-items .content-item.item-left .box-icon {
    position: absolute;
    display: block;
    right: -37.5px;
}
.howdoes .box-diagram .diagram-items .box-items .content-item.item-right .box-icon {
    position: absolute;
    display: block;
    left: -37.5px;
}
.howdoes .box-diagram .diagram-items .box-items .content-item .box-icon .box-img {
    width: 75px;
    height: 75px;
    background: #F4F4F4 0% 0% no-repeat padding-box;
    border: 3px solid #FFFFFF;
    border-radius: 50%;
    position: relative;
}
.howdoes .box-diagram .diagram-items .box-items .content-item .box-icon .box-img img {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
.howdoes .box-diagram .diagram-items .box-items .content-item .box-text{
    margin-top: 26.5px;
}
.howdoes .box-diagram .diagram-items .box-items .content-item.item-left .box-text {
    margin-right: 75px;
}
.howdoes .box-diagram .diagram-items .box-items .content-item.item-right .box-text {
    margin-left: 75px;
}
.howdoes .box-diagram .diagram-items .box-items .content-item .box-text h3 {
	color: #57C1A6;
    font-size: 18px;
    font-weight: 600;
    margin-top: 0;
    margin-bottom: 10px;
}
.howdoes .box-diagram .diagram-items .box-items .content-item .box-icon:before{
	content: "";
    position: absolute;
    width: 90px;
    background-color: #E2E2E2;
    height: 4px;
    top: 50%;
    transform: translateY(-50%);
}
.howdoes .box-diagram .diagram-items .box-items .content-item.item-left .box-icon:before{
    right: 12px;
}
.howdoes .box-diagram .diagram-items .box-items .content-item.item-right .box-icon:before{
	left: 12px;
}
.howdoes .box-diagram .diagram-items .box-items .content-item .box-text p {
	color: #4C4C4C;
    font-size: 14px;
        margin-bottom: 0;
}
.howdoes .box-diagram .diagram-items .box-items .content-item .box-text .box-link {
	margin-top: 20px;
    display: inline-flex;
}
.howdoes .box-diagram .diagram-items .box-items .content-item .box-text .box-link a {
    color: #393939;
    font-size: 14px;
    padding: 12px 25px;
    background: #FDE76C 0% 0% no-repeat padding-box;
    box-shadow: 0px 3px 6px #0000001A;
    border-radius: 33px;
}
@media(max-width: 1024px){

}
@media(max-width: 991px){
	.howdoes .box-diagram h2 {
	    font-size: 40px;
	}
}
@media(max-width: 610px){
	.howdoes .box-diagram {
	    margin-bottom: 0;
	}
	.howdoes .box-diagram .diagram-items {
	    position: inherit;
	    height: auto;
        margin: 30px 0;
	}
	.howdoes .box-diagram .diagram-items .line-diagram {
	    display: none;
	}
	.howdoes .box-diagram .diagram-items .box-items .content-item{
	    position: inherit !important;
		width: 100%;
		box-shadow: 0px 3px 6px #00000029;
		margin-bottom: 20px;
		padding: 30px 20px;
		border-radius: 15px;
	}
	.howdoes .box-diagram .diagram-items .box-items .content-item.item-right .box-icon,
	.howdoes .box-diagram .diagram-items .box-items .content-item.item-left .box-icon{
		position: inherit !important;
	}
	.howdoes .box-diagram .diagram-items .box-items .content-item.item-right .box-text {
	    margin-left: 0px;
	}
	.howdoes .box-diagram .diagram-items .box-items .content-item.item-left .box-text {
	    margin-right: 0px;
	}
	.howdoes .box-diagram .diagram-items .box-items .content-item.item-left,
	.howdoes .box-diagram .diagram-items .box-items .content-item.item-right {
	    text-align: center;
	}
	.howdoes .box-diagram .diagram-items .box-items .content-item .box-icon:before{
		display: none;
	}
	.howdoes .box-diagram .diagram-items .box-items .content-item .box-icon .box-img {
	    margin: 0 auto;
	}
}
</style>
