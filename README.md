# peekr

Peek at a real-life view of a GPX track.

## Do what?

https://markdrayton.github.io/peekr/

## Motivation

Strava's route builder is great for making new routes but I often want to double-check what roads look like before riding the route (or worse, taking others on it). `peekr` plots the route from a GPX file and, with a click on the route, shows the Street View panorama for that location in the direction of travel. It'd be nice if this was integrated into the editing process directly but it certainly beats trying to find a road on Google Maps.

## Shortcomings

* doesn't handle more than one track/route per GPX file
* silently does nothing when a location has no Street View coverage
* naff UI design, probably awful on mobile, etc

## Acknowledgements

Thanks to [Luuka/GPXParser.js](https://github.com/Luuka/GPXParser.js) for the GPX parser library and intro to Vuew.js.
