![status](https://img.shields.io/badge/Status-WIP-red.svg)
[![Slack Status](https://uc-slack.herokuapp.com/badge.svg)](https://uc-slack.herokuapp.com)

# Firepad-RethinkDB

Firepad-RethinkDB is an open-source, collaborative code and text editor. It is
designed to be embedded inside larger web applications.

## Forked from [Firepad](https://firepad.io)
This repo is a fork from Firepad which was origianlly built to be used with Firebase. I started to use it, and really didn't like the Firebase back end for security and robustness reasons. So I am rewritting this to work with RethinkDB instead. Which is a server-side realtime database.

## ToDo

If you are thinking about contributing to this project, then this is the place you will want to start. The following items are what needs to be done.

1. Document Source (The current code isn't fully document, and can be dense. Need to go through and document extensively everything)
2. Rename Project (RethinkPad???)
3. Create UML Diagrams for current code
4. Create UML Diagrams for planned code (Client & Server)
5. Create RethinkDB adapter (socketio)
6. Remove Firebase Adapter
7. REmove Firebase References and refactor code to new project name
8. Setup Server
9. Build Tests for new code
10. Profit

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

Join our slack chat at [Unrestricted Coding Slack](http://uc-slack.herokuapp.com)

Visit site at [Unrestricted Coding](http://unrestrictedcoding.com/)
