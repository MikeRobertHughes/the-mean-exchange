[![Stories in Ready](https://badge.waffle.io/austin-pair-programming/the-mean-exchange.png?label=ready&title=Ready)](https://waffle.io/austin-pair-programming/the-mean-exchange)
the-mean-exchange
=================

Where MEANies get JOBSies :)

App that sets up training paths and tests based on MEAN stack (full stack JavaScript) jobs
entered and approved by recruiters and hiring managers.


Getting Started
===============

* `git clone https://github.com/austin-pair-programming/the-mean-exchange.git`
* `cd the-mean-exchange`
* `npm install`
* `bower install`
* `npm install -g gulp`
* `gulp server`
* navigate to http://localhost:8000


Testing
=======

Unit
----

For TDD
`gulp test`

To run the tests once
`gulp test:single`

End-to-end
----------

You must install the selenium server before running end-to-end tests via protractor. 
`./node_modules/.bin/webdriver-manager update`

To run the tests 
`./node_modules/.bin/protractor test/protractor.conf.js`

Note: you must have a development server (`gulp server`) running at the same time for the e2e tests to work.
