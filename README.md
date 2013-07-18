usa-map
================
Various imagemaps of the USA, including the usable SVG files for making your own.<br />
jQuery ImageMapster has also been implemented for the imagemap styling/scaling/etc.<br />
Because I need this at 1 point or another in my programming life, I thought I'd put it out there!

FEATURES:
=========
* USA w/o labels
* USA w/ labels for small states only
* USA w/ all labels
* Custom styled/scaled USA w/ Puerto Rico to demonstrate what can be done w/ the images
* jQuery ImageMapster built in for custom hover states in the imagemap

DEMO:
=====
http://one-off.textures-tones.com/usa-map/

CREDITS:
========
jQuery ImageMapster: http://www.outsharked.com/imagemapster/<br />
SVG files from Wikipedia<br />
I also found this site while stumbling, haven't looked into it too much yet though, but looks promising: http://digital-vector-maps.com/catalog.aspx/

HOW TO USE:
===========
It's a pretty standard HTML imagemap...?<br />
The ImageMapster is:
```
$(document).ready(function() {
	$("#usa-blank-image").mapster({
		fillOpacity: 0.5,
		fillColor: "000000",
		mapKey: "data-state",
		fadeInterval: 50
	});
});
```

NOTES:
======
For inspiration and more info, see the demo (http://one-off.textures-tones.com/usa-map/) and go through the source or peruse through the included files in this repository.