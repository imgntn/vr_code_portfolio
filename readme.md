
#James Pollack

##Virtual Reality Code Portfolio

Includes work in High Fidelity, webVR (A-Frame), and Three.js.


INTERACTIVE OBJECTS AND ENTITIES
--------------------------------

[Bow and Arrow // A-Frame](https://github.com/imgntn/jBow)

[Bow and Arrow // High Fidelity](https://github.com/highfidelity/hifi/blob/master/unpublishedScripts/marketplace/bow/bow.js)

[Xylophone](https://github.com/imgntn/jbp-hifi-apps/blob/master/xylophone/createXylophone.js), [Xylophone Key](https://github.com/imgntn/jbp-hifi-apps/blob/master/xylophone/xylophoneKey.js)

[Ping Pong Gun](https://github.com/highfidelity/hifi/blob/master/scripts/tutorials/entity_scripts/pingPongGun.js)

[Gaming Table](https://github.com/imgntn/jbp-hifi-apps/tree/master/gameTable)

LOCOMOTION
----------

[Hand Controller Teleportation System](https://github.com/highfidelity/hifi/blob/master/scripts/system/controllers/teleport.js)

Uses smooth arrival teleporting to move user through space.  Works with Oculus Touch, Vive, and Hydra Razer.


DATA VISUALIZATION
------------------

[Live Earthquakes Visualization](https://github.com/highfidelity/hifi/blob/master/script-archive/data_visualization/earthquakes_live.js)

Puts spheres on the globe wherever there are earthquakes and colors them according to magnitude -- updates with most recent USGS data.


3D USER INTERFACES (SPATIAL)
------------------
[Control the position, rotation, and proprties of lights](https://github.com/highfidelity/hifi/tree/master/script-archive/light_modifier)

Use physical objects to control lighting.  works with multiple users.


2D USER INTERFACE IMPROVMENTS (NON-DIEGETIC)
-----------------------------

[dat.gui connected Particle System Explorer](https://github.com/highfidelity/hifi/blob/master/scripts/system/particle_explorer/particleExplorer.js)

Before, there was no way to quickly explore the parameters of particle systems.  Improved content creator productivity.

[New Editor for Shared Entity UserData JSON](https://github.com/highfidelity/hifi/pull/8505)

Before, you had to try to input properly formatted JSON as a string into a textarea to share data between entities.  Adapted a much nicer JSON editor based on user feedback.


A.I. & BEHAVIORS
----------------

[steering behavior for animated 'rat' entity in alley scene](https://github.com/highfidelity/hifi/blob/master/script-archive/drylake/ratSteer.js)

a steering behavior where the rat avoids avatars and other obstacles.

[a* pathfinding example using easystar library and tween.js](https://github.com/highfidelity/hifi/blob/master/script-archive/libraries/easyStarExample.js)

pathfinding algorithm that finds a path through a grid of obstacles.


EXPERIMENTS
-----------
[Doppelganger](https://github.com/highfidelity/hifi/blob/master/script-archive/dressing_room/doppelganger.js) 

A copy of your avatar where your movements are mirrored onto the entity.  Part of "Dressing Room" in "Home" content set.

[Grand Central](https://github.com/imgntn/jbp-hifi-apps/blob/master/grandcentral/main.js)

Domain where all currently occupied user domains are represented spatially and can be teleported into by walking

[Feel Speak](https://github.com/imgntn/jbp-hifi-apps/tree/master/feelspeak)

Uses haptics to tie one user's voice to another user's hand controllers.  You can feel when someone else speaks.  

[VNC in VR - Synchronized Virtual Desktops](http://blog.highfidelity.com/blog/2016/4/25/vnc-in-vr-synchronized-virtual-desktops)

See your normal desktop in VR using web technologies.  

BROWSER-RELATED
---------------

[Add support for pop-up windows to Qt WebEngineView](https://github.com/highfidelity/hifi/pull/7143)  

[Enable HTML5 userMedia APIs in QTWebengine view](https://github.com/highfidelity/hifi/pull/7137)

360 VIDEO
---------
[export 4K resolution 360 Videos and Photos from inside of Three.js scenes](https://github.com/imgntn/j360)

Create videos from insides of your scenes that you can post to Facebook and YouTube.


HIFI PULL REQUESTS
-------------
[All my Pull Requests from High Fidelity](https://github.com/highfidelity/hifi/pulls?utf8=%E2%9C%93&q=is%3Apr%20is%3Aclosed%20author%3Aimgntn)

A quick way to see work from 2015-2016.
