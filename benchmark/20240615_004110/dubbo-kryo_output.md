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
# Warmup Iteration   1: 1.731 ops/ms
Iteration   1: 6.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.607 ops/ms


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
# Warmup Iteration   1: 5.374 ops/ms
Iteration   1: 12.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.155 ops/ms


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
# Warmup Iteration   1: 5.754 ops/ms
Iteration   1: 12.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.884 ops/ms


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
# Warmup Iteration   1: 4.856 ops/ms
Iteration   1: 8.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.748 ops/ms


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.067 ms/op
Iteration   1: 2.030 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.030 ms/op


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
# Warmup Iteration   1: 3.308 ±(99.9%) 0.056 ms/op
Iteration   1: 1.879 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.879 ms/op


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
# Warmup Iteration   1: 3.095 ±(99.9%) 0.061 ms/op
Iteration   1: 1.981 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.981 ms/op


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
# Warmup Iteration   1: 4.901 ±(99.9%) 0.151 ms/op
Iteration   1: 3.034 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.034 ms/op


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.093 ms/op
Iteration   1: 2.322 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   2.187 ms/op
                 createUser·p0.90:   2.937 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   6.505 ms/op
                 createUser·p0.999:  18.391 ms/op
                 createUser·p0.9999: 20.593 ms/op
                 createUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13762
  mean =      2.322 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10181 
    [ 2.500,  5.000) = 3319 
    [ 5.000,  7.500) = 132 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      6.505 ms/op
     p(99.9000) =     18.391 ms/op
     p(99.9900) =     20.593 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 3.104 ±(99.9%) 0.096 ms/op
Iteration   1: 1.808 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   1.716 ms/op
                 existUser·p0.90:   2.130 ms/op
                 existUser·p0.95:   2.343 ms/op
                 existUser·p0.99:   3.178 ms/op
                 existUser·p0.999:  11.097 ms/op
                 existUser·p0.9999: 11.951 ms/op
                 existUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17707
  mean =      1.808 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 17081 
    [ 2.500,  3.750) = 453 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      1.716 ms/op
     p(90.0000) =      2.130 ms/op
     p(95.0000) =      2.343 ms/op
     p(99.0000) =      3.178 ms/op
     p(99.9000) =     11.097 ms/op
     p(99.9900) =     11.951 ms/op
     p(99.9990) =     11.977 ms/op
     p(99.9999) =     11.977 ms/op
    p(100.0000) =     11.977 ms/op


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
# Warmup Iteration   1: 3.364 ±(99.9%) 0.077 ms/op
Iteration   1: 2.130 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.569 ms/op
                 getUser·p0.50:   1.964 ms/op
                 getUser·p0.90:   2.725 ms/op
                 getUser·p0.95:   2.953 ms/op
                 getUser·p0.99:   4.096 ms/op
                 getUser·p0.999:  15.450 ms/op
                 getUser·p0.9999: 15.834 ms/op
                 getUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15057
  mean =      2.130 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 143 
    [ 1.250,  2.500) = 12032 
    [ 2.500,  3.750) = 2671 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.725 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      4.096 ms/op
     p(99.9000) =     15.450 ms/op
     p(99.9900) =     15.834 ms/op
     p(99.9990) =     15.909 ms/op
     p(99.9999) =     15.909 ms/op
    p(100.0000) =     15.909 ms/op


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
# Warmup Iteration   1: 4.820 ±(99.9%) 0.146 ms/op
Iteration   1: 3.046 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   2.826 ms/op
                 listUser·p0.90:   3.748 ms/op
                 listUser·p0.95:   4.108 ms/op
                 listUser·p0.99:   5.425 ms/op
                 listUser·p0.999:  17.494 ms/op
                 listUser·p0.9999: 17.985 ms/op
                 listUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10640
  mean =      3.046 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 907 
    [ 2.500,  3.750) = 8660 
    [ 3.750,  5.000) = 872 
    [ 5.000,  6.250) = 112 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.425 ms/op
     p(99.9000) =     17.494 ms/op
     p(99.9900) =     17.985 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.607          ops/ms
ClientSimple.existUser                       thrpt         12.155          ops/ms
ClientSimple.getUser                         thrpt         12.884          ops/ms
ClientSimple.listUser                        thrpt          8.748          ops/ms
ClientSimple.createUser                       avgt          2.030           ms/op
ClientSimple.existUser                        avgt          1.879           ms/op
ClientSimple.getUser                          avgt          1.981           ms/op
ClientSimple.listUser                         avgt          3.034           ms/op
ClientSimple.createUser                     sample  13762   2.322 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.660           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.187           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.937           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.265           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.505           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.391           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.593           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.939           ms/op
ClientSimple.existUser                      sample  17707   1.808 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.568           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.716           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.130           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.178           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.097           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.951           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.977           ms/op
ClientSimple.getUser                        sample  15057   2.130 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.569           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.964           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.725           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.953           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.096           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.450           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.834           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.909           ms/op
ClientSimple.listUser                       sample  10640   3.046 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.927           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.826           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.748           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.108           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.425           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.494           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.985           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.990           ms/op

Benchmark result is saved to 1718411835116.json
