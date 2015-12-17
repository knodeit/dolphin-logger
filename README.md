### Logger for an application

### Installation
```npm install dolphin-logger --save```

```
var Logger = require('dolphin-logger');
```

### Methods

* info
* warn
* error
* debug

By default log level is "debug", for production mode better to set `NODE_DEBUG_LEVEL=info` The logger will write only error, warn and info logs.

### Examples

```
var obj = {a:1};

Logger.info('Info message:', obj);

Logger.warn('warn message:', obj);

Logger.error('Wrror message:', obj);

Logger.debug('Debug message:', obj);

```
