mb-equalheight
==============

Simple jQuery plugin that equalize height of the children of a set of elements.

Usage
-----
	<!-- Load jQuery -->
	<script src="//ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>
	<script>
		// If load from CDN fail load jQuery locally
		if (typeof jQuery == 'undefined') {
	            document.write(unescape("%3Cscript src='js/Lib/jquery-1.11.0.min.js' type='text/javascript'%3E%3C/script%3E"));
	        }
	</script>
	<!-- Load plugin -->
	<script src="js/jquery.mb-equalheight.js"></script>
	<script>
		//Apply method to a container element (div, section, etc.)
		$(container).mb_equalheight([childrenSelector], [callback]);
		/*
		container: 		A selector that represents a container element or a set of 
					container elements
		childrenSelector:	A selector that filters children of parent element(s)	
		callback:		A Function launched everytyme the equalization of children of 
					a parent element is completed. The funzione pass a single 
					paramenter that is parent element just	processed
		*/
												
	
	</script>
