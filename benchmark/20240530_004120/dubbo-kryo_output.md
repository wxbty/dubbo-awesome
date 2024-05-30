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
# Warmup Iteration   1: 2.014 ops/ms
Iteration   1: 6.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.710 ops/ms


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
# Warmup Iteration   1: 6.823 ops/ms
Iteration   1: 11.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.066 ops/ms


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
# Warmup Iteration   1: 5.630 ops/ms
Iteration   1: 12.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.605 ops/ms


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
# Warmup Iteration   1: 5.828 ops/ms
Iteration   1: 8.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.049 ops/ms


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.075 ms/op
Iteration   1: 1.982 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.982 ms/op


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
# Warmup Iteration   1: 3.105 ±(99.9%) 0.046 ms/op
Iteration   1: 1.849 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.849 ms/op


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
Iteration   1: 2.070 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.070 ms/op


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
# Warmup Iteration   1: 4.328 ±(99.9%) 0.089 ms/op
Iteration   1: 3.290 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.290 ms/op


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
# Warmup Iteration   1: 3.630 ±(99.9%) 0.101 ms/op
Iteration   1: 2.163 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   1.931 ms/op
                 createUser·p0.90:   2.683 ms/op
                 createUser·p0.95:   2.966 ms/op
                 createUser·p0.99:   6.448 ms/op
                 createUser·p0.999:  14.893 ms/op
                 createUser·p0.9999: 17.498 ms/op
                 createUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14784
  mean =      2.163 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 20 
    [ 1.250,  2.500) = 12377 
    [ 2.500,  3.750) = 2114 
    [ 3.750,  5.000) = 84 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      6.448 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     17.498 ms/op
     p(99.9990) =     17.498 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 3.367 ±(99.9%) 0.094 ms/op
Iteration   1: 2.044 ±(99.9%) 0.041 ms/op
                 existUser·p0.00:   0.293 ms/op
                 existUser·p0.50:   1.866 ms/op
                 existUser·p0.90:   2.519 ms/op
                 existUser·p0.95:   2.888 ms/op
                 existUser·p0.99:   5.790 ms/op
                 existUser·p0.999:  33.173 ms/op
                 existUser·p0.9999: 35.438 ms/op
                 existUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15626
  mean =      2.044 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13996 
    [ 2.500,  5.000) = 1369 
    [ 5.000,  7.500) = 147 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.293 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      5.790 ms/op
     p(99.9000) =     33.173 ms/op
     p(99.9900) =     35.438 ms/op
     p(99.9990) =     36.176 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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
# Warmup Iteration   1: 3.580 ±(99.9%) 0.080 ms/op
Iteration   1: 2.353 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.570 ms/op
                 getUser·p0.50:   2.359 ms/op
                 getUser·p0.90:   2.941 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.913 ms/op
                 getUser·p0.999:  12.911 ms/op
                 getUser·p0.9999: 13.101 ms/op
                 getUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13655
  mean =      2.353 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 7983 
    [ 2.500,  3.750) = 5420 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 0 
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
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.359 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.913 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     13.101 ms/op
     p(99.9990) =     13.107 ms/op
     p(99.9999) =     13.107 ms/op
    p(100.0000) =     13.107 ms/op


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
# Warmup Iteration   1: 4.843 ±(99.9%) 0.140 ms/op
Iteration   1: 3.259 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   6.128 ms/op
                 listUser·p0.999:  13.733 ms/op
                 listUser·p0.9999: 14.533 ms/op
                 listUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9794
  mean =      3.259 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 845 
    [ 2.500,  3.750) = 6631 
    [ 3.750,  5.000) = 1980 
    [ 5.000,  6.250) = 253 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     13.733 ms/op
     p(99.9900) =     14.533 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.710          ops/ms
ClientSimple.existUser                       thrpt         11.066          ops/ms
ClientSimple.getUser                         thrpt         12.605          ops/ms
ClientSimple.listUser                        thrpt          8.049          ops/ms
ClientSimple.createUser                       avgt          1.982           ms/op
ClientSimple.existUser                        avgt          1.849           ms/op
ClientSimple.getUser                          avgt          2.070           ms/op
ClientSimple.listUser                         avgt          3.290           ms/op
ClientSimple.createUser                     sample  14784   2.163 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.001           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.931           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.683           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.966           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.448           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.893           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.498           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.498           ms/op
ClientSimple.existUser                      sample  15626   2.044 ± 0.041   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.293           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.866           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.888           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.790           ms/op
ClientSimple.existUser:existUser·p0.999     sample         33.173           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         35.438           ms/op
ClientSimple.existUser:existUser·p1.00      sample         36.176           ms/op
ClientSimple.getUser                        sample  13655   2.353 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.570           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.359           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.941           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.080           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.913           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.911           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.101           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.107           ms/op
ClientSimple.listUser                       sample   9794   3.259 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.147           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.925           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.128           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.733           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.533           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.533           ms/op

Benchmark result is saved to 1717029414923.json
