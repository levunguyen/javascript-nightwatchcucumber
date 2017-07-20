# javascript-nightwatchcucumber
### Install nightwatch cucumber
npm install --save-dev nightwatch cucumber
### Install Selenium Driver
npm install -g selenium-server
### Install Phantomjs
npm install phantomjs-prebuilt
### run nightwatch
node_modules/.bin/nightwatch
## inorder to open the browser ,
we must implement chrome version >5 ( 59.0.3071.115)
## To open browser run
node_modules/.bin/nightwatch --env chrome
## generathtml report
npm install cucumber-html-reporter --save-dev
Then modify the nightwatch cucumber config file

## reference documents

https://www.libhive.com/providers/npm/packages/nightwatch-cucumber
https://github.com/mucsi96/nightwatch-cucumber

## API from here
http://nightwatchjs.org/
