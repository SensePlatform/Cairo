# Sense Cairo

This is modified version of 
[the R Cairo package](http://www.rforge.net/Cairo) version 1.5-3 by 
Urbanek and Horner. It is intended for use on
[Sense](https://www.senseplatform.com) with the 
[R engine](https://github.com/SensePlatform/sense-r-engine) and is
preinstalled on Sense. You might want to install it locally to develop
or modify the engine.

## Installation and usage

Install using

```R CMD INSTALL Cairo```

Usage is similar to the stock Cairo package, but two additional
functions useful to Sense are exported:

* `SensePNG` is the default graphics device used by R on Sense.
* `SenseDeviceChanges` returns the image data for all SensePNG devices
  that have changed since the last call.

## Support

* Email: support@senseplatform.com
* Google Group: https://groups.google.com/forum/?fromgroups#!forum/sense-users
* IRC: `#senseplatform` on `irc.freenode.net`