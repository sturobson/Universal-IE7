# Universal-IE7

An updated (Sassified) version of Andy Clarke's Universal IE6 stylesheet for IE7 and down.

To hide all your other stylesheets from Internet Explorer 7, wrap them inside this Conditional Comment.

	<!--[if ! lte IE 7]><!-->
	/* Stylesheets for browsers other than Internet Explorer 7 */
	<!--<![endif]-->

Then add the Universal Internet Explorer 6 stylesheet.

	<!--[if lte IE 7]>
	<link rel="stylesheet" href="css/universal-IE7.css" media="screen, projection">
	<![endif]-->


### notes:

This is how I'll be 'supporting' IE7 and IE6 unless a client requires different. I've coded the Sass to suit my way of working but hopefully it makes sense. Fork it and pull it apart.