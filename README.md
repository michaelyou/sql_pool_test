## 测试标准库database/sql提供的连接池

```shell
$ ab -c 100 -n 1000 'http://localhost:9090/pool'
```

在数据库中通过`show processlist`可以查看数据库连接
