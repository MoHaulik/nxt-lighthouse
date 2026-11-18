# The Keeper

A WebXR virtual-reality game for **Meta Quest**, in the browser, with three.js. Played with bare hands (controllers work too).
A [NXT/WebXR](https://www.nxtwebxr.com) production.

You stand in the lantern room of a lighthouse, twenty-eight metres above a night sea, everything drawn like an old wood engraving. Strike a match and light the lamp. Turn the great Fresnel lens by its brass ring so the beam finds the rocks before the ships do; captains steer around only what your light has shown them. Wind the clockwork, pour the oil, rub the soot off the lens, pull the foghorn cord when the fog rolls in, and throw the life ring out of the door to haul shipwrecked sailors up on a rope. Three nights, then dawn.

Built on the die Hände / Petri Dish skeleton (hand tracking, pinch with hysteresis, synthesized audio, `?sim` desktop preview). One file, no build step.

## Desktop preview

`python3 -m http.server 8782`, then `http://localhost:8782/?sim`. Mouse = hand, hold = pinch, right-drag = look, wheel = reach, hold T = tip what you hold.
