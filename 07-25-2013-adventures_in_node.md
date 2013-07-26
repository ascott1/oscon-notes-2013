# Adventures in Node.js Faisal Abid (Dynamatik, Inc.)

[Cover slide](http://osconmonkey.nodejitsu.com/)

Node is single threaded:

- built around events
- event loops is always running, checking for new everns
- fires callbacks when new events are received
- "single threaded = blocking" - server will hang up if you have blocking code

