# ColdBox Elixir Vue Integration

This package provides Webpack support for compiling `.vue` files in your ColdBox Elixir 2 projects.

### Step 1: Install

```
npm install coldbox-elixir-vue --save-dev
```

### Step 2: Gulpfile.js

```
var elixir = require( "coldbox-elixir" );

require( "coldbox-elixir-vue" );

elixir( function( mix ) {
    mix.webpack( "main.js" ); // resources/assets/js/main.js
} );
```

## Contributions and Bugs

Project tracking for this project can be found at the [Ortus Solutions Jira](https://ortussolutions.atlassian.net/projects/ELIXIR/summary).  Please log all bugs, improvements, and features there.

Pull requests are welcome and encouraged.  Please [check on the Jira page](https://ortussolutions.atlassian.net/projects/ELIXIR/issues/?filter=allissues) before starting any large amount of work so your time isn't wasted.

Brad Wood (@bdw429s) has a [great guide on submitting pull requests.](https://www.ortussolutions.com/blog/submit-your-first-pull-request-to-an-open-source-project)  If you are unsure where to go, in need of help, or have a question, come ask in the #box-products channel on the [CFML Slack](http://cfml-slack.herokuapp.com/).
