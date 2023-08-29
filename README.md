# Leaflet.SmoothWheelZoom

Smooth wheel zoom for leaflet.

This plugin provide smooth zoom UX like Google map.

[Demo](https://dcode-evo.github.io/Leaflet.SmoothWheelZoom/)

### Usage

```
var map = L.map('map', {
  scrollWheelZoom: false, // disable original zoom function
  smoothWheelZoom: true,  // enable smooth zoom 
  smoothSensitivity: 1,   // zoom speed. default is 1
  zoomSnap: 0,            // disable zoom snapping (for touchscreen zooming, and fitBounds(), etc.)
});
```

![demo](./demo_gif/demo.gif "demo")
