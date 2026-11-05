# Camera Tester

A static page for testing camera access inside iOS and Android webviews. It's hosted on GitHub Pages so it runs on a different origin than creditkarma.com.

It tests:
- `getUserMedia` live stream (front and back cameras) and capturing a frame
- `enumerateDevices` and the Permissions API
- Environment details: secure context, whether it's in an iframe, the user agent

Everything is also logged to `console` with the prefix `[camera-tester]`.
