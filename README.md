# e-json, because EJSON was already taken in npm

[![Build Status](https://travis-ci.org/primus/EJSON.png)](https://travis-ci.org/primus/EJSON)
[![NPM version](https://badge.fury.io/js/e-json.png)](http://badge.fury.io/js/e-json)

`e-json` is [Meteor EJSON](http://docs.meteor.com/#ejson) parser made compatible for Node.js and regular browser
clients. This allows use for real-time systems such as [Primus](https://github.com/primus/primus).

The API is exactly the same as the API that Meteor provides as it uses exactly
the same code. The most important API's are:

- `EJSON.clone`
- `EJSON.parse`
- `EJSON.stringify`

And some utility methods:

- `EJSON.toJSONValue`
- `EJSON.fromJSONValue`
- `EJSON.isBinary`
- `EJSON.newBinary`
- `EJSON.equals`

### License

This module is licensed under MIT. Same as Meteor.js is.
