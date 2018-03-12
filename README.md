"BigTest" SQL Logic Test Suite
---


This repository contains an extensive test suite of SQL logic
tests. To run the bigtests on CockroachDB, perform the following
steps:

1. Clone this repository using `go get`
2. In the CockroachDB repository, run `make testlogic`, and cancel the
   test run once the `logictest.test` binary is built.
3. `cd` into `pkg/sql/logictest`
4. Run `./logictest.test -bigtest -test.v`
