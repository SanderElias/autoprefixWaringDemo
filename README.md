# TestAutoprefixer

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.1.

The only purpose of this repo is to demonstrate an autoprefix warning during build.
to fix this, un-comment the last to lines in `src/browserslist`, and restart `yarn start`.

turns out, the browserlist is cached in memory during watch mode, so when you update it, you need to restart the cli watch mode.
