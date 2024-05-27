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
# Warmup Iteration   1: 2.114 ops/ms
Iteration   1: 7.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.550 ops/ms


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
# Warmup Iteration   1: 6.095 ops/ms
Iteration   1: 14.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.165 ops/ms


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
# Warmup Iteration   1: 6.091 ops/ms
Iteration   1: 12.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.404 ops/ms


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
# Warmup Iteration   1: 5.572 ops/ms
Iteration   1: 8.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.196 ops/ms


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
# Warmup Iteration   1: 4.437 ±(99.9%) 0.090 ms/op
Iteration   1: 2.229 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.229 ms/op


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
# Warmup Iteration   1: 3.097 ±(99.9%) 0.039 ms/op
Iteration   1: 2.031 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.031 ms/op


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
# Warmup Iteration   1: 3.176 ±(99.9%) 0.054 ms/op
Iteration   1: 2.222 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.222 ms/op


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
# Warmup Iteration   1: 4.413 ±(99.9%) 0.098 ms/op
Iteration   1: 3.300 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.300 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.724 ±(99.9%) 0.090 ms/op
Iteration   1: 1.923 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.528 ms/op
                 createUser·p0.50:   1.796 ms/op
                 createUser·p0.90:   2.265 ms/op
                 createUser·p0.95:   2.466 ms/op
                 createUser·p0.99:   7.034 ms/op
                 createUser·p0.999:  14.582 ms/op
                 createUser·p0.9999: 15.758 ms/op
                 createUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16634
  mean =      1.923 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 607 
    [ 1.250,  2.500) = 15278 
    [ 2.500,  3.750) = 490 
    [ 3.750,  5.000) = 22 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      7.034 ms/op
     p(99.9000) =     14.582 ms/op
     p(99.9900) =     15.758 ms/op
     p(99.9990) =     16.171 ms/op
     p(99.9999) =     16.171 ms/op
    p(100.0000) =     16.171 ms/op


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
# Warmup Iteration   1: 2.935 ±(99.9%) 0.066 ms/op
Iteration   1: 1.778 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.572 ms/op
                 existUser·p0.50:   1.638 ms/op
                 existUser·p0.90:   2.048 ms/op
                 existUser·p0.95:   2.204 ms/op
                 existUser·p0.99:   2.613 ms/op
                 existUser·p0.999:  33.358 ms/op
                 existUser·p0.9999: 33.456 ms/op
                 existUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17992
  mean =      1.778 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17737 
    [ 2.500,  5.000) = 191 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      1.638 ms/op
     p(90.0000) =      2.048 ms/op
     p(95.0000) =      2.204 ms/op
     p(99.0000) =      2.613 ms/op
     p(99.9000) =     33.358 ms/op
     p(99.9900) =     33.456 ms/op
     p(99.9990) =     33.456 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 3.391 ±(99.9%) 0.089 ms/op
Iteration   1: 2.012 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.463 ms/op
                 getUser·p0.50:   1.825 ms/op
                 getUser·p0.90:   2.499 ms/op
                 getUser·p0.95:   2.712 ms/op
                 getUser·p0.99:   5.142 ms/op
                 getUser·p0.999:  12.419 ms/op
                 getUser·p0.9999: 12.960 ms/op
                 getUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15909
  mean =      2.012 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 14215 
    [ 2.500,  3.750) = 1355 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      5.142 ms/op
     p(99.9000) =     12.419 ms/op
     p(99.9900) =     12.960 ms/op
     p(99.9990) =     12.960 ms/op
     p(99.9999) =     12.960 ms/op
    p(100.0000) =     12.960 ms/op


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
# Warmup Iteration   1: 4.653 ±(99.9%) 0.135 ms/op
Iteration   1: 3.678 ±(99.9%) 0.069 ms/op
                 listUser·p0.00:   0.605 ms/op
                 listUser·p0.50:   3.478 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  28.967 ms/op
                 listUser·p0.9999: 29.032 ms/op
                 listUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8702
  mean =      3.678 ±(99.9%) 0.069 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1244 
    [ 2.500,  5.000) = 6887 
    [ 5.000,  7.500) = 472 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     28.967 ms/op
     p(99.9900) =     29.032 ms/op
     p(99.9990) =     29.032 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.550          ops/ms
ClientSimple.existUser                       thrpt         14.165          ops/ms
ClientSimple.getUser                         thrpt         12.404          ops/ms
ClientSimple.listUser                        thrpt          8.196          ops/ms
ClientSimple.createUser                       avgt          2.229           ms/op
ClientSimple.existUser                        avgt          2.031           ms/op
ClientSimple.getUser                          avgt          2.222           ms/op
ClientSimple.listUser                         avgt          3.300           ms/op
ClientSimple.createUser                     sample  16634   1.923 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.528           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.796           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.265           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.466           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.034           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.582           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.758           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.171           ms/op
ClientSimple.existUser                      sample  17992   1.778 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.572           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.638           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.048           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.204           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.613           ms/op
ClientSimple.existUser:existUser·p0.999     sample         33.358           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         33.456           ms/op
ClientSimple.existUser:existUser·p1.00      sample         33.456           ms/op
ClientSimple.getUser                        sample  15909   2.012 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.463           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.825           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.499           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.142           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.419           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.960           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.960           ms/op
ClientSimple.listUser                       sample   8702   3.678 ± 0.069   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.605           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.478           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.850           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.095           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.020           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.967           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.032           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.032           ms/op

Benchmark result is saved to 1716812080669.json
