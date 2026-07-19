# Field Area Calculator

A web-based tool for measuring agricultural field boundaries and calculating land area, built with Leaflet.js. Users can identify their field either by entering a registration number (mock lookup) or by using their current GPS location and manually drawing the field boundary on an interactive map.

## Features


* GPS Location — Center the map on your current location using the browser's Geolocation API
* Field Registration Lookup — Look up pre-defined field boundaries by a mock registration number
* Interactive Drawing — Draw, edit, and delete polygon boundaries directly on the map using Leaflet.draw
* Accurate Area Calculation — Area computed using the spherical excess formula, accounting for the curvature of the Earth
* Unit Conversion — View areas in Square Meters, Acres, or Hectares
* Multiple Fields — Draw and track several polygons at once, with a running total area
* Responsive UI — Clean, modern interface that works across devices

## Tech Stack


1. Leaflet.js — Interactive map rendering
2. Leaflet.draw — Drawing and editing tools for map shapes
3. Vanilla JavaScript — No framework dependencies
4. HTML5 Geolocation API — For retrieving the user's current position


# Contributing

Contributions are welcome! Please open an issue or submit a pull request with any improvements or bug fixes.

# License

This project is available under the MIT License. See LICENSE for details.
