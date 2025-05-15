#  Interactive Elevation Profile Viewer

This is a lightweight and interactive web tool for visualizing elevation profiles by clicking points on a map. It uses the Open Elevation API to fetch elevation data and displays the results in a clean elevation chart.

##  Features

- Interactive map with point selection
- Automatic conversion of clicked coordinates to elevation data
- Elevation profile plotting using Chart.js
- Map download functionality as PNG image
- Refresh/reset option for the map and chart
- Integrated geocoding with OpenStreetMap (Nominatim)

##  Demo

Try it live: [Demo Link](https://reshma-1986.github.io/Elevation-Profile/)

##  Tech Stack

- [OpenLayers](https://openlayers.org/) for the interactive map
- [Chart.js](https://www.chartjs.org/) for the elevation profile plot
- [Open Elevation API](https://open-elevation.com/) for fetching elevation data
- [html2canvas](https://html2canvas.hertzen.com/) for downloading map image
- [ol-geocoder](https://github.com/jonataswalker/ol-geocoder) for place search


##  How to Use

1. **Open the tool in your browser**
2. **Click on at least two locations on the map**  
   Red dots will appear to mark the selected points.
3. **Click "Show Elevation Profile"**  
   A smooth line chart will be generated based on the elevation values.
4. **Optional Actions:**
   - "Download Map Image" to save the current view
   - "Refresh Map" to reset the map and chart

##  How It Works

- Captures clicked coordinates (longitude, latitude) on the map
- Sends them in bulk to the [Open Elevation API](https://open-elevation.com/)
- Displays the elevation values using a line chart

##  Notes

- This tool is intended for light use and demonstration purposes.
- The free Open Elevation API has request limits — for production use, consider hosting your own elevation server or switching to a paid API.

##  License

This project is licensed under the [MIT License](LICENSE).

##  Acknowledgements

- OpenStreetMap & Nominatim
- Open Elevation API
- Chart.js
- OpenLayers
- html2canvas

---

Feel free to contribute, customize, or extend the tool with additional functionality like GPX import, cumulative distance calculation, or DEM overlays.


