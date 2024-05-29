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
# Warmup Iteration   1: 1.647 ops/ms
Iteration   1: 7.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.226 ops/ms


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
# Warmup Iteration   1: 6.451 ops/ms
Iteration   1: 12.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.898 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.355 ops/ms
Iteration   1: 13.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.990 ops/ms


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
# Warmup Iteration   1: 4.531 ops/ms
Iteration   1: 8.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.927 ops/ms


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
# Warmup Iteration   1: 3.943 ±(99.9%) 0.070 ms/op
Iteration   1: 2.193 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.193 ms/op


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
# Warmup Iteration   1: 3.092 ±(99.9%) 0.046 ms/op
Iteration   1: 1.826 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.826 ms/op


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
# Warmup Iteration   1: 3.443 ±(99.9%) 0.063 ms/op
Iteration   1: 2.522 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.522 ms/op


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
# Warmup Iteration   1: 4.481 ±(99.9%) 0.097 ms/op
Iteration   1: 3.336 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.336 ms/op


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
# Warmup Iteration   1: 3.478 ±(99.9%) 0.082 ms/op
Iteration   1: 2.482 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.580 ms/op
                 createUser·p0.50:   2.306 ms/op
                 createUser·p0.90:   2.916 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   13.697 ms/op
                 createUser·p0.999:  19.761 ms/op
                 createUser·p0.9999: 21.294 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12927
  mean =      2.482 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8169 
    [ 2.500,  5.000) = 4446 
    [ 5.000,  7.500) = 152 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      2.306 ms/op
     p(90.0000) =      2.916 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =     13.697 ms/op
     p(99.9000) =     19.761 ms/op
     p(99.9900) =     21.294 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 2.944 ±(99.9%) 0.070 ms/op
Iteration   1: 1.727 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.458 ms/op
                 existUser·p0.50:   1.481 ms/op
                 existUser·p0.90:   2.408 ms/op
                 existUser·p0.95:   2.650 ms/op
                 existUser·p0.99:   3.959 ms/op
                 existUser·p0.999:  25.706 ms/op
                 existUser·p0.9999: 25.995 ms/op
                 existUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18512
  mean =      1.727 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17078 
    [ 2.500,  5.000) = 1328 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      1.481 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.959 ms/op
     p(99.9000) =     25.706 ms/op
     p(99.9900) =     25.995 ms/op
     p(99.9990) =     26.051 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 3.380 ±(99.9%) 0.077 ms/op
Iteration   1: 1.931 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.467 ms/op
                 getUser·p0.50:   1.778 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.638 ms/op
                 getUser·p0.99:   3.504 ms/op
                 getUser·p0.999:  11.305 ms/op
                 getUser·p0.9999: 11.498 ms/op
                 getUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16540
  mean =      1.931 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 15049 
    [ 2.500,  3.750) = 1281 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.504 ms/op
     p(99.9000) =     11.305 ms/op
     p(99.9900) =     11.498 ms/op
     p(99.9990) =     11.616 ms/op
     p(99.9999) =     11.616 ms/op
    p(100.0000) =     11.616 ms/op


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
# Warmup Iteration   1: 5.533 ±(99.9%) 0.305 ms/op
Iteration   1: 3.435 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   3.416 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.241 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 13.206 ms/op
                 listUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9310
  mean =      3.435 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1380 
    [ 2.500,  3.750) = 5141 
    [ 3.750,  5.000) = 2416 
    [ 5.000,  6.250) = 202 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.241 ms/op
     p(99.9000) =     12.861 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     13.206 ms/op
     p(99.9999) =     13.206 ms/op
    p(100.0000) =     13.206 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.226          ops/ms
ClientSimple.existUser                       thrpt         12.898          ops/ms
ClientSimple.getUser                         thrpt         13.990          ops/ms
ClientSimple.listUser                        thrpt          8.927          ops/ms
ClientSimple.createUser                       avgt          2.193           ms/op
ClientSimple.existUser                        avgt          1.826           ms/op
ClientSimple.getUser                          avgt          2.522           ms/op
ClientSimple.listUser                         avgt          3.336           ms/op
ClientSimple.createUser                     sample  12927   2.482 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.580           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.306           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.916           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.215           ms/op
ClientSimple.createUser:createUser·p0.99    sample         13.697           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.761           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.294           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.332           ms/op
ClientSimple.existUser                      sample  18512   1.727 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.458           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.481           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.959           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.706           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.995           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.051           ms/op
ClientSimple.getUser                        sample  16540   1.931 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.467           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.778           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.504           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.305           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.498           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.616           ms/op
ClientSimple.listUser                       sample   9310   3.435 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.079           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.416           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.858           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.241           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.861           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.206           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.206           ms/op

Benchmark result is saved to 1717006224868.json
