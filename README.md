![status](https://img.shields.io/badge/Status-WIP-red.svg)
[![Visit Facebook Group](https://img.shields.io/badge/Facebook-Visit%20Community-blue.svg)](https://www.facebook.com/groups/204308966622383)

# THIS PROJECT IS STALE, FOR MORE INFORMATION PLEASE VISIT THIS PAGE: [http://unrestrictedcoding.com/projects/](http://unrestrictedcoding.com/projects/)

# Firepad-RethinkDB

Firepad-RethinkDB is an open-source, collaborative code and text editor. It is
designed to be embedded inside larger web applications.

## Forked from [Firepad](https://firepad.io)
This repo is a fork from Firepad which was origianlly built to be used with Firebase. I started to use it, and really didn't like the Firebase back end for security and robustness reasons. So I am rewritting this to work with RethinkDB instead. Which is a server-side realtime database.

## ToDo

If you are thinking about contributing to this project, then this is the place you will want to start. The following items are what needs to be done.

1. Choose Documentation Library (Yui, Doxx, Mr. Doc???)
2. Document Source (The current code isn't fully document, and can be dense. Need to go through and document extensively everything)
3. Rename Project (RethinkPad???)
4. Create UML Diagrams for current code
5. Create UML Diagrams for planned code (Client & Server)
6. Create RethinkDB adapter (socketio)
7. Remove Firebase Adapter
8. REmove Firebase References and refactor code to new project name
9. Setup Server
10. Build Tests for new code
11. Profit

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

[![Visit Facebook Group](https://img.shields.io/badge/Facebook-Visit%20Community-blue.svg)](https://www.facebook.com/groups/204308966622383)

Visit site at [Unrestricted Coding](http://unrestrictedcoding.com/)
