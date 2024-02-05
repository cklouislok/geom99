Brief Description of the Bug
- Failed to load basemap

Steps to Reproduce the Bug
1. Open the website

Expected Result
- Display a map of the Santa Monica Mountains in California using the topographic basemap layer

Actual Result
- Basemap not loaded
- Zoom in and Zoom out buttons present

Environment
- Browswers: Chrome, Edge; Safari
- Device: Desktop; iPhone
- OS: Windows 11; iOS 17

Scope
- All students trying to use ArcGIS Maps SDK for JavaScript

Browser Concole Errors
- GET https://basemapstyles-api.arcgis.com/arcgis/rest/services/styles/v2/webmaps/arcgis/topographic?language=en&token=AAPKe129fa0d558e45bd933c2d9bc247516bna1Wdg3j6A1WflwncTUNCVPlG_sS4aoCBu57yXVTmXVoC0rRmDSlnhHS_Af_Knbb 401 (Unauthorized)
- [esri.Basemap] #load() Failed to load basemap (title: 'Basemap', id: '18d7ba36dc4-basemap-0') f {name: 'request:server', details: {…}, message: 'Token Invalid.'}

![DisplayAMap2D_Errors](https://github.com/cklouislok/geom99lab2/assets/146376082/984a4ae8-d9e9-4b0b-9d63-9491d2fac503)
