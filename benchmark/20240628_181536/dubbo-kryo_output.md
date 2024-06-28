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
# Warmup Iteration   1: 1.531 ops/ms
Iteration   1: 6.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.530 ops/ms


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
# Warmup Iteration   1: 6.540 ops/ms
Iteration   1: 13.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.561 ops/ms


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
# Warmup Iteration   1: 5.836 ops/ms
Iteration   1: 11.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.870 ops/ms


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
# Warmup Iteration   1: 4.731 ops/ms
Iteration   1: 8.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.294 ops/ms


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
# Warmup Iteration   1: 3.655 ±(99.9%) 0.060 ms/op
Iteration   1: 2.406 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.406 ms/op


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
# Warmup Iteration   1: 3.339 ±(99.9%) 0.052 ms/op
Iteration   1: 1.759 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.759 ms/op


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
# Warmup Iteration   1: 3.338 ±(99.9%) 0.063 ms/op
Iteration   1: 1.880 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.880 ms/op


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
# Warmup Iteration   1: 4.201 ±(99.9%) 0.139 ms/op
Iteration   1: 3.290 ±(99.9%) 0.016 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.934 ±(99.9%) 0.109 ms/op
Iteration   1: 2.368 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.309 ms/op
                 createUser·p0.50:   2.134 ms/op
                 createUser·p0.90:   2.814 ms/op
                 createUser·p0.95:   3.432 ms/op
                 createUser·p0.99:   9.094 ms/op
                 createUser·p0.999:  30.867 ms/op
                 createUser·p0.9999: 31.883 ms/op
                 createUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13491
  mean =      2.368 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10831 
    [ 2.500,  5.000) = 2286 
    [ 5.000,  7.500) = 171 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.309 ms/op
     p(50.0000) =      2.134 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      3.432 ms/op
     p(99.0000) =      9.094 ms/op
     p(99.9000) =     30.867 ms/op
     p(99.9900) =     31.883 ms/op
     p(99.9990) =     31.883 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 3.053 ±(99.9%) 0.071 ms/op
Iteration   1: 1.839 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.397 ms/op
                 existUser·p0.50:   1.665 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   3.215 ms/op
                 existUser·p0.999:  29.032 ms/op
                 existUser·p0.9999: 29.237 ms/op
                 existUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17532
  mean =      1.839 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16581 
    [ 2.500,  5.000) = 834 
    [ 5.000,  7.500) = 53 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      1.665 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.215 ms/op
     p(99.9000) =     29.032 ms/op
     p(99.9900) =     29.237 ms/op
     p(99.9990) =     29.262 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 3.492 ±(99.9%) 0.087 ms/op
Iteration   1: 2.111 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   2.040 ms/op
                 getUser·p0.90:   2.691 ms/op
                 getUser·p0.95:   2.953 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  14.598 ms/op
                 getUser·p0.9999: 14.940 ms/op
                 getUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15333
  mean =      2.111 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 306 
    [ 1.250,  2.500) = 12705 
    [ 2.500,  3.750) = 2109 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      2.040 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     14.940 ms/op
     p(99.9990) =     14.975 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.139 ms/op
Iteration   1: 2.946 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.034 ms/op
                 listUser·p0.50:   2.777 ms/op
                 listUser·p0.90:   3.744 ms/op
                 listUser·p0.95:   4.067 ms/op
                 listUser·p0.99:   5.067 ms/op
                 listUser·p0.999:  7.358 ms/op
                 listUser·p0.9999: 7.413 ms/op
                 listUser·p1.00:   7.414 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10850
  mean =      2.946 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 23 
    [1.500, 2.000) = 168 
    [2.000, 2.500) = 1224 
    [2.500, 3.000) = 5968 
    [3.000, 3.500) = 1904 
    [3.500, 4.000) = 921 
    [4.000, 4.500) = 431 
    [4.500, 5.000) = 98 
    [5.000, 5.500) = 26 
    [5.500, 6.000) = 55 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      2.777 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.067 ms/op
     p(99.9000) =      7.358 ms/op
     p(99.9900) =      7.413 ms/op
     p(99.9990) =      7.414 ms/op
     p(99.9999) =      7.414 ms/op
    p(100.0000) =      7.414 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.530          ops/ms
ClientSimple.existUser                       thrpt         13.561          ops/ms
ClientSimple.getUser                         thrpt         11.870          ops/ms
ClientSimple.listUser                        thrpt          8.294          ops/ms
ClientSimple.createUser                       avgt          2.406           ms/op
ClientSimple.existUser                        avgt          1.759           ms/op
ClientSimple.getUser                          avgt          1.880           ms/op
ClientSimple.listUser                         avgt          3.290           ms/op
ClientSimple.createUser                     sample  13491   2.368 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.309           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.134           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.814           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.432           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.094           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.867           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.883           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.883           ms/op
ClientSimple.existUser                      sample  17532   1.839 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.397           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.665           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.215           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.032           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.237           ms/op
ClientSimple.existUser:existUser·p1.00      sample         29.262           ms/op
ClientSimple.getUser                        sample  15333   2.111 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.692           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.040           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.691           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.953           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.194           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.598           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.940           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.975           ms/op
ClientSimple.listUser                       sample  10850   2.946 ± 0.019   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.034           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.777           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.744           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.067           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.067           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.358           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.413           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.414           ms/op

Benchmark result is saved to 1719598256483.json
