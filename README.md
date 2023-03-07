[![SWUbanner](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://supportukrainenow.org/)

# World boundaries in GeoJSON format
This repository contains GeoJSON data for all the countries boundaries including boundaries for states of bigger 
countries (note that this repository is currently filling).
Detalization is good for using this data on scales up to 1:10000000 / gmaps zoom 6-7 (it's the best quality in combination with free-to-use license).
Data is created using [geojson.io](http://geojson.io/) tool.

![Quality example](https://user-images.githubusercontent.com/15987211/179500121-a3dd509b-dc05-43b4-8f2c-40d42b4741da.png)

## Countries (release 1.0)
Contries boundaries besides mainlands include all the geographically separated, but de jure dependent, associated and managed territories. Separated mainland and all the territories mentioned are added in release 2. Countries states are to be added in release 3.
More about countries boundaries release [here](http://www.httphobo.com/all/world-geojson-release-1-0-0/).

## Additional areas (release 2.0)
Besides bigger countries which are to be splitted into states, some smaller are also worth to be splitted into geographical areas.
More about additional area boundaries release [here](http://www.httphobo.com/all/world-geojson-release-2-0-0/).

Countries split into areas are:
* Azerbaijan (2): Mainland/Nakhchivan
* Denmark (3): Mainland/Greenland/Faroe Islands
* Ecuador (2): Mainland/Galápagos Islands
* France (18): Mainland/Corsica/French Guiana/Guadeloupe/Martinique/Mayotte/Réunion/Clipperton Island/French Polynesia/New Caledonia/Saint Barthélemy/Saint Martin/Saint Pierre and Miquelon/Wallis and Futuna/French Southern and Atlantic Lands
* Italy (3): Mainland/Sardinia/Sicily
* Netherlands (7): Mainland/Bonaire/Saba/Sint Eustatius/Aruba/Curaçao/Sin Maarten
* New Zealand (12): Mainland/North Island/South Island/Tokelau/Kermadec Islands/Chatham Islands/Three Kings Islands/Antipodes Islands/Auckland Islands/Bounty Islands/Campbell Island/Snares Islands
* Norway (3): Mainland/Svalbard/Jan Mayen
* Portugal (3): Mainland/Azores/Madeira
* Spain (3): Mailand/Canary Islands/Balearic Islands
* United Kingdom (21): United Kingdom/England/Scotland/Wales/Northern Ireland/Isle of Man/Guernsey/Jersey/Gibraltar/Akrotiri and Dhekelia/Bermuda/Turks and Caicos Islands/British Virgin Islands/Anguilla/Cayman Islands/Montserrat/Pitcairn Islands/Saint Helena, Ascension and Tristan de Cunha/British Indian Ocean Territory/Falkland Islands/South Georgia and the South Sandwich Islands
* USA (17): Mainland (to be split to states in v3)/Palmyra Atoll/Guam/Northern Mariana Islands/Puerto Rico/United States Virgin Islands/American Samoa/Baker Island/Howland Island/Jarvis Island/Johnston Atoll/Kingman Reef/Wake Island/Midway Atoll/Navassa Island/Serranilla Bank/Bajo Nuevo Bank

## Aligned borders (release 3.0 - work in progress)

Most of the countries boundaries were prepared manually, so borders don't perfectly align. 
Here is the progress:
* Countries (10.4% done)
* States (0% done)

Was / Is:

<img width="35%" src="https://user-images.githubusercontent.com/15987211/223083854-86f8ffef-6cf9-4964-a8b5-a55f389fc102.png" /><img width="40%" src="https://user-images.githubusercontent.com/15987211/223084469-1fbb1fc2-4cf5-4064-a251-a65a4eea7401.png" />


## States boundaries (release 4.0 - on pause)
Countries which we are going to provide state boundaries for:
* Australia (ready)
* Argentina (pending: 24)
* Brazil (pending: 26)
* Canada (ready / OSM / low quality)
* China (pending: 33)
* India (pending: 29)
* Indonesia (pending: 34)
* Kazakhstan (pending: 14)
* Mexico (pending: 31)
* Philippines (pending: 18)
* Russia (pending: 83)
* USA (ready, OSM data)

Note that some states boundaries are provided by OSM, however quality of that data is much lower. It's planned
to replace them with handmade ones eventually.

## Install

This library can be installed manually or via Composer or NPM (via GitHub Packages).

Via Composer:
```json
  "require": {
    "georgique/world-geojson": "^2.3.2"
  }
```

Via NPM:
```json
  "dependencies": {
    "@georgique/world-geojson": "^2.3.2",
  }
```
and create .npmrc file in the root of your project with the following content:
```
@georgique:registry=https://npm.pkg.github.com
```

## Reference
* [GitHub Repository](https://github.com/georgique/world-geojson)
* [Composer package](https://packagist.org/packages/georgique/world-geojson)
* [Tool for editing GeoJSON - geojson.io](http://geojson.io/)
* [OpenStreetMap](https://www.openstreetmap.org)

