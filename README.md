# Shuttle Strike

First-person badminton in the browser. Your webcam tracks your hand: close it as if gripping a racket, then swing.

- **Grip:** close your hand ✊ — the racket sits in your fist and tilts with your wrist.
- **Swing:** swing fast when the shuttle reaches the racket head; swing left or right to aim.
- **Shots:** racket high + hard swing = smash, racket low = clear, soft swing = drop shot.
- **Pause:** hold an open palm ✋ still; close your hand to resume.
- No webcam? Choose "Play with mouse".

Everything is in `index.html`. It needs an internet connection (3D library and hand tracker load from a CDN) and must be served over HTTPS or localhost for the camera to work.
