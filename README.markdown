Introduction
============

RubyOSA is a bridge that connects Ruby to the Apple Event Manager 
infrastructure.
 
It automatically populates the API (classes, methods, constants) according 
to the target application's scriptable definition.

RubyOSA is an alternative to RubyAEOSA, and meant to replace it.

RubyOSA is licensied under a BSD license, see the COPYRIGHT file for more 
information.

More information on the [project home page](http://rubyosa.rubyforge.org).

Requirements
============

* Mac OS X 10.4.X or greater
* ruby 1.8.X or greater
* libxml-ruby 0.3.8 or greater

Get started
===========

	$ ruby extconf.rb
	$ make
	$ sudo make install
	$ sudo make install-extras

`make install` will only install the core of the bridge, while 
`make install-extras` will install some additional tools such as the rdoc-osa
utility.

Support
=======

A tutorial is available online at [http://rubyosa.rubyforge.org/tutorial.html](http://rubyosa.rubyforge.org/tutorial.html).

Sample code is available in the `sample' sub-directory.

The rdoc-osa tool can be used to generate API reference documentation
for the given application. See its --help flag for more information
about how to use it.

Feel free to send feedback to rubyosa-discuss@rubyforge.org.

You can also file bugs, patches and feature requests to [the tracker](http://rubyforge.org/tracker/?group_id=1845.)

When reporting a bug, please set the AEDebugSends and AEDebugReceives 
environment variables to 1 and attach the logs.
