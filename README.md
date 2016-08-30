# osgi-xstream

An OSGI repository for the popular XStream library from http://x-stream.github.io/

This repository provides an OSGI plugin repository for the XStream
library.  The source code has not been modified in any way. The
repository is merely a convenient packaging format for both binary and
related source material for developers.

## Install

The most recent version of the library included in the repository is
for XStream **1.4.8** and can be installed using Eclipse's plugin
manager.

Add the following URL to the list of available software sites in
eclipse.

```
https://raw.githubusercontent.com/wiki/markroyer/osgi-xstream/com.thoughtworks.xstream.repository/updates
```

## Building

The project can be built most easily using maven from the
`com.thoughtworks.xstream.parent` directory. Typing

```bash
mvn clean verify
```

will compile the project and create a repository containing all of the
related libraries in

```bash
../../osgi-xstream.wiki/
```

## LICENSE

The license is BSD style.  See the included LICENSE file for details.

## Thanks

The ant build scripts are based on code from:

[http://www.lorenzobettini.it/2015/01/creating-p2-composite-repositories-during-the-build/](http://www.lorenzobettini.it/2015/01/creating-p2-composite-repositories-during-the-build/)

<!--  LocalWords:  osgi xstream XStream mvn
 -->
