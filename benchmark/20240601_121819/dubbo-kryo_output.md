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
# Warmup Iteration   1: 1.538 ops/ms
Iteration   1: 7.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.868 ops/ms


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
# Warmup Iteration   1: 5.769 ops/ms
Iteration   1: 12.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.871 ops/ms
Iteration   1: 11.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.856 ops/ms


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
# Warmup Iteration   1: 4.860 ops/ms
Iteration   1: 8.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.343 ops/ms


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
# Warmup Iteration   1: 4.166 ±(99.9%) 0.091 ms/op
Iteration   1: 2.295 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.295 ms/op


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
# Warmup Iteration   1: 3.498 ±(99.9%) 0.096 ms/op
Iteration   1: 2.054 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.054 ms/op


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
# Warmup Iteration   1: 3.618 ±(99.9%) 0.066 ms/op
Iteration   1: 2.075 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.075 ms/op


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.086 ms/op
Iteration   1: 3.255 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.255 ms/op


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
# Warmup Iteration   1: 3.424 ±(99.9%) 0.080 ms/op
Iteration   1: 2.177 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.592 ms/op
                 createUser·p0.50:   1.978 ms/op
                 createUser·p0.90:   2.634 ms/op
                 createUser·p0.95:   2.886 ms/op
                 createUser·p0.99:   4.072 ms/op
                 createUser·p0.999:  19.923 ms/op
                 createUser·p0.9999: 20.678 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14728
  mean =      2.177 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12352 
    [ 2.500,  5.000) = 2253 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.886 ms/op
     p(99.0000) =      4.072 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     20.678 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 3.189 ±(99.9%) 0.080 ms/op
Iteration   1: 1.882 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.471 ms/op
                 existUser·p0.50:   1.821 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   3.475 ms/op
                 existUser·p0.999:  17.891 ms/op
                 existUser·p0.9999: 18.552 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17077
  mean =      1.882 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 792 
    [ 1.250,  2.500) = 15348 
    [ 2.500,  3.750) = 829 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.475 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     18.552 ms/op
     p(99.9990) =     18.645 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 3.076 ±(99.9%) 0.072 ms/op
Iteration   1: 1.757 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.496 ms/op
                 getUser·p0.50:   1.559 ms/op
                 getUser·p0.90:   2.560 ms/op
                 getUser·p0.95:   2.720 ms/op
                 getUser·p0.99:   3.502 ms/op
                 getUser·p0.999:  12.632 ms/op
                 getUser·p0.9999: 13.009 ms/op
                 getUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18401
  mean =      1.757 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1719 
    [ 1.250,  2.500) = 14492 
    [ 2.500,  3.750) = 2045 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      1.559 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      3.502 ms/op
     p(99.9000) =     12.632 ms/op
     p(99.9900) =     13.009 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


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
# Warmup Iteration   1: 4.649 ±(99.9%) 0.162 ms/op
Iteration   1: 3.419 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.025 ms/op
                 listUser·p0.50:   3.404 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   5.390 ms/op
                 listUser·p0.999:  10.643 ms/op
                 listUser·p0.9999: 10.764 ms/op
                 listUser·p1.00:   10.764 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9387
  mean =      3.419 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 70 
    [ 2.000,  3.000) = 3887 
    [ 3.000,  4.000) = 2950 
    [ 4.000,  5.000) = 2333 
    [ 5.000,  6.000) = 94 
    [ 6.000,  7.000) = 17 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 1 
    [ 9.000, 10.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.025 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     10.643 ms/op
     p(99.9900) =     10.764 ms/op
     p(99.9990) =     10.764 ms/op
     p(99.9999) =     10.764 ms/op
    p(100.0000) =     10.764 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.868          ops/ms
ClientSimple.existUser                       thrpt         12.605          ops/ms
ClientSimple.getUser                         thrpt         11.856          ops/ms
ClientSimple.listUser                        thrpt          8.343          ops/ms
ClientSimple.createUser                       avgt          2.295           ms/op
ClientSimple.existUser                        avgt          2.054           ms/op
ClientSimple.getUser                          avgt          2.075           ms/op
ClientSimple.listUser                         avgt          3.255           ms/op
ClientSimple.createUser                     sample  14728   2.177 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.592           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.978           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.634           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.886           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.072           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.923           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.678           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.709           ms/op
ClientSimple.existUser                      sample  17077   1.882 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.471           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.821           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.475           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.891           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.552           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.645           ms/op
ClientSimple.getUser                        sample  18401   1.757 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.496           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.559           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.720           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.502           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.632           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.009           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.009           ms/op
ClientSimple.listUser                       sample   9387   3.419 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.025           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.404           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.390           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.643           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.764           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.764           ms/op

Benchmark result is saved to 1717244022005.json
