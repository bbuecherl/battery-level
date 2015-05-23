# battery-level [![Build Status](https://travis-ci.org/gillstrom/battery-level.svg?branch=master)](https://travis-ci.org/gillstrom/battery-level)

> Get current battery level

*Currently OS X systems only*


## Install

```
$ npm install --save battery-level
```


## Usage

```js
var batteryLevel = require('battery-level');

batteryLevel(function (err, res) {
	console.log(res);
	//=> 0.5525
});
```


## CLI

```
$ npm install --global battery-level
```

```
$ battery-level --help

  Usage
    $ battery-level
```


## License

MIT © [Andreas Gillström](http://github.com/gillstrom)
