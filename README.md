# Attila

A content focused responsive theme for [Ghost](https://github.com/tryghost/ghost/).

## Development

Install [Grunt](https://gruntjs.com/getting-started/):

    npm install -g grunt-cli

Install Grunt dependencies:

    npm install

Run the local server:

    grunt

## Production Builds

Build Grunt project:

    grunt build

The `compress` Grunt task packages the theme files into `dist/<theme-name>.zip`,
which you can then upload to your site.

    grunt compress
