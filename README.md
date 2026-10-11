Tracks spraying patterns using GPS.

## Testing without driving

Open `v3.html`, enter the swath width, and choose **DEMO DRIVE**. The demo feeds a smooth moving path through the same GPS handler used by the device, so you can test the map, pass recording, lightbar, area calculation, and work log at a desk. Reload the page to stop the demo timer.

## GPS behavior

The app rejects fixes with accuracy worse than 30 meters, rejects implausible jumps, and lightly smooths accepted fixes based on reported accuracy. Satellite tiles are rendered at their native size; the previous 1.42x enlargement was removed because it blurred the imagery.
