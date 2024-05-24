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
# Warmup Iteration   1: 1.877 ops/ms
Iteration   1: 7.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.172 ops/ms


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
# Warmup Iteration   1: 6.088 ops/ms
Iteration   1: 14.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.957 ops/ms


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
# Warmup Iteration   1: 5.141 ops/ms
Iteration   1: 12.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.940 ops/ms


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
# Warmup Iteration   1: 5.014 ops/ms
Iteration   1: 8.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.553 ops/ms


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
# Warmup Iteration   1: 3.447 ±(99.9%) 0.068 ms/op
Iteration   1: 2.058 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.058 ms/op


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
# Warmup Iteration   1: 3.223 ±(99.9%) 0.058 ms/op
Iteration   1: 1.795 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.795 ms/op


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
# Warmup Iteration   1: 3.125 ±(99.9%) 0.055 ms/op
Iteration   1: 1.794 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.794 ms/op


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
# Warmup Iteration   1: 4.524 ±(99.9%) 0.114 ms/op
Iteration   1: 3.527 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.527 ms/op


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
# Warmup Iteration   1: 3.427 ±(99.9%) 0.080 ms/op
Iteration   1: 2.178 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   1.952 ms/op
                 createUser·p0.90:   2.544 ms/op
                 createUser·p0.95:   2.981 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  17.695 ms/op
                 createUser·p0.9999: 19.075 ms/op
                 createUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14741
  mean =      2.178 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 243 
    [ 1.250,  2.500) = 12763 
    [ 2.500,  3.750) = 1203 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 121 
    [ 6.250,  7.500) = 134 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.981 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     19.075 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 3.061 ±(99.9%) 0.077 ms/op
Iteration   1: 1.960 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   1.825 ms/op
                 existUser·p0.90:   2.335 ms/op
                 existUser·p0.95:   2.556 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  26.695 ms/op
                 existUser·p0.9999: 27.287 ms/op
                 existUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16328
  mean =      1.960 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15368 
    [ 2.500,  5.000) = 800 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =     26.695 ms/op
     p(99.9900) =     27.287 ms/op
     p(99.9990) =     27.329 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 3.178 ±(99.9%) 0.078 ms/op
Iteration   1: 1.890 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.429 ms/op
                 getUser·p0.50:   1.782 ms/op
                 getUser·p0.90:   2.269 ms/op
                 getUser·p0.95:   2.458 ms/op
                 getUser·p0.99:   3.578 ms/op
                 getUser·p0.999:  9.050 ms/op
                 getUser·p0.9999: 10.238 ms/op
                 getUser·p1.00:   10.355 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17150
  mean =      1.890 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 21 
    [ 1.000,  2.000) = 12412 
    [ 2.000,  3.000) = 4458 
    [ 3.000,  4.000) = 107 
    [ 4.000,  5.000) = 82 
    [ 5.000,  6.000) = 6 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 47 
    [ 9.000, 10.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      1.782 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      3.578 ms/op
     p(99.9000) =      9.050 ms/op
     p(99.9900) =     10.238 ms/op
     p(99.9990) =     10.355 ms/op
     p(99.9999) =     10.355 ms/op
    p(100.0000) =     10.355 ms/op


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
# Warmup Iteration   1: 4.328 ±(99.9%) 0.132 ms/op
Iteration   1: 3.737 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  8.765 ms/op
                 listUser·p0.9999: 8.995 ms/op
                 listUser·p1.00:   8.995 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8562
  mean =      3.737 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 3 
    [1.500, 2.000) = 28 
    [2.000, 2.500) = 349 
    [2.500, 3.000) = 874 
    [3.000, 3.500) = 1941 
    [3.500, 4.000) = 2913 
    [4.000, 4.500) = 1539 
    [4.500, 5.000) = 491 
    [5.000, 5.500) = 115 
    [5.500, 6.000) = 103 
    [6.000, 6.500) = 68 
    [6.500, 7.000) = 22 
    [7.000, 7.500) = 48 
    [7.500, 8.000) = 34 
    [8.000, 8.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =      8.995 ms/op
     p(99.9990) =      8.995 ms/op
     p(99.9999) =      8.995 ms/op
    p(100.0000) =      8.995 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.172          ops/ms
ClientSimple.existUser                       thrpt         14.957          ops/ms
ClientSimple.getUser                         thrpt         12.940          ops/ms
ClientSimple.listUser                        thrpt          8.553          ops/ms
ClientSimple.createUser                       avgt          2.058           ms/op
ClientSimple.existUser                        avgt          1.795           ms/op
ClientSimple.getUser                          avgt          1.794           ms/op
ClientSimple.listUser                         avgt          3.527           ms/op
ClientSimple.createUser                     sample  14741   2.178 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.613           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.952           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.544           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.981           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.438           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.695           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.075           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.759           ms/op
ClientSimple.existUser                      sample  16328   1.960 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.634           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.825           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.276           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.695           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.287           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.329           ms/op
ClientSimple.getUser                        sample  17150   1.890 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.429           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.782           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.269           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.578           ms/op
ClientSimple.getUser:getUser·p0.999         sample          9.050           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.238           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.355           ms/op
ClientSimple.listUser                       sample   8562   3.737 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.333           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.682           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.997           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.348           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.765           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.995           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.995           ms/op

Benchmark result is saved to 1716552857741.json
