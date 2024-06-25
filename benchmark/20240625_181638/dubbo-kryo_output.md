# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.650 ops/ms
Iteration   1: 6.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.805 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.685 ops/ms
Iteration   1: 11.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.987 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.257 ops/ms
Iteration   1: 13.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.021 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.585 ops/ms
Iteration   1: 8.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.796 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ±(99.9%) 0.064 ms/op
Iteration   1: 1.893 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.893 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.003 ±(99.9%) 0.050 ms/op
Iteration   1: 1.722 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.722 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.384 ±(99.9%) 0.055 ms/op
Iteration   1: 2.143 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.143 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.160 ±(99.9%) 0.093 ms/op
Iteration   1: 3.889 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.889 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.425 ±(99.9%) 0.091 ms/op
Iteration   1: 1.990 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.624 ms/op
                 createUser·p0.50:   1.849 ms/op
                 createUser·p0.90:   2.321 ms/op
                 createUser·p0.95:   2.654 ms/op
                 createUser·p0.99:   4.879 ms/op
                 createUser·p0.999:  17.957 ms/op
                 createUser·p0.9999: 18.900 ms/op
                 createUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16443
  mean =      1.990 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 351 
    [ 1.250,  2.500) = 14914 
    [ 2.500,  3.750) = 881 
    [ 3.750,  5.000) = 138 
    [ 5.000,  6.250) = 88 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.321 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      4.879 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     18.900 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.938 ±(99.9%) 0.067 ms/op
Iteration   1: 1.858 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   1.747 ms/op
                 existUser·p0.90:   2.232 ms/op
                 existUser·p0.95:   2.404 ms/op
                 existUser·p0.99:   3.483 ms/op
                 existUser·p0.999:  12.200 ms/op
                 existUser·p0.9999: 12.479 ms/op
                 existUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17353
  mean =      1.858 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 16703 
    [ 2.500,  3.750) = 391 
    [ 3.750,  5.000) = 30 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.232 ms/op
     p(95.0000) =      2.404 ms/op
     p(99.0000) =      3.483 ms/op
     p(99.9000) =     12.200 ms/op
     p(99.9900) =     12.479 ms/op
     p(99.9990) =     12.599 ms/op
     p(99.9999) =     12.599 ms/op
    p(100.0000) =     12.599 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.472 ±(99.9%) 0.114 ms/op
Iteration   1: 2.089 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   1.958 ms/op
                 getUser·p0.90:   2.662 ms/op
                 getUser·p0.95:   2.957 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  13.056 ms/op
                 getUser·p0.9999: 13.947 ms/op
                 getUser·p1.00:   14.008 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15372
  mean =      2.089 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 12920 
    [ 2.500,  3.750) = 2228 
    [ 3.750,  5.000) = 58 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.957 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =     13.056 ms/op
     p(99.9900) =     13.947 ms/op
     p(99.9990) =     14.008 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.210 ±(99.9%) 0.183 ms/op
Iteration   1: 3.511 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   0.701 ms/op
                 listUser·p0.50:   3.432 ms/op
                 listUser·p0.90:   4.261 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  23.000 ms/op
                 listUser·p0.9999: 23.364 ms/op
                 listUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9098
  mean =      3.511 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 275 
    [ 2.500,  5.000) = 8678 
    [ 5.000,  7.500) = 112 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.261 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     23.000 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     23.364 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.805          ops/ms
ClientSimple.existUser                       thrpt         11.987          ops/ms
ClientSimple.getUser                         thrpt         13.021          ops/ms
ClientSimple.listUser                        thrpt          8.796          ops/ms
ClientSimple.createUser                       avgt          1.893           ms/op
ClientSimple.existUser                        avgt          1.722           ms/op
ClientSimple.getUser                          avgt          2.143           ms/op
ClientSimple.listUser                         avgt          3.889           ms/op
ClientSimple.createUser                     sample  16443   1.990 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.624           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.849           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.321           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.654           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.879           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.957           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.900           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.005           ms/op
ClientSimple.existUser                      sample  17353   1.858 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.573           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.747           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.232           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.483           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.200           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.479           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.599           ms/op
ClientSimple.getUser                        sample  15372   2.089 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.696           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.958           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.662           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.957           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.678           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.056           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.947           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.008           ms/op
ClientSimple.listUser                       sample   9098   3.511 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.701           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.432           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.261           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.423           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.000           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.364           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.364           ms/op

Benchmark result is saved to 1719339141209.json
