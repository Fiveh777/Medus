<template>
  <div class="header content">
    <div class="container">
      <div class="row">
        <div class="box-logo col-md-4 col-sm-4 col-xs-6">
            <img src="../assets/images/nexme_logowhite.svg">
        </div>
        <div class="box-link col-md-4 col-sm-4 col-xs-0">
          <div class="box-button">
            <a href="">Partner with us</a>
          </div>
        </div>
        <div class="box-nav col-md-4 col-sm-4 col-xs-6">
            <ul class="nav-top">
                <li>
                    <a href="">Buy</a>
                </li>
                <li>
                    <a href="">Sell</a>
                </li>
                <li class="box-icon-user">
                    <div class="button-nav">
                      <div class="icon-menu">
                        <img src="../assets/images/Group14485.svg">
                      </div>
                      <div class="icon-user">
                        <img src="../assets/images/Path23848.svg">
                      </div>
                    </div>
                </li>
            </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'CompHeader',
    
  }
  
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
    padding: 22px 0 41px;
        top: 0;
    left: 0;
    width: 100%;
    position: fixed;
        z-index: 99;
}
.header .row {
    display: flex;
    align-items: center;
}
.header .box-nav ul.nav-top {
    float: right;
    display: flex;
        align-items: center;
}
.header .box-nav ul.nav-top li.box-icon-user {
    border: 2px solid #FFFFFF;
    border-radius: 28px;
    padding: 6px 6px 6px 15px;
    cursor: pointer;
}
.header .box-nav ul.nav-top li.box-icon-user .button-nav {
    display: flex;
    align-items: center;
}
.header .box-nav ul.nav-top li.box-icon-user .button-nav div{
  display: inherit;
}
.header .box-nav ul.nav-top li.box-icon-user .button-nav .icon-user {
    width: 30px;
    height: 30px;
    background: #E2E2E2;
    border-radius: 50%;
    margin-left: 10px;
    position: relative;
}
.header .box-nav ul.nav-top li.box-icon-user .button-nav .icon-user img{
  position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
.header .box-nav ul.nav-top li.box-icon-user .button-nav .icon-menu img{
  max-width: 15px;
}
.header .box-nav ul.nav-top li a{
    font-size: 16px;
    color: #FCFEFD;
    padding: 0 15px;
}
.header .box-logo img {
    max-width: 148px;
}
.header .box-link {
    text-align: center;
}
.header.darkHeader{
      background: #123B41;
      box-shadow: 0px 3px 6px #00000029;
}
.header.darkHeader .box-link .box-button{
  display: inline-flex;
}
.header .box-link .box-button{
    display: -webkit-inline-box;
    display: -ms-inline-flexbox;
    display: inline-flex;
    display: none;
}
.header .box-link .box-button a {
    color: #393939;
    font-size: 14px;
    padding: 12px 25px;
    background: #FDE76C 0% 0% no-repeat padding-box;
    box-shadow: 0px 3px 6px #0000001A;
    border-radius: 33px;
}
@media (max-width: 1024px){
  .header {
    padding: 20px 0;
  }
}
@media (max-width: 767px){
  .header .box-link {
    display: none;
  }
}
@media (max-width: 441px){
  .header .box-logo img {
      max-width: 120px;
  }
  .header .box-nav ul.nav-top li a {
      padding: 0 5px;
  }
  .header .box-nav ul.nav-top li.box-icon-user {
      padding: 5px 5px 5px 10px;
  }
  .header .box-nav ul.nav-top li.box-icon-user .button-nav .icon-user {
      width: 20px;
      height: 20px;
  }
  .header .box-nav ul.nav-top{
    margin-top: 8px;
  }
}
</style>
