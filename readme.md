# Schools in Western North Carolina 2021-2022
This interactive web map shows the distribution of schools across western North Carolina. The schools are categorized by type(public, private, and postsecondary) using three colorblind friendly colors. A choropleth map was created using county polygons and the total number of schools within each county.
There are several interactions used to view the data on the map. Mouseover was used to display the county name and total number of schools within the county when hovering over a county polygon. Click to zoom was also added to the county polygons to allow users to view schools within the county with more detail.

## Libraries Used
- Leaflet.js     Javascript library
- Leaflet.ajax   Leaflet plugin for working with GeoJSON data.
- jQuery         Javascript library with more features
- Chroma.js      Library for colors
- Font Awesome   Vector icon for school
- Google Fonts   Additional fonts

## Data Sources
- School Information; <a href="https://nces.ed.gov/programs/edge/geographic/schoollocations" target="_blank">National Center for Education and Statistics</a>
- County GeoJSON; <a href="https://www.nconemap.gov/datasets/d192da4d0ac249fa9584109b1d626286/about?layer=0" target="_blank">North Carolina Department of Transportation</a>
- Base Map &copy;CartoDB