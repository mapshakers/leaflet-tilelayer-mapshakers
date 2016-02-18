leaflet-tilelayer-mapshakers
==============================

Mapshakers map tiles for [Leaflet](http://leafletjs.com).

*Requires Leaflet 0.7.0 or newer*

## Demo
[Check out demo!](http://mapshakers.com/leaflet-tilelayer-mapshakers/example/)
## Using the plugin

## Available styles
 * default
 * retro
 * greyDark
 * greyBright
 * greyBright2
 * tourist
 * relief
 * blueprint

### Usage
Create a new L.tilelayer.mapshakers

```javascript
var mapkeyTiles = L.tileLayer.mapshakers({
    style: 'retro',
    key: 'your-API-key'
});
mapkeyTiles.addTo(map)
```

### License

**leaflet-tilelayer** is free software, and may be redistributed under the MIT-LICENSE.
