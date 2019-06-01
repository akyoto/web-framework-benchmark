# Web Framework Benchmark

## Results

```text
BenchmarkAeroStatic-12            100000             16643 ns/op             700 B/op          0 allocs/op
BenchmarkAeroGitHubAPI-12          50000             27487 ns/op            1409 B/op          0 allocs/op
BenchmarkAeroGplusAPI-12         1000000              1390 ns/op              69 B/op          0 allocs/op
BenchmarkAeroParseAPI-12          500000              2558 ns/op             138 B/op          0 allocs/op

BenchmarkEchoStatic-12             50000             30702 ns/op            1950 B/op        157 allocs/op
BenchmarkEchoGitHubAPI-12          30000             45431 ns/op            2782 B/op        203 allocs/op
BenchmarkEchoGplusAPI-12          500000              2500 ns/op             173 B/op         13 allocs/op
BenchmarkEchoParseAPI-12          300000              4234 ns/op             323 B/op         26 allocs/op

BenchmarkGinStatic-12              50000             37885 ns/op            8231 B/op        157 allocs/op
BenchmarkGinGitHubAPI-12           30000             55092 ns/op           10903 B/op        203 allocs/op
BenchmarkGinGplusAPI-12           500000              3059 ns/op             693 B/op         13 allocs/op
BenchmarkGinParseAPI-12           300000              5687 ns/op            1363 B/op         26 allocs/op
```

## Installation

- `go get github.com/akyoto/web-framework-benchmark`

## Running Benchmark

```sh
go test -bench=.
```