<template>
  <div class="download-app content">
    <div class="container">
    	<h2>Download the app</h2>
    	<div class="box-img">
    		<img src="../assets/images/Appstore.svg"> 
    		<img src="../assets/images/Googleplay.svg"> 
    	</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CompDownloadApp',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.download-app {
    padding: 90px 0;
    text-align: center;
    background: #FDE76C;
}
.download-app h2 {
    color: #393939;
    font-weight: 600;
    font-size: 30px;
    line-height: 75px;
    margin: 0;
}
.download-app .box-img img {
    margin: 0 10px;
    max-width: 196px;
}
@media (max-width: 991px){
    .download-app {
      padding: 50px 0;
    }
}
@media (max-width: 610px){
  .download-app .box-img img {
      margin: 10px;
  }
}
</style>
