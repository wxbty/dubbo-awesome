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
# Warmup Iteration   1: 1.797 ops/ms
Iteration   1: 8.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.476 ops/ms


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
# Warmup Iteration   1: 6.217 ops/ms
Iteration   1: 12.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.224 ops/ms


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
# Warmup Iteration   1: 5.653 ops/ms
Iteration   1: 11.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.734 ops/ms


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
# Warmup Iteration   1: 4.738 ops/ms
Iteration   1: 8.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.394 ops/ms


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
# Warmup Iteration   1: 3.628 ±(99.9%) 0.062 ms/op
Iteration   1: 2.274 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.274 ms/op


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
# Warmup Iteration   1: 2.983 ±(99.9%) 0.045 ms/op
Iteration   1: 1.724 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.724 ms/op


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
# Warmup Iteration   1: 3.485 ±(99.9%) 0.077 ms/op
Iteration   1: 1.856 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.856 ms/op


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
# Warmup Iteration   1: 4.810 ±(99.9%) 0.127 ms/op
Iteration   1: 3.827 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.827 ms/op


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
# Warmup Iteration   1: 3.698 ±(99.9%) 0.091 ms/op
Iteration   1: 2.196 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   1.989 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   2.953 ms/op
                 createUser·p0.99:   5.167 ms/op
                 createUser·p0.999:  15.303 ms/op
                 createUser·p0.9999: 15.550 ms/op
                 createUser·p1.00:   15.565 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14557
  mean =      2.196 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 192 
    [ 1.250,  2.500) = 11209 
    [ 2.500,  3.750) = 2976 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      5.167 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     15.550 ms/op
     p(99.9990) =     15.565 ms/op
     p(99.9999) =     15.565 ms/op
    p(100.0000) =     15.565 ms/op


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
# Warmup Iteration   1: 2.980 ±(99.9%) 0.061 ms/op
Iteration   1: 1.902 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.308 ms/op
                 existUser·p0.50:   1.698 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.544 ms/op
                 existUser·p0.99:   3.282 ms/op
                 existUser·p0.999:  22.381 ms/op
                 existUser·p0.9999: 22.784 ms/op
                 existUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16967
  mean =      1.902 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15955 
    [ 2.500,  5.000) = 934 
    [ 5.000,  7.500) = 14 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.308 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =      3.282 ms/op
     p(99.9000) =     22.381 ms/op
     p(99.9900) =     22.784 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 3.177 ±(99.9%) 0.082 ms/op
Iteration   1: 1.941 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.651 ms/op
                 getUser·p0.50:   1.792 ms/op
                 getUser·p0.90:   2.499 ms/op
                 getUser·p0.95:   2.712 ms/op
                 getUser·p0.99:   3.508 ms/op
                 getUser·p0.999:  11.583 ms/op
                 getUser·p0.9999: 11.726 ms/op
                 getUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16459
  mean =      1.941 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 14646 
    [ 2.500,  3.750) = 1540 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      1.792 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      3.508 ms/op
     p(99.9000) =     11.583 ms/op
     p(99.9900) =     11.726 ms/op
     p(99.9990) =     11.747 ms/op
     p(99.9999) =     11.747 ms/op
    p(100.0000) =     11.747 ms/op


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
# Warmup Iteration   1: 4.362 ±(99.9%) 0.112 ms/op
Iteration   1: 3.440 ±(99.9%) 0.070 ms/op
                 listUser·p0.00:   0.555 ms/op
                 listUser·p0.50:   3.367 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.834 ms/op
                 listUser·p0.999:  36.110 ms/op
                 listUser·p0.9999: 36.897 ms/op
                 listUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9286
  mean =      3.440 ±(99.9%) 0.070 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1331 
    [ 2.500,  5.000) = 7815 
    [ 5.000,  7.500) = 91 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.834 ms/op
     p(99.9000) =     36.110 ms/op
     p(99.9900) =     36.897 ms/op
     p(99.9990) =     36.897 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.476          ops/ms
ClientSimple.existUser                       thrpt         12.224          ops/ms
ClientSimple.getUser                         thrpt         11.734          ops/ms
ClientSimple.listUser                        thrpt          8.394          ops/ms
ClientSimple.createUser                       avgt          2.274           ms/op
ClientSimple.existUser                        avgt          1.724           ms/op
ClientSimple.getUser                          avgt          1.856           ms/op
ClientSimple.listUser                         avgt          3.827           ms/op
ClientSimple.createUser                     sample  14557   2.196 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.603           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.989           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.167           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.303           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.550           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.565           ms/op
ClientSimple.existUser                      sample  16967   1.902 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.308           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.698           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.282           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.381           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.784           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.807           ms/op
ClientSimple.getUser                        sample  16459   1.941 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.651           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.792           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.499           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.508           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.583           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.726           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.747           ms/op
ClientSimple.listUser                       sample   9286   3.440 ± 0.070   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.555           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.367           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.834           ms/op
ClientSimple.listUser:listUser·p0.999       sample         36.110           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         36.897           ms/op
ClientSimple.listUser:listUser·p1.00        sample         36.897           ms/op

Benchmark result is saved to 1717179044258.json
