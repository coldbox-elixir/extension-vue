# ColdBox Elixir Vue Integration

This package provides Webpack support for compiling `.vue` files in your ColdBox Elixir 2 projects.

## Step 1: Install

```
npm install coldbox-elixir-vue --save-dev
```

## Step 2: Gulpfile.js

```
var elixir = require( "coldbox-elixir" );

require( "coldbox-elixir-vue" );

elixir( function( mix ) {
    mix.webpack( "main.js" ); // resources/assets/js/main.js
} );
```
