# Saiku Chart Plus

Welcome to Saiku Chart Plus Project.

What is Saiku Chart Plus? 

It is an open source project that helps Pentaho BI users to create other types of charts and maps based on Saiku Project, Highcharts and Google Maps.

### Read More

To learn more visit our page http://it4biz.github.com/SaikuChartPlus/


### Installation

* For Pentaho BA Users, please use Pentaho Marketplace
* For Saiku Server Users, please follow the tutorial at section "advanced instalation" in http://it4biz.github.io/SaikuChartPlus/


### Licenses

Before you put this project in your production environment, please visit http://www.highcharts.com/ to learn more about the Highchart project, and https://developers.google.com/maps/terms to learn more about the Google GeoChart project.

Saiku Chart Plus is a free and open source software. The UI, contained in this repository, is available under the terms of the Apache License Version 2. A copy is attached for your convenience.


###Changelog

2.4 Stable version:
* Position legend - https://github.com/it4biz/SaikuChartPlus/issues/4
* Error label description - https://github.com/it4biz/SaikuChartPlus/issues/11
* Add support for multiple measures at geoChart/Map
* Ass support to GeoChart with resolution provinces

2.5 RC4 version:
* Removed dependency of bootstrap

* Removed load.js by Google, this is load at index.html

* Removed Highcharts files because insconsistence with IE, now this is load at index.html

* Changed Button Plus, add togle for table render button

* For installation consider this:
```
        <script type="text/javascript" src="js/saiku/plugins/SaikuChartPlus/plugin.js" defer></script>
```
