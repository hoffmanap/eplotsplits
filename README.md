# Urban Lot Splitter & Capacity Simulator

An interactive, client-side geospatial dashboard designed to simulate urban lot splits and predict net housing unit yields under changing regulatory paradigms.

## 🏙️ Interactive Workspace Features
- **Dynamic Optimization Canvas:** Real-time client-side calculation of lot splits using Leaflet.js and Turf.js.
- **Micro-Lot Controls:** Adjust minimum square footage and lot width tolerances dynamically using input sliders.
- **Physical Constraint Masking:** Toggleable building footprint layers (`eligible_buildings.geojson`) to deduct existing structures from total buildable area metrics.
- **Regulatory Overlay Checks:** Toggleable historic zoning layer (`historic.geojson`) to screen out or allow development inside historic protection boundaries.

## 📂 Repository File Architecture
- `index.html` - Core frontend interface layout, style definitions, and spatial engines.
- `requirements.txt` - Python backend environment package listings.
- `data/` - Content delivery folder holding local spatial datasets:
  - `eligible_parcels.geojson`
  - `eligible_buildings.geojson`
  - `historic.geojson`
  - `context_areas.geojson`
  - `hex_grid.geojson`