# metaljs.com

> [Metal.js](https://github.com/metal/metal.js)' website and documentation source.


## Building

Building the website requires a few dependencies:

- NodeJS >= 10.0
- Ruby (for Compass and Sass) and Ruby Gems
- Bower

Having those, simply:

1. Fetch npm and bower related dependencies:

	```sh
	$ npm install && bower install
	```

2. Run the `build` gulp task:

	```sh
	$ gulp build 
	```


## Running locally

To run the website locally just run the default gulp task after steps `1` and `2`. This task will build the project, watch for changes and create an HTTP server for serving it:

	```sh
	$ gulp
	```


## License

[BSD License](https://github.com/metal/metal.js/blob/master/LICENSE.md) © Liferay, Inc.

