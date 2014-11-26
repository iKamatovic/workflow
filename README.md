# Workflow

----
## What is Workflow?

It's a starter kit for JS development (Browserify + Gulp + Angular)

----
## Instalation

* Install [Node.JS](http://nodejs.org) if it's not already installed (tested on version 0.10.30)
* Clone project `git clone https://github.com/iKamatovic/workflow.git`
* From the place where packege.js is placed run `npm install`
* Install gulp.js `npm install -g gulp`

----
## Usage

At the moment just few tasks are available and you can execute them via gulp:

*  `gulp build` - it will collect your JS and templates and create one bundle file
*  `gulp watch` - it will observe changes on your JS files and templates and on every change execute build task
*  `gulp test [--env [local | remote] | --type [ acceptance | unit] | --tests coma_separated_paths_to_specific_test ]` - it will run your tests by default it will run acceptance tests on local environment

----
## TODO

*  create example app
*  task for reimporting static files into Java application
*  tests
*  provide better usage description
