## mc-logger

The peoples null logger:

```javascript

function noop() {}

module.exports =
  { info: noop
  , log: noop
  , error: noop
  , warn: noop
  , debug: noop
  }


```