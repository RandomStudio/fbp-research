# Some useful resources

Wikipedia article
https://en.wikipedia.org/wiki/Flow-based_programming

From the "inventor"
http://www.jpaulmorrison.com/fbp/

A GitHub list
https://github.com/samuell/awesome-fbp


# Comparison of FBP environments

## Node-RED
https://nodered.org/

Pros
- supported by IBM
- default installed on Raspbian OS
- excellent UI for editor
- easy to run locally, in Docker, etc. etc. (not tied to a service)
- made for IoT
- plenty of user-contributed components

Cons
- not many media-specific components (yet) but definitely web, streaming, etc.

Interesting examples
- Check out https://github.com/Streampunk/node-red-contrib-dynamorse-core which appears to allow transformations (using CPU and GPU operations) on video and audio streams, including SDI via BlackMagic!
- OpenCV motion detection on video, generating new encoded video as output (with overlays) https://flows.nodered.org/flow/c172899be094e2cf37a92f32b7c47635


## NoFlo
https://noflojs.org/

Pros
- already has good support for HTML5 stuff like WebAudio, webcams, canvas drawing, etc.

Cons
- UI has some odd quirks
- documentation about built-in components is very incomplete

## Total JS
https://www.totaljs.com/flow/

Cons
- seems to be tied into a kind of platform, https://www.totaljs.com/framework/
