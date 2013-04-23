# KiUI - [Kendo UI Web](http://www.kendoui.com/web.aspx) lost features

***

## Project objectives

Widgets, validators and other features for **Kendo UI Web** that were lost in time (and space)

## Installation

todo...

We should have a **NuGet** bundle

## Contributing

### Prepare the environment

* Install [Node.js](http://nodejs.org/) and NPM (should come with it)
* Install global dependencies: `npm install -g grunt-cli karma`
* Install local dev dependencies: `npm install` while current directory is KiUI repo

### Build

The project uses [Grunt](http://gruntjs.com/) as its build system.

To build the whole project execute `grunt`, this will run `jshint:dist`, `karma:singleRun`, `concat:dist`, `uglify:dist` targets.

### TDD

This project uses [Karma](http://karma-runner.github.com) to execute the tests.

To run all project's tests execute `grunt karma:singleRun`