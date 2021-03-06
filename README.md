# Performance Lab

JavaScript performance tests for Handsontable (http://handsontable.github.io/performance-lab/benchmark/)

## Install

Install dependencies via [NPM](http://npmjs.com/)

```sh
$ npm install
```

and [Bower](http://bower.io/)

```sh
$ bower install
```

## Example

To run performance tests execute script

```sh
$ ./bin/hot-perf
```

or 

```sh
$ npm test
```

Once completed you can view generated tests report in `benchmark/results` directory. You can compare them in our 
benchmark viewer at `benchmark/index.html`.

## Usage

##### ```> ./bin/hot-perf```

Run tests

Arguments:
- ```--hot-branch``` - Select version of Handsontable to test or branch name from Handsontable repository.
- ```--gen-map-file``` - Regenerate `results/map.json` file which contains all available generated report paths.
- ```--server``` - Run local HTTP server.

## License

[MIT License](http://opensource.org/licenses/MIT)
