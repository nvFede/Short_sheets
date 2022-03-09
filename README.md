# Short_sheets


	$('.fb-custom-btn').click(function() {
		window.open('https://www.facebook.com/sharer/sharer.php?u=' 
   + encodeURIComponent(document.URL) + '&t=' 
   + encodeURIComponent(document.URL)); return false;
	})
	
	$('.pin-custom-btn').click(function() {
		window.open('http://pinterest.com/pin/create/button/?url=' 
   + encodeURIComponent(document.URL) + '&description=' 
   + encodeURIComponent(document.title)); return false;
	});
	
	$('.tw-custom-btn').click(function() {
	  window.open('https://twitter.com/intent/tweet?url=' 
	 + encodeURIComponent(document.URL) + '&text=' 
	 + encodeURIComponent(document.title)); return false;
	});

	$('.lnk-custom-btn').click(function() {
		window.open('http://www.linkedin.com/shareArticle?mini=true&url=' 
   + encodeURIComponent(document.URL) + '&title=' 
   + encodeURIComponent(document.title)); return false;
	});
	
	$('.wsp-custom-btn').click(function() {
		window.open('whatsapp://send?text=' 
   + encodeURIComponent(document.URL) + '&title=' 
   + encodeURIComponent(document.title)); return false;
	});
