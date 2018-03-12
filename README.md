"BigTest" SQL Logic Test Suite
---


This repository contains an extensive test suite of SQL logic
tests. To run the bigtests on CockroachDB, clone this repository using
`go get`, and then in the main CockroachDB repository, run:

`make testlogic TESTFLAGS="-bigtest -test.v"`
