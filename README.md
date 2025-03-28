# Lab 4 - Interactive Thematic Web Map

## Population Density Across the 26 Counties in the Republic of Ireland

### Description

This map visualizes the population density across the 26 counties in the Republic of Ireland. The population density data is represented with varying colors to indicate areas with high and low population densities.

### How the Map Works

The map is built using Leaflet.js, which is a popular JavaScript library for interactive maps. It uses a GeoJSON file for representing the counties of Ireland. The map colors each county based on its population density.

---

#### Legend

The color scale used for the map ranges from light green (lower population density) to dark green (higher population density).

---

#### Population Data

The population data displayed is sourced from the [Central Statistics Office Ireland](https://data.cso.ie/table/F1013).

---

#### Map Information

This map was created by Bridget Barr and uses the following technologies:

- **Leaflet.js**: A JavaScript library for interactive maps
- **GeoJSON**: Format used to store geographic data
- **Chroma.js**: A color scale library used to generate the density color scale

---

### Map Functionality

- The map is centered on the coordinates [53.426985, -7.694935] and is zoomed to a level of 7.
- Each county's color is determined by its population density, with a color scale ranging from light green to dark green.
- Hover over a county to see its population density in people per square kilometer.
- Clicking on a county will zoom into that county.
