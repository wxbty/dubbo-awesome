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
# Warmup Iteration   1: 1.430 ops/ms
Iteration   1: 6.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.651 ops/ms


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
# Warmup Iteration   1: 6.327 ops/ms
Iteration   1: 12.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.611 ops/ms


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
# Warmup Iteration   1: 5.589 ops/ms
Iteration   1: 12.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.257 ops/ms


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
# Warmup Iteration   1: 5.190 ops/ms
Iteration   1: 7.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.933 ops/ms


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
# Warmup Iteration   1: 3.708 ±(99.9%) 0.082 ms/op
Iteration   1: 2.080 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.080 ms/op


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
# Warmup Iteration   1: 3.182 ±(99.9%) 0.054 ms/op
Iteration   1: 1.914 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.914 ms/op


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
# Warmup Iteration   1: 3.498 ±(99.9%) 0.063 ms/op
Iteration   1: 1.913 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.913 ms/op


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
# Warmup Iteration   1: 4.780 ±(99.9%) 0.114 ms/op
Iteration   1: 3.325 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.325 ms/op


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
# Warmup Iteration   1: 3.606 ±(99.9%) 0.081 ms/op
Iteration   1: 2.289 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.489 ms/op
                 createUser·p0.50:   2.109 ms/op
                 createUser·p0.90:   2.765 ms/op
                 createUser·p0.95:   3.342 ms/op
                 createUser·p0.99:   6.057 ms/op
                 createUser·p0.999:  18.119 ms/op
                 createUser·p0.9999: 19.011 ms/op
                 createUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14064
  mean =      2.289 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 148 
    [ 1.250,  2.500) = 10977 
    [ 2.500,  3.750) = 2513 
    [ 3.750,  5.000) = 232 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.489 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      3.342 ms/op
     p(99.0000) =      6.057 ms/op
     p(99.9000) =     18.119 ms/op
     p(99.9900) =     19.011 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 3.179 ±(99.9%) 0.081 ms/op
Iteration   1: 2.025 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.553 ms/op
                 existUser·p0.50:   1.884 ms/op
                 existUser·p0.90:   2.609 ms/op
                 existUser·p0.95:   2.912 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  18.292 ms/op
                 existUser·p0.9999: 18.602 ms/op
                 existUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15782
  mean =      2.025 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 412 
    [ 1.250,  2.500) = 13298 
    [ 2.500,  3.750) = 1841 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      4.051 ms/op
     p(99.9000) =     18.292 ms/op
     p(99.9900) =     18.602 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.398 ±(99.9%) 0.091 ms/op
Iteration   1: 2.178 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.271 ms/op
                 getUser·p0.50:   2.060 ms/op
                 getUser·p0.90:   2.818 ms/op
                 getUser·p0.95:   3.035 ms/op
                 getUser·p0.99:   5.112 ms/op
                 getUser·p0.999:  17.530 ms/op
                 getUser·p0.9999: 18.271 ms/op
                 getUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14671
  mean =      2.178 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 286 
    [ 1.250,  2.500) = 11157 
    [ 2.500,  3.750) = 2999 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 87 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.271 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      5.112 ms/op
     p(99.9000) =     17.530 ms/op
     p(99.9900) =     18.271 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 4.274 ±(99.9%) 0.119 ms/op
Iteration   1: 3.089 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   2.748 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.336 ms/op
                 listUser·p0.99:   7.116 ms/op
                 listUser·p0.999:  16.760 ms/op
                 listUser·p0.9999: 17.236 ms/op
                 listUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10353
  mean =      3.089 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2554 
    [ 2.500,  3.750) = 6345 
    [ 3.750,  5.000) = 1175 
    [ 5.000,  6.250) = 135 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      2.748 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.336 ms/op
     p(99.0000) =      7.116 ms/op
     p(99.9000) =     16.760 ms/op
     p(99.9900) =     17.236 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.651          ops/ms
ClientSimple.existUser                       thrpt         12.611          ops/ms
ClientSimple.getUser                         thrpt         12.257          ops/ms
ClientSimple.listUser                        thrpt          7.933          ops/ms
ClientSimple.createUser                       avgt          2.080           ms/op
ClientSimple.existUser                        avgt          1.914           ms/op
ClientSimple.getUser                          avgt          1.913           ms/op
ClientSimple.listUser                         avgt          3.325           ms/op
ClientSimple.createUser                     sample  14064   2.289 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.489           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.109           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.342           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.057           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.119           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.011           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.464           ms/op
ClientSimple.existUser                      sample  15782   2.025 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.553           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.884           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.609           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.912           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.051           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.292           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.602           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.678           ms/op
ClientSimple.getUser                        sample  14671   2.178 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.271           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.060           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.818           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.035           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.112           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.530           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.271           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.317           ms/op
ClientSimple.listUser                       sample  10353   3.089 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.575           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.748           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.899           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.336           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.116           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.760           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.236           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.236           ms/op

Benchmark result is saved to 1719535071599.json
