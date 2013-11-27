# ![BaseballEmberJS](https://raw.github.com/andyfrith/BaseballExtJS/master/media/BaseballEmberJS.png)

## An application demo utilizing HTML 5, Ember.js, Ember Data, REST, PHP, and MySQL.

BaseballExtJS functionality provides the ability for a user to view and compare statistics for current and past MLB baseball players.  Stats are displayed in both tables and charts.  The User Interface was developed as a Sencha Ext JS MVC application.  Data access architecture utilizes the Slim PHP framework, as well as an Ext Direct API.  The database is an export of the lahman baseball database, created by Sean Lahman.

## Live demo

A live demo is available on our [website](http://demo.goodapplemedia.com)

## Screenshot

![screenshot](https://raw.github.com/andyfrith/BaseballExtJS/master/media/BaseballEmberJSScreenshot.png)

Asset Compilation
Ember App Kit is built around Grunt, an extremely easy-to-use task runner built in Node.js. Grunt is the de facto build tool of the front-end world, and EAK uses its huge ecosystem of tasks for compiling all kinds of assets, including:

Ember App Kit provides a base scaffolding for projects using Ember Tools.

Flat UI - Design Framework (HTML, CSS, JS). Flat UI Kit is made on the basis of Twitter Bootstrap, a comfortable, responsive, and functional framework that simplifies the development of websites.

Ember Data Build Status

Ember Data is a library for loading data from a persistence layer (such as a JSON API), mapping this data to a set of models within your client application, updating those models, then saving the changes back to a persistence layer. It provides many of the facilities you'd find in server-side ORMs like ActiveRecord, but is designed specifically for the unique environment of JavaScript in the browser.

Ember Data provides a central Data Store, which can be configured with a range of provided Adapters, but two core Adapters are provided: the RESTAdapter and FixtureAdapter.

The RESTAdapter is configured for use by default. You can read more about it in the Guides. It provides a fully RESTful mechanism for communicating with your persistence layer, and is the preferred and recommended choice for use with Ember Data.


Handlebars templates (or Emblem)
LESS (or SASS, or Compass, or Stylus…)
CoffeeScript
Minified JS & CSS

Features

prescribed file organization for sanity
scaffolding for learning curve mitigation
template precompilation for performance
single file application build for convenience
generators for faster application development
commonjs (node-style) modules
Version Information

Current Version: 0.01

Package versions:

ember v1.1.2
ember-data v1.0.0-beta.3
handlebars v1.0.0
jQuery 1.9.1
Flat-UI 2.1.1
Chart.js

D3.js
UI Packs

Future Goals

Source maps for transpiled modules
Better support for Ember generators
Easier to install 3rd party packages
Faster, more intelligent builds
Think anything else is missing? Feel free to open an issue (or, even better, a PR)! Discussion and feedback is always appreciated.