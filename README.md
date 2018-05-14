# WebVRtoSteamVR
Experiments with getting WebVR apps working natively

Approaches
Electron (uses chromium (Chrome) backend). Also, Nativefier (packages existing online website)
NW.js (uses chromium (Chrome) backend)
  allows passing of chrome launch flags, including --enable-webvr
    http://docs.nwjs.io/en/latest/References/Command%20Line%20Options/
    https://peter.sh/experiments/chromium-command-line-switches/
  https://www.reddit.com/r/WebVR/comments/41s192/i_added_a_bounty_to_nwjs_to_create_a_webvr_build/
qbrt (uses gecko (Firefox) backend)
  maybe more promising, because the stable version of firefox supports webvr, whereas you have to either enable a flag or use chrome canary to get webvr working in chrome

Crosswalk (compiles to mobile): https://github.com/Jam3/webvr-gearvr-test

supermedium browser (not great option, just a browser that works in vr and has an app directory)

appimage

web app manifest? https://tomitm.github.io/appmanifest/

Some past github feature requests
https://github.com/electron/electron/issues/3271
https://github.com/electron/electron/issues/12468

Not updated recently, but maybe promising (though developed for a different purpose):
https://github.com/mncharity/node-webvr-alt-stack
