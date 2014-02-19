
> Prettify JavaScript with js-beautify.

## Getting Started
Install the module with: `npm install gulp-js-prettify`

## Usage

```js
var gulp = require('gulp');
var prettify = require('gulp-prettify');

gulp.task('prettify', function() {
  gulp.src('./src/foo.js')
    .pipe(prettify({collapseWhitespace: true}))
    .pipe(gulp.dest('./src')) // edit in place
});
```

See the [js-beautify docs](https://github.com/einars/js-beautify) for options.

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality.

## Authors

+ [github/mackers](https://github.com/mackers)
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License
Copyright (c) 2014 David McNamara, Jon Schlinkert
Licensed under the MIT license.
