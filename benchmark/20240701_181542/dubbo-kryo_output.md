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
# Warmup Iteration   1: 1.515 ops/ms
Iteration   1: 7.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.065 ops/ms


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
# Warmup Iteration   1: 5.187 ops/ms
Iteration   1: 12.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.615 ops/ms


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
# Warmup Iteration   1: 5.709 ops/ms
Iteration   1: 12.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.350 ops/ms


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
# Warmup Iteration   1: 4.501 ops/ms
Iteration   1: 8.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.222 ops/ms


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.070 ms/op
Iteration   1: 2.231 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.231 ms/op


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.067 ms/op
Iteration   1: 1.992 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.992 ms/op


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
# Warmup Iteration   1: 3.262 ±(99.9%) 0.057 ms/op
Iteration   1: 1.904 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.904 ms/op


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
# Warmup Iteration   1: 4.624 ±(99.9%) 0.105 ms/op
Iteration   1: 3.672 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.672 ms/op


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
# Warmup Iteration   1: 3.743 ±(99.9%) 0.100 ms/op
Iteration   1: 2.278 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   1.972 ms/op
                 createUser·p0.90:   2.843 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   9.682 ms/op
                 createUser·p0.999:  37.618 ms/op
                 createUser·p0.9999: 37.853 ms/op
                 createUser·p1.00:   37.880 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14103
  mean =      2.278 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10666 
    [ 2.500,  5.000) = 3251 
    [ 5.000,  7.500) = 26 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.843 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      9.682 ms/op
     p(99.9000) =     37.618 ms/op
     p(99.9900) =     37.853 ms/op
     p(99.9990) =     37.880 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


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
# Warmup Iteration   1: 3.236 ±(99.9%) 0.089 ms/op
Iteration   1: 2.047 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   1.989 ms/op
                 existUser·p0.90:   2.547 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   4.140 ms/op
                 existUser·p0.999:  12.786 ms/op
                 existUser·p0.9999: 13.019 ms/op
                 existUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15630
  mean =      2.047 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 13565 
    [ 2.500,  3.750) = 1739 
    [ 3.750,  5.000) = 99 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.547 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      4.140 ms/op
     p(99.9000) =     12.786 ms/op
     p(99.9900) =     13.019 ms/op
     p(99.9990) =     13.074 ms/op
     p(99.9999) =     13.074 ms/op
    p(100.0000) =     13.074 ms/op


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
# Warmup Iteration   1: 3.288 ±(99.9%) 0.088 ms/op
Iteration   1: 2.033 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   1.966 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.691 ms/op
                 getUser·p0.99:   4.092 ms/op
                 getUser·p0.999:  13.963 ms/op
                 getUser·p0.9999: 14.207 ms/op
                 getUser·p1.00:   14.254 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15739
  mean =      2.033 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 594 
    [ 1.250,  2.500) = 13767 
    [ 2.500,  3.750) = 1178 
    [ 3.750,  5.000) = 89 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      4.092 ms/op
     p(99.9000) =     13.963 ms/op
     p(99.9900) =     14.207 ms/op
     p(99.9990) =     14.254 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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
# Warmup Iteration   1: 4.631 ±(99.9%) 0.138 ms/op
Iteration   1: 3.985 ±(99.9%) 0.178 ms/op
                 listUser·p0.00:   0.790 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.849 ms/op
                 listUser·p0.99:   18.015 ms/op
                 listUser·p0.999:  77.201 ms/op
                 listUser·p0.9999: 77.857 ms/op
                 listUser·p1.00:   77.857 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8021
  mean =      3.985 ±(99.9%) 0.178 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7651 
    [ 5.000, 10.000) = 262 
    [10.000, 15.000) = 3 
    [15.000, 20.000) = 34 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 4 
    [65.000, 70.000) = 4 
    [70.000, 75.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.849 ms/op
     p(99.0000) =     18.015 ms/op
     p(99.9000) =     77.201 ms/op
     p(99.9900) =     77.857 ms/op
     p(99.9990) =     77.857 ms/op
     p(99.9999) =     77.857 ms/op
    p(100.0000) =     77.857 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.065          ops/ms
ClientSimple.existUser                       thrpt         12.615          ops/ms
ClientSimple.getUser                         thrpt         12.350          ops/ms
ClientSimple.listUser                        thrpt          8.222          ops/ms
ClientSimple.createUser                       avgt          2.231           ms/op
ClientSimple.existUser                        avgt          1.992           ms/op
ClientSimple.getUser                          avgt          1.904           ms/op
ClientSimple.listUser                         avgt          3.672           ms/op
ClientSimple.createUser                     sample  14103   2.278 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.561           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.972           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.843           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.097           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.682           ms/op
ClientSimple.createUser:createUser·p0.999   sample         37.618           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.853           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.880           ms/op
ClientSimple.existUser                      sample  15630   2.047 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.931           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.989           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.547           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.140           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.786           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.019           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.074           ms/op
ClientSimple.getUser                        sample  15739   2.033 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.804           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.966           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.691           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.092           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.963           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.207           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.254           ms/op
ClientSimple.listUser                       sample   8021   3.985 ± 0.178   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.790           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.576           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.849           ms/op
ClientSimple.listUser:listUser·p0.99        sample         18.015           ms/op
ClientSimple.listUser:listUser·p0.999       sample         77.201           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         77.857           ms/op
ClientSimple.listUser:listUser·p1.00        sample         77.857           ms/op

Benchmark result is saved to 1719857488916.json
