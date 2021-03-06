![Ionic Rocket](https://pbs.twimg.com/media/BkdKf_PCAAE8-wU.png:large "Ionic Rocket")

# Ionic Rocket

The best solution to bootstrap your HTML5 Mobile Application, created by [@yrezgui](https://github.com/yrezgui).

Ionic Rocket is a collection of tools for building easily your HTML5 mobile application from prototyping to production. It's a bunch of opensource libraries and frameworks. It is recommanded to use it on Unix systems (Linux, Mac OS, etc.) but it works on every platform supported by [@NodeJS](https://github.com/joyent/node).

You can follow me on Twitter for any questions: [@yrezgui](https://twitter.com/yrezgui).

Ionic Rocket is built on these projects :


1. [Ionic Framework](https://github.com/driftyco/ionic)
2. [AngularJS](https://github.com/angular/angular.js)
3. [Cordova](https://github.com/apache/cordova-cli)
4. [Sass](https://github.com/less/less.js)
5. [Jade](https://github.com/visionmedia/jade)
6. [Gulp](https://github.com/gulpjs/gulp)
7. [NodeJS](https://github.com/joyent/node)
8. [NPM](https://github.com/npm/npm)
9. [Bower](https://github.com/bower/bower)

## Getting started
Run these commands in your terminal in the directory of the cloned repository:

```
npm install
bower install
```

If you don't have Gulp already installed, execute this command :
```
npm install -g gulp
```

And finally this command to have your automatic build:
```
gulp watch
```

You need a HTTP server to serve your files. I will certainly add an express instance soon. For now, you can use this command (which is useful for a quick HTTP server) :
```
python -m SimpleHTTPServer
```
Don't forget to run it in the root folder of Ionic Rocket. The watch task clean at first the **www** folder and it crashes python server if you loaded from there.

## Contributing

Fork the project, create a pull request and in your commit need to be like that :

```
(#idOfIssue) Simple description

More details. This line is optionnal.

```

If there is no issue related to your commit, create one first. It will be better to understand the goal of your work.
