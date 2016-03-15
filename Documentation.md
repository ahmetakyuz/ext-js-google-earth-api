## Installation ##

  1. Download and unzip Ext.ux.GEarthPanel-1.1.1.zip: http://code.google.com/p/ext-js-google-earth-api/downloads/list
  1. Click on example.html


---


## Functions ##

### fetchKml(kmlURL) ###
Load and display a KML file.

```
earthPanel.fetchKml('http://earthatlas.info/kml/statistics/infant_mortality_rate_2005_prism.kmz');
```

### findLocation(location) ###
Find/fly to location.

```
earthPanel.findLocation('Oslo');
```

### getEarth() ###
Returns Google Earth instance.

```
var earthInstance = earthPanel.getEarth();
```

### getLayersPanel() ###
Returns FormPanel with checkboxes for each Google Earth layer.

```
var layersPanel = earthPanel.getLayersPanel();
```

### getLocationPanel() ###
Returns FormPanel for location search/fly to.

```
var locationPanel = earthPanel.getLocationPanel();
```

### getOptionsPanel() ###
Returns FormPanel with checkboxes for each Google Earth option.

```
var optionsPanel = earthPanel.getOptionsPanel();
```

### setLayers(layersObj) ###
Set Google Earth layers.

### setOptions(optionsObj) ###
Set Google Earth options.


---


## Events ##

### earthLoaded ###

Fired when Google Earth panel and instance are ready.

```
earthPanel.on('earthLoaded', function(){
  ...
});
```