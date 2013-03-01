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

You can use .html as file extension as well as .dot by adding an options: 
	
	extension: 'html'

## Warn

* Make sure that you put your templates in a sperate directory named as 'templates'.

