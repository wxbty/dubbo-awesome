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
# Warmup Iteration   1: 1.884 ops/ms
Iteration   1: 6.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.996 ops/ms


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
# Warmup Iteration   1: 6.769 ops/ms
Iteration   1: 13.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.405 ops/ms


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
# Warmup Iteration   1: 6.057 ops/ms
Iteration   1: 11.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.765 ops/ms


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
# Warmup Iteration   1: 4.605 ops/ms
Iteration   1: 8.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.341 ops/ms


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.079 ms/op
Iteration   1: 2.167 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.167 ms/op


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
# Warmup Iteration   1: 3.213 ±(99.9%) 0.047 ms/op
Iteration   1: 1.785 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.785 ms/op


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
# Warmup Iteration   1: 3.321 ±(99.9%) 0.053 ms/op
Iteration   1: 2.038 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.038 ms/op


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
# Warmup Iteration   1: 4.639 ±(99.9%) 0.082 ms/op
Iteration   1: 3.410 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.410 ms/op


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
# Warmup Iteration   1: 3.500 ±(99.9%) 0.088 ms/op
Iteration   1: 2.097 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.464 ms/op
                 createUser·p0.50:   1.942 ms/op
                 createUser·p0.90:   2.408 ms/op
                 createUser·p0.95:   2.613 ms/op
                 createUser·p0.99:   9.315 ms/op
                 createUser·p0.999:  19.202 ms/op
                 createUser·p0.9999: 19.718 ms/op
                 createUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15242
  mean =      2.097 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 319 
    [ 1.250,  2.500) = 13875 
    [ 2.500,  3.750) = 784 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      1.942 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      9.315 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     19.718 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 3.388 ±(99.9%) 0.089 ms/op
Iteration   1: 1.926 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   1.845 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.761 ms/op
                 existUser·p0.99:   3.685 ms/op
                 existUser·p0.999:  13.086 ms/op
                 existUser·p0.9999: 14.833 ms/op
                 existUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16639
  mean =      1.926 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 474 
    [ 1.250,  2.500) = 14792 
    [ 2.500,  3.750) = 1259 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      3.685 ms/op
     p(99.9000) =     13.086 ms/op
     p(99.9900) =     14.833 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 3.125 ±(99.9%) 0.073 ms/op
Iteration   1: 2.081 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.602 ms/op
                 getUser·p0.50:   1.952 ms/op
                 getUser·p0.90:   2.671 ms/op
                 getUser·p0.95:   3.043 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  23.167 ms/op
                 getUser·p0.9999: 23.704 ms/op
                 getUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15355
  mean =      2.081 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13242 
    [ 2.500,  5.000) = 1957 
    [ 5.000,  7.500) = 92 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     23.167 ms/op
     p(99.9900) =     23.704 ms/op
     p(99.9990) =     23.757 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 4.466 ±(99.9%) 0.142 ms/op
Iteration   1: 3.131 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.997 ms/op
                 listUser·p0.999:  6.634 ms/op
                 listUser·p0.9999: 8.397 ms/op
                 listUser·p1.00:   8.421 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10218
  mean =      3.131 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 15 
    [1.500, 2.000) = 68 
    [2.000, 2.500) = 1076 
    [2.500, 3.000) = 4691 
    [3.000, 3.500) = 2112 
    [3.500, 4.000) = 1044 
    [4.000, 4.500) = 802 
    [4.500, 5.000) = 160 
    [5.000, 5.500) = 96 
    [5.500, 6.000) = 58 
    [6.000, 6.500) = 78 
    [6.500, 7.000) = 13 
    [7.000, 7.500) = 4 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =      6.634 ms/op
     p(99.9900) =      8.397 ms/op
     p(99.9990) =      8.421 ms/op
     p(99.9999) =      8.421 ms/op
    p(100.0000) =      8.421 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.996          ops/ms
ClientSimple.existUser                       thrpt         13.405          ops/ms
ClientSimple.getUser                         thrpt         11.765          ops/ms
ClientSimple.listUser                        thrpt          8.341          ops/ms
ClientSimple.createUser                       avgt          2.167           ms/op
ClientSimple.existUser                        avgt          1.785           ms/op
ClientSimple.getUser                          avgt          2.038           ms/op
ClientSimple.listUser                         avgt          3.410           ms/op
ClientSimple.createUser                     sample  15242   2.097 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.464           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.942           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.408           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.613           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.315           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.202           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.718           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.890           ms/op
ClientSimple.existUser                      sample  16639   1.926 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.515           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.845           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.761           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.685           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.086           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.833           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.909           ms/op
ClientSimple.getUser                        sample  15355   2.081 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.602           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.952           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.043           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.456           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.167           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.704           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.757           ms/op
ClientSimple.listUser                       sample  10218   3.131 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.317           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.929           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.080           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.997           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.634           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.397           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.421           ms/op

Benchmark result is saved to 1718215886622.json
