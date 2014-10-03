Firefox 3D audio bug - OSX
==========================

* Run this example http://playcanvas.github.io/#audio/3D/index.html in Chrome. You will hear a footstep 3D sound.
* While the example runs in Chrome open up Firefox and run this example: http://vkalpias.github.io/index.html. You will not hear any sounds playing either from Firefox or Chrome. In fact the entire OS will stop playing audio UNTIL the audio sample is finished in Firefox. After the audio sample is finished in Firefox all audio will go back to normal.

Reproduced in Firefox versions:
* 32.0.3
* 32.0.1

OSX versions:
* 10.9.4