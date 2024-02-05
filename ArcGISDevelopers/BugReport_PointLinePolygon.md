Brief Description of the Bug
- Failed to load basemap

Steps to Reproduce the Bug
1. Open the website

Expected Result
- Display a map of the Santa Monica Mountains in California using the topographic basemap layer
- Display point, line, and polygon features as graphics
- Display a pop-up when polygon feature is clicked

Actual Result
- Basemap not loaded
- Zoom in and Zoom out buttons present
- Point, line, and polygon features are displayed
- Pop-up displayed when polygon feature is clicked
- Zoomo level is not correct

Environment
- Browswers: Chrome, Edge; Safari
- Device: Desktop; iPhone
- OS: Windows 11; iOS 17

Scope
- All students trying to use ArcGIS Maps SDK for JavaScript

Browser Concole Errors
- GET https://basemapstyles-api.arcgis.com/arcgis/rest/services/styles/v2/webmaps/arcgis/topographic?language=en&token=AAPKe129fa0d558e45bd933c2d9bc247516bna1Wdg3j6A1WflwncTUNCVPlG_sS4aoCBu57yXVTmXVoC0rRmDSlnhHS_Af_Knbb 401 (Unauthorized)
- [esri.Basemap] #load() Failed to load basemap (title: 'Basemap', id: '18d7bab5ef5-basemap-0') f {name: 'request:server', details: {…}, message: 'Token Invalid.'}
![FindPlaces_Errors](https://github.com/cklouislok/geom99lab2/assets/146376082/52da9fb1-2152-40ee-b96c-2d00920980df)
