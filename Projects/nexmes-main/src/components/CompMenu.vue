<template>
  <div class="nav-right">
              <div class="header-nav-right">
                  <div class="box-left">
                      <h2>Menu</h2>
                  </div>
                  <div class="icon-close">
                      <i class="fa fa-times" aria-hidden="true"></i>
                  </div>
              </div>
              <ul class="clearfix">
                  <li>
                      <a href="#">Favorites</a>
                  </li>
                  <li>
                      <a href="#">Buy a home</a>
                  </li>
                  <li>
                      <a href="#">Sell a home</a>
                  </li>
                  <li>
                      <a href="#">Get pre-approved</a>
                  </li>
                  <li class="box-link-image">
                      <a href="#">
                        <div class="box-img">
                          <img src="../assets/images/Group1905.svg"> 
                        </div>
                        Download the app
                      </a>
                  </li>
                  <li>
                      <a href="#">Partners</a>
                  </li>
                  <li>
                      <a href="#">About</a>
                  </li>
                  <li>
                      <a href="#">Careers</a>
                  </li>
                  <li>
                      <a href="#">Log in/ Sign up</a>
                  </li>
                  <li>
                      <div class="box-button">
                        <a href="">Partner with us</a>
                      </div>
                  </li>
              </ul>
            </div>
</template>

<script>
export default {
  name: 'CompMenu',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav-right{
    position: fixed;
    top: 109px;
    bottom: 0;
    z-index: 19;
    overflow: hidden;
    width: 315px;
    transition: all 500ms ease 0s;
    transform: translateX(315px);
    opacity: 1;
    right: 0;
    padding: 0;
    margin: 0;
    background: #fff;
    overflow: auto;
    padding: 30px;
    box-shadow: -10px 3px 10px #0000001A;
  }
.nav-right.active{
    transform: translateX(0px);
  }
.nav-right .header-nav-right{
    display: flex;
    align-items: center;
    margin-bottom: 30px;
}
.nav-right .header-nav-right .box-left{
    width: 50%;
    text-align: left;
}
.nav-right .header-nav-right .box-left h2 {
        margin: 0;
    color: #4C4C4C;
    letter-spacing: 0px;
    font-weight: 600;
}
.nav-right .header-nav-right .icon-close{
    width: 50%;
    text-align: right;
}
.nav-right .header-nav-right .icon-close i{
    color: #A0A0A0;
}
.nav-right ul li{
  padding: 23px 0;
  border-top: 1px solid #E7ECF2;
}
.nav-right ul li a{
  font-size: 16px;
  color: #4C4C4C;
}
.nav-right ul li.box-link-image a{
  display: flex;
  align-items: center;
}
.nav-right ul li.box-link-image a .box-img{
  background: #FBEB6C;
  border-radius: 13px;
  position: relative;
  width: 52px;
  height: 52px;
  margin-right: 12px;
}
.nav-right ul li.box-link-image a .box-img img{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%,-50%);
}
.nav-right ul li:last-child{
  display: none;
}
.nav-right ul li .box-button {
    text-align: center;
}
.nav-right ul li .box-button a {
    color: #393939;
    font-size: 14px;
    padding: 12px 25px;
    background: #FDE76C 0% 0% no-repeat padding-box;
    -webkit-box-shadow: 0px 3px 6px #0000001A;
    box-shadow: 0px 3px 6px #0000001A;
    border-radius: 33px;
}
@media(max-width: 1024px){
  .nav-right {
    top: 86px;
  }
}
@media(max-width: 767px){
  .nav-right ul li:last-child{
    display: block;
  }
}
@media (max-width: 441px){
  .nav-right {
      top: 82px;
  }
}
</style>
