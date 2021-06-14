# Yaegi Benchmark for Reva

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