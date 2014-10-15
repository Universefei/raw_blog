GIS
===

这个文件夹讲解我在实验室涉及到的GIS相关的技术知识，因为实验室会涉及到保密内容，所以这里只记录遇到的开源技术，不涉及到机密内容

##主要内容
* 数据存储
* 数据访问(引擎)
* 数据处理

## 1.数据存储
数据存储负责存储空间矢量数据，这部分包含两个方面，一是存储介质的介绍，二是相关数据介质格式之间的转换

介质大致可分为两种：数据库 和 文件：

1. 数据库PostGIS + PostgreSQL
2. 数据库Oracle spatial
3. shapefile
4. geojson
5. kml
6. gml
7. osm

数据格式之间的转换可以使用GDAL/OGR这个强大的库

1. shp2pgsql
2. osm2pgsql
3. ogr2ogr
4. ogrinfo
5. pgShapeLoader


## 2.数据访问
数据访问负责从介质中读取空间数据，组织成上层应用逻辑需要的内存数据结构。数据访问用到的技术包括以下：

1. GDAL
2. Terralib
3. libpq
4. odbc
5. libxml2
6. json-c

## 3.数据处理

1. QGIS










