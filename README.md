This project is a for a simple web application that allows users to draw polylines on a Leaflet map and then simplify those polylines using Turf.js. The simplified and unsimplified polylines are displayed on the map, and users have the option to clear the drawn polylines.

Additional Notes
-The Leaflet map is initialized with a default settings being centered at coordinates [51.505, -0.09]
-Polylines drawn by users are stored as arrays of coordinates, and Turf.js is used to simplify these polylines.
-Polyline simplification is performed with a tolerance of 0.01 and highQuality set to false.

