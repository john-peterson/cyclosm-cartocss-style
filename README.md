CyclOSM expedition version  . find food trails towers for exploring planet
=======

discuss contribute and find hosting in this issue 

https://github.com/osm-fr/infrastructure/issues/

this map show

food amenities and name of shop . that sell larder pantry off shelf . even small kiosk can provide food for a week in no mans land

small trails away from motor vehicles and houses

cell towers with operator name if avalanche in data base 

# cell tower operators 

I would like to see operator in the label  either from name or new operator tag but tower operators are mostly missing  . I added a few in Finland from cell mapper but it was so tedious on my phone I gave up 

the ones I found lacked either DNA or Telia but Elisa was always present so I used that and hoped all towers would reach me

in Australia I'm almost never online and need auto recharge that works with Optus . I also have only one Sim slot and haven't tried Telstra . occasionally I have suffered from no signal where Telstra has a signal . frustrating 

---

CyclOSM is a [CartoCSS](https://carto.com/developers/styling/cartocss/) map style
designed with cycling in mind. It leverages
[OpenStreetMap](https://www.openstreetmap.org/) data to create a beautiful and
practical cycling map!

[![Build Status](https://api.travis-ci.org/cyclosm/cyclosm-cartocss-style.svg?branch=master)](https://travis-ci.org/cyclosm/cyclosm-cartocss-style)

[![CyclOSM](https://www.cyclosm.org/images/social_media.png)](https://www.cyclosm.org/)


## Demonstration

A demonstration of this style is available at [https://cyclosm.org](https://cyclosm.org).

The tile server url is
`https://{s}.tile-cyclosm.openstreetmap.fr/cyclosm/{z}/{x}/{y}.png`. Tiles can
be reused under the general OpenStreetMap [tile usage
policy](https://operations.osmfoundation.org/policies/tiles/).

The map is available by default in the following smartphone applications:
- [OSMAnd](https://osmand.net/)
- [OpenMultiMaps](https://framagit.org/tom79/openmaps)
- [All-In-One Offline Maps](https://www.offline-maps.net) and [AlpineQuest Rando GPS](https://alpinequest.net)

The tile server is provided by
[OpenStreetMap-France](https://www.openstreetmap.fr), many thanks to them for
the support!

## Philosophy

CyclOSM is a new cycle-oriented render. Contrary to
[OpenCycleMap](http://opencyclemap.org/), this render is free and open-source
software and aims at being more complete to take into account a wider
diversity of cycling habits.

In urban areas, it renders the main different types of cycle tracks and lanes,
on each side of the road, for helping you draw your bike to work route. It also
features essential POIs as well as bicycle parking spots or spots shared with
motorbikes, specific infrastructure (elevators / ramps), road speeds or
surfaces to avoid streets with pavings, bumpers and bike boxes, etc.

The same render also lets you visualize main bicycle touring routes as well as
essential POIs when touring (emergency services, shelters, tourism, shops).


## Features

Render:

* Cycleways track, lanes, cycle-bus lanes
* Motor oneway - two way for bicycle
* Cycle routes (local, regional, national, international)
* Parking for bicycle (or motorcycle parking open to bicycle)
* Steps with bicycle friendly ramp
* Bicycle shop and repair stations
* First aid amenities : shelter, hospital, pharmacy, police station, water, food store
* Travel amenities : camping, hotel, train station, museum, picnic table, peaks...
* Emphasis on low speed roads (<= 30km/h)
* Elevation curves and shading
* Smoothness of the roads
* Traffic calming
* …

A full list of rendered features is available in [the
legend](https://www.cyclosm.org/legend.html).

A list of the tags considered by this render is available in [Taginfo JSON
format](https://wiki.openstreetmap.org/wiki/Taginfo/Projects) in [`taginfo.json`](taginfo.json).

Some extra information about the way OSM tags are rendered is available in
[the wiki](https://github.com/cyclosm/cyclosm-cartocss-style/wiki/Tag-to-Render).


## Getting started

Getting started instructions are available in the [`docs/INSTALL.md`](docs/INSTALL.md) file.


## Printing

Instructions for printing maps with a CyclOSM render are available in
the [`docs/PRINT.md`](docs/PRINT.md) file.


## Contributing

Some getting started information for contributing is available in
[`CONTRIBUTING.md`](CONTRIBUTING.md) file.


## Changelog

Changes to this theme are listed in the [`CHANGELOG.md`](CHANGELOG.md) file.
Versions are tagged with Git tags and are available through Github releases
feature.


## MapCSS validators

We also offer some MapCSS checkers for bicycle tags which can be used with
[JOSM](https://josm.openstreetmap.de/wiki/Help/Preferences/Validator) for
instance in the [`validator`](validator) folder of this repository.


## Licenses

See [`LICENSE.md`](LICENSE.md) file.

## Links

* http://www.cyclosm.org, official website.
* http://www.cyclosm.org/legend.html, full detailed key.
* https://wiki.openstreetmap.org/wiki/CyclOSM, wiki page on the OSM wiki.
* A list of the tags considered by CyclOSM is available in [Taginfo JSON format](https://wiki.openstreetmap.org/wiki/Taginfo/Projects) in [`taginfo.json`](https://github.com/cyclosm/cyclosm-cartocss-style/blob/master/taginfo.json).


## Related projects

* An unofficial Docker image to deploy a CyclOSM tile server is available at https://github.com/mhajder/openstreetmap-tile-server-cyclosm.
* A gravel-oriented fork from CxBerlin is available at https://github.com/cxberlin/gravel-cartocss-style
* An high quality (especially DEM) tile server for Belgium is available from
    Champs-Libres, see https://www.champs-libres.coop/blog/post/2020-09-17-cyclosm/.
