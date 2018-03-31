### Getting started
```
phonegap create myApp
cd myApp
phonegap serve
```

### Install SQLite plugin
```
phonegap plugin add cordova-sqlite-storage --save
```

### Install JQueryMobile 1.4.5
Download the requisite files and link them according in index.html
```
<link rel="stylesheet" href="css/jquery.mobile-1.4.5.min.css" />
<script src="js/jquery-1.11.1.min.js"></script>
<script src="js/jquery.mobile-1.4.5.min.js"></script>
```
Edit the index.html to have a multi-page structure