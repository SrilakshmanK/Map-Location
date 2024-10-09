# Map Animation: Bus Stops between Gandhipuram and Sulur

This project displays a simple map animation using Mapbox, showing bus stops between Gandhipuram and Sulur. The animation moves a marker across the map, indicating the different stops along the route at 1-second intervals.

## Features

- **Mapbox Integration**: The map is rendered using the Mapbox API.
- **Marker Animation**: A marker moves across the map, stopping at each location in the `busStops` array, representing bus stops.
- **Responsive UI**: The map fills the screen, and the button triggers the animation to display bus stops.

## How It Works

### HTML Structure

The HTML consists of a `div` element for the map container and a button to trigger the movement of the marker.

```html
<div id="map"></div>
<div class="map-overlay top">
    <button style="font-size: 2em" onclick="move()">Show stops between Gandhipuram and Sulur</button>
</div>
