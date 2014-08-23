# cursor

> Helper for `requestAnimationFrame`

## Install

```sh
$ npm install --save speedr/raf
```

## Usage

```js
var raf = require('raf');
var id = raf.start(function(elapsed) {
  // Called every frames
  game.update(elapsed);
});
```

## API

### raf.start(fn)

Calls `fn` on __every__ frame with `elapsed` set to the elapsed time in milliseconds.  
Returns the request ID.

### raf.stop(id)

Cancels the specified animation frame request.

## License

MIT © Florent Cailhol
