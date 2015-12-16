# Firepad-RethinkDB

Firepad-RethinkDB is an open-source, collaborative code and text editor. It is
designed to be embedded inside larger web applications.

## Forked from [Firepad](https://firepad.io)
This repo is a fork from Firepad which was origianlly built to be used with Firebase. I started to use it, and really didn't like the Firebase back end for security and robustness reasons. So I am rewritting this to work with RethinkDB instead. Which is a server-side realtime database.

## Live Demo

Coming Soon.

## Setup
Firepad-RethinkDB uses [RethinkDB](https://www.rethinkdb.com) as a backend, so it does require server side code. 

```HTML
<!-- Firebase -->
<script src="https://cdn.firebase.com/js/client/2.2.4/firebase.js"></script>

<!-- CodeMirror -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/codemirror/5.2.0/codemirror.js"></script>
<!-- Insert firepad-rethinkdb link here -->

<!-- Firepad -->
<link rel="stylesheet" href="https://cdn.firebase.com/libs/firepad/1.2.0/firepad.css" />
<!-- Insert firepad-rethinkdb link here -->
```

and calling an init function.

```HTML
<!-- Rewrite with new init functions -->
```

Firepad-RethinkDB supports rich text editing with [CodeMirror](http://codemirror.net/) and code editing via
[ACE](http://ace.c9.io/). Check out the detailed setup instructions at ( Coming Soon... ).

## Contributing

We love pull requests. If you'd like to contribute to Firepad-RethinkDB, run the following commands to get your environment set up:

```bash
$ git clone https://github.com/shadowcodex/firepad-rethinkdb.git
$ cd firepad-rethinkdb      # go to the firepad directory
$ npm install -g grunt-cli  # globally install grunt task runner
$ npm install -g bower      # globally install Bower package manager
$ npm install               # install local npm build / test dependencies
$ bower install             # install local JavaScript dependencies
$ grunt coffee              # build coffee once initially (so tests will work)
$ grunt watch               # watch for source file changes
```

`grunt watch` will watch for changes in the `/lib/` directory and lint, concatenate, and minify the
source files when a change occurs. The output files are written to the `/dist/` directory.

You can run the test suite by navigating to `file:///path/to/firepad-rethinkdb/test/index.html` or via the
command line using `grunt test`.


## Getting Help

Join our slack chat at [Unrestricted Coding](http://uc-slack.herokuapp.com)
