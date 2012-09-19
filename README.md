robson
======

Robson is a script that automates the release process for building PhoneGap releases.

Usage
-----
	./robson all 2.1.0 2.0.0
   	// Creates temp directory which contains release folder and repositories folder for Apache Cordova. Creates phonegap directory for phonegap release.
	
	./robson prepare 2.1.0 2.0.0
	// Creates temp directory which contains release folder and repositories folder for Apache Cordova. (runs coho)
	
	./robson build 2.1.0 2.0.0
	// assumes prepare command has been run, updates phonegap directory to latest code.
	
	
Issues
------

Please file all issues at https://github.com/stevengill/robson/issues