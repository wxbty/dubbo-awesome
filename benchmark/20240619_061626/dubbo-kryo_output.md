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
# Warmup Iteration   1: 1.815 ops/ms
Iteration   1: 6.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.969 ops/ms


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
# Warmup Iteration   1: 5.686 ops/ms
Iteration   1: 12.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.496 ops/ms


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
# Warmup Iteration   1: 5.551 ops/ms
Iteration   1: 12.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.698 ops/ms


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
# Warmup Iteration   1: 3.388 ops/ms
Iteration   1: 8.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.259 ops/ms


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.074 ms/op
Iteration   1: 2.203 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.203 ms/op


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
# Warmup Iteration   1: 3.751 ±(99.9%) 0.064 ms/op
Iteration   1: 2.084 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.084 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.051 ms/op
Iteration   1: 2.018 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.018 ms/op


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
# Warmup Iteration   1: 5.065 ±(99.9%) 0.126 ms/op
Iteration   1: 4.004 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.004 ms/op


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.094 ms/op
Iteration   1: 2.388 ±(99.9%) 0.055 ms/op
                 createUser·p0.00:   0.401 ms/op
                 createUser·p0.50:   2.114 ms/op
                 createUser·p0.90:   2.961 ms/op
                 createUser·p0.95:   3.416 ms/op
                 createUser·p0.99:   11.846 ms/op
                 createUser·p0.999:  27.784 ms/op
                 createUser·p0.9999: 28.234 ms/op
                 createUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13549
  mean =      2.388 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9926 
    [ 2.500,  5.000) = 3264 
    [ 5.000,  7.500) = 103 
    [ 7.500, 10.000) = 53 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.401 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.416 ms/op
     p(99.0000) =     11.846 ms/op
     p(99.9000) =     27.784 ms/op
     p(99.9900) =     28.234 ms/op
     p(99.9990) =     28.246 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 3.451 ±(99.9%) 0.145 ms/op
Iteration   1: 1.863 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   1.755 ms/op
                 existUser·p0.90:   2.384 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   3.944 ms/op
                 existUser·p0.999:  16.613 ms/op
                 existUser·p0.9999: 16.974 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17243
  mean =      1.863 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1254 
    [ 1.250,  2.500) = 14744 
    [ 2.500,  3.750) = 989 
    [ 3.750,  5.000) = 158 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      1.755 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =     16.613 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.236 ms/op
Iteration   1: 2.363 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   2.249 ms/op
                 getUser·p0.90:   2.769 ms/op
                 getUser·p0.95:   3.012 ms/op
                 getUser·p0.99:   3.980 ms/op
                 getUser·p0.999:  29.409 ms/op
                 getUser·p0.9999: 30.110 ms/op
                 getUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13514
  mean =      2.363 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10088 
    [ 2.500,  5.000) = 3352 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.249 ms/op
     p(90.0000) =      2.769 ms/op
     p(95.0000) =      3.012 ms/op
     p(99.0000) =      3.980 ms/op
     p(99.9000) =     29.409 ms/op
     p(99.9900) =     30.110 ms/op
     p(99.9990) =     30.179 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 4.325 ±(99.9%) 0.106 ms/op
Iteration   1: 3.062 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.774 ms/op
                 listUser·p0.50:   2.847 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.731 ms/op
                 listUser·p0.999:  8.562 ms/op
                 listUser·p0.9999: 10.031 ms/op
                 listUser·p1.00:   10.076 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10444
  mean =      3.062 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 86 
    [ 2.000,  3.000) = 6635 
    [ 3.000,  4.000) = 2686 
    [ 4.000,  5.000) = 882 
    [ 5.000,  6.000) = 70 
    [ 6.000,  7.000) = 47 
    [ 7.000,  8.000) = 4 
    [ 8.000,  9.000) = 31 
    [ 9.000, 10.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.731 ms/op
     p(99.9000) =      8.562 ms/op
     p(99.9900) =     10.031 ms/op
     p(99.9990) =     10.076 ms/op
     p(99.9999) =     10.076 ms/op
    p(100.0000) =     10.076 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.969          ops/ms
ClientSimple.existUser                       thrpt         12.496          ops/ms
ClientSimple.getUser                         thrpt         12.698          ops/ms
ClientSimple.listUser                        thrpt          8.259          ops/ms
ClientSimple.createUser                       avgt          2.203           ms/op
ClientSimple.existUser                        avgt          2.084           ms/op
ClientSimple.getUser                          avgt          2.018           ms/op
ClientSimple.listUser                         avgt          4.004           ms/op
ClientSimple.createUser                     sample  13549   2.388 ± 0.055   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.401           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.114           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.961           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.416           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.846           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.784           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.234           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.246           ms/op
ClientSimple.existUser                      sample  17243   1.863 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.760           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.755           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.384           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.944           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.613           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.974           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.974           ms/op
ClientSimple.getUser                        sample  13514   2.363 ± 0.041   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.851           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.249           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.769           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.012           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.980           ms/op
ClientSimple.getUser:getUser·p0.999         sample         29.409           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         30.110           ms/op
ClientSimple.getUser:getUser·p1.00          sample         30.179           ms/op
ClientSimple.listUser                       sample  10444   3.062 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.774           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.847           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.998           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.731           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.562           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.031           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.076           ms/op

Benchmark result is saved to 1718777536700.json
