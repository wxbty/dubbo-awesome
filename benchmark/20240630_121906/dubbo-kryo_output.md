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
# Warmup Iteration   1: 1.768 ops/ms
Iteration   1: 8.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.283 ops/ms


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
# Warmup Iteration   1: 6.114 ops/ms
Iteration   1: 12.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.476 ops/ms


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
# Warmup Iteration   1: 5.832 ops/ms
Iteration   1: 12.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.567 ops/ms


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
# Warmup Iteration   1: 3.939 ops/ms
Iteration   1: 7.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.261 ops/ms


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
# Warmup Iteration   1: 3.693 ±(99.9%) 0.051 ms/op
Iteration   1: 2.101 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.101 ms/op


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
# Warmup Iteration   1: 3.349 ±(99.9%) 0.048 ms/op
Iteration   1: 1.958 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.958 ms/op


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
# Warmup Iteration   1: 3.307 ±(99.9%) 0.051 ms/op
Iteration   1: 2.117 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.117 ms/op


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
# Warmup Iteration   1: 4.807 ±(99.9%) 0.104 ms/op
Iteration   1: 3.762 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.762 ms/op


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
# Warmup Iteration   1: 3.473 ±(99.9%) 0.077 ms/op
Iteration   1: 2.258 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.428 ms/op
                 createUser·p0.50:   1.892 ms/op
                 createUser·p0.90:   2.793 ms/op
                 createUser·p0.95:   3.204 ms/op
                 createUser·p0.99:   11.922 ms/op
                 createUser·p0.999:  22.905 ms/op
                 createUser·p0.9999: 22.970 ms/op
                 createUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14155
  mean =      2.258 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11268 
    [ 2.500,  5.000) = 2618 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.793 ms/op
     p(95.0000) =      3.204 ms/op
     p(99.0000) =     11.922 ms/op
     p(99.9000) =     22.905 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 3.197 ±(99.9%) 0.083 ms/op
Iteration   1: 1.778 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   1.686 ms/op
                 existUser·p0.90:   1.978 ms/op
                 existUser·p0.95:   2.286 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  18.514 ms/op
                 existUser·p0.9999: 20.080 ms/op
                 existUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17986
  mean =      1.778 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17562 
    [ 2.500,  5.000) = 291 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      1.686 ms/op
     p(90.0000) =      1.978 ms/op
     p(95.0000) =      2.286 ms/op
     p(99.0000) =      3.531 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     20.080 ms/op
     p(99.9990) =     20.185 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 3.306 ±(99.9%) 0.075 ms/op
Iteration   1: 2.104 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   1.997 ms/op
                 getUser·p0.90:   2.617 ms/op
                 getUser·p0.95:   2.859 ms/op
                 getUser·p0.99:   4.763 ms/op
                 getUser·p0.999:  15.204 ms/op
                 getUser·p0.9999: 16.119 ms/op
                 getUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15179
  mean =      2.104 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 150 
    [ 1.250,  2.500) = 12773 
    [ 2.500,  3.750) = 2020 
    [ 3.750,  5.000) = 135 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      4.763 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     16.119 ms/op
     p(99.9990) =     16.433 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


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
# Warmup Iteration   1: 4.929 ±(99.9%) 0.176 ms/op
Iteration   1: 3.038 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.157 ms/op
                 listUser·p0.99:   5.503 ms/op
                 listUser·p0.999:  6.508 ms/op
                 listUser·p0.9999: 6.626 ms/op
                 listUser·p1.00:   6.627 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10528
  mean =      3.038 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 18 
    [1.500, 2.000) = 139 
    [2.000, 2.500) = 2332 
    [2.500, 3.000) = 2940 
    [3.000, 3.500) = 2894 
    [3.500, 4.000) = 1384 
    [4.000, 4.500) = 606 
    [4.500, 5.000) = 74 
    [5.000, 5.500) = 34 
    [5.500, 6.000) = 77 
    [6.000, 6.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      5.503 ms/op
     p(99.9000) =      6.508 ms/op
     p(99.9900) =      6.626 ms/op
     p(99.9990) =      6.627 ms/op
     p(99.9999) =      6.627 ms/op
    p(100.0000) =      6.627 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.283          ops/ms
ClientSimple.existUser                       thrpt         12.476          ops/ms
ClientSimple.getUser                         thrpt         12.567          ops/ms
ClientSimple.listUser                        thrpt          7.261          ops/ms
ClientSimple.createUser                       avgt          2.101           ms/op
ClientSimple.existUser                        avgt          1.958           ms/op
ClientSimple.getUser                          avgt          2.117           ms/op
ClientSimple.listUser                         avgt          3.762           ms/op
ClientSimple.createUser                     sample  14155   2.258 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.428           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.892           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.793           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.204           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.922           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.905           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.970           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.970           ms/op
ClientSimple.existUser                      sample  17986   1.778 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.669           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.686           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.978           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.286           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.531           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.514           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.080           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.185           ms/op
ClientSimple.getUser                        sample  15179   2.104 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.944           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.997           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.859           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.763           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.204           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.119           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.433           ms/op
ClientSimple.listUser                       sample  10528   3.038 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.957           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.986           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.883           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.157           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.503           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.508           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.626           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.627           ms/op

Benchmark result is saved to 1719749673624.json
