[![Build Status](https://travis-ci.com/autimio/docker-images-gis.svg?branch=master)](https://travis-ci.com/autimio/docker-images-gis) 

## Docker image for SGS Web application with GIS and image processing

Automated build for docker image used by SGS for Web applicatons that requires GIS and image processing.

## Image: autimio/web-gis-imageprocessing-gdal-grass (Dockerfile.gdal)
This image is based on tomcat:8.5 and contains:
 - GDAL
 - GRASS7
 - Git, maven , curl, cmake, python and some other tools required to build applications above
 
 #### DockerHub

`docker pull autimio/web-gis-imageprocessing-gdal-grass`

https://cloud.docker.com/repository/docker/autimio/web-gis-imageprocessing-gdal-grass

## Image: autimio/web-gis-imageprocessing-gdal-grass-postgis (Dockerfile.gdal_postgis)
This image is based on autimio/tomcat-gdal-grass:latest and contains:
 - GDAL
 - GRASS7
 - PostgreSQL
 - PostGIS
 - Git, maven , curl, cmake, python and some other tools required to build applications above
 
 #### DockerHub

`docker pull autimio/web-gis-imageprocessing-gdal-grass-postgis`

https://cloud.docker.com/repository/docker/autimio/web-gis-imageprocessing-gdal-grass-postgis

## Image: autimio/web-gis-imageprocessing-gdal-grass-postgis-r (Dockerfile.gdal_postgis_r)
This image is based on autimio/tomcat-gdal-grass-postgis:latest and contains:
 - GDAL
 - GRASS7
 - R (with some GIS related packages)
 - PostgreSQL
 - PostGIS
 - Git, maven , curl, cmake, python and some other tools required to build applications above
 
 #### DockerHub

`docker pull autimio/web-gis-imageprocessing-gdal-grass-postgis-r`

https://cloud.docker.com/repository/docker/autimio/web-gis-imageprocessing-gdal-grass-postgis-r

Tags are defined by commit hash and latest is always up-to-date with master branch. Check DockerHub repository to all tags available.

## License
Feel free to use, extend and submit a pull request.
