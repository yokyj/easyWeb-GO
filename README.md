# easyWeb-GO

## install

```
git clone https://github.com/yokyj/easyWeb-GO.git
cd easyWeb-GO
go run server.go

```

## Apache test

```
Server Software:        
Server Hostname:        localhost
Server Port:            8080

Document Path:          /login
Document Length:        282 bytes

Concurrency Level:      100
Time taken for tests:   0.393 seconds
Complete requests:      1000
Failed requests:        0
Total transferred:      399000 bytes
HTML transferred:       282000 bytes
Requests per second:    2542.04 [#/sec] (mean)
Time per request:       39.338 [ms] (mean)
Time per request:       0.393 [ms] (mean, across all concurrent requests)
Transfer rate:          990.50 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    1   1.7      0       7
Processing:     3   37   8.3     39      49
Waiting:        0   37   8.3     38      49
Total:          8   38   7.5     39      50

Percentage of the requests served within a certain time (ms)
  50%     39
  66%     41
  75%     43
  80%     44
  90%     45
  95%     47
  98%     49
  99%     49
 100%     50 (longest request)
```
