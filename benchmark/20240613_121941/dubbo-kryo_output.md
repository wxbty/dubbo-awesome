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
# Warmup Iteration   1: 1.676 ops/ms
Iteration   1: 6.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.616 ops/ms


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
# Warmup Iteration   1: 5.483 ops/ms
Iteration   1: 12.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.984 ops/ms


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
# Warmup Iteration   1: 5.030 ops/ms
Iteration   1: 11.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.462 ops/ms


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
# Warmup Iteration   1: 5.189 ops/ms
Iteration   1: 9.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.498 ops/ms


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.083 ms/op
Iteration   1: 2.096 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.096 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.014 ±(99.9%) 0.044 ms/op
Iteration   1: 1.691 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.691 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.153 ±(99.9%) 0.054 ms/op
Iteration   1: 2.155 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.155 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.003 ±(99.9%) 0.113 ms/op
Iteration   1: 3.373 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.373 ms/op


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.130 ms/op
Iteration   1: 2.568 ±(99.9%) 0.065 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   2.249 ms/op
                 createUser·p0.90:   3.334 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   8.628 ms/op
                 createUser·p0.999:  39.649 ms/op
                 createUser·p0.9999: 41.344 ms/op
                 createUser·p1.00:   41.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12435
  mean =      2.568 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12249 
    [ 5.000, 10.000) = 90 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.249 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      8.628 ms/op
     p(99.9000) =     39.649 ms/op
     p(99.9900) =     41.344 ms/op
     p(99.9990) =     41.615 ms/op
     p(99.9999) =     41.615 ms/op
    p(100.0000) =     41.615 ms/op


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
# Warmup Iteration   1: 2.831 ±(99.9%) 0.068 ms/op
Iteration   1: 1.766 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   1.647 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.630 ms/op
                 existUser·p0.99:   2.941 ms/op
                 existUser·p0.999:  4.645 ms/op
                 existUser·p0.9999: 5.790 ms/op
                 existUser·p1.00:   5.923 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18093
  mean =      1.766 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 26 
    [1.000, 1.500) = 5324 
    [1.500, 2.000) = 8607 
    [2.000, 2.500) = 2487 
    [2.500, 3.000) = 1506 
    [3.000, 3.500) = 97 
    [3.500, 4.000) = 14 
    [4.000, 4.500) = 12 
    [4.500, 5.000) = 12 
    [5.000, 5.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      1.647 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      2.941 ms/op
     p(99.9000) =      4.645 ms/op
     p(99.9900) =      5.790 ms/op
     p(99.9990) =      5.923 ms/op
     p(99.9999) =      5.923 ms/op
    p(100.0000) =      5.923 ms/op


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
# Warmup Iteration   1: 3.466 ±(99.9%) 0.100 ms/op
Iteration   1: 2.213 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.414 ms/op
                 getUser·p0.50:   2.019 ms/op
                 getUser·p0.90:   2.847 ms/op
                 getUser·p0.95:   2.998 ms/op
                 getUser·p0.99:   5.059 ms/op
                 getUser·p0.999:  12.485 ms/op
                 getUser·p0.9999: 12.559 ms/op
                 getUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14538
  mean =      2.213 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 10796 
    [ 2.500,  3.750) = 3479 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.414 ms/op
     p(50.0000) =      2.019 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      2.998 ms/op
     p(99.0000) =      5.059 ms/op
     p(99.9000) =     12.485 ms/op
     p(99.9900) =     12.559 ms/op
     p(99.9990) =     12.567 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


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
# Warmup Iteration   1: 4.537 ±(99.9%) 0.132 ms/op
Iteration   1: 3.370 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   3.248 ms/op
                 listUser·p0.90:   4.048 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.758 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 15.434 ms/op
                 listUser·p1.00:   15.434 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9477
  mean =      3.370 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 612 
    [ 2.500,  3.750) = 6769 
    [ 3.750,  5.000) = 1761 
    [ 5.000,  6.250) = 153 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      4.048 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     15.434 ms/op
     p(99.9990) =     15.434 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.616          ops/ms
ClientSimple.existUser                       thrpt         12.984          ops/ms
ClientSimple.getUser                         thrpt         11.462          ops/ms
ClientSimple.listUser                        thrpt          9.498          ops/ms
ClientSimple.createUser                       avgt          2.096           ms/op
ClientSimple.existUser                        avgt          1.691           ms/op
ClientSimple.getUser                          avgt          2.155           ms/op
ClientSimple.listUser                         avgt          3.373           ms/op
ClientSimple.createUser                     sample  12435   2.568 ± 0.065   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.764           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.249           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.334           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.654           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.628           ms/op
ClientSimple.createUser:createUser·p0.999   sample         39.649           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         41.344           ms/op
ClientSimple.createUser:createUser·p1.00    sample         41.615           ms/op
ClientSimple.existUser                      sample  18093   1.766 ± 0.011   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.569           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.647           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.630           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.941           ms/op
ClientSimple.existUser:existUser·p0.999     sample          4.645           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          5.790           ms/op
ClientSimple.existUser:existUser·p1.00      sample          5.923           ms/op
ClientSimple.getUser                        sample  14538   2.213 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.414           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.019           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.847           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.998           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.059           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.485           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.559           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.567           ms/op
ClientSimple.listUser                       sample   9477   3.370 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.937           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.248           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.048           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.758           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.336           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.434           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.434           ms/op

Benchmark result is saved to 1718280914203.json
