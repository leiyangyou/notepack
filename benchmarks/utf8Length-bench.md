```
$ node utf8Length-bench.js
+-------------------+--------------------+--------------------+--------------------+-------------------+
|                   │ 8                  │ 16                 │ 32                 │ 64                |
+-------------------+--------------------+--------------------+--------------------+-------------------+
| utf8Length        │ 29,518,061 ops/sec │ 18,848,201 ops/sec │ 6,824,132 ops/sec  │ 3,580,518 ops/sec |
+-------------------+--------------------+--------------------+--------------------+-------------------+
| buffer.byteLength │ 13,974,463 ops/sec │ 13,467,664 ops/sec │ 11,604,155 ops/sec │ 9,450,807 ops/sec |
+-------------------+--------------------+--------------------+--------------------+-------------------+
```