# leafgl 0.2.2 (2024-11-13)

#### 🐛 bug fixes

  * src version now works also in shiny. #71

#### 💬 documentation etc

  * we now have pckgdown site - Thanks to @olivroy #102

#### 🍬 miscellaneous

  * remove obsolete .travis.yml

## leafgl 0.2.1

new features:

  * all methods can now have labels/tooltips. Currently only lines and polygons support passing of a column name, points need a predefined label vector.

miscallaneous:

  * all methods now have a pane argument to control layer ordering (thanks to @trafficonese). #67 #64

## leafgl 0.2.0

miscallaneous:

  * update upstream javascript dependency to 3.2.0

## leafgl 0.1.2

new features:

  * expose additional JavaScript arguments in addGlPoints via magic dots. #54 & #60

## leafgl 0.1.1

initial release.
