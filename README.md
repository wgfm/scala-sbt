# Scala and sbt Dockerfile

This repository contains **Dockerfile** of [Scala](http://www.scala-lang.org)
and [sbt](http://www.scala-sbt.org).

This fork fixes sbt's version at 0.13.12, because of issues with my CI
environment.


## Base Docker Image ##

* [java:8](https://registry.hub.docker.com/_/java/)


## Installation ##

1. Install [Docker](https://www.docker.com)
2. Pull [automated build](https://hub.docker.com/r/wgfm/scala-sbt/):
```
docker pull wgfm/scala-sbt
```
Alternatively, you can build an image from Dockerfile:
```
docker build -t wgfm/scala-sbt github.com/wgfm/scala-sbt
```


## Usage ##

```
docker run -it --rm wgfm/scala-sbt
```


## Contribution policy ##

Original author: hseeberger

Contributions via GitHub pull requests are gladly accepted from their original
author. Along with any pull requests, please state that the contribution is your
original work and that you license the work to the project under the project's
open source license. Whether or not you state this explicitly, by submitting any
copyrighted material via pull request, email, or other means you agree to
license the material under the project's open source license and warrant that
you have the legal authority to do so.


## License ##

This code is open source software licensed under the
[Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").
