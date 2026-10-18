# NetPulse — 3D Network Monitoring Dashboard

An interactive network monitoring dashboard built with [Three.js](https://threejs.org/), all in a single HTML file.

- **3D topology:** Internet, Server, Database, Desktop, Laptop and Mobile nodes on a grid, with animated data packets travelling between them.
- **Traffic classification:** packets are color-coded green (normal), orange (suspicious) or red (malicious). The simulation includes periodic port-scan bursts.
- **Live statistics:** total packets, packets per second, throughput, a breakdown by class and a stacked bar chart of the last 30 seconds.
- **Live log:** search by IP, node, protocol or threat, and filter by class.
- **Node details:** click any node to see its IP, MAC, uptime, traffic and threat counts.
- **Pause / resume** button (or press <kbd>Space</kbd>).

> All devices, addresses and traffic are randomly generated in the browser for demo purposes. Nothing is captured from a real network.

## Run locally

Open `index.html` in a modern browser. No build step is needed, and Three.js loads from the jsDelivr CDN.

## Deploy

`render.yaml` deploys the repo as a Render static site.
