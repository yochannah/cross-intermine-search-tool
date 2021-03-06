# Cross InterMine Search Tool (GSoC'18)
<p align="center"><img src="https://badges.frapsoft.com/os/v1/open-source.png?v=103"> <img src="https://img.shields.io/badge/License-LGPL%202.1-blue.svg"> <img src="https://img.shields.io/david/strongloop/express.svg"></p><br>

<div style="text-align:center"><img src ="https://i.imgur.com/BWlY9De.png" /></div>
<br>

[Cross InterMine Search Tool](http://cross-intermine-search-tool.herokuapp.com/)

  InterMine is a data warehouse system for biological research. There are around 30+ instances of InterMine all around the world.
  InterMines consist of huge datasets of biological and genetic data.
  Earlier, if a person wanted to search for a gene in multiple InterMines, he/she had no other choice than going to every InterMine portal and do the search.
  It was very difficult for a person to manage so many portals simultaneously and compare the results and filter them to get the required items.
  This whole process of searching and exploring InterMine data can be simplified by the use of Cross InterMine Search Tool.

> For the project organization, please refer to https://github.com/intermine

## Development

The project has been developed using [Vue.js](https://vuejs.org). It uses InterMine APIs under the hood.
[IM.js](https://github.com/intermine/imjs) has been used for making HTTP requests to the InterMine API endpoints.

## Dependencies

Check `package.json` for getting the list of all the npm dependencies.

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# run tests
npm run test

# build documentation
npm run build-docs

# start production server at localhost:5000 after build is done
npm start

```

## Test Suite

An automated test suite has been setup for testing the application.
The test suite uses Karma and Mocha for the testing stack.
The test suite also generates a code coverage report which can be found at [tests-coverage-report](https://cross-intermine-search-tool.herokuapp.com/test-report).

## Documentation

Apart from the in-line comments in the code, documentation generated by JSDocs is available [here](https://cross-intermine-search-tool.herokuapp.com/docs).

## Deployment

The application is ready to be deployed on Heroku.
The project has been configured to run on a Node.js server.
The `dist/` folder contains the production build which is served by `server.js`.
> Note: The project works best on Google Chrome.
Use Google Chrome during development.
Mozilla Firefox needs some additional CORS configuration in order to run the application in dev mode.
Please deploy the application on InterMine server, otherwise, use a reverse proxy server to add CORS headers to HTTP requests in order to avoid CORS issues (especially on Firefox).
[CORS Anywhere](https://github.com/Rob--W/cors-anywhere) can be used for this purpose.

## Contact

You can contact the developers by opening an issue, or by email/chat.

## Screenshots

Homepage<br>
<div style="text-align:center"><img src ="https://i.imgur.com/McHZbUw.png" /></div>
<br>
Tour Mode<br>
<div style="text-align:center"><img src ="https://i.imgur.com/vXLEJyM.png" /></div>
<br>
InterMines Info<br>
<div style="text-align:center"><img src ="https://i.imgur.com/gFNL9K7.png" /></div>
<br>
Search Results<br>
<div style="text-align:center"><img src ="https://i.imgur.com/vf37xOq.png" /></div>
<br>
Result Popup<br>
<div style="text-align:center"><img src ="https://i.imgur.com/zEavrGq.png" /></div>
<br>
