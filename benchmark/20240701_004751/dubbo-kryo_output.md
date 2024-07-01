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
# Warmup Iteration   1: 1.978 ops/ms
Iteration   1: 7.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.780 ops/ms


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
# Warmup Iteration   1: 6.048 ops/ms
Iteration   1: 12.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.915 ops/ms


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
# Warmup Iteration   1: 5.590 ops/ms
Iteration   1: 12.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.749 ops/ms


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
# Warmup Iteration   1: 5.143 ops/ms
Iteration   1: 8.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.251 ops/ms


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.079 ms/op
Iteration   1: 2.140 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.140 ms/op


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
# Warmup Iteration   1: 3.351 ±(99.9%) 0.064 ms/op
Iteration   1: 1.946 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.946 ms/op


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
# Warmup Iteration   1: 3.274 ±(99.9%) 0.067 ms/op
Iteration   1: 1.956 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.956 ms/op


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
# Warmup Iteration   1: 5.020 ±(99.9%) 0.117 ms/op
Iteration   1: 3.454 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.454 ms/op


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.130 ms/op
Iteration   1: 2.243 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.486 ms/op
                 createUser·p0.50:   2.058 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   2.925 ms/op
                 createUser·p0.99:   10.591 ms/op
                 createUser·p0.999:  15.991 ms/op
                 createUser·p0.9999: 16.829 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14257
  mean =      2.243 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 199 
    [ 1.250,  2.500) = 12051 
    [ 2.500,  3.750) = 1620 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      2.058 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =     10.591 ms/op
     p(99.9000) =     15.991 ms/op
     p(99.9900) =     16.829 ms/op
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
# Warmup Iteration   1: 2.927 ±(99.9%) 0.062 ms/op
Iteration   1: 1.859 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   1.761 ms/op
                 existUser·p0.90:   2.150 ms/op
                 existUser·p0.95:   2.314 ms/op
                 existUser·p0.99:   2.900 ms/op
                 existUser·p0.999:  15.516 ms/op
                 existUser·p0.9999: 16.182 ms/op
                 existUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17246
  mean =      1.859 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 16702 
    [ 2.500,  3.750) = 342 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.150 ms/op
     p(95.0000) =      2.314 ms/op
     p(99.0000) =      2.900 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     16.182 ms/op
     p(99.9990) =     16.253 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


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
# Warmup Iteration   1: 3.432 ±(99.9%) 0.081 ms/op
Iteration   1: 2.065 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.519 ms/op
                 getUser·p0.50:   1.913 ms/op
                 getUser·p0.90:   2.548 ms/op
                 getUser·p0.95:   2.801 ms/op
                 getUser·p0.99:   4.810 ms/op
                 getUser·p0.999:  12.927 ms/op
                 getUser·p0.9999: 13.971 ms/op
                 getUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15483
  mean =      2.065 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 13577 
    [ 2.500,  3.750) = 1653 
    [ 3.750,  5.000) = 58 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.801 ms/op
     p(99.0000) =      4.810 ms/op
     p(99.9000) =     12.927 ms/op
     p(99.9900) =     13.971 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 4.455 ±(99.9%) 0.152 ms/op
Iteration   1: 3.607 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   5.284 ms/op
                 listUser·p0.999:  6.979 ms/op
                 listUser·p0.9999: 7.668 ms/op
                 listUser·p1.00:   7.668 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8873
  mean =      3.607 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 22 
    [1.500, 2.000) = 219 
    [2.000, 2.500) = 577 
    [2.500, 3.000) = 1534 
    [3.000, 3.500) = 1355 
    [3.500, 4.000) = 1830 
    [4.000, 4.500) = 2349 
    [4.500, 5.000) = 805 
    [5.000, 5.500) = 137 
    [5.500, 6.000) = 26 
    [6.000, 6.500) = 6 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =      6.979 ms/op
     p(99.9900) =      7.668 ms/op
     p(99.9990) =      7.668 ms/op
     p(99.9999) =      7.668 ms/op
    p(100.0000) =      7.668 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.780          ops/ms
ClientSimple.existUser                       thrpt         12.915          ops/ms
ClientSimple.getUser                         thrpt         12.749          ops/ms
ClientSimple.listUser                        thrpt          8.251          ops/ms
ClientSimple.createUser                       avgt          2.140           ms/op
ClientSimple.existUser                        avgt          1.946           ms/op
ClientSimple.getUser                          avgt          1.956           ms/op
ClientSimple.listUser                         avgt          3.454           ms/op
ClientSimple.createUser                     sample  14257   2.243 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.486           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.058           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.925           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.591           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.991           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.829           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.843           ms/op
ClientSimple.existUser                      sample  17246   1.859 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.631           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.761           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.150           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.314           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.900           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.516           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.182           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.253           ms/op
ClientSimple.getUser                        sample  15483   2.065 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.519           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.913           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.548           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.801           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.810           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.927           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.971           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.025           ms/op
ClientSimple.listUser                       sample   8873   3.607 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.165           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.723           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.727           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.284           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.979           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.668           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.668           ms/op

Benchmark result is saved to 1719794609217.json
