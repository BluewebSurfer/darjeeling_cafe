$(window).scroll(function(event) {
  
    // slide in from left
    $(".module-from-left").each(function(i, el) {
        var el = $(el);
        if (el.visible(true)) {
            console.log('in screen');
          // el.addClass("come-in"); 
          el.addClass("slide-left"); 
        } 
      });

  });