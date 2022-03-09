(function ($) {
  'use strict';
    var drawerMenu = function () {
      const $menu = $('.box_Mobile');
      const $menu_2 = $('[data-dropdown|="mobile_menu"]');
      $(document).mouseup(e => {
        if (!$menu.is(e.target) && !$menu_2.is(e.target) // if the target of the click isn't the container...
            && $menu.has(e.target).length === 0 && $menu_2.has(e.target).length === 0) // ... nor a descendant of the container
        {
          $('#header').find('div[data-dropdown|="mobile_menu"]').removeClass('is-active');
          $(".box_Mobile .header__mobile-nav-toggle").removeClass("is-active")
        }
      });

      $('.box_Mobile .header__mobile-nav-toggle').on('click', () => {                            
                                                     $(".box_Mobile .header__mobile-nav-toggle").toggleClass("is-active")
      $('div[data-dropdown|="mobile_menu"]').toggleClass('is-active');
    });

  };
  var menuscroll_Desktop = function () {
    if ($("#shopify-section-header .main-nav__wrapper").length) {
      var contentPaddingTop$ = parseInt($(".index-sections").css("paddingTop"), 10);
      var header_position = $("#shopify-section-header .main-nav__wrapper").offset().top;
      $(window).on("scroll touchmove", function() {
        var scroll = $(window).scrollTop();
        if (scroll > header_position) {
          if ($("#shopify-section-header .main-nav__wrapper").not(".sticky").length) {
            $("#shopify-section-header .main-nav__wrapper").addClass("sticky");
            var headerHeight$ = $("#shopify-section-header .main-nav__wrapper").height();
            $(".index-sections").css("paddingTop", contentPaddingTop$ + headerHeight$ + "px");
          }
        } else {
          if ($("#shopify-section-header .main-nav__wrapper").hasClass("sticky")) {
            $("#shopify-section-header .main-nav__wrapper").removeClass("sticky");
            $(".index-sections").css("paddingTop", contentPaddingTop$ + "px");
          }
        }
      });
    }
  };
  var menuscrollMobile = function () {
    if ($("#shopify-section-header .top-bar").length) {
      var contentPaddingTop$ = parseInt($(".index-sections").css("paddingTop"), 10);
      var header_position = $("#shopify-section-header .top-bar").offset().top;
      $(window).on("scroll touchmove", function() {
        var scroll = $(window).scrollTop();
        if (scroll > header_position) {
          if ($("#shopify-section-header .top-bar").not(".sticky").length) {
            $("#shopify-section-header .top-bar").addClass("sticky");
            var headerHeight$ = $("#shopify-section-header .top-bar").height();
            $(".index-sections").css("paddingTop", contentPaddingTop$ + headerHeight$ + "px");
          }
        } else {
          if ($("#shopify-section-header .top-bar").hasClass("sticky")) {
            $("#shopify-section-header .top-bar").removeClass("sticky");
            $(".index-sections").css("paddingTop", contentPaddingTop$ + "px");
          }
        }
      });
    }
  };
  var tabsProduct = function () {
    $( "#tabs" ).tabs();
    $( "#tabs-product" ).tabs();
  };

  var sliderCustom = function () {
    $('.section-text-with-icons .text-with-icons').flickity({
      // options
      cellAlign: 'center',
      contain: true,
      prevNextButtons: false,
      pageDots: false
    });
    $('.accordian-product-tab.desktop .slider_Image').flickity({
      // options
      cellAlign: 'center',
      contain: true,
      prevNextButtons: false,
      pageDots: true
    });
    $('.accordian-product-tab.mobile .slider_Image').flickity({
      // options
      cellAlign: 'center',
      contain: true,
      prevNextButtons: false,
      pageDots: true
    });
  };
  var checkScreenSize = function(){
    var newWindowWidth = $(window).width();
    if (newWindowWidth <= 481) {
      $('.promo-bar-v2 .text-with-icons__item').flickity({
        // options
        cellAlign: 'center',
        contain: true,
        prevNextButtons: false,
        pageDots: true,
        autoPlay: true
      });
    }
    if (newWindowWidth <= 769 ) {
      $('.promo-block-in-collection .block-list').flickity({
        // options
        cellAlign: 'center',
        contain: true,
        prevNextButtons: false,
        pageDots: false
      });
    }
  }
  var accordionProduct = function () {
    $('.card__collapsible .card__collapsible-button').on('click', function () {
      $(this).parent().children('.card__collapsible-main').slideToggle();
      $(this).toggleClass('active');
      return false;
    });
    
    $('.accordian-product-tab.mobile .card__collapsible-button').on('click', function () {
      $(this).parent().children('.card__collapsible-main').slideToggle();
      $(this).toggleClass('active');
      return false;
    });
    
  }
  
  var toggleText = function () {
    $(".expandable-content__toggle").click(function(){
      var text = $(this).children(".expandable-content__toggle-text").html();
      if(text === "View more"){
        $(this).addClass("is-active");
        $(this).children(".expandable-content__toggle-text").text("View less");
        $(this).parent().find(".expandable-content").attr("aria-expanded", "false");

      } else if(text === "View less"){
        $(this).removeClass("is-active");
        $(this).children(".expandable-content__toggle-text").text("View more");
        $(this).parent().find(".expandable-content").attr("aria-expanded", "true");
        $('html, body').animate({
          scrollTop: $(this).parent().offset().top
        }, 600)
      }
    })
  }
  var toggleAccounts = function () {
    $(".main_Accounts a").click(function(){
      $(this).parent().toggleClass("is-active")
      $(this).parent().find("#account-popover").toggleClass("is-active");
      $(this).parent().find("#header-login-panel").toggleClass("is-active");
    })
    $("#create_account").click(function(){
      $(this).parent().parent().parent().parent().removeClass("is-active");
      $(this).parent().parent().parent().parent().parent().find("#header-register-panel").addClass("is-active")
    })
    $("#recover_password").click(function(){
      $(this).parent().parent().parent().parent().removeClass("is-active");
      $(this).parent().parent().parent().parent().parent().find("#header-recover-panel").addClass("is-active")
    })
    $("#login_here").click(function(){
      $(this).parent().parent().parent().parent().removeClass("is-active");
      $(this).parent().parent().parent().parent().parent().find("#header-login-panel").addClass("is-active")
    })
    $("#back_to_login").click(function(){
      $(this).parent().parent().parent().parent().removeClass("is-active");
      $(this).parent().parent().parent().parent().parent().find("#header-login-panel").addClass("is-active")
    })
   
    const $menu = $('.main_Accounts');
    $(document).mouseup(e => {
      if (!$menu.is(e.target) // if the target of the click isn't the container...
          && $menu.has(e.target).length === 0) // ... nor a descendant of the container
      {
        $menu.removeClass("is-active");
        $menu.find("#account-popover").removeClass('is-active');
        $menu.find(".popover__panel").removeClass("is-active")
      }
    });

  }
  var toggleAccountsMobile = function () {
    $(".div_Mobile .show_Menu").click(function(){
      $(this).toggleClass("is-active")
      $(this).parent().find(".box_Menu").toggleClass("is-active")
    })
   
    const $menu = $('.div_Mobile .value-picker__inner');
    $(document).mouseup(e => {
      if (!$menu.is(e.target) // if the target of the click isn't the container...
          && $menu.has(e.target).length === 0) // ... nor a descendant of the container
      {
        $menu.parent().removeClass("is-active");
      }
    });
    $(".div_Mobile .value-picker__close").click(function(){
      $(this).parent().parent().parent().removeClass("is-active")
      $(this).parent().parent().parent().parent().find(".show_Menu").removeClass("is-active")
    })

  }

  jQuery(document).ready(function ($) {
    drawerMenu();
    menuscroll_Desktop();
    menuscrollMobile();
    tabsProduct();
    sliderCustom();
    checkScreenSize();
    accordionProduct();
    toggleText();
    toggleAccounts();
    toggleAccountsMobile();
  });
  jQuery(window).on("resize", function (e) {
    checkScreenSize();
  });

})(jQuery);

