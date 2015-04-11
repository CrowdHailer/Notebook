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

