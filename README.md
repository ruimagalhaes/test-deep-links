# Route Selector

A simple web application that allows users to select origin and destination points on a map to generate Circuit ride-sharing routes.

## Features

- Interactive map interface using Leaflet.js
- Quick city selection buttons for Coimbra, Washington DC, and Philadelphia
- Click-to-select origin and destination points
- Direct integration with Circuit ride-sharing service
- Mobile-friendly responsive design

## Usage

1. Select a city using one of the preset city buttons, or navigate the map manually
2. Click once on the map to set the origin point
3. Click again to set the destination point
4. Click "Open in Circuit" to open the route in Circuit's ride-sharing service
5. Use "Reset Points" to clear the selected points and start over

## Technical Details

- Built with vanilla JavaScript
- Uses Leaflet.js for map functionality
- OpenStreetMap tiles for map display
- Responsive CSS layout with flexbox
- Double-tap prevention for mobile devices

## Setup

Simply open `index.html` in a web browser. No build process or server required.

## Dependencies

- Leaflet.js 1.7.1
- OpenStreetMap tile server

## License

This project is open source and available for use and modification.
