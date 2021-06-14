# Yaegi Benchmark for Reva

# How to run the benchmarks?

1. First, get the plugin code:
```
go get github.com/jimil749/reva-yaegi-benchmark
```
This will get the following code in your $GOPATH. It is **important**, that you have this code in your GOPATH because yaegi searches for plugins in GOPATH.

2. That's it, after fetching the plugin code (this repo) in your go path, you can run benchmarks, which are located [here](https://github.com/jimil749/reva-plugin-benchmark)

**Note**: If you get an import error, make sure you add the correct GOPATH in [here](https://github.com/jimil749/reva-plugin-benchmark/blob/main/main_test.go#L32)

# Benchmarks

```
goos: linux
goarch: amd64
pkg: github.com/jimil749/reva-plugin-benchmark
cpu: Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz
BenchmarkYaegi/GetUser-4         	  294484	      3920 ns/op
BenchmarkYaegi/GetUserByClaim-4  	  275185	      4348 ns/op
BenchmarkYaegi/GetUserGroups-4   	  207049	      5597 ns/op
BenchmarkYaegi/FindUser-4        	   41671	     28621 ns/op
PASS
ok  	github.com/jimil749/reva-plugin-benchmark	5.164s

```