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
# Warmup Iteration   1: 1.787 ops/ms
Iteration   1: 7.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.180 ops/ms


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
# Warmup Iteration   1: 6.365 ops/ms
Iteration   1: 12.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.032 ops/ms


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
# Warmup Iteration   1: 6.094 ops/ms
Iteration   1: 13.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.303 ops/ms


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
# Warmup Iteration   1: 4.686 ops/ms
Iteration   1: 8.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.631 ops/ms


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
# Warmup Iteration   1: 3.811 ±(99.9%) 0.064 ms/op
Iteration   1: 1.881 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.881 ms/op


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
# Warmup Iteration   1: 2.992 ±(99.9%) 0.055 ms/op
Iteration   1: 1.770 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.770 ms/op


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
# Warmup Iteration   1: 3.592 ±(99.9%) 0.066 ms/op
Iteration   1: 2.191 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.191 ms/op


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
# Warmup Iteration   1: 4.570 ±(99.9%) 0.089 ms/op
Iteration   1: 3.178 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.178 ms/op


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
# Warmup Iteration   1: 3.827 ±(99.9%) 0.097 ms/op
Iteration   1: 2.090 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.437 ms/op
                 createUser·p0.50:   1.894 ms/op
                 createUser·p0.90:   2.564 ms/op
                 createUser·p0.95:   2.826 ms/op
                 createUser·p0.99:   7.881 ms/op
                 createUser·p0.999:  19.956 ms/op
                 createUser·p0.9999: 20.054 ms/op
                 createUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15391
  mean =      2.090 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13621 
    [ 2.500,  5.000) = 1481 
    [ 5.000,  7.500) = 114 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.437 ms/op
     p(50.0000) =      1.894 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      7.881 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 2.762 ±(99.9%) 0.064 ms/op
Iteration   1: 1.964 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.438 ms/op
                 existUser·p0.50:   1.946 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.630 ms/op
                 existUser·p0.99:   3.277 ms/op
                 existUser·p0.999:  10.666 ms/op
                 existUser·p0.9999: 10.732 ms/op
                 existUser·p1.00:   10.732 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16292
  mean =      1.964 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 714 
    [ 1.250,  2.500) = 14178 
    [ 2.500,  3.750) = 1333 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.438 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      3.277 ms/op
     p(99.9000) =     10.666 ms/op
     p(99.9900) =     10.732 ms/op
     p(99.9990) =     10.732 ms/op
     p(99.9999) =     10.732 ms/op
    p(100.0000) =     10.732 ms/op


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
# Warmup Iteration   1: 3.151 ±(99.9%) 0.077 ms/op
Iteration   1: 1.760 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.378 ms/op
                 getUser·p0.50:   1.655 ms/op
                 getUser·p0.90:   2.100 ms/op
                 getUser·p0.95:   2.363 ms/op
                 getUser·p0.99:   3.053 ms/op
                 getUser·p0.999:  12.170 ms/op
                 getUser·p0.9999: 12.540 ms/op
                 getUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18172
  mean =      1.760 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 239 
    [ 1.250,  2.500) = 17320 
    [ 2.500,  3.750) = 534 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.378 ms/op
     p(50.0000) =      1.655 ms/op
     p(90.0000) =      2.100 ms/op
     p(95.0000) =      2.363 ms/op
     p(99.0000) =      3.053 ms/op
     p(99.9000) =     12.170 ms/op
     p(99.9900) =     12.540 ms/op
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
# Warmup Iteration   1: 4.591 ±(99.9%) 0.122 ms/op
Iteration   1: 3.206 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.174 ms/op
                 listUser·p0.999:  19.016 ms/op
                 listUser·p0.9999: 21.004 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9937
  mean =      3.206 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 319 
    [ 2.500,  5.000) = 9474 
    [ 5.000,  7.500) = 118 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.174 ms/op
     p(99.9000) =     19.016 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.180          ops/ms
ClientSimple.existUser                       thrpt         12.032          ops/ms
ClientSimple.getUser                         thrpt         13.303          ops/ms
ClientSimple.listUser                        thrpt          8.631          ops/ms
ClientSimple.createUser                       avgt          1.881           ms/op
ClientSimple.existUser                        avgt          1.770           ms/op
ClientSimple.getUser                          avgt          2.191           ms/op
ClientSimple.listUser                         avgt          3.178           ms/op
ClientSimple.createUser                     sample  15391   2.090 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.437           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.894           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.564           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.826           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.881           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.956           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.054           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.054           ms/op
ClientSimple.existUser                      sample  16292   1.964 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.438           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.946           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.630           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.277           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.666           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.732           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.732           ms/op
ClientSimple.getUser                        sample  18172   1.760 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.378           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.655           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.100           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.363           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.053           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.170           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.540           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.567           ms/op
ClientSimple.listUser                       sample   9937   3.206 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.911           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.937           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.022           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.174           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.016           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.004           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.004           ms/op

Benchmark result is saved to 1717395132254.json
