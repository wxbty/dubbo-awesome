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
# Warmup Iteration   1: 1.752 ops/ms
Iteration   1: 6.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.582 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.866 ops/ms
Iteration   1: 11.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.422 ops/ms


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
# Warmup Iteration   1: 5.639 ops/ms
Iteration   1: 13.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.007 ops/ms


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
# Warmup Iteration   1: 4.497 ops/ms
Iteration   1: 6.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  6.983 ops/ms


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
# Warmup Iteration   1: 3.834 ±(99.9%) 0.107 ms/op
Iteration   1: 2.152 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.152 ms/op


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
# Warmup Iteration   1: 3.211 ±(99.9%) 0.057 ms/op
Iteration   1: 1.703 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.703 ms/op


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
# Warmup Iteration   1: 3.394 ±(99.9%) 0.075 ms/op
Iteration   1: 1.976 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.976 ms/op


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
# Warmup Iteration   1: 5.026 ±(99.9%) 0.111 ms/op
Iteration   1: 3.518 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.518 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.446 ±(99.9%) 0.082 ms/op
Iteration   1: 2.205 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   2.036 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   2.893 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  31.130 ms/op
                 createUser·p0.9999: 31.261 ms/op
                 createUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14695
  mean =      2.205 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12576 
    [ 2.500,  5.000) = 1925 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.893 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     31.130 ms/op
     p(99.9900) =     31.261 ms/op
     p(99.9990) =     31.261 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.072 ms/op
Iteration   1: 1.960 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.418 ms/op
                 existUser·p0.50:   1.849 ms/op
                 existUser·p0.90:   2.486 ms/op
                 existUser·p0.95:   2.744 ms/op
                 existUser·p0.99:   3.820 ms/op
                 existUser·p0.999:  17.269 ms/op
                 existUser·p0.9999: 17.772 ms/op
                 existUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16419
  mean =      1.960 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 820 
    [ 1.250,  2.500) = 14026 
    [ 2.500,  3.750) = 1391 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      3.820 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     17.772 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 3.288 ±(99.9%) 0.081 ms/op
Iteration   1: 2.089 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.442 ms/op
                 getUser·p0.50:   2.046 ms/op
                 getUser·p0.90:   2.585 ms/op
                 getUser·p0.95:   2.777 ms/op
                 getUser·p0.99:   4.075 ms/op
                 getUser·p0.999:  11.246 ms/op
                 getUser·p0.9999: 11.345 ms/op
                 getUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15306
  mean =      2.089 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 522 
    [ 1.250,  2.500) = 12753 
    [ 2.500,  3.750) = 1865 
    [ 3.750,  5.000) = 88 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      2.046 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      4.075 ms/op
     p(99.9000) =     11.246 ms/op
     p(99.9900) =     11.345 ms/op
     p(99.9990) =     11.354 ms/op
     p(99.9999) =     11.354 ms/op
    p(100.0000) =     11.354 ms/op


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
# Warmup Iteration   1: 5.020 ±(99.9%) 0.314 ms/op
Iteration   1: 3.438 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.441 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.302 ms/op
                 listUser·p0.99:   8.040 ms/op
                 listUser·p0.999:  16.329 ms/op
                 listUser·p0.9999: 16.581 ms/op
                 listUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9356
  mean =      3.438 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1502 
    [ 2.500,  3.750) = 4930 
    [ 3.750,  5.000) = 2688 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.302 ms/op
     p(99.0000) =      8.040 ms/op
     p(99.9000) =     16.329 ms/op
     p(99.9900) =     16.581 ms/op
     p(99.9990) =     16.581 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.582          ops/ms
ClientSimple.existUser                       thrpt         11.422          ops/ms
ClientSimple.getUser                         thrpt         13.007          ops/ms
ClientSimple.listUser                        thrpt          6.983          ops/ms
ClientSimple.createUser                       avgt          2.152           ms/op
ClientSimple.existUser                        avgt          1.703           ms/op
ClientSimple.getUser                          avgt          1.976           ms/op
ClientSimple.listUser                         avgt          3.518           ms/op
ClientSimple.createUser                     sample  14695   2.205 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.652           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.036           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.893           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.808           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.130           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.261           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.261           ms/op
ClientSimple.existUser                      sample  16419   1.960 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.418           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.849           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.744           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.820           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.269           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.772           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.793           ms/op
ClientSimple.getUser                        sample  15306   2.089 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.442           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.046           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.075           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.246           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.345           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.354           ms/op
ClientSimple.listUser                       sample   9356   3.438 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.384           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.441           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.071           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.302           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.040           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.329           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.581           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.581           ms/op

Benchmark result is saved to 1719771024638.json
