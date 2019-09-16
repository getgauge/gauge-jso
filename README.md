# Gauge-JSO

This project is an true offline installable variation of [Gauge-JS](https://github.com/getgauge/gauge-js) runner. This is based on [pure js](https://github.com/grpc/grpc-node/blob/master/packages/grpc-js/README.md) implementation of GRPC.
## Getting started

### Pre-requisite

- [Gauge](https://gauge.org/index.html)


#### Build from Source
The plugin is authored in [Javascript](https://en.wikipedia.org/wiki/JavaScript).
Gauge is authored in golang. These are independent processes talking to each other over TCP on port GAUGE_INTERNAL_PORT (env variable) using [Protobuf](https://github.com/getgauge/gauge-proto).

##### Pre-Requisites
* [Node.js](https://nodejs.org/en/) - Version > 8
* [Npm](https://www.npmjs.com/get-npm)

##### Compiling
```
npm install
```

##### Run tests:
```
npm test
```

##### Installing from source
```
npm run installPlugin
```

##### Create package
```
npm run package
```

## Copyright

Copyright 2018 ThoughtWorks, Inc.
