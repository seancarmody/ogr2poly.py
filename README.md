ogr2poly.py
===========

Original forked fr0m https://gist.github.com/joshdoe/1434632

Later version found in svn at http://trac.openstreetmap.org/browser/applications/utils/osm-extract/polygons/ogr2poly.py


Files just being stored here as we don't use svn

Author is https://gist.github.com/joshdoe/1434632

-----

Converts any of the GDAL OGR Vector Formats to an OSM Poly File.
See http://www.gdal.org/ogr/ogr_formats.html

-----

```
Usage: ogr2poly.py [options] src_datasource [layer]

options:
-p --prefix  Text to Prepend to Output Poly File Name
-b --buffer-distance Set buffer distance in meters (default: 0).
-s --simplify-distance Set simplify tolerance in meters (default: 0).
-f --field-name Field name to use to name files. (Field name in source file I presume)
-v --verbose true/false Print detailed status messages.

[layer] layer=0 layer number in datasource to use (default=0)

```

------

