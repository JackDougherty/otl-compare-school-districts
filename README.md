# otl-compare-school-districts
Compare any US school district boundaries and data, side-by-side in the same scale map, using this MapBox JS tool with zoom sync. Map data layers by EdBuild.org.

## Link

http://jackdougherty.github.io/otl-compare-school-districts/index-frame.html

## embed shortcode
[iframe src='http://jackdougherty.github.io/otl-compare-school-districts' width="100%" height=500]

## Background
- Expands on 2015 EdBuild US school district map (http://maps.edbuild.org/DividingLines.html)
- Replaces 2012 Google Maps v3 School District Comparison Viewer created with UConn MAGIC (http://magic.lib.uconn.edu/otl/dualzoom_schooldistricts.html)

## Requires
- MapBox access token (free use up to a limited number of views per month)

## Credits
- Thanks to Sara Hodges and others at http://EdBuild.org for creating the US school districts map and poverty data layers, making them publicly available on MapBox, and encouraging collaboration.
- Thanks to Dan Swick at MapBox for great advice on the geocoder input values.

## To Do
- Add basemap layer that displays more place names; see MapBox options that appear in http://geojson.io/#map=10/42.9549/-75.6161
- Ask MAGIC to support Google Analytics and remove my GA code from index.html
- Ask MAGIC for code advice that will enable tool to accept a URL string that includes specific latlng coords and zoom levels for map1 and map2, similar to: http://magic.lib.uconn.edu/otl/dualcontrol_aerialchange.html
- If above is not feasible, then code a second HTML/JS version to display Hartford vs Morrisville NY (with default Hartford-Charlotte)
