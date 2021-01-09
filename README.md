# Marcel Berberich Ghost Theme

A content focused responsive theme for [Ghost](http://github.com/tryghost/ghost/).

## Setup

To enable [Disqus](https://disqus.com/) comments go to your blogs code injection settings and add `<script>var disqus = 'YOUR_DISQUS_SHORTNAME';</script>` to your blog header.

## Development

Install [Grunt](http://gruntjs.com/getting-started/):

	npm install -g grunt-cli

Install Grunt dependencies:

	npm install

Build Grunt project:

	grunt build

Release Grunt project:

	grunt release

This copies a clean theme into a folder "release". This folder can be zip'd and uploaded to Ghost.

## Copyright & License

This theme is based on Attila:
Copyright (C) 2015-2018 Peter Amende - Released under the [MIT License](https://github.com/zutrinken/attila/blob/master/LICENSE).
