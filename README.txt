GRUMPY'S WEATHER BOARD — AUTOMATIC RADAR UPDATE

Upload index.html to the root of your existing Grumpys-weather-board GitHub repository, replacing the existing index.html. Keep grumpys-logo.png beside it. The included logo is unchanged.

Continue using your existing GitHub Pages URL in VXT. Reload the board after GitHub Pages finishes publishing; if it still shows the previous version, refresh the VXT player cache.

NORMAL: Current conditions, next six hours, and five-day forecast.
STORM MODE: Twin Cities radar on the left, current conditions on the right, next six hours across the bottom. Five-day forecast hidden.

Radar activates for current thunderstorms, snow, freezing precipitation, or heavy rain; or these conditions in an hourly forecast overlapping the next two hours with precipitation probability at least 40%. Relevant NWS watches, warnings, and advisories covering St. Bonifacius also activate it. This uses forecast and alert information, not automated radar storm tracking.

Weather refreshes every 10 minutes; local alerts and visible radar refresh every 2 minutes. The normal layout returns 10 minutes after the last qualifying trigger. Expired alerts and weather responses older than 30 minutes stop triggering radar. Failed radar loads show an unavailable message and automatically retry.

Radar source: NOAA / National Weather Service Twin Cities (KMPX) standard animated radar. The map includes its own observation times and reflectivity legend. Reflectivity colors show intensity, not a guaranteed rain/snow distinction. Hourly conditions provide precipitation type. Radar may lag observations; look at the timestamps on the map.

PREVIEW: Upload radar-demo.html too, or append ?demo=storm to the board URL. Use ?demo=snow for sample snow conditions or ?demo=clear for the normal layout. Demo weather is clearly labeled and simulated; radar still shows actual current weather. Remove the query string for the live VXT board.

The design scales a 1920x1080 layout to the screen. Actual playback in your VXT player still needs checking. This update has not been pushed to your GitHub repository.
