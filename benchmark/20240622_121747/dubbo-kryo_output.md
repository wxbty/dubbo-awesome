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
# Warmup Iteration   1: 1.559 ops/ms
Iteration   1: 6.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.464 ops/ms


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
# Warmup Iteration   1: 5.805 ops/ms
Iteration   1: 11.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.939 ops/ms


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
# Warmup Iteration   1: 6.236 ops/ms
Iteration   1: 13.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.743 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.255 ops/ms
Iteration   1: 8.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.835 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.662 ±(99.9%) 0.097 ms/op
Iteration   1: 2.149 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.149 ms/op


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
# Warmup Iteration   1: 3.129 ±(99.9%) 0.059 ms/op
Iteration   1: 1.692 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.692 ms/op


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
# Warmup Iteration   1: 3.448 ±(99.9%) 0.083 ms/op
Iteration   1: 1.983 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.983 ms/op


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
# Warmup Iteration   1: 4.766 ±(99.9%) 0.117 ms/op
Iteration   1: 3.575 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.575 ms/op


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
# Warmup Iteration   1: 3.445 ±(99.9%) 0.104 ms/op
Iteration   1: 2.183 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   2.060 ms/op
                 createUser·p0.90:   2.626 ms/op
                 createUser·p0.95:   2.897 ms/op
                 createUser·p0.99:   8.119 ms/op
                 createUser·p0.999:  17.334 ms/op
                 createUser·p0.9999: 18.261 ms/op
                 createUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14892
  mean =      2.183 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 554 
    [ 1.250,  2.500) = 12050 
    [ 2.500,  3.750) = 2039 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.897 ms/op
     p(99.0000) =      8.119 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     18.261 ms/op
     p(99.9990) =     18.678 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 3.097 ±(99.9%) 0.079 ms/op
Iteration   1: 1.901 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.459 ms/op
                 existUser·p0.50:   1.821 ms/op
                 existUser·p0.90:   2.294 ms/op
                 existUser·p0.95:   2.433 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  17.111 ms/op
                 existUser·p0.9999: 17.900 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16816
  mean =      1.901 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 525 
    [ 1.250,  2.500) = 15657 
    [ 2.500,  3.750) = 452 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.459 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.433 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =     17.111 ms/op
     p(99.9900) =     17.900 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 3.387 ±(99.9%) 0.090 ms/op
Iteration   1: 2.061 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   2.001 ms/op
                 getUser·p0.90:   2.593 ms/op
                 getUser·p0.95:   2.732 ms/op
                 getUser·p0.99:   3.026 ms/op
                 getUser·p0.999:  14.008 ms/op
                 getUser·p0.9999: 14.130 ms/op
                 getUser·p1.00:   14.139 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15520
  mean =      2.061 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 211 
    [ 1.250,  2.500) = 13087 
    [ 2.500,  3.750) = 2158 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      3.026 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     14.130 ms/op
     p(99.9990) =     14.139 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


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
# Warmup Iteration   1: 4.557 ±(99.9%) 0.144 ms/op
Iteration   1: 2.990 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   2.814 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.130 ms/op
                 listUser·p0.99:   4.654 ms/op
                 listUser·p0.999:  6.586 ms/op
                 listUser·p0.9999: 7.444 ms/op
                 listUser·p1.00:   7.447 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10692
  mean =      2.990 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 29 
    [1.500, 2.000) = 88 
    [2.000, 2.500) = 514 
    [2.500, 3.000) = 7177 
    [3.000, 3.500) = 1081 
    [3.500, 4.000) = 1051 
    [4.000, 4.500) = 613 
    [4.500, 5.000) = 53 
    [5.000, 5.500) = 27 
    [5.500, 6.000) = 10 
    [6.000, 6.500) = 25 
    [6.500, 7.000) = 19 
    [7.000, 7.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.130 ms/op
     p(99.0000) =      4.654 ms/op
     p(99.9000) =      6.586 ms/op
     p(99.9900) =      7.444 ms/op
     p(99.9990) =      7.447 ms/op
     p(99.9999) =      7.447 ms/op
    p(100.0000) =      7.447 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.464          ops/ms
ClientSimple.existUser                       thrpt         11.939          ops/ms
ClientSimple.getUser                         thrpt         13.743          ops/ms
ClientSimple.listUser                        thrpt          8.835          ops/ms
ClientSimple.createUser                       avgt          2.149           ms/op
ClientSimple.existUser                        avgt          1.692           ms/op
ClientSimple.getUser                          avgt          1.983           ms/op
ClientSimple.listUser                         avgt          3.575           ms/op
ClientSimple.createUser                     sample  14892   2.183 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.642           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.060           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.626           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.897           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.119           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.334           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.261           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.678           ms/op
ClientSimple.existUser                      sample  16816   1.901 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.459           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.821           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.294           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.612           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.111           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.900           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.990           ms/op
ClientSimple.getUser                        sample  15520   2.061 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.637           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.001           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.026           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.008           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.130           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.139           ms/op
ClientSimple.listUser                       sample  10692   2.990 ± 0.018   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.079           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.814           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.822           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.130           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.654           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.586           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.444           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.447           ms/op

Benchmark result is saved to 1719058406343.json
