# Hanwella Dengue Prevalence Map

## Overview
This project provides an interactive web map displaying dengue prevalence levels across three specific locations in Hanwella, Sri Lanka. The map color-codes locations based on their risk level (high, medium, low) and provides detailed information for each location.

## Features
- Interactive map centered on Hanwella, Sri Lanka
- Three marked locations with different dengue prevalence levels:
  - **High risk** (red): Hanwella Town Center
  - **Medium risk** (orange): Pahala Hanwella
  - **Low risk** (green): Maha Hanwella
- Popup information for each location showing:
  - Location name
  - Number of reported cases
  - Additional details about the area
  - Risk level indicator
- Color-coded legend explaining the different risk levels
- Responsive design that works on different screen sizes

## Files
- `map.html` - Main HTML file containing the map and all related code

## Usage Instructions
1. Open the `map.html` file in any modern web browser
2. The map will load automatically centered on Hanwella
3. Click on any marker to see detailed information about that location
4. Use the +/- controls or mouse wheel to zoom in/out
5. Click and drag to pan around the map

## Technical Implementation
- Built with HTML, CSS, and JavaScript
- Uses [Leaflet.js](https://leafletjs.com/) for the mapping functionality
- Uses [OpenStreetMap](https://www.openstreetmap.org/) tiles for the base map
- Custom markers and popups designed with CSS

## Customization
To modify map locations or data:

1. Open the `map.html` file in a text editor
2. Locate the JavaScript section with the `locations` array
3. Edit the coordinates, names, case numbers, or risk levels as needed:

```javascript
const locations = [
    {
        name: "Hanwella Town Center",
        coords: [6.9013, 80.0833],
        level: "high",
        cases: 42,
        details: "Dense population area with standing water issues"
    },
    // Add or modify locations here
];
```

## Browser Compatibility
- Chrome 49+
- Firefox 45+
- Safari 9+
- Edge 13+
- Opera 36+

## Dependencies
- Leaflet.js (1.9.4) - loaded via CDN
- No server-side dependencies required

## License
This project is available for free use with attribution.

## Contact
For questions or support, please contact the project maintainer.

---

Last updated: May 20, 2025
