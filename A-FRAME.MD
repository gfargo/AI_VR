# A-Frame VR Framework

https://github.com/ngokevin/kframe

### Components

- https://www.npmjs.com/package/aframe-text-component
- https://www.npmjs.com/package/aframe-textwrap-component
- https://www.npmjs.com/package/aframe-html
- https://www.npmjs.com/package/aframe-map
- https://www.npmjs.com/package/aframe-video-billboard
- https://www.npmjs.com/package/aframe-passthrough-component

## Unit of Measurement

A-Frame’s distance unit is in meters because the WebVR API returns pose data in meters. When designing a scene for VR, it is important to consider the real world scale of the entities we create. A box with height="10" may look normal on our computer screens, but in VR the box will appear massive.


## Delaying A-Frame Initital

https://github.com/aframevr/aframe/issues/302
http://stackoverflow.com/questions/38835415/how-to-defer-or-load-an-a-frame-scene-programmatically
