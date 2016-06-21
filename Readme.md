# Usage

#### If you are using the `newapp` tool

1. Run `$ newapp template <project name>`
2. Change in to your new project
3. Initialize Git `$ git init`
4. Build

#### If you are NOT using the `newapp` tool

1. Clone down this repo
2. Rename and change into the project folder
3. Remove `git` from it `$ rm -rf .git`
4. Initialize Git `$ git init`
5. Install the dependencies `$ npm install`
6. Build 


# Features

This template features a couple different tools. First it utalizes both NPM and Gulp for different tasks.

## Gulp Tasks

All tasks are listed below, but ideally you will just need to run `gulp start` and be done with it.

- `gulp start`: This is the primary task that will fire up the server and allow you to start building
- `gulp server`: This will start a Browsersync server with live-reload
- `gulp sass`: This will compile your SASS
- `gulp browserify`: This will transpile your JS from ES6 to ES5
- `gulp watch`: This will start a watcher for files

## NPM Scripts

- `npm run test`: This will launch Mocha in your terminal and run any tests
- `npm run deploy`: This will deploy your application to Surge.sh for you
- `npm run lint`: This will run ESLint on your `/src/js` folder
