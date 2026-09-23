# tiny-planet

A cartoony, comic-book style 3D planet built with [Three.js](https://threejs.org/), in a single `index.html` with no build step.

It has cel-shaded terrain with ink outlines, oceans, snowy mountains, forests, cities with lit windows, highways and bridges, plus cars, buses, planes towing banners, hot-air balloons and drifting clouds.

## Run

Open `index.html` in a modern browser. Three.js loads from the jsDelivr CDN through an import map, so you need to be online. If your browser blocks ES modules on `file://`, serve the folder instead:

```sh
python3 -m http.server 8000   # then open http://localhost:8000
```

## Controls

- **Drag** to orbit, **scroll/pinch** to zoom, **right-drag** to pan
- **Double-click** anything to fly in close
- **Auto-spin** toggles slow rotation, **Reset view** flies back out
