# Website for hackGC 2018

## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/BlackrockDigital/startbootstrap-agency/master/LICENSE)
[![npm version](https://img.shields.io/npm/v/startbootstrap-agency.svg)](https://www.npmjs.com/package/startbootstrap-agency)
[![Build Status](https://travis-ci.org/BlackrockDigital/startbootstrap-agency.svg?branch=master)](https://travis-ci.org/BlackrockDigital/startbootstrap-agency)
[![dependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-agency/status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-agency)
[![devDependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-agency/dev-status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-agency?type=dev)


## For contributors -- Using Node.js to alter CSS and more

While editing the `index.html` file can be done without any advanced tools, you need to use transpiling tools in Node.js if you want to be able to work with the SCSS files. Here are some steps to help you get started:
1. [Download](https://nodejs.org/en/download/) and install Node.
2. Using the terminal, navigate to your project folder, then type `npm install`. This tells the **n**ode **p**ackage **m**anager to install all the packages that are specified in `package.json`.
3. One of the packages that were installed in the previous step is `gulp`, which is a tool that helps automate the development process. It can transpile your SCSS into CSS, minimize them, and more. All the terminal commands can be found in `gulpfile.js`, but the most important ones are:
  - `gulp css`: compiles all `.scss` files into minified `.css`
  - `gulp js`: minifies all `.js` files
  - `gulp dev`: does all of the above *automatically* whenever it detects a change!!

This website is based on the [Agency](https://blackrockdigital.github.io/startbootstrap-agency/) template from [Start Bootstrap](https://startbootstrap.com/template-overviews/agency/).
