# WVU Pattern Library - Masthead Logo Module

[![Build Status](https://travis-ci.org/wvu-patterns/wvu-patterns-masthead-logo.svg?branch=master)](https://travis-ci.org/wvu-patterns/wvu-patterns-masthead-logo)

Use [Bower](http://bower.io/) to install this module.

```bash
$ bower install --save wvu-patterns-masthead-logo
```

### Overrideable defaults
```scss
$wvu-masthead-small-breakpoint: 'min-width: 38em' !default;

$wvu-masthead-logo-png-url: '//static.wvu.edu/global/images/logos/wvu/masthead/wvu-logo__300x44--1.0.0.png' !default;
$wvu-masthead-logo-svg-url: '//static.wvu.edu/global/images/logos/wvu/masthead/wvu-logo--1.0.0.svg' !default;
```


###Pattern Development

Requires:

* Ruby 1.9.3-p484
* NodeJS
* Gulp

*RVM is Preferred* but not required

####Installation

* `cd {install-dir}/wvu-patterns-footer-links`
* `gem install bundler`
* `bundle install`
* `npm install`

####Pattern Testing

* `gulp test` will create a build directory so you can view pattern
* `gulp ci` will run lint test to make sure .scss file is valid