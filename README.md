# matchstick-scanner

scan your local network for matchstick devices and return the
first found.

### Usage
```javascript
var scanner = require('matchstick-scanner');

scanner(function(err, service) {
  console.log('matchstick %s running on: %s:%s',
    service.name,
    service.address,
    service.port);
});
```

### Installation

`npm install matchstick-scanner`

## License
MIT

### Original version

This is a fork from https://github.com/xat/chromecast-scanner that scanned for Chromecast devices.
