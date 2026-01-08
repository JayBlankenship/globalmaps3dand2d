# MapLibre Globe App

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A simple web application demonstrating the use of MapLibre GL JS, an open-source alternative to Mapbox GL JS, to display an interactive map with toggleable 2D and 3D globe views using OpenStreetMap tiles.

## Features

- **Toggleable Views**: Switch between a 2D flat map and a 3D spherical globe view.
- **Globe Projection**: Displays the map in a 3D globe view, allowing rotation and exploration.
- **OpenStreetMap Tiles**: Uses free, open-source OpenStreetMap raster tiles for both 2D and globe views, with globe projection for 3D rendering.
- **Zero Licensing Lock-in**: Fully open-source, with the same API as Mapbox GL JS.
- **Interactive Controls**: Includes navigation controls for zooming, panning, and rotating the map/globe.

## Installation

Clone or download this repository. No dependencies are required for basic usage—the app loads MapLibre GL JS via CDN.

For local development with a server (recommended to avoid potential CORS issues with map tiles):

1. Install Node.js if not already installed.
2. Run `npm install` to install the development server.

## Usage

- **Basic (static)**: Open `index.html` directly in a web browser.
- **With server**: Run `npm start` to start the development server on `http://localhost:8083`.

The app starts with a 2D map using OpenStreetMap tiles. Click the "Switch to Globe View" button to toggle to a 3D spherical globe. You can interact with both views using mouse or touch controls.

## Technologies Used

- [MapLibre GL JS](https://maplibre.org/maplibre-gl-js/docs/) - Open-source mapping library
- [OpenStreetMap](https://www.openstreetmap.org/) - Free map data
- [http-server](https://www.npmjs.com/package/http-server) - Simple static file server

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to submit issues and pull requests.

## Acknowledgments

- MapLibre for providing the open-source mapping library
- OpenStreetMap contributors for the map data