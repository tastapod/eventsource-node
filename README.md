# EventSource

This library implements the [EventSource](http://dev.w3.org/html5/eventsource/) client for Node.js. The API aims to be W3C compatible.

## Install

    npm install eventsource

## Usage

```javascript
var EventSource = require('eventsource');

es = new EventSource('someurl');
```

See the [spec](http://dev.w3.org/html5/eventsource/) for API docs.

