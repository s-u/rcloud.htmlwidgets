## 1.1.2
* respect widget's sizing policy when generating an iframe

## 1.1.1
* merges user library support from 1.0.8

## 1.1.0
* more efficient embedding in RCloud cells
* support for displaying without iframe

## 1.0.8
* detect user library paths and produce corresponding `shared.R` URLs

## 1.0.7
* call resolveDependencies in order to remove redundant dependencies. (DT was broken because of multiple jQuery)

## 1.0.6
* support htmltools package+relative path dependencies

## 1.0.5
* hack to support R 3.5.4 which stopped us from overriding methods in htmlwidgets & htmltools

## 1.0.4
* do not attempt to expand NULL files in dependencies (these usually have hrefs instead). (#22 / #23)

## 1.0.3
* do not resize widgets until they are displayed (#18)

## 1.0.2
* look in `lib/` as well as `www/` of package dependencies, for plotly 4.6 etc.
* also print htmltools-tagged stuff (`shiny.tag`) in same way as htmlwidgets, for compatibility with
  metricsgraphics `mjs_grid` etc.

## 1.0.1
* fix automatic resizing of widgets in mini.html
* fix [mini.html example](https://gist.github.com/gordonwoodhull/fc9220160fb8819edb1c6e972d874305)

## 1.0
Initial release
