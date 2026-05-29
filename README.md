# Range Fan Map Generator

Interactive azimuthal equidistant range-fan mapping tool for quick aircraft, missile, radio, and distance-sector visualization.

## Features

- Pick a range origin by place name.
- Draw one or more range fans from comma-separated distances.
- Set center azimuth and fan width.
- Add labeled points with simple place lookup.
- Export the current view as JPG.
- Export range fan polygons as GeoJSON or KML for GIS software.
- Vector and raster basemap modes.

## GitHub Pages

This repo is ready for GitHub Pages. Use `index.html` as the site entry point.

Recommended Pages setting:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`

## Local Test

From this folder:

```powershell
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

