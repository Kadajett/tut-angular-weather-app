# weather-app

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.11.1.

## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.

## Getting Started 

First things first, go into app/scripts/ and rename `appConfig_example.js` to `appConfig.js`.
Take a look inside and you will see: 
```javascript 
'use strict';
var config = (function(){
	return {
		weatherApi: 'keyHere'
	};
}());
```
Just replace the `keyHere` value with an api key from [openweathermap.org](http://openweathermap.org/api)