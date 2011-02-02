MooWatermark
===========

Help your users by providing a disappearing text right in the text field.

![Screenshot](http://www.magicwebsolutions.co.uk/demos/watermark/screenshot.png)

How to Use
----------

MooWatermark is essentially very easy to use

HTML

	<input type="text" name="watermarkname" id="watermarkname" />

JavaScript

	new MooWatermark({
		textField: 'watermarkname', 
		hint: 'Your name please'
	});	

If you wish to customise the style of the watermark, just add your own CSS class. A custom CSS class can be applied to the watermark by means of passing an additional watermarkClass attribute.

	new MooWatermark({
		textField: 'watermarkemail', 
		hint: 'Your email please',
		watermarkClass: 'watermarkGreen'
	});	

