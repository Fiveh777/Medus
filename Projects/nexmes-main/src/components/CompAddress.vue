<template>
  <div class="address content">
    <div class="container">
    	<div class="row">
    		<div class="box-text col-md-6 col-sm-6 col-xs-12">
    			<h2>Where is Nexme available?</h2>
    			<p>Nexme is available in <a href="">Washington</a> state and <a href="">Massachusetts</a>.</p>
    			<span>California coming soon!</span>
    		</div>
    		<div class="box-map col-md-6 col-sm-6 col-xs-12">
    			<img src="../assets/images/map.png"> 
    		</div>
    	</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CompAddress',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.address {
	padding: 70px 0;
}
.address .box-map img{
	width: 100%;
}
.address .box-text h2 {
    color: #57C1A6;
    font-weight: 600;
    font-size: 40px;
    margin: 0;
    margin-bottom: 10px;
}
.address .box-text p {
    color: #4C4C4C;
    font-size: 16px;
}
.address .box-text p a{
    color: #4C4C4C;
    font-size: 16px;
    text-decoration: underline;
}
.address .box-text span {
    color: #8DAAAE;
    font-size: 16px;
}
@media (max-width: 991px){
    .address {
      padding: 50px 0;
    }
}
@media (max-width: 767px){
    .address .box-map img {
        margin-top: 20px;
    }
}
</style>
