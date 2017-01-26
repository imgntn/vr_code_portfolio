
#James Pollack

##Virtual Reality Code Portfolio

Includes work in High Fidelity, webVR (A-Frame), and Three.js.

INTERACTIVE OBJECTS AND ENTITIES
--------------------------------

[Bow and Arrow using A-Frame](https://github.com/imgntn/jBow), [Bow and Arrow using High Fidelity](https://github.com/highfidelity/hifi/blob/master/unpublishedScripts/marketplace/bow/bow.js)

[Xylophone](https://github.com/imgntn/jbp-hifi-apps/blob/master/xylophone/createXylophone.js), [Xylophone Key](https://github.com/imgntn/jbp-hifi-apps/blob/master/xylophone/xylophoneKey.js)

[Ping Pong Gun](https://github.com/highfidelity/hifi/blob/master/scripts/tutorials/entity_scripts/pingPongGun.js)

[Gaming Table ](https://github.com/imgntn/jbp-hifi-apps/tree/master/gameTable)

LOCOMATION
----------

[Hand Controller Teleportation System](https://github.com/highfidelity/hifi/blob/master/scripts/system/controllers/teleport.js)

Uses "dash" teleporting to move user through space.  Works with Oculus Touch, Vive, and Hydra Razer.


DATA VISUALIZATION
------------------

[Live Earthquakes Visualization](https://github.com/highfidelity/hifi/blob/master/script-archive/data_visualization/earthquakes_live.js)

Puts spheres on the globe wherever there are earthquakes and colors them according to magnitude -- updates with most recent USGS data.


3D USER INTERFACES (SPATIAL)
------------------
[Control the position, rotation, and proprties of lights](https://github.com/highfidelity/hifi/tree/master/script-archive/light_modifier)


2D USER INTERFACE IMPROVMENTS (NON-DIEGETIC)
-----------------------------

[dat.gui connected Particle System Explorer](https://github.com/highfidelity/hifi/blob/master/scripts/system/particle_explorer/particleExplorer.js)

[New Editor for Shared Entity Userdata JSON ](https://github.com/highfidelity/hifi/pull/8505)

Prior to this PR, you had to try to input properly formatted JSON as a string into a textarea.  Adapted a much nicer JSON editor based on user feedback.


A.I. & BEHAVIORS
----------------

[steering behavior for animated 'rat' entity going down alley.  avoids avatars and certain blocks.](https://github.com/highfidelity/hifi/blob/master/script-archive/drylake/ratSteer.js)

[a* pathfinding example using easystar library and tween.js](https://github.com/highfidelity/hifi/blob/master/script-archive/libraries/easyStarExample.js)


EXPERIMENTS
-----------
[Doppelganger](https://github.com/highfidelity/hifi/blob/master/script-archive/dressing_room/doppelganger.js) 

A copy of your avatar where your movements are mirrored onto the entity.  Part of "Dressing Room" in "Home" content set.

[Grand Central](https://github.com/imgntn/jbp-hifi-apps/blob/master/grandcentral/main.js)

Domain where all currently occupied user domains are represented spatially and can be teleported into by walking

[FeelSpeak](https://github.com/imgntn/jbp-hifi-apps/tree/master/feelspeak)

Uses haptics to tie one user's voice to another user's hand controllers.  You can feel when someone else speaks.  

[VNC in VR - Synchronized Virtual Desktops](http://blog.highfidelity.com/blog/2016/4/25/vnc-in-vr-synchronized-virtual-desktops)

See your normal desktop in VR using web technologies.  

BROWSER-RELATED / UTILITIES
---------------

[Add support for pop-up windows to Qt WebEngineView](https://github.com/highfidelity/hifi/pull/7143)  

[Enable HTML5 userMedia APIs in QTWebengine view](https://github.com/highfidelity/hifi/pull/7137)

[Batched Stats Collection](https://github.com/highfidelity/hifi/blob/d83600a22ee1579b15acf742e2fa83a84ce9951c/script-archive/example/misc/collectHifiStats.js)

360 VIDEO
---------
[export 4K resolution 360 Videos and Photos from inside of Three.js scenes](https://github.com/imgntn/j360)

Create videos from insides of your scenes that you can post to Facebook and YouTube