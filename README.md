# grunt-init-myapp

Create a new WebApp files with [grunt-init][], including Bower package manager, LESS with LESSHAT3 mixins, RequireJS with r.js optimizer, jshint, livereloading.

[grunt-init]: http://gruntjs.com/project-scaffolding

## Prerequisites
This plugin requires Grunt ```0.4.x```
```
npm install -g grunt-cli
npm install -g bower
```

## Installation
```
git clone git@github.com:slinto/grunt-init-myapp.git ~/.grunt-init/myapp
```

## Usage

At the command-line, cd into an empty directory, run this command and follow the prompts.

```
grunt-init myapp
npm install && bower install
```

## Workflow

### Recomended dev workflow
Default server on localhost:9000 (including livereload)
```
grunt server
```

### Production build
In production remove ```DEV USE``` section and uncomment ```PRODUCTION USE``` html code from ```index.html``` and others ```.html``` files. Final build is in ```/dist``` folder.
```
grunt build
```

### Default task
```
grunt
```
