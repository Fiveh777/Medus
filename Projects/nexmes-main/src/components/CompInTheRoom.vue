<template>
  <div class="room content">
  	<div class="container">
  		<img src="../assets/images/Elephanticon.svg"> 
	    <h2>The elephant in the room</h2>
	    <p>Why do we ask you to give 50% of your commission back?</p>
	    <div class="line"></div>
	    <p>Typically, you spend a lot of money and many hours to get new leads. Then you nurture them for weeks, if not months, with no idea if it will ever pan out. Our technology does all the upfront leg work so you can focus on giving our home buyers and sellers great service. You’re not doing any kind of outreach. We don’t give you a list of leads to follow up on, or a batch of zip codes for you to own. Homebuyers and sellers come directly to you. We make sure you get a qualified person who is interested in buying and/or selling a home. So what do we do with the rest of the commission? We give it back to the homebuyer and/or seller. We don’t take a commission.</p>
  	</div>
  </div>
</template>

<script>
export default {
  name: 'CompInTheRoom',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.room {
    padding: 50px 0;
    background: #1A545D;
    text-align: center;
}
.room img {
    width: 30px;
    margin-bottom: 30px;
}
.room h2 {
    font-size: 50px;
    color: #fff;
    font-weight: 600;
    margin: 0 0 10px;
}
.room p {
    color: #fff;
    line-height: 27px;
    font-size: 14px;
    margin-bottom: 0;
}
.room .line {
    height: 42px;
    border: 1px solid #FFFFFF;
    width: 0px;
    margin: 30px auto;
}
@media (max-width: 991px){
    .room h2 {
        font-size: 40px;
    }
    .room p {
      font-size: 16px;
  }
}
</style>
