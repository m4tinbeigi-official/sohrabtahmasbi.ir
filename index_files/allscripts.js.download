// $ = jQuery
jQuery(function ($) {
  $(document).ready(function () {

    if ($("#crs-participants-carousel").length) {
      var sliderpost = tns({
        container: "#crs-participants-carousel",
        items: 1,
        gutter: 0,
        nav: true,
        mouseDrag: true,
        edgePadding: 0,
        autoplay: false,
        loop: false,
        autoplayButtonOutput: false,
        controlsText: [
          '<i class="ticon ticon-angle-left" aria-hidden="true"></i>',
          '<i class="ticon ticon-angle-right" aria-hidden="true"></i>',
        ],
        responsive: {
          520: {
            edgePadding: 0,
            items: 1,
          },
          768: {
            edgePadding: 0,
            items: 2,
          },
          980: {
            edgePadding: 0,
            items: 2,
          },
        },
      });
    }


    if ($("#whybozhan-carousel-in").length) {
      var sliderpost = tns({
        container: "#whybozhan-carousel-in",
        items: 1,
        gutter: 0,
        nav: true,
        mouseDrag: true,
        edgePadding: 40,
        autoplay: false,
        autoHeight: false,
        loop: true,
        autoplayButtonOutput: false,
        center: false,
        controlsText: [
          '<i class="ticon ticon-angle-left" aria-hidden="true"></i>',
          '<i class="ticon ticon-angle-right" aria-hidden="true"></i>',
        ],
        responsive: {
          520: {
            edgePadding: 60,
            items: 1,
          },
          768: {
            edgePadding: 0,
            items: 2,
          },
          980: {
            edgePadding: 0,
            items: 5,
          },
        },
      });
    }


    $(".questions-list-s>h2").click(function () {
      var self = $(this).parent();
      if (self.hasClass("active")) {
        $(".questions-list-s").removeClass("active");
      } else {
        $(".questions-list-s").removeClass("active");
        self.addClass("active");
      }
    });

    $(".courses-menu a").click(function (e) {
      e.preventDefault();
      let href = $(this).attr("href");
      $([document.documentElement, document.body]).animate(
        {
          scrollTop: $(href).offset().top - 130,
        },
        500
      );
    });


    $(".gotocrs, li.gotocrs a").click(function (e) {
      e.preventDefault();
      let href = $(this).attr("href");
      $([document.documentElement, document.body]).animate(
        {
          scrollTop: $(href).offset().top - 100,
        },
        500
      );
    });



    $(".courses-menu a").click(function () {
      var self = $(this).parent();
      if (self.hasClass("active")) {
        $(".courses-menu li").removeClass("active");
      } else {
        $(".courses-menu li").removeClass("active");
        self.addClass("active");
      }
    });


    /* ------------------------------ SIGNUP MODAL ----------------------------- */
    $(document).on("click", "#get-signup", function (event) {
      event.preventDefault();
      $(".signup_modal").addClass("signup_modal-show");
      $("body").css("overflow", "hidden");
    });

    $(document).on("click", ".signup_modal-close", function (event) {
      event.preventDefault();
      $(this).parent().parent().removeClass("signup_modal-show");
      $("body").css("overflow", "unset");
    });

    $(document).on("click", ".signup_modal-back", function (event) {
      event.preventDefault();
      $(this).parent().removeClass("signup_modal-show");
      $("body").css("overflow", "unset");
    });
    /* -------------------------------------------------------------------------------------- */

    /* ------------------------------ SIGNUP MODAL ----------------------------- */
    $(document).on("click", "#get-company", function (event) {
      event.preventDefault();
      $(".signup_modal").addClass("signup_modal-show");
      $("body").css("overflow", "hidden");
    });

    $(document).on("click", ".signup_modal-close", function (event) {
      event.preventDefault();
      $(this).parent().parent().removeClass("signup_modal-show");
      $("body").css("overflow", "unset");
    });

    $(document).on("click", ".signup_modal-back", function (event) {
      event.preventDefault();
      $(this).parent().removeClass("signup_modal-show");
      $("body").css("overflow", "unset");
    });
    /* -------------------------------------------------------------------------------------- */

    /* ------------------------------ SIGNUP MODAL ----------------------------- */
    $(document).on("click", "#get-headlines", function (event) {
      event.preventDefault();
      $(".headlines_modal").addClass("signup_modal-show");
      $("body").css("overflow", "hidden");
    });

    var fileUrl = $('#file-url').data('url')
    $('#file-url').remove();
    $('.file-url-input').val(fileUrl);


    $(document).on("click", ".signup_modal-close", function (event) {
      event.preventDefault();
      $(this).parent().parent().removeClass("signup_modal-show");
      $("body").css("overflow", "unset");
    });

    $(document).on("click", ".signup_modal-back", function (event) {
      event.preventDefault();
      $(this).parent().removeClass("signup_modal-show");
      $("body").css("overflow", "unset");
    });
    /* -------------------------------------------------------------------------------------- */


    $(document).on("click", "#get-levels-modal", function (event) {
      event.preventDefault();
      $(".signup_modal").addClass("signup_modal-show");
      $("body").css("overflow", "hidden");
    });

    $(document).on("click", "#get-levels-modal2", function (event) {
      event.preventDefault();
      if ($("input[name=level_modal_name]").val()) {
        $(".signup_modal").removeClass("signup_modal-show");
        $(".levels-modal2").addClass("levels-modal2-show");
        $("body").css("overflow", "hidden");
        $("input[name=quform_16_4]").val($("input[name=level_modal_name]").val());
        var text = "من " + $("input[name=level_modal_name]").val() + " به خودم و مدرسه بوژان قول میدهم موارد بالا را در دوره مدیریت محصول رعایت کنم.";
        $('.quform-option-label-16_3_1 span').html(text);
      } else {
        $("#level_input_name").addClass("input-warning");
      }
    });

    $(document).on("click", ".signup_modal-close", function (event) {
      event.preventDefault();
      $(this).parent().parent().removeClass("levels-modal2-show");
      $("body").css("overflow", "unset");
    });

    $(document).on("click", ".signup_modal-back", function (event) {
      event.preventDefault();
      $(this).parent().removeClass("levels-modal2-show");
      $("body").css("overflow", "unset");
    });

    $(document).on("click", ".lsn-box-en h5", function (event) {
      if ($(window).width() < 768) {
        event.preventDefault();
        $(this).parent().toggleClass("showul");
      }
    });


    $(document).on('click', '.kj-modal-open', function(e) {

      e.preventDefault();
  

      // Get the href attribute value of the clicked link
      var modalId = $(this).attr('href');

      // Add the 'active' class to the div with the corresponding ID
      $(modalId).addClass('active');
    });
  
    $(document).on('click', '.kj-modal-back, .kj-modal-close', function(e) {
      // Remove 'active' class from all kj-modal elements
      $('.kj-modal').removeClass('active');
    });






    /* ------------------------------ PDF MODAL ----------------------------- */
    $(document).on("click", "#level_pdf_modal", function (event) {
      event.preventDefault();
      $(".pdf-modal").addClass("signup_modal-show");
      $("body").css("overflow", "hidden");
    });

    $(document).on("click", ".level_video_modal", function (event) {
      event.preventDefault();
      $(".video-modal").addClass("signup_modal-show");
      $("body").css("overflow", "hidden");
    });

    /* -------------------------------------------------------------------------------------- */


$(document).on('click', '.log-link', function(e) {

      e.preventDefault();

      var link = $(this); // Save a reference to the link element
      var parent = link.parent(); // Save a reference to the parent element

      if (link.hasClass('loading')) {
        return; // Return early if the link already has the "loading" class
      }

      link.addClass('loading'); // Add the "loading" class to the link

      if (parent.find('a.agree_link').length === 0) {
        parent.append(agree_link); // Append the agree link HTML if no <a> element exists in the parent
      }

      link.removeClass('loading'); // Remove the "loading" class from the link

      if (link.hasClass('level_video_modal') || link.hasClass('kj-modal-open')) {
        return; // Return early if the link already has the "loading" class
      }

      // Redirect the user to the clicked URL
        window.open(url, '_blank');
    });



      $(document).on('click', '.agree_link', function(e) {

      e.preventDefault();
    
      var link = $(this); // Save a reference to the link element
      var parent = link.parent(); // Save a reference to the parent element
    
      if (link.hasClass('loading')) {
        return; // Return early if the link already has the "loading" class
      }
    
      link.addClass('loading'); // Add the "loading" class to the link
      link.hide();
      link.removeClass('loading'); // Remove the "loading" class from the link
    });
    


  });
});

