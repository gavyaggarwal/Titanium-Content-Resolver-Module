Titanium Content Resolver Module
================================

Allows Titanium Mobile (Android) Projects to Resolve Content URLs

Copyright 2014 by Gavy Aggarwal

Sample Usage:

	var contentResolver = require('com.feistapps.contentresolver');
	var filePath = "file://" + contentResolver.resolveURL();
	var file = Ti.Filesystem.getFile(filePath);



*Note: The Titanium Mobile 3.2.1GA Release fails to resolve content:// URLs, so I made this module as a workaround.
