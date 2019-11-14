# Front-end JS Architect Assessment

## Overview

The [`light-level` CSS `@media` feature](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/light-level) is a yet to be implemented media query which will allow developers to change their user interfaces to the suit the device's ambient light level.

There are currently 2 JavaScript APIs which can query for a device's light level:

1. `devicelight` (deprecated) https://developer.mozilla.org/en-US/docs/Web/API/Ambient_Light_Events
2. `AmbientLightSensor` https://developer.mozilla.org/en-US/docs/Web/API/AmbientLightSensor

Between them, they have support for Chrome (behind a `enable-generic-sensor-extra-classes` flag), Edge and Firefox (behind a `device.sensors.ambientLight.enabled` flag).

It is worth reading [Using light sensors](https://developer.mozilla.org/en-US/docs/Web/API/DeviceLightEvent/Using_light_sensors) and the [Ambient Light Sensor spec](https://w3c.github.io/ambient-light/) to learn more.

## Task

We'd like you write a progressive enhancement polyfill/ponyfill for this media query and demonstrate its usage within the context of a simple interface of your choosing.

It provides us a chance to see your:

* Clean architectural implementation demonstrating separation of concerns, encapsulation of IO, and testable methods.
* Your level of general JavaScript knowledge.
* Understanding of cross-browser environments.

You will require access to an Android or Windows device with a light sensor with Chrome, Firefox and Edge installed (if applicable). Unfortunately, Macs don't seem to expose its light sensor to web APIs, and Safari on iOS has zero support.

## Guidance on time spent

While you should be free to decide how much time you'd like to spend developing your solution, in the interests of not taking up all your time, we strongly advise to limit yourself to five hours or less. Feel free to document approaches you would have taken had time been ample.

## Submission

Please push your changes to a public GitHub repo and let us know when you're done via email or by logging an issue on this repo.
