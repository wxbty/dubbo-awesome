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
# Warmup Iteration   1: 1.810 ops/ms
Iteration   1: 6.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.955 ops/ms


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
# Warmup Iteration   1: 6.300 ops/ms
Iteration   1: 12.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.432 ops/ms


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
# Warmup Iteration   1: 5.692 ops/ms
Iteration   1: 12.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.724 ops/ms


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
# Warmup Iteration   1: 4.264 ops/ms
Iteration   1: 8.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.633 ops/ms


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
# Warmup Iteration   1: 4.236 ±(99.9%) 0.078 ms/op
Iteration   1: 2.231 ±(99.9%) 0.009 ms/op


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
# Warmup Iteration   1: 3.362 ±(99.9%) 0.063 ms/op
Iteration   1: 1.931 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.931 ms/op


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
# Warmup Iteration   1: 3.357 ±(99.9%) 0.051 ms/op
Iteration   1: 2.299 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.299 ms/op


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.087 ms/op
Iteration   1: 3.365 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.365 ms/op


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.106 ms/op
Iteration   1: 2.116 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   1.919 ms/op
                 createUser·p0.90:   2.630 ms/op
                 createUser·p0.95:   2.916 ms/op
                 createUser·p0.99:   7.382 ms/op
                 createUser·p0.999:  14.593 ms/op
                 createUser·p0.9999: 17.548 ms/op
                 createUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15325
  mean =      2.116 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 203 
    [ 1.250,  2.500) = 13100 
    [ 2.500,  3.750) = 1664 
    [ 3.750,  5.000) = 160 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.916 ms/op
     p(99.0000) =      7.382 ms/op
     p(99.9000) =     14.593 ms/op
     p(99.9900) =     17.548 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 2.910 ±(99.9%) 0.072 ms/op
Iteration   1: 1.945 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.329 ms/op
                 existUser·p0.50:   1.954 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.576 ms/op
                 existUser·p0.99:   3.021 ms/op
                 existUser·p0.999:  4.969 ms/op
                 existUser·p0.9999: 6.826 ms/op
                 existUser·p1.00:   6.889 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16456
  mean =      1.945 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 7 
    [0.500, 1.000) = 70 
    [1.000, 1.500) = 2811 
    [1.500, 2.000) = 5916 
    [2.000, 2.500) = 6357 
    [2.500, 3.000) = 1130 
    [3.000, 3.500) = 42 
    [3.500, 4.000) = 61 
    [4.000, 4.500) = 9 
    [4.500, 5.000) = 41 
    [5.000, 5.500) = 7 
    [5.500, 6.000) = 2 
    [6.000, 6.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      3.021 ms/op
     p(99.9000) =      4.969 ms/op
     p(99.9900) =      6.826 ms/op
     p(99.9990) =      6.889 ms/op
     p(99.9999) =      6.889 ms/op
    p(100.0000) =      6.889 ms/op


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
# Warmup Iteration   1: 3.577 ±(99.9%) 0.092 ms/op
Iteration   1: 2.052 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   1.909 ms/op
                 getUser·p0.90:   2.549 ms/op
                 getUser·p0.95:   2.810 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  15.159 ms/op
                 getUser·p0.9999: 15.866 ms/op
                 getUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15585
  mean =      2.052 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 13850 
    [ 2.500,  3.750) = 1516 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.549 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =     15.159 ms/op
     p(99.9900) =     15.866 ms/op
     p(99.9990) =     16.122 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.119 ms/op
Iteration   1: 3.374 ±(99.9%) 0.061 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.121 ms/op
                 listUser·p0.999:  24.379 ms/op
                 listUser·p0.9999: 24.740 ms/op
                 listUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9470
  mean =      3.374 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1661 
    [ 2.500,  5.000) = 7516 
    [ 5.000,  7.500) = 203 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.121 ms/op
     p(99.9000) =     24.379 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.955          ops/ms
ClientSimple.existUser                       thrpt         12.432          ops/ms
ClientSimple.getUser                         thrpt         12.724          ops/ms
ClientSimple.listUser                        thrpt          8.633          ops/ms
ClientSimple.createUser                       avgt          2.231           ms/op
ClientSimple.existUser                        avgt          1.931           ms/op
ClientSimple.getUser                          avgt          2.299           ms/op
ClientSimple.listUser                         avgt          3.365           ms/op
ClientSimple.createUser                     sample  15325   2.116 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.639           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.919           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.916           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.382           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.593           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.548           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.874           ms/op
ClientSimple.existUser                      sample  16456   1.945 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.329           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.954           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.021           ms/op
ClientSimple.existUser:existUser·p0.999     sample          4.969           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          6.826           ms/op
ClientSimple.existUser:existUser·p1.00      sample          6.889           ms/op
ClientSimple.getUser                        sample  15585   2.052 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.900           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.909           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.549           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.100           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.159           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.866           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.122           ms/op
ClientSimple.listUser                       sample   9470   3.374 ± 0.061   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.788           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.023           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.727           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.121           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.379           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.740           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.740           ms/op

Benchmark result is saved to 1716833451537.json
