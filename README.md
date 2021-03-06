# Geohashr
[![Version][Version image]][Version]
[![Build][Build image]][Build]
[![Coverage][Coverage image]][Coverage]

Geohash is a latitude/longitude geocoding system. It is a hierarchical
spatial data structure which subdivides space into buckets of grid shape.


### Geohash precision

Here is some information regarding the precision/length of the geohash string:

Precision | Size | Rough Size | Width (tiles) | Height (tiles) | Approx # Tiles
---|---|---|---|---|---|---|---
1 | 5003 km (3109 mi) | Continent | 8 | 4 | 32
2 | 625 km (388 mi) | US State; Small country | 32 | 32 | 1k
3 | 123 km (76 mi) | US County | 256 | 128 | 32k
4 | 19 km (12 mi) | City | 1024 | 1024 | 1.04m
5 | 3.8 km (2 mi) | US Postal Code | 8192 | 4096 | 33.55m
6 | 610 m (2001 ft) | Neighborhood | 32768 | 32768 | 1.074b
7 | 118 m (387 ft) | Street | 262144 | 1310762 | 34.36b
8 | 19 m (62 ft) | House / Office | 1048576 | 1048576 | 1.09t
9 | 3.7 m (12 ft) | Room | 8388608 | 4194304 | 35.18t
10 | 0.6 m (2 ft) | Desk | 33554432 | 33554432 | 1.12quadrillion


### Usefull geohash links

* [Geohash (slides)](http://www.slideshare.net/sandeepbhaskar2/geohash)
* [Geohash in mapping applications (slides)](http://www.slideshare.net/AlexTumanoff/geohash-in-mapping-applications)
* [Geohash intro (blog post)](http://www.bigfastblog.com/geohash-intro)
* [Geohash explorer](http://openlocation.org/geohash/geohash-js/)
* [Another geohash explorer](http://geohash.gofreerange.com/)
* [Geohash Wikipedia page](https://en.wikipedia.org/wiki/Geohash)


#### xkcd comic
<img src="http://wiki.xkcd.com/wgh/images/5/51/Coordinates.png" alt="xkcd" height="200px" style="width: 200px;"/>


### Contributing

If you'd like to contribute, that's awesome. There's a guide to contributing
(both code and general help) over in [CONTRIBUTING.md](CONTRIBUTING.md)


### Development

To see what has changed in recent versions, see the [CHANGELOG.md](CHANGELOG.md).


### License

Copyright 2014 JohnnyT

Licensed under the MIT License

[Version]: https://rubygems.org/gems/geohashr
[Build]: https://travis-ci.org/johnnyt/geohashr
[Coverage]: https://coveralls.io/r/johnnyt/geohashr

[Version image]: https://badge.fury.io/rb/geohashr.png
[Build image]: https://travis-ci.org/johnnyt/geohashr.png
[Coverage image]: https://coveralls.io/repos/johnnyt/geohashr/badge.png?branch=master
