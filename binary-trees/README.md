## binary trees

1. the original version 

```bash
$ go build binarytrees.go
$ ./binary-tree 18
```

2. version with profile code 

```bash
$ go build binarytrees-prof.go
$ ./binarytrees-prof -cpuprofile=cpuprofile.prof -memprofile=memprofile.mprof 18
$ go tool pprof ./binarytrees-prof cpuprofile.prof
$ go tool pprof ./binarytrees-prof memprofile.mprof
```

