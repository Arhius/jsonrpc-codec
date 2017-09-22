# JSON-RPC 2.0 [![GoDoc](https://godoc.org/github.com/Arhius/jsonrpc-codec/jsonrpc1?status.svg)](http://godoc.org/github.com/Arhius/jsonrpc-codec/jsonrpc1) [![Build Status](https://travis-ci.org/Arhius/jsonrpc-codec.svg)](https://travis-ci.org/Arhius/jsonrpc-codec) [![Coverage Status](https://coveralls.io/repos/Arhius/jsonrpc-codec/badge.svg?branch=master&service=github)](https://coveralls.io/github/Arhius/jsonrpc-codec?branch=master)

This package is copy of https://github.com/powerman/rpc-codec jsonrpc2 package with few modification

jsonrpc1 is a codec for net/rpc.

Implements [JSON-RPC 1.0](http://www.jsonrpc.org/specification) and
[JSON-RPC 1.0 Transport: HTTP](http://www.simple-is-better.org/json-rpc/transport_http.html)
specifications with following limitations:

- Client: Batch Request not supported.
- HTTP Client&Server: Pipelined Requests/Responses not supported.
- HTTP Client&Server: GET Request not supported.

## Installation

```sh
go get github.com/Arhius/jsonrpc-codec/...
```
