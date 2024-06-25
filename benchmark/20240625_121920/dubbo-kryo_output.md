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
# Warmup Iteration   1: 1.873 ops/ms
Iteration   1: 7.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.632 ops/ms


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
# Warmup Iteration   1: 6.155 ops/ms
Iteration   1: 13.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.771 ops/ms


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
# Warmup Iteration   1: 6.546 ops/ms
Iteration   1: 13.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.998 ops/ms


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
# Warmup Iteration   1: 5.225 ops/ms
Iteration   1: 8.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.265 ops/ms


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.077 ms/op
Iteration   1: 2.036 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.036 ms/op


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
# Warmup Iteration   1: 3.174 ±(99.9%) 0.056 ms/op
Iteration   1: 2.109 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.109 ms/op


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
# Warmup Iteration   1: 3.480 ±(99.9%) 0.058 ms/op
Iteration   1: 1.925 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.925 ms/op


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
# Warmup Iteration   1: 4.282 ±(99.9%) 0.094 ms/op
Iteration   1: 3.291 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.291 ms/op


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.100 ms/op
Iteration   1: 2.205 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.408 ms/op
                 createUser·p0.50:   1.980 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   6.740 ms/op
                 createUser·p0.999:  21.029 ms/op
                 createUser·p0.9999: 25.494 ms/op
                 createUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14524
  mean =      2.205 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12191 
    [ 2.500,  5.000) = 1994 
    [ 5.000,  7.500) = 227 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      6.740 ms/op
     p(99.9000) =     21.029 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 3.079 ±(99.9%) 0.066 ms/op
Iteration   1: 2.027 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.475 ms/op
                 existUser·p0.50:   1.954 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.568 ms/op
                 existUser·p0.99:   3.310 ms/op
                 existUser·p0.999:  27.200 ms/op
                 existUser·p0.9999: 28.431 ms/op
                 existUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15909
  mean =      2.027 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14891 
    [ 2.500,  5.000) = 951 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.310 ms/op
     p(99.9000) =     27.200 ms/op
     p(99.9900) =     28.431 ms/op
     p(99.9990) =     28.508 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 3.234 ±(99.9%) 0.086 ms/op
Iteration   1: 2.134 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.631 ms/op
                 getUser·p0.50:   2.060 ms/op
                 getUser·p0.90:   2.683 ms/op
                 getUser·p0.95:   2.879 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  12.896 ms/op
                 getUser·p0.9999: 13.460 ms/op
                 getUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14982
  mean =      2.134 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 12040 
    [ 2.500,  3.750) = 2734 
    [ 3.750,  5.000) = 24 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =     12.896 ms/op
     p(99.9900) =     13.460 ms/op
     p(99.9990) =     13.566 ms/op
     p(99.9999) =     13.566 ms/op
    p(100.0000) =     13.566 ms/op


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
# Warmup Iteration   1: 4.705 ±(99.9%) 0.124 ms/op
Iteration   1: 3.874 ±(99.9%) 0.059 ms/op
                 listUser·p0.00:   1.479 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   9.004 ms/op
                 listUser·p0.999:  22.708 ms/op
                 listUser·p0.9999: 22.905 ms/op
                 listUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8341
  mean =      3.874 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 263 
    [ 2.500,  5.000) = 7595 
    [ 5.000,  7.500) = 354 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.479 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      9.004 ms/op
     p(99.9000) =     22.708 ms/op
     p(99.9900) =     22.905 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.632          ops/ms
ClientSimple.existUser                       thrpt         13.771          ops/ms
ClientSimple.getUser                         thrpt         13.998          ops/ms
ClientSimple.listUser                        thrpt          8.265          ops/ms
ClientSimple.createUser                       avgt          2.036           ms/op
ClientSimple.existUser                        avgt          2.109           ms/op
ClientSimple.getUser                          avgt          1.925           ms/op
ClientSimple.listUser                         avgt          3.291           ms/op
ClientSimple.createUser                     sample  14524   2.205 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.408           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.980           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.203           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.740           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.029           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.494           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.494           ms/op
ClientSimple.existUser                      sample  15909   2.027 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.475           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.954           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.310           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.200           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.431           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.508           ms/op
ClientSimple.getUser                        sample  14982   2.134 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.631           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.060           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.879           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.609           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.896           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.460           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.566           ms/op
ClientSimple.listUser                       sample   8341   3.874 ± 0.059   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.479           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.740           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.333           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.004           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.708           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.905           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.905           ms/op

Benchmark result is saved to 1719317710306.json
