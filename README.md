# Startpoint for every web projects

The Sass-based starting point to web projects. Pure Sass, no Javascript.

 ***!!! I can't promise backwards compatible before version 1.0.0 !!!***


### Docs

**[https://www.rane.io/startpoint](https://www.rane.io/startpoint)**


#### Demo Site

[https://startpoint.rane.io](https://startpoint.rane.io)


#### Dependencies

No dependencies, but I recommend to use [Normalize](https://necolas.github.io/normalize.css/)


#### Author

Rane Ahonen, [Rane.io](https://www.rane.io)


#### Licenses
[MIT](https://spdx.org/licenses/MIT.html)

---

#### How to test with demo site

1. `npm install --save startpoint-sass`
1. Add to your main.sass: `@import 'node_modules/startpoint-sass/index.sass'`
1. `npm install --save-dev node-sass`
1. Copy variables from `./default.sass` to `./demo/sass/variables.sass`
1. Make some changes to `./demo/sass/variables.sass`
1. `npm run demo`
1. Open `./demo/index.html` with your browser
