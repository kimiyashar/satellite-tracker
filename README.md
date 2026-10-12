# Satellite Tracker

An interactive browser-based 3D globe showing roughly 12,000 satellites at their propagated positions and identifying which satellites are currently above the viewer's horizon.

## Features

- Real-time satellite positions from bundled CelesTrak orbital data
- Browser geolocation for the local overhead list
- Color-coded satellite owners and operators
- Hover labels and click-to-focus globe interactions
- A comparison page for satellite operators, hardware, scale, and engineering metrics

## Technology

This is a static HTML/CSS/JavaScript project built with [Globe.GL](https://globe.gl/), [Three.js](https://threejs.org/), and [satellite.js](https://github.com/shashwatak/satellite-js). It does not require a backend.

Open `index.html` through a local static-file server or deploy the repository to a static host.
