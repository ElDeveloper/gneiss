# gneiss changelog

## Version 0.3.2
* Added `balance_boxplot` and `balance_barplot` to make interpretation balance partitions easier.
* Added `assign_ids` command to allow for ids to be added manually.

## Version 0.3.0
* Added q2 support for linear regression and linear mixed effects models [#98](https://github.com/biocore/gneiss/pull/98)
* Added q2 support hierarchical clustering [#116](https://github.com/biocore/gneiss/pull/116)
* Added interactive heatmaps with highlights with matplotlib [#114](https://github.com/biocore/gneiss/pull/114)
* Added tree visualizations for unrooted trees with bokeh [#112](https://github.com/biocore/gneiss/pull/112)
* Added support of cross validation for ordinary least squares [#101](https://github.com/biocore/gneiss/pull/101)


## Version 0.2.1
* Added heatmap dendrogram plotting functionality [#87](https://github.com/biocore/gneiss/issues/87)
* Added principal balance analysis heuristic using proportionality and wards clustering algorithm [#83](https://github.com/biocore/gneiss/issues/83)

## Version 0.2.0

### Features
* Added filehandle support for write and read io in RegressionResults object [#77](https://github.com/biocore/gneiss/issues/77)


## Version 0.1.3

### Features
* Added write and read io for RegressionResults object [#72](https://github.com/biocore/gneiss/issues/72)

## Version 0.1.2

### Features
* Added `ladderize` and `gradient_sort` [#29](https://github.com/biocore/gneiss/issues/29)

### Bug fixes


## Version 0.0.2

### Features
* Added statsmodels inference [#22](https://github.com/biocore/gneiss/pull/22)
* Added support for ordinary least squares regression [#33](https://github.com/biocore/gneiss/pull/33)
* Added support for linear mixed effects models [#38](https://github.com/biocore/gneiss/pull/38)
* Added RegressionResults object to summarize statistics from statistical analyses
* Adding in a niche sorting algorithm `gneiss.sort.niche_sort` that can generate a band table given a gradient [#16](https://github.com/biocore/gneiss/pull/16)
* Adding in utility functions for handing feature tables, metadata, and trees. [#12](https://github.com/biocore/gneiss/pull/12)
* Adding GPL license.

### Bug fixes
