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
# Warmup Iteration   1: 1.743 ops/ms
Iteration   1: 6.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.981 ops/ms


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
# Warmup Iteration   1: 6.859 ops/ms
Iteration   1: 13.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.571 ops/ms


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
# Warmup Iteration   1: 5.589 ops/ms
Iteration   1: 12.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.289 ops/ms


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
# Warmup Iteration   1: 4.214 ops/ms
Iteration   1: 6.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  6.802 ops/ms


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
# Warmup Iteration   1: 4.216 ±(99.9%) 0.070 ms/op
Iteration   1: 2.274 ±(99.9%) 0.009 ms/op


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
# Warmup Iteration   1: 2.930 ±(99.9%) 0.042 ms/op
Iteration   1: 1.808 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.808 ms/op


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
# Warmup Iteration   1: 3.242 ±(99.9%) 0.068 ms/op
Iteration   1: 2.170 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.170 ms/op


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
# Warmup Iteration   1: 4.357 ±(99.9%) 0.101 ms/op
Iteration   1: 3.537 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.537 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.105 ms/op
Iteration   1: 2.417 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   2.351 ms/op
                 createUser·p0.90:   2.871 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   6.235 ms/op
                 createUser·p0.999:  13.283 ms/op
                 createUser·p0.9999: 14.179 ms/op
                 createUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13246
  mean =      2.417 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 8094 
    [ 2.500,  3.750) = 4742 
    [ 3.750,  5.000) = 138 
    [ 5.000,  6.250) = 93 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.351 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      6.235 ms/op
     p(99.9000) =     13.283 ms/op
     p(99.9900) =     14.179 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 2.920 ±(99.9%) 0.070 ms/op
Iteration   1: 1.839 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   1.710 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.511 ms/op
                 existUser·p0.99:   3.475 ms/op
                 existUser·p0.999:  20.238 ms/op
                 existUser·p0.9999: 20.923 ms/op
                 existUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17382
  mean =      1.839 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16484 
    [ 2.500,  5.000) = 817 
    [ 5.000,  7.500) = 17 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      1.710 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.511 ms/op
     p(99.0000) =      3.475 ms/op
     p(99.9000) =     20.238 ms/op
     p(99.9900) =     20.923 ms/op
     p(99.9990) =     20.972 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.078 ms/op
Iteration   1: 2.106 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.454 ms/op
                 getUser·p0.50:   1.997 ms/op
                 getUser·p0.90:   2.548 ms/op
                 getUser·p0.95:   2.793 ms/op
                 getUser·p0.99:   3.629 ms/op
                 getUser·p0.999:  12.791 ms/op
                 getUser·p0.9999: 12.960 ms/op
                 getUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15302
  mean =      2.106 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 13409 
    [ 2.500,  3.750) = 1637 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =     12.791 ms/op
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
# Warmup Iteration   1: 4.467 ±(99.9%) 0.141 ms/op
Iteration   1: 3.467 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.042 ms/op
                 listUser·p0.50:   3.465 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   6.491 ms/op
                 listUser·p0.999:  7.111 ms/op
                 listUser·p0.9999: 7.274 ms/op
                 listUser·p1.00:   7.274 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9267
  mean =      3.467 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 25 
    [1.500, 2.000) = 113 
    [2.000, 2.500) = 681 
    [2.500, 3.000) = 2326 
    [3.000, 3.500) = 1635 
    [3.500, 4.000) = 2388 
    [4.000, 4.500) = 1283 
    [4.500, 5.000) = 545 
    [5.000, 5.500) = 154 
    [5.500, 6.000) = 14 
    [6.000, 6.500) = 12 
    [6.500, 7.000) = 65 
    [7.000, 7.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.491 ms/op
     p(99.9000) =      7.111 ms/op
     p(99.9900) =      7.274 ms/op
     p(99.9990) =      7.274 ms/op
     p(99.9999) =      7.274 ms/op
    p(100.0000) =      7.274 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.981          ops/ms
ClientSimple.existUser                       thrpt         13.571          ops/ms
ClientSimple.getUser                         thrpt         12.289          ops/ms
ClientSimple.listUser                        thrpt          6.802          ops/ms
ClientSimple.createUser                       avgt          2.274           ms/op
ClientSimple.existUser                        avgt          1.808           ms/op
ClientSimple.getUser                          avgt          2.170           ms/op
ClientSimple.listUser                         avgt          3.537           ms/op
ClientSimple.createUser                     sample  13246   2.417 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.878           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.351           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.871           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.170           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.235           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.283           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.179           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.238           ms/op
ClientSimple.existUser                      sample  17382   1.839 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.684           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.710           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.511           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.475           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.238           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.923           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.972           ms/op
ClientSimple.getUser                        sample  15302   2.106 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.454           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.997           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.548           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.793           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.629           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.791           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.960           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.960           ms/op
ClientSimple.listUser                       sample   9267   3.467 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.042           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.465           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.710           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.491           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.111           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.274           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.274           ms/op

Benchmark result is saved to 1717288789795.json
