# Breeze Viz has moved back into the main Breeze Repo

https://github.com/scalanlp/breeze



breeze-viz
=============

Visualization library backed by Breeze and JFreeChart.

See https://github.com/scalanlp/breeze/wiki/Quickstart for documentation.

Installation
------------
- clone the repository: `git clone git@github.com:scalanlp/breeze-viz.git`
- run sbt: `$ sbt`
- publish locally: `sbt> publish-local`

Add `breeze-viz` dependency to your project:
```scala
libraryDependencies  ++= Seq(
  // other dependencies here
  "org.scalanlp" %% "breeze" % "0.10",
  // native libraries are not included by default. add this if you want them (as of 0.7)
  // native libraries greatly improve performance, but increase jar sizes.
  "org.scalanlp" %% "breeze-natives" % "0.10",
  "org.scalanlp" %% "breeze-viz" % "0.10"
)
```

Release and maintenance
-----------------------

The current release is 0.5.1

The current release under development is 0.8-Snapshot.

breeze-viz is primarily maintained by @MartinSenne from 2013-10-14 on.

Planned features ( for 0.6 )
----------------------------

* Support for LaTex (axis) labels.

Request for ideas and future features
-------------------------------------

Please do **not hesitate** to 

* edit the Wiki page ( https://github.com/scalanlp/breeze-viz/wiki ) or
* create an issue 

in order to let us now **your** features wishes, requirements, ideas.
