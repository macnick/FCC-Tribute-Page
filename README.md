# freeCodeCamp: Tribute

This is my tribute page for freeCodeCamp's first [basic front end project](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-projects/build-a-tribute-page) dedicated to Burt Munro, one of the most inspiring names in the speed records history. Demo is available [on codepen.io](https://codepen.io/macnick/full/POXYeg).

[![Tribute Page](/screenshot.jpg)](https://zsolti.co/fcc/tribute/)

Icons made by [Freepik](http://www.freepik.com) from [flaticon.com](https://www.flaticon.com/) and licensed by [CC 3.0 BY](http://creativecommons.org/licenses/by/3.0/).

## User Stories

- [x] I can view a tribute page with an image and text.
- [x] I can click on a link that will take me to an external website with further information on the topic.

## Tools Used

- [Gulp.js](https://github.com/gulpjs/gulp) task runner
- [Webpack](https://github.com/webpack/webpack) module bundler
- [Babel](https://github.com/babel/babel) compiler
- [ESLint](https://github.com/eslint/eslint) linter with Airbnb's [base config](https://www.npmjs.com/package/eslint-config-airbnb-base)
- [Pug](https://github.com/pugjs/pug) template engine
- [Sass](http://sass-lang.com) with [PostCSS](https://github.com/postcss/postcss)' [Autoprefixer](https://github.com/postcss/autoprefixer)
- [Particles.js](https://github.com/VincentGarreau/particles.js)

## Install and Build

You need to have `yarn` [installed](https://yarnpkg.com/lang/en/docs/install/) on your computer. (Actually, you could also use `npm` but I prefer `yarn` 👌)

#### Clone this repo

``` bash
git clone https://github.com/zsoltime/fcc-tribute.git
cd fcc-tribute
```

#### Install dependencies

``` bash
yarn install
# OR
npm install
```

#### Start dev server with browser sync

It builds HTML, CSS, and the JavaScript bundle, starts a dev server and refreshes the browser on every changes.

``` bash
yarn start
# OR
npm start
```

#### Build production bundle

It uglifies JS, minifies CSS and images, replaces references to non-optimized scripts and stylesheets in HTML files and copies everything necessary to the `dist` folder - ready to upload.

``` bash
yarn build
# OR
npm run build
```

#### Preview production build

It's the same as the build task above but it also starts a server so you can check your work.

``` bash
yarn preview
# OR
npm run preview
```
