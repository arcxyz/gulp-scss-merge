# Usage

```js
var scssMerge = require('gulp-scss-merge');

gulp.task('sass:merge', function() {
  return gulp.src('./src/scss/main.scss')
    .pipe(scssMerge('main.all.scss'))
    .pipe(gulp.dest('./src/scss/'));
});
```

# TODO

* Add unit tests
* Read files asynchronously (breaks with our setup)
* Support for SCSS multi-line @import's
* Ignore native CSS @import's
