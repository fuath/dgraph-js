# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Wrapper classes for certain proto classes to simplify the api and avoid repetitive
  serialization/deserialization code
- Add `DgraphClientStub#close` to close the grpc client associated with `DgraphClientStub`
- Add `DgraphClientStub#grpcClient` to return the grpc client associated with
  `DgraphClientStub`
- Add `DgraphClientStub#waitForReady` to provide a promisified version of
  `grpc.Client#waitForReady`

## [1.0.0] - 2017-12-20

- Fully compatible with Dgraph v1.0

[Unreleased]: https://github.com/dgraph-io/dgraph-js/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/dgraph-io/dgraph-js/tree/v1.0.0