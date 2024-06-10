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
# Warmup Iteration   1: 2.042 ops/ms
Iteration   1: 7.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.117 ops/ms


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
# Warmup Iteration   1: 6.586 ops/ms
Iteration   1: 12.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.755 ops/ms


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
# Warmup Iteration   1: 6.009 ops/ms
Iteration   1: 13.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.142 ops/ms


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
# Warmup Iteration   1: 5.480 ops/ms
Iteration   1: 8.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.557 ops/ms


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
# Warmup Iteration   1: 3.885 ±(99.9%) 0.068 ms/op
Iteration   1: 2.289 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.289 ms/op


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
# Warmup Iteration   1: 2.979 ±(99.9%) 0.054 ms/op
Iteration   1: 1.825 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.825 ms/op


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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.051 ms/op
Iteration   1: 1.934 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.934 ms/op


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
# Warmup Iteration   1: 5.190 ±(99.9%) 0.089 ms/op
Iteration   1: 3.489 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.489 ms/op


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
# Warmup Iteration   1: 3.821 ±(99.9%) 0.210 ms/op
Iteration   1: 2.190 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   2.030 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   2.838 ms/op
                 createUser·p0.99:   8.216 ms/op
                 createUser·p0.999:  16.151 ms/op
                 createUser·p0.9999: 16.828 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14600
  mean =      2.190 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 148 
    [ 1.250,  2.500) = 12133 
    [ 2.500,  3.750) = 1957 
    [ 3.750,  5.000) = 121 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.838 ms/op
     p(99.0000) =      8.216 ms/op
     p(99.9000) =     16.151 ms/op
     p(99.9900) =     16.828 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 3.186 ±(99.9%) 0.077 ms/op
Iteration   1: 1.838 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.404 ms/op
                 existUser·p0.50:   1.657 ms/op
                 existUser·p0.90:   2.232 ms/op
                 existUser·p0.95:   2.388 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  31.549 ms/op
                 existUser·p0.9999: 32.671 ms/op
                 existUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17402
  mean =      1.838 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16808 
    [ 2.500,  5.000) = 473 
    [ 5.000,  7.500) = 57 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      1.657 ms/op
     p(90.0000) =      2.232 ms/op
     p(95.0000) =      2.388 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =     31.549 ms/op
     p(99.9900) =     32.671 ms/op
     p(99.9990) =     32.768 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 3.255 ±(99.9%) 0.087 ms/op
Iteration   1: 2.108 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.500 ms/op
                 getUser·p0.50:   1.929 ms/op
                 getUser·p0.90:   2.765 ms/op
                 getUser·p0.95:   2.966 ms/op
                 getUser·p0.99:   3.837 ms/op
                 getUser·p0.999:  14.205 ms/op
                 getUser·p0.9999: 15.489 ms/op
                 getUser·p1.00:   15.565 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15160
  mean =      2.108 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 11542 
    [ 2.500,  3.750) = 3381 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      3.837 ms/op
     p(99.9000) =     14.205 ms/op
     p(99.9900) =     15.489 ms/op
     p(99.9990) =     15.565 ms/op
     p(99.9999) =     15.565 ms/op
    p(100.0000) =     15.565 ms/op


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
# Warmup Iteration   1: 4.796 ±(99.9%) 0.175 ms/op
Iteration   1: 3.216 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.947 ms/op
                 listUser·p0.999:  20.583 ms/op
                 listUser·p0.9999: 22.315 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9949
  mean =      3.216 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1507 
    [ 2.500,  5.000) = 8192 
    [ 5.000,  7.500) = 217 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     20.583 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.117          ops/ms
ClientSimple.existUser                       thrpt         12.755          ops/ms
ClientSimple.getUser                         thrpt         13.142          ops/ms
ClientSimple.listUser                        thrpt          8.557          ops/ms
ClientSimple.createUser                       avgt          2.289           ms/op
ClientSimple.existUser                        avgt          1.825           ms/op
ClientSimple.getUser                          avgt          1.934           ms/op
ClientSimple.listUser                         avgt          3.489           ms/op
ClientSimple.createUser                     sample  14600   2.190 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.668           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.030           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.838           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.216           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.151           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.828           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.843           ms/op
ClientSimple.existUser                      sample  17402   1.838 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.404           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.657           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.232           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.707           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.549           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         32.671           ms/op
ClientSimple.existUser:existUser·p1.00      sample         32.768           ms/op
ClientSimple.getUser                        sample  15160   2.108 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.500           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.929           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.765           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.966           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.837           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.205           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.489           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.565           ms/op
ClientSimple.listUser                       sample   9949   3.216 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.298           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.925           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.059           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.947           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.583           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.315           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.315           ms/op

Benchmark result is saved to 1717999997340.json
