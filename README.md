Queue
=====

[![Build Status](https://github.com/amirvalhalla/queue/actions/workflows/golang-ci.yml/badge.svg)](https://github.com/amirvalhalla/queue/actions/workflows/golang-ci.yml)
[![GoDoc](https://godoc.org/github.com/amirvalhalla/queue?status.svg)](https://godoc.org/github.com/amirvalhalla/queue)
[![Code of Conduct](https://img.shields.io/badge/code%20of%20conduct-active-blue.svg)]()

A fast Golang queue using a ring-buffer, based on the version suggested by Dariusz Górecki. Using this instead of other,
simpler, queue implementations (slice+append or linked list) provides substantial memory and time benefits, and fewer GC
pauses.

The v2 subfolder requires Go 1.18 or later and makes use of generics.

Follows semantic versioning using https://gopkg.in/ - import from gopkg.in/amirvalhalla/queue.v1 for guaranteed API
stability.

### Usage:

 ```
 go get -u https://github.com/amirvalhalla/queue
 ```

## Great Thanks

Enhanced and Improved (make thread-safe) from: [eapache/queue](https://github.com/eapache/queue)
