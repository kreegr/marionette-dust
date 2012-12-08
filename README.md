# marionette-dust

## Overview
DustJS templates for Marionette. Overrides the appropriate Marionette functions 
to allow dust rendering in the normal Marionette flow of execution.

## Dependencies
* RequireJS
* Backbone and its dependencies
* Dust (winth LinkedIn helpers - if you want them)

## Usage
Include as a dependency in any file using Marionette Views along with Marionette. 
MUST pre compile templates using the DustJS pre-compiler as the render method 
must run synchronously. Later versions will allow asynchronous rendering.

To use, set the template property in your view to the pre-compiled template name 
(string). Marionette will do the rest for you.