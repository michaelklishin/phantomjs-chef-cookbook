# PhantomJS Chef Cookbook

This is an OpsCode Chef cookbook for [PhantomJS](http://phantomjs.org).

It uses [PhantomJS binaries](http://phantomjs.org/download.html) to provision PhantomJS.


## Phantom Version

This cookbook provides PhantomJS `1.8.1`+.


## Recipes

Main recipe is `phantomjs::tarball`.


## Attributes

 * `node[:phantomjs][:version]` (default: `1.8.1`): version to provision


## Supported OSes

Recent Ubuntu releases (actively tested with Ubuntu 12.04).


## Supported architectures

Currently this cookbook supports 32 and 64 bit systems.


## Dependencies

None.


## Copyright & License

Michael S. Klishin, Travis CI Development Team, 2012-2013.

Released under the [Apache Public License 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/michaelklishin/phantomjs-chef-cookbook/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

