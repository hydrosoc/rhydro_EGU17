[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2554019.svg)](https://doi.org/10.5281/zenodo.2554019)


[Details](#Details) 
/ [Topics](#Topics) 
/ [Slides](#Slides) 
/ [Check](#Checks) 
/ [Resources](#Resources) 
/ [Citation](#Citation)

# Using R in Hydrology - EGU2017 Short Course

**(Co-)Conveners and Instructors**: Berry Boessenkool (C, I), Shaun Harrigan (Co-C), Katie Smith (Co-C), and Daniel Klotz (I) 
**Contact**: Berry Boessenkool, Potsdam University (Germany), <berry-b@gmx.de>

You are invited to post and discuss questions in the 
[Hydrology in R Facebook group](https://www.facebook.com/groups/1130214777123909/).

## Details 
- **Where?**  Monday, 24 April, 15:30–17:00  / Room -2.31  (*basement!*); 
- **Course Description**: http://meetingorganizer.copernicus.org/EGU2017/session/25731

## Topics
This course is directed primarily at hydrologists interested in using R for their research.
You will get (a) an impression of how powerful R is as a tool and (b) all the code to get started yourself.
The following topics are covered:

* Good coding practice, report generation (Rstudio, `rmarkdown`, R notebook)
* Using R as GIS (reading a rainfall shapefile + Kriging, `sf` + `leaflet` + `mapview` + `OSMscale`)
* River discharge time-series visualisation and extreme value statistics (`animation` + `extremeStat`)
* Hydrological modelling with `airGR`
* Trend Analysis in R (`trend` + `hydroTSM`)


## Slides
You can `rightclick - Save as` the 
[html notebook with R output](https://github.com/hydrosoc/rhydro_EGU17/raw/master/presentations/rhydro.nb.html)
and then open the html document in a regular browser.  
For smartphones, you can try the [pdf](https://github.com/hydrosoc/rhydro_EGU17/raw/master/presentations/rhydro.pdf)
(without the interactive graphs).

To get all the material including the datasets and presentation source code, we recommend to
[download the whole github course repository](https://codeload.github.com/hydrosoc/rhydro_EGU18/zip/master).



## Checks
You can check if your laptop is prepared for the course by running the
[checkpc](https://github.com/hydrosoc/rhydro_EGU17/blob/master/checkpc.R) script in your R console:
```R
source("https://raw.githubusercontent.com/hydrosoc/rhydro_EGU17/master/checkpc.R")
```
This will give instructions if packages are missing / outdated.


## Resources
* [R-Resources for Hyrology](http://abouthydrology.blogspot.co.uk/2012/08/r-resources-for-hydrologists.html) - huge list of R-resources about hydrology
* [hdtools](https://ropensci.github.io/hddtools/) - R package to facilitate access to a variety of online open data sources relevant for hydrologists
* [rdwd](https://github.com/brry/rdwd#rdwd) - R package specifically for German meteorological data
* [airGR](https://cran.r-project.org/web/packages/airGR/vignettes/airGR.html) - The description of the airGR package
* [Hydrology in R Facebook group](https://www.facebook.com/groups/1130214777123909/)
* [RegressionInfluence](https://davidpwright.shinyapps.io/LinearRegressionInfluenceExample/) - Shiny App by  David Wright
* [Evapotranspiration](https://cran.r-project.org/package=Evapotranspiration) -  R package that enables the use of 17 well-known ET models in a consistent manner.
* [GDAL intro part 1 (installation & gdalinfo)](https://medium.com/planet-stories/a-gentle-introduction-to-gdal-part-1-a3253eb96082),
  [part 2 (Map Projections & gdalwarp)](https://medium.com/planet-stories/a-gentle-introduction-to-gdal-part-2-map-projections-gdalwarp-e05173bd710a),
  [part 3 (Geodesy & Local Map Projections)](https://medium.com/@robsimmon/a-gentle-introduction-to-gdal-part-3-geodesy-local-map-projections-794c6ff675ca) and
  [part 4 (Working with Satellite Data)](https://medium.com/@robsimmon/a-gentle-introduction-to-gdal-part-4-working-with-satellite-data-d3835b5e2971),

More resources and R installation instructions at

* [github.com/brry/course](https://github.com/brry/course#install)

## Citation

Please refer to this work as:

* Berry Boessenkool, Shaun Harrigan, Katie Smith, & Daniel Klotz. (2017, April). Using R in Hydrology at EGU2017 (Version 1.0.0). Zenodo. http://doi.org/10.5281/zenodo.2554019

```
@misc{rhydro_EGU2017, title={Using R in Hydrology at EGU2017}, DOI={10.5281/zenodo.2554019}, abstractNote={<p>This repository contains all contributions to the <a href="http://meetingorganizer.copernicus.org/EGU2017/session/25731">short course delivered at EGU 2018</a>. Materials to this and other short courses can be found on the <a href="https://github.com/hydrosoc">YHS GitHub repository</a>.</p>}, publisher={Zenodo}, author={Berry Boessenkool and Shaun Harrigan and Katie Smith and Daniel Klotz}, year={2017}, month={Apr}}
```
