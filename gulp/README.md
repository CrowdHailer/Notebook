# Gulp

### Setup

- Requires node, best used with npm, [instructions for linux](https://github.com/CrowdHailer/Almighty/blob/master/installing%20node%20and%20npm.md)
- `npm install --save gulp`
- Create basic gulpfile.js in root

```js
var gulp = require('gulp')
var requireDir = require('require-dir');

// Require all tasks as separate directory files
var dir = requireDir('./tasks');

gulp.task('hello', function() {
  console.log('Hello!')
});
```

### Examples
- useful but old [gist](https://gist.github.com/mikaelbr/8425025)
- large example [gulpfile](https://github.com/greypants/gulp-starter)

### Plugins
Gulp recommends using node modules where possible. There is a [blacklist](https://github.com/gulpjs/plugins/blob/master/src/blackList.json) of plugins that define behaviour easily available from node modules

##### SASS Compilation
Example of sass compilation file [link](http://www.mikestreety.co.uk/blog/a-simple-sass-compilation-gulpfilejs)
