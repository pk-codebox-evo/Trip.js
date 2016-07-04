# Trip.js

[![Build Status](https://travis-ci.org/EragonJ/Trip.js.png?branch=master)](https://travis-ci.org/EragonJ/Trip.js) [![Join the chat at https://gitter.im/EragonJ/Trip.js](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/EragonJ/Trip.js?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

![Trip.js](https://raw.github.com/EragonJ/Trip.js/master/public/img/logo-tiny.png "Trip.js")

Trip.js is a jQuery plugin that can help you customize a tutorial trip easily with more flexibilities. Right now Trip.js support lots of useful stuffs like **keyboard binding**, **animations**, **changing themes** ... etc. If you want to highly customize your own tutorial trip, then Trip.js is definitely worth to give it a try !

## Browser support

Trip.js has been tested and work well on `IE 9+`, `Chrome 32+`, `Firefox 32+` and `Safari 9+`

## Version

3.2.0

## How to

### Use this library

Please check [website](http://eragonj.github.io/Trip.js), [setup](http://eragonj.github.io/Trip.js/doc-setup.html), [configuration](http://eragonj.github.io/Trip.js/doc-configuration.html) and [API](http://eragonj.github.io/Trip.js/doc-api.html) :P

### Run tests

```bash
grunt test # run all QUnit tests
```

### Build

```bash
grunt build # build js and CSS files
```

```bash
grunt build-js # build only js files
```

```bash
grunt build-css # build only CSS files
```

### Compile HTML

```bash
grunt html # static files that will be displayed on website
```

### Genereate docs

```bash
grunt doc # jsdoc and our documentations
```

### Bump version

```bash
grunt bumpversion --oldv=VERSION_FROM --newv=VERSION_TO # below is an example
grunt bumpversion --oldv=3.1.7 --newv=3.2.0 # change version number in src
```

```bash
grunt all # regenerate everything including docs, HTML, CSS, dist scripts
```

### Deploy website

```bash
./update_gh_pages # this will make sure to include needed data for gh-pages branch
```

## Special thanks

* Everyone who is engaged in this project.
* [Animate.css](http://daneden.github.io/animate.css/)

## Support Trip.js !

If you do love Trip.js, feel free to buy me some beers ! :beers:

My bitcoin wallet : **1KtpFtaLW52tCe2VhWxCMHmRt8Mrxqj4WB**

## Author

Chia-Lung, Chen (EragonJ)

## License

MIT
