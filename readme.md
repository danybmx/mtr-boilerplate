# Meteor boilerplate
This is a boilerplate that I use on my projects.

## Packages
* iron:router
* alanning:roles
* aldeed:collection2
* aldeed:autoform
* dburles:collection-helpers
* particle4dev:sass

## Core packages
* insecure
* lodash
* accounts-base

## Testing related packages
* velocity:html-reporter
* sanjo:jasmine

## Files structure
    |_ docs *Project documentation*
    |_ client
    | |_ layouts
    | | |_ *Website layouts*
    | |_ styles
    | | |_ *Website stylesheets*
    | |_ modules
    | | |_ example_module
    | | | |_ *Holds interface event handlers, route definitions, etc.*
    | | |_ example_module.html *Layouts for named module*
    |_ server
    | |_ modules
    | | |_ example_module
    | | | |_ *Holds publication functions, permission settings, etc.*
    |_ lib
    | |_ modules
    | | |_ example_module
    | | | |_ *Holds collection definitions, data validation/formatting functions, etc.*
    |_ public
    | |_ *Hold all static resources like images, vendor libraries, etc.*
    |_ private
    | |_ *Use for info that we don't want to share*
    |_ tests
    | |_ jasmine
    | | |_ client *Client-side*
    | | | |_ integration
    | | | | |_ *Executed directly inside the browser in a copy of the app*
    | | | | |_ *Can use subfolders*
    | | | |_ unit
    | | | | |_ *Executed directly inside the browser in the app*
    | | | | |_ *Can use subfolders*
    | | |_ server *Server-side*
    | | | |_ integration
    | | | | |_ *Executed directly inside the browser in a copy of the app*
    | | | | |_ *Can use subfolders*
    | | | |_ unit
    | | | | |_ *Executed directly inside the browser in the app*
    | | | | |_ *Can use subfolders*