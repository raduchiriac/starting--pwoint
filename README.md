## Starting Pwoint

> When you are a bit sluggish, you hire leprechauns to bundle everything for you. ~ *Anonymous*

Spoiler alert: Gulp-Inject, Sass, Babel, Handlebars, ESLint, BrowserSync and Bower Injection with Wiredep

<img src="https://blog.openshift.com/wp-content/uploads/imported/yeoman-logo.png" height="100"/>

Based on the awesome Yeoman [webapp generator](https://github.com/yeoman/generator-webapp) with added functionality for Handlebars templates and automatic JS injection inside the main HTML file.

Your playground will be the `/app` folder. All frontend dependencies should be installed via **bower** using the **-S** flag.

##### Are you a first timer?
Make sure you have `bower` and `gulp-cli` installed globally.
```shell
$ npm i && bower i
```

##### During development:
```shell
$ gulp serve
```
It's when BrowserSync will watch and serve the `/.tmp` folder.

##### Move to production:
```shell
$ gulp
```
Look, everything is bundled with care inside the `/dist` folder.
