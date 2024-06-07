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
# Warmup Iteration   1: 1.410 ops/ms
Iteration   1: 6.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.945 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.138 ops/ms
Iteration   1: 12.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.328 ops/ms


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
# Warmup Iteration   1: 5.533 ops/ms
Iteration   1: 11.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.371 ops/ms


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
# Warmup Iteration   1: 4.629 ops/ms
Iteration   1: 8.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.867 ops/ms


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.082 ms/op
Iteration   1: 2.354 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.354 ms/op


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
# Warmup Iteration   1: 3.305 ±(99.9%) 0.055 ms/op
Iteration   1: 2.005 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.005 ms/op


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
# Warmup Iteration   1: 3.185 ±(99.9%) 0.061 ms/op
Iteration   1: 2.066 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.066 ms/op


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
# Warmup Iteration   1: 5.601 ±(99.9%) 0.120 ms/op
Iteration   1: 3.541 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.541 ms/op


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
# Warmup Iteration   1: 3.603 ±(99.9%) 0.098 ms/op
Iteration   1: 2.216 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.770 ms/op
                 createUser·p0.50:   2.019 ms/op
                 createUser·p0.90:   2.671 ms/op
                 createUser·p0.95:   2.949 ms/op
                 createUser·p0.99:   5.210 ms/op
                 createUser·p0.999:  18.448 ms/op
                 createUser·p0.9999: 19.515 ms/op
                 createUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14420
  mean =      2.216 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 11878 
    [ 2.500,  3.750) = 2180 
    [ 3.750,  5.000) = 118 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      2.019 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.949 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     19.515 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 3.197 ±(99.9%) 0.071 ms/op
Iteration   1: 2.007 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   1.917 ms/op
                 existUser·p0.90:   2.503 ms/op
                 existUser·p0.95:   2.687 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  24.183 ms/op
                 existUser·p0.9999: 24.281 ms/op
                 existUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15928
  mean =      2.007 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14318 
    [ 2.500,  5.000) = 1545 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =     24.183 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     24.281 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 3.641 ±(99.9%) 0.099 ms/op
Iteration   1: 2.352 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   2.261 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.985 ms/op
                 getUser·p0.999:  12.916 ms/op
                 getUser·p0.9999: 13.695 ms/op
                 getUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13647
  mean =      2.352 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 8882 
    [ 2.500,  3.750) = 4493 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.261 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.985 ms/op
     p(99.9000) =     12.916 ms/op
     p(99.9900) =     13.695 ms/op
     p(99.9990) =     13.713 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


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
# Warmup Iteration   1: 4.873 ±(99.9%) 0.154 ms/op
Iteration   1: 3.343 ±(99.9%) 0.080 ms/op
                 listUser·p0.00:   0.847 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   12.553 ms/op
                 listUser·p0.999:  39.114 ms/op
                 listUser·p0.9999: 41.353 ms/op
                 listUser·p1.00:   41.353 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9584
  mean =      3.343 ±(99.9%) 0.080 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9317 
    [ 5.000, 10.000) = 169 
    [10.000, 15.000) = 33 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =     12.553 ms/op
     p(99.9000) =     39.114 ms/op
     p(99.9900) =     41.353 ms/op
     p(99.9990) =     41.353 ms/op
     p(99.9999) =     41.353 ms/op
    p(100.0000) =     41.353 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.945          ops/ms
ClientSimple.existUser                       thrpt         12.328          ops/ms
ClientSimple.getUser                         thrpt         11.371          ops/ms
ClientSimple.listUser                        thrpt          8.867          ops/ms
ClientSimple.createUser                       avgt          2.354           ms/op
ClientSimple.existUser                        avgt          2.005           ms/op
ClientSimple.getUser                          avgt          2.066           ms/op
ClientSimple.listUser                         avgt          3.541           ms/op
ClientSimple.createUser                     sample  14420   2.216 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.770           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.019           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.671           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.949           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.210           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.448           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.515           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.530           ms/op
ClientSimple.existUser                      sample  15928   2.007 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.564           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.917           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.503           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.687           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.465           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.183           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.281           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.281           ms/op
ClientSimple.getUser                        sample  13647   2.352 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.641           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.261           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.970           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.150           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.985           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.916           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.695           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.713           ms/op
ClientSimple.listUser                       sample   9584   3.343 ± 0.080   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.847           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.908           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.071           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.99        sample         12.553           ms/op
ClientSimple.listUser:listUser·p0.999       sample         39.114           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         41.353           ms/op
ClientSimple.listUser:listUser·p1.00        sample         41.353           ms/op

Benchmark result is saved to 1717762593792.json
