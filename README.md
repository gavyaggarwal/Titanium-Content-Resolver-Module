Titanium-Content-Resolver-Module
================================

Allows Titanium Mobile (Android) Projects to Resolve content:// URLs

Copyright 2014 by Gavy Aggarwal

Sample Usage:

	var contentResolver = require('com.feistapps.contentresolver');
  var filePath = "file://" + contentResolver.resolveURL();
	var file = Ti.Filesystem.getFile(filePath);
