#doT Middleware for Connect

doT - middleware (adapted from the stylus middleware)


## Installation

	npm install --save dot-middleware

## Usage

If you're using express, then put the following configuration to your app.

	app.use(require('dot-middleware')({
	    src: __dirname + '/public',
	    compress: true,
	    amd: true,
	    debug: true
	}));
	app.use(express.static(path.join(__dirname, 'public')));

## Warn

<<<<<<< HEAD
Make sure that you put your templates in a sperate directory as .
=======
Just started.
>>>>>>> 5af36b98e63fe006a0e17988ea3a7caa0bbb301b
