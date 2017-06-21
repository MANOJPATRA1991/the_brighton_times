# The Brighton Times 

## Table of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Demo](#Demo)
5. [Reference](#reference)
6. [License](#license)

## Introduction
A simple news style website made as part of project assignment during the **[Udacity's Full Stack Nanodegree program](https://in.udacity.com/course/full-stack-web-developer-nanodegree--nd004/)'s Core Module 1's [Responsive Web Design Fundamentals](https://www.udacity.com/course/responsive-web-design-fundamentals--ud893) classes**.
The website is responsive to various display devices.
While building this website, the basics of responsive web design and responsive images were put into practice.

### Installation

The project requires [nodeJS](https://nodejs.org/en/download/) in order to install the required node modules.

After installing nodeJS, run `npm install` in the Command Line from within the working directory to install **Grunt** and othergrunt node packages from the package.json file.

If you haven't used [Grunt](https://gruntjs.com/) before, be sure to check out the [Getting Started](https://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](https://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins.

After installing grunt as a node package, we need to install Grunt CLI globally. To do this
`npm install -g grunt-cli`.

The grunt modules required for this project are:
1. `grunt-contrib-jshint`
2. `grunt-contrib-nodeunit`
3. `grunt-contrib-uglify`
4.  `grunt-contrib-clean`
5.  `grunt-mkdir`
6.  `grunt-contrib-copy`

Check out the [gruntfile.js](https://github.com/MANOJPATRA1991/the_brighton_times/blob/master/Gruntfile.js) for this project.

To run grunt tasks, in command prompt type `grunt`.

Here, we are creating new images with reduced width and quality, for use within our responsive website. The new images are created with 400 x 267 and file size: 18.1 KB(original image 2047 x 1364, file size: 433 KB) inside `images_resp` folder.

### Demo

You can check the demo of the website [here](https://youtu.be/v7mIOb7yetE).

### Reference
1. [Grunt](https://gruntjs.com/)
2. [Responsive Images](https://classroom.udacity.com/courses/ud882-nd)

### License
The content of this repository is licensed under [MIT](https://choosealicense.com/licenses/mit/).
