# node-timelord 

NodeJS implementation of Timelord



## How to run

### Development

```sh
git clone github.com/UniversityRadioYork/node-timelord/
cd node-timelord
npm install
grunt install
bower install
grunt
# browse to localhost:8000 to see it
# any changes to files in `public/` will be compiled and the browser will automatically reload 
```

### Production

```sh
$ git clone github.com/UniversityRadioYork/node-timelord/
$ cd node-timelord
$ npm install
$ grunt install
$ bower install
$ forever start -c "npm start" ./
$ # browse to localhost:8000 to see it
$ # forever will restart the app if it crashes for any reason
```

#### To stop forever

```sh
$ forever list # to get the pid
info:    Forever processes running
data:        uid  command   script forever pid  id logfile                       uptime      
data:    [0] arxY npm start        4758    4771    /home/chris/.forever/arxY.log 0:0:2:3.667 
$ forever stop 4771
```

## Dependencies

- [express](https://github.com/strongloop/express/) - Fast, unopinionated, minimalist web framework for node. [http://expressjs.com](http://expressjs.com)
- [grunt](https://github.com/gruntjs/grunt): The JavaScript Task Runner
- [grunt-contrib-connect](https://github.com/gruntjs/grunt-contrib-connect): Start a connect web server
- [grunt-contrib-uglify](https://github.com/gruntjs/grunt-contrib-uglify): Minify files with UglifyJS
- [grunt-contrib-watch](https://github.com/gruntjs/grunt-contrib-watch): Run predefined tasks whenever watched file patterns are added, changed or deleted.
- [grunt-sass](https://github.com/sindresorhus/grunt-sass): Compile Sass to CSS using node-sass
- [grunt-wiredep](https://github.com/stephenplusplus/grunt-wiredep): Inject your Bower dependencies right into your HTML from Grunt.
- [serve-static](https://github.com/expressjs/serve-static): Serve static files

## Global Dependencies

- [grunt-cli](https://github.com/gruntjs/grunt-cli): Grunt's command line interface. [http://gruntjs.com/](http://gruntjs.com/)
- [bower](http://bower.io/): A package manager for the web
- [forever](http://github.com/foreverjs/forever) - A simple CLI tool for ensuring that a given script runs continuously (i.e. forever) [http://github.com/foreverjs/forever](http://github.com/foreverjs/forever)

## License

ISC

_Generated by [package-json-to-readme](https://github.com/zeke/package-json-to-readme)_
