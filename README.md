# Universal-IE7


An updated (Sassified) version of Andy Clarke's Universal IE6 stylesheet for IE7

To hide all your other stylesheets from Internet Explorer 7, wrap them inside this Conditional Comment.

	<!--[if ! lte IE 7]><!-->
	/* Stylesheets for browsers other than Internet Explorer 7 */
	<!--<![endif]-->

Then add the Universal Internet Explorer 6 stylesheet.

	<!--[if lte IE 7]>
	<link rel="stylesheet" href="css/universal-IE7.css" media="screen, projection">
	<![endif]-->


