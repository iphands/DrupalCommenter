Drupal Commenter
================

An API that lets you comment on Drupal nodes via ajax from a non Drupal page.
AFAIK this only works on Drupal7 and I have really only tested it on one Drupal site (patches welcome).

You must have an AMD module loader like [require.js](http://requirejs.org/) to use this and have jquery setup as a module.

##Usage
~~~
require(['drupal_commenter'], function (drupal_commenter) {
    drupal_commenter.add_comment('Hey Newby here is some super awesome comment.', { node_url: '/node/1234});
});
~~~

##License
Copyright (c) 2013 Ian Page Hands. Licensed under the GPLv2 license.