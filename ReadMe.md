Uses AR.js [https://github.com/jeromeetienne/AR.js]
Tracks a marker using artoolkit.
This code is set to use a specific marker.
patternUrl : 'js/patt.hiro'

Didn't need to use a-frame, I was able to load a gltf model w/ script and Threejs, which allows for animation and interactivity!
Must use a perspective camera for interactivity.

I used Blender2.8 principled BSDF node w/image texture then exported as gltf 2
The light in gltf scene would not show, try again...

Shield scene has a plane below so it can cover the marker and receive a shadow
For this simple test the interactivity just toggles the plane on/off


Created a new QR+Marker, arshield-marker.png, that points to [http://dev.krissnik.com/arshield/index.html]
using [https://jeromeetienne.github.io/AR.js/three.js/examples/arcode.html]
