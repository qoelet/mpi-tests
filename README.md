# MPI tests

Test programs for a small XU4 cluster.

```shell
$ cat nodes
10.10.10.2:2
10.10.10.3:3
10.10.10.4:2

$ mpiexec -f ~/nodes -n 6 ./cpi
Process 5 of 6 is on san
Process 0 of 6 is on ichi
Process 3 of 6 is on ni
Process 1 of 6 is on ichi
Process 4 of 6 is on ni
Process 2 of 6 is on ni
pi is approximately 3.1415926544231243, Error is 0.0000000008333312
wall clock time = 0.006851
```
