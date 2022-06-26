# Week-13-Challenge

## Challenge Overview
We are continuing our work with Basil and Sahana. They asked for us to further enhance our earthquake map. They requested to see a map of earthquakes in relation to the tectonic plates’ locations. They also requested to see earthquake with magnitudes greater than 4.5.

In this challenge, we used an open-source JavaScript map library called, Leaflet. Along with Leaflet, we utilized HTML, JavaScript, and D3 to generate our interactive earthquake map. 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Leaflet Basic Map</title>

<!-- LEAFLET CSS -->
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.8.0/dist/leaflet.css"
integrity="sha512-hoalWLoI8r4UszCkZ5kL8vayOGVae1oxXe/2A4AO6J9+580uKHDO3JdHb7NzwwzK5xr/Fs0W40kiNHxM9vyTtQ=="
crossorigin=""/>
    
<!-- d3 JavaScript -->
  <script src="https://d3js.org/d3.v5.min.js"></script>

<!--Our CSS -->
<link rel="stylesheet" type="text/css" href="static/css/style.css">

</head>
<body>

<!-- The div that holds our map -->
<div id="mapid"></div>

<!-- Leaflet JS -->
<script src="https://unpkg.com/leaflet@1.8.0/dist/leaflet.js"
integrity="sha512-BB3hKbKWOc9Ez/TAwyWxNXeoV9c1v6FIeYiBieIWkpLjauysF18NzgR1MBNBXf8/KABdlkX68nAhlwcDFLGPCQ=="
crossorigin=""></script>

<!-- API key -->
<script type="text/javascript" src="static/js/config.js"></script>

<!-- Our JavaScript -->
<script type="text/javascript" src="static/js/challenge_logic.js"></script>

</body>
</html>
