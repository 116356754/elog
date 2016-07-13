# ellog
A node module for log in electron applications.

##Introduction
Just a very simple logging module for your Electron application. No complicated configuration. Just require and use.

This module can used in main process or render process in electron,we use third party module--**elis** 	

##install
    npm install ellog --save

##usage
    var log = require('ellog');
    log.info('hello world');
    log.error('hello error');

##location

By default it writes logs to :
	$HOME/AppData/Roaming/`<app name>`/`year_month_day_`log.txt