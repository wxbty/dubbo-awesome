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
# Warmup Iteration   1: 1.764 ops/ms
Iteration   1: 6.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.744 ops/ms


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
# Warmup Iteration   1: 5.881 ops/ms
Iteration   1: 13.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.192 ops/ms


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
# Warmup Iteration   1: 6.364 ops/ms
Iteration   1: 13.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.235 ops/ms


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
# Warmup Iteration   1: 4.699 ops/ms
Iteration   1: 7.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.918 ops/ms


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.077 ms/op
Iteration   1: 2.024 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.024 ms/op


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
# Warmup Iteration   1: 3.414 ±(99.9%) 0.087 ms/op
Iteration   1: 1.917 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.917 ms/op


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
# Warmup Iteration   1: 3.289 ±(99.9%) 0.076 ms/op
Iteration   1: 2.118 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.118 ms/op


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
# Warmup Iteration   1: 4.650 ±(99.9%) 0.137 ms/op
Iteration   1: 3.447 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.447 ms/op


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
# Warmup Iteration   1: 3.629 ±(99.9%) 0.101 ms/op
Iteration   1: 2.148 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.514 ms/op
                 createUser·p0.50:   1.858 ms/op
                 createUser·p0.90:   2.806 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   11.256 ms/op
                 createUser·p0.999:  17.764 ms/op
                 createUser·p0.9999: 31.081 ms/op
                 createUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14887
  mean =      2.148 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12208 
    [ 2.500,  5.000) = 2345 
    [ 5.000,  7.500) = 132 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =     11.256 ms/op
     p(99.9000) =     17.764 ms/op
     p(99.9900) =     31.081 ms/op
     p(99.9990) =     31.097 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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
# Warmup Iteration   1: 3.094 ±(99.9%) 0.084 ms/op
Iteration   1: 1.701 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.359 ms/op
                 existUser·p0.50:   1.513 ms/op
                 existUser·p0.90:   2.195 ms/op
                 existUser·p0.95:   2.470 ms/op
                 existUser·p0.99:   4.985 ms/op
                 existUser·p0.999:  21.305 ms/op
                 existUser·p0.9999: 21.675 ms/op
                 existUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18826
  mean =      1.701 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17957 
    [ 2.500,  5.000) = 683 
    [ 5.000,  7.500) = 56 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.359 ms/op
     p(50.0000) =      1.513 ms/op
     p(90.0000) =      2.195 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      4.985 ms/op
     p(99.9000) =     21.305 ms/op
     p(99.9900) =     21.675 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 4.075 ±(99.9%) 0.123 ms/op
Iteration   1: 2.132 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   2.077 ms/op
                 getUser·p0.90:   2.601 ms/op
                 getUser·p0.95:   2.806 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  11.387 ms/op
                 getUser·p0.9999: 12.736 ms/op
                 getUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15025
  mean =      2.132 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 279 
    [ 1.250,  2.500) = 12630 
    [ 2.500,  3.750) = 1924 
    [ 3.750,  5.000) = 91 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.077 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =     11.387 ms/op
     p(99.9900) =     12.736 ms/op
     p(99.9990) =     13.173 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.134 ms/op
Iteration   1: 3.444 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.203 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.761 ms/op
                 listUser·p0.999:  20.873 ms/op
                 listUser·p0.9999: 21.627 ms/op
                 listUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9279
  mean =      3.444 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 361 
    [ 2.500,  5.000) = 8765 
    [ 5.000,  7.500) = 114 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.761 ms/op
     p(99.9000) =     20.873 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     21.627 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.744          ops/ms
ClientSimple.existUser                       thrpt         13.192          ops/ms
ClientSimple.getUser                         thrpt         13.235          ops/ms
ClientSimple.listUser                        thrpt          7.918          ops/ms
ClientSimple.createUser                       avgt          2.024           ms/op
ClientSimple.existUser                        avgt          1.917           ms/op
ClientSimple.getUser                          avgt          2.118           ms/op
ClientSimple.listUser                         avgt          3.447           ms/op
ClientSimple.createUser                     sample  14887   2.148 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.514           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.858           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.806           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.215           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.256           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.764           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.081           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.097           ms/op
ClientSimple.existUser                      sample  18826   1.701 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.359           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.513           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.195           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.985           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.305           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.675           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.791           ms/op
ClientSimple.getUser                        sample  15025   2.132 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.748           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.077           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.293           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.387           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.736           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.173           ms/op
ClientSimple.listUser                       sample   9279   3.444 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.274           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.203           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.761           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.873           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.627           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.627           ms/op

Benchmark result is saved to 1717611044346.json
