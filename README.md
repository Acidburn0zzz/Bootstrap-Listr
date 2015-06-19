# Bootstrap Listr

[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![GitHub release](https://img.shields.io/github/release/idleberg/Bootstrap-Listr.svg?style=flat-square)](https://github.com/idleberg/Bootstrap-Listr/releases)
[![Travis](https://img.shields.io/travis/idleberg/Bootstrap-Listr.svg?style=flat-square)](https://travis-ci.org/idleberg/Bootstrap-Listr)
[![David](https://img.shields.io/david/dev/idleberg/Bootstrap-Listr.svg?style=flat-square)](https://david-dm.org/idleberg/Bootstrap-Listr#info=devDependencies)

A replacement for default server indices, Bootstrap Listr beautifully displays folders and files in the browser. It is built upon the [Bootstrap](http://getbootstrap.com) framework and optionally makes use of [Bootswatch](http://bootswatch.com/) themes and [Font Awesome](http://fortawesome.github.io/Font-Awesome/) icons.

*Watch a [live demo](http://demo.idleberg.com/Bootstrap-Listr-2/)!*

## Installation

Download the [latest release](https://github.com/idleberg/Bootstrap-Listr/releases) or clone the repository.

## Usage

The simplest way is to use the default configuration. Copy the `dist`-folder to your webserver, then place all files that should be accessible in the browser go into the `_public` folder. Point your browser to the `dist`-folder rather than the files and folder inside `_public`. If you run 403 or 404 errors, please refer to the [FAQ](https://github.com/idleberg/Bootstrap-Listr/wiki/FAQ).

## Building

### Gulp

[Gulp](http://gulpjs.com/) tasks are used to configure and build your application. You can install Gulp globally using `npm install gulp -g`.

You can now run the default task `gulp` to set up the application. On first run, this will guide you through the installation process, after that it will only upgrade the codebase. To force a clean installation, you can use `gulp setup-clean`.

Please visit the [project wiki](https://github.com/idleberg/Bootstrap-Listr/wiki/Gulp-tasks) for details.

### CDN

Instead of running your dependencies locally, you can make use of various content delivery networks (CDN). Initialize your application using `gulp init` and set `dependencies` to `cdn` in your `config.json`. You can then specify your preferred CDNs (and all other preferences) in this file as well (see [below](#options) for details!)

## Deployment

Deploy the entire `dist/` folder to your server. All files that should be accessible in the browser go into the `_public` folder (you can change the folder in the config). Depending on your Apache settings, you might have to uncomment the `RewriteBase` setting in the `.htaccess` file and maybe add parent folder name right after the slash.

## Options

You can configure a number of settings in the file `config.json`:

* Optional columns for size modified date
* Document icons
* File viewer for images, videos, audio, source code and HTML
* Search box to filter results
* Column sorting
* Responsive tables
* List of ignored files
* Default location for JavaScript libraries and style sheets
* Syntax highlighting in file viewer
* Save to Dropbox
* Share buttons
* Google Analytics
* Language

Please visit the [project wiki](https://github.com/idleberg/Bootstrap-Listr/wiki/Understanding-config.json) for details.

## Contribute

1. Fork the repository
2. Make your changes
3. Send a pull request with your changes

## Credits

This project is built upon—or includes—code from the following people:

* Greg Johnson - [PHPDL lite](http://web.archive.org/web/20130920165711/http://greg-j.com/phpdl/) [Internet Archive]
* Na Wong - [Listr](http://nadesign.net/listr/)

Contributors:

* [@melalj](https://github.com/melalj) - subfolder support
* [@Zerquix18](https://github.com/Zerquix18) - security fixes

## License

The MIT License (MIT)

Copyright (c) 2014 Jan T. Sott

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/Bootstrap-Listr) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`
