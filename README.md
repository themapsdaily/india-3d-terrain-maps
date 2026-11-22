# QGIS 3D State Maps

Interactive 3D terrain maps of Indian states that run in a web browser, made in QGIS with the Qgis2threejs plugin. This is an early experiment from 2022 that came before our newer 3D relief maps.

## What is inside

| Folder | What it is |
|---|---|
| `himachal-pradesh/` | A 3D map of Himachal Pradesh. Open `index.html` in a browser. |
| `goa/` | A 3D map of Goa. Open `goa.html` in a browser. |

## How to view a map

1. Download or clone this repository.
2. Open the HTML file for the state you want in a modern browser.

If the map stays blank, start a small local web server first (`python3 -m http.server`) and open the page from `http://localhost:8000`. Some browsers block local files from loading their own data.

## See also

Our newer renders live in [themapsdaily-relief-maps](https://github.com/themapsdaily/themapsdaily-relief-maps), which makes shaded-relief maps of Indian states in R.

## Licence

The code in this repository is released under the MIT licence (see `LICENSE`). It includes [Qgis2threejs](https://github.com/minorua/Qgis2threejs) by Minoru Akagi and [three.js](https://threejs.org), both of which are also MIT licensed.

The source of the terrain data used for each map was not recorded when these maps were made. Check the original data provider's terms before reusing the data files.

## History

This repository combines two older repositories: himachal-pradesh and goa-3d. Their full commit history is kept.
