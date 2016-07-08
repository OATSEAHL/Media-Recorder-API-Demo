# Media Recorder API Demo

This Teacher Virus payload was created from a fork of the original Media Recorder API Demo as seen here:
https://github.com/nusofthq/Media-Recorder-API-Demo 

Which provided a demo implementation of the (new) [Media Recorder API](http://w3c.github.io/mediacapture-record/MediaRecorder.html) (also known as MediaStream Recording API).

This version was created so that we could experiment with Video recording and it's integration into Teacher Virus and the ability to add content directly into the TV Player library for immediate access by students connecting to a TV server (hotspot school)

From testing the first obstacle encountered is the change to Chrome that requires HTTPS be used (Which is not supported on Android yet) and thus requires an SSL Certificate be in use - this precludes some of the simple deployment approaches

See Below:
"getUserMedia() no longer works on insecure origins. To use this feature, you should consider switching your application to a secure origin, such as HTTPS. See https://goo.gl/rStTGz for more details."

