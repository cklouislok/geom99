Brief Description of the Bug
- Failed to load basemap

Steps to Reproduce the Bug
1. Open the website

Expected Result
- Display a map of tromso using the navigation basemap layer
- Display a place category selector
- Display places of a chosen category when a place type is the place category selector is chosen

Actual Result
- Basemap not loaded
- Zoom in and Zoom out buttons present
- Place category selector displayed at top-right corner
- Places not loaded when a place category is selected

Environment
- Browswers: Chrome, Edge; Safari
- Device: Desktop; iPhone
- OS: Windows 11; iOS 17

Scope
- All students trying to use ArcGIS Maps SDK for JavaScript

Browser Concole Errors
- GET https://basemapstyles-api.arcgis.com/arcgis/rest/services/styles/v2/webmaps/arcgis/navigation?language=en&token=AAPKe129fa0d558e45bd933c2d9bc247516bna1Wdg3j6A1WflwncTUNCVPlG_sS4aoCBu57yXVTmXVoC0rRm
- [esri.Basemap] #load() Failed to load basemap (title: 'Basemap', id: '18d7bab5ef5-basemap-0') f {name: 'request:server', details: {…}, message: 'Token Invalid.'}

![FindPlaces_Errors](https://github.com/cklouislok/geom99lab2/assets/146376082/bedc91e0-7b70-45b7-a296-59ce609f7dd9)
