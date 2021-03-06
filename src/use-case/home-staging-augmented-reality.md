# Bringing Augmented Reality to the web

Augmented Reality opens up entirely new ways of user interaction.
Thanks to ARKit (native iOS implementation by Apple) and ARCore ( Google Android pendant ) Augmented Reality is finally becoming what is was promised to be some time ago.

We couldn't wait to try it out and build a small demo that allows the user to draw a floor plan while standing in the room and furnish it without the need to push or carry anything.

## Furnishing proposals right in your room

Once a room has been measured by marking corners, windows and doors (see below), we have enough structural information at hand to let our [Home Staging AI](https://3d.io/docs/api/1/home-staging-ai.html) compute some furnishing proposals.

* Within a few seconds a solution gets computed that fit the room structure and circulation
* Generic furniture items can be replaced with real ones to get an idea how your room looks with different styles

![staging](https://storage.3d.io/535e624259ee6b0200000484/2017-09-13_11-42-23_XUM61N/home-staging-ai.gif)

## Measuring a room with a few clicks

The augmented reality kit on the device detects the floor plane and sets the correct scale.
This allows us to simply draw the room without any need for measurements.

* Point at a corner in your room and tab the screen to mark the beginning of a wall
* Do that for all four corners to close the loop
* Mark windows and doors by setting their start and end point on the wall

![draw-plan](https://storage.3d.io/535e624259ee6b0200000484/2017-09-13_11-56-39_wW7wLF/draw-plan.gif)

## Developer preview

The demo can be tried out live on [glitch.me](https://homestaging-ar.glitch.me/). It is also available on [github](https://github.com/archilogic-com/3dio-js/tree/master/examples-browser/staging/stage-room-ar).

To run it you need an ARKit or ARCore device with a compatible browser.

[Getting started with AR on the Web](https://developers.google.com/ar/develop/web/getting-started)

## Stay tuned =)

