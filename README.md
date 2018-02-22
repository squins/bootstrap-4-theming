# Bootstrap 4 theming


Basic setup to theme Bootstrap 4 library without modifying the library itself and package it in a distributable library.

Based on a modified version of [github.com/twbs/bootstrap/issues/24370#issuecomment-336684275](https://github.com/twbs/bootstrap/issues/24370#issuecomment-336684275)

## Environment

Package versions used

* npx: 9.7.1
* npm: 5.6.0
* node: 9.3.0

## Running the project

* In a console run `npx webpack -w`
* Run a webserver in `/dist`. To let `IDEA` run the webserver: right click on `dist/index.html` > `Run index.html` 

`webpack` is now watching for changes in `src`, edits will be visible in the browser after refresh.