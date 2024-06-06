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
# Warmup Iteration   1: 1.871 ops/ms
Iteration   1: 7.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.007 ops/ms


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
# Warmup Iteration   1: 6.154 ops/ms
Iteration   1: 12.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.479 ops/ms


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
# Warmup Iteration   1: 5.707 ops/ms
Iteration   1: 11.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.992 ops/ms


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
# Warmup Iteration   1: 5.588 ops/ms
Iteration   1: 8.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.479 ops/ms


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.078 ms/op
Iteration   1: 2.071 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.071 ms/op


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
# Warmup Iteration   1: 3.130 ±(99.9%) 0.055 ms/op
Iteration   1: 1.678 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.678 ms/op


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
# Warmup Iteration   1: 3.502 ±(99.9%) 0.059 ms/op
Iteration   1: 1.867 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.867 ms/op


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
# Warmup Iteration   1: 4.677 ±(99.9%) 0.093 ms/op
Iteration   1: 3.698 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.698 ms/op


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.101 ms/op
Iteration   1: 2.240 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.600 ms/op
                 createUser·p0.50:   1.966 ms/op
                 createUser·p0.90:   2.744 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   6.730 ms/op
                 createUser·p0.999:  17.170 ms/op
                 createUser·p0.9999: 21.299 ms/op
                 createUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14247
  mean =      2.240 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11199 
    [ 2.500,  5.000) = 2829 
    [ 5.000,  7.500) = 91 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      6.730 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 2.953 ±(99.9%) 0.069 ms/op
Iteration   1: 1.946 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.514 ms/op
                 existUser·p0.50:   1.867 ms/op
                 existUser·p0.90:   2.413 ms/op
                 existUser·p0.95:   2.578 ms/op
                 existUser·p0.99:   3.579 ms/op
                 existUser·p0.999:  21.070 ms/op
                 existUser·p0.9999: 21.440 ms/op
                 existUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16412
  mean =      1.946 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15303 
    [ 2.500,  5.000) = 1035 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      1.867 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.578 ms/op
     p(99.0000) =      3.579 ms/op
     p(99.9000) =     21.070 ms/op
     p(99.9900) =     21.440 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 3.302 ±(99.9%) 0.080 ms/op
Iteration   1: 2.143 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.550 ms/op
                 getUser·p0.50:   2.068 ms/op
                 getUser·p0.90:   2.621 ms/op
                 getUser·p0.95:   2.834 ms/op
                 getUser·p0.99:   5.283 ms/op
                 getUser·p0.999:  14.500 ms/op
                 getUser·p0.9999: 15.204 ms/op
                 getUser·p1.00:   15.204 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14914
  mean =      2.143 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 221 
    [ 1.250,  2.500) = 12313 
    [ 2.500,  3.750) = 2119 
    [ 3.750,  5.000) = 59 
    [ 5.000,  6.250) = 130 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      2.068 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      5.283 ms/op
     p(99.9000) =     14.500 ms/op
     p(99.9900) =     15.204 ms/op
     p(99.9990) =     15.204 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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
# Warmup Iteration   1: 4.677 ±(99.9%) 0.158 ms/op
Iteration   1: 3.442 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   3.473 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.896 ms/op
                 listUser·p0.999:  7.043 ms/op
                 listUser·p0.9999: 7.807 ms/op
                 listUser·p1.00:   7.807 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9314
  mean =      3.442 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 55 
    [1.500, 2.000) = 164 
    [2.000, 2.500) = 624 
    [2.500, 3.000) = 1758 
    [3.000, 3.500) = 2197 
    [3.500, 4.000) = 2771 
    [4.000, 4.500) = 1235 
    [4.500, 5.000) = 272 
    [5.000, 5.500) = 89 
    [5.500, 6.000) = 66 
    [6.000, 6.500) = 62 
    [6.500, 7.000) = 9 
    [7.000, 7.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.896 ms/op
     p(99.9000) =      7.043 ms/op
     p(99.9900) =      7.807 ms/op
     p(99.9990) =      7.807 ms/op
     p(99.9999) =      7.807 ms/op
    p(100.0000) =      7.807 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.007          ops/ms
ClientSimple.existUser                       thrpt         12.479          ops/ms
ClientSimple.getUser                         thrpt         11.992          ops/ms
ClientSimple.listUser                        thrpt          8.479          ops/ms
ClientSimple.createUser                       avgt          2.071           ms/op
ClientSimple.existUser                        avgt          1.678           ms/op
ClientSimple.getUser                          avgt          1.867           ms/op
ClientSimple.listUser                         avgt          3.698           ms/op
ClientSimple.createUser                     sample  14247   2.240 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.600           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.966           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.730           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.170           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.299           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.758           ms/op
ClientSimple.existUser                      sample  16412   1.946 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.514           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.867           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.413           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.578           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.579           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.070           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.440           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.692           ms/op
ClientSimple.getUser                        sample  14914   2.143 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.550           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.068           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.834           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.283           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.500           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.204           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.204           ms/op
ClientSimple.listUser                       sample   9314   3.442 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.998           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.473           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.896           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.043           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.807           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.807           ms/op

Benchmark result is saved to 1717697439981.json
