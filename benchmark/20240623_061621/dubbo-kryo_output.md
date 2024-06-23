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
Iteration   1: 6.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.636 ops/ms


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
# Warmup Iteration   1: 6.326 ops/ms
Iteration   1: 12.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.143 ops/ms


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
# Warmup Iteration   1: 5.403 ops/ms
Iteration   1: 10.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.357 ops/ms


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
# Warmup Iteration   1: 4.457 ops/ms
Iteration   1: 8.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.439 ops/ms


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.069 ms/op
Iteration   1: 1.986 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.986 ms/op


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
# Warmup Iteration   1: 3.232 ±(99.9%) 0.049 ms/op
Iteration   1: 1.848 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.848 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.059 ms/op
Iteration   1: 2.043 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.043 ms/op


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
# Warmup Iteration   1: 5.015 ±(99.9%) 0.096 ms/op
Iteration   1: 3.434 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.434 ms/op


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
# Warmup Iteration   1: 3.454 ±(99.9%) 0.080 ms/op
Iteration   1: 2.481 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.678 ms/op
                 createUser·p0.50:   2.290 ms/op
                 createUser·p0.90:   2.933 ms/op
                 createUser·p0.95:   3.229 ms/op
                 createUser·p0.99:   8.864 ms/op
                 createUser·p0.999:  26.084 ms/op
                 createUser·p0.9999: 32.252 ms/op
                 createUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13394
  mean =      2.481 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9046 
    [ 2.500,  5.000) = 4057 
    [ 5.000,  7.500) = 131 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      2.290 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.229 ms/op
     p(99.0000) =      8.864 ms/op
     p(99.9000) =     26.084 ms/op
     p(99.9900) =     32.252 ms/op
     p(99.9990) =     32.408 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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
# Warmup Iteration   1: 2.953 ±(99.9%) 0.072 ms/op
Iteration   1: 1.989 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   1.894 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.683 ms/op
                 existUser·p0.99:   4.402 ms/op
                 existUser·p0.999:  15.236 ms/op
                 existUser·p0.9999: 15.368 ms/op
                 existUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16080
  mean =      1.989 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 175 
    [ 1.250,  2.500) = 14515 
    [ 2.500,  3.750) = 1136 
    [ 3.750,  5.000) = 181 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      1.894 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      4.402 ms/op
     p(99.9000) =     15.236 ms/op
     p(99.9900) =     15.368 ms/op
     p(99.9990) =     15.368 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


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
# Warmup Iteration   1: 3.115 ±(99.9%) 0.071 ms/op
Iteration   1: 1.938 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   1.751 ms/op
                 getUser·p0.90:   2.388 ms/op
                 getUser·p0.95:   2.605 ms/op
                 getUser·p0.99:   4.195 ms/op
                 getUser·p0.999:  18.006 ms/op
                 getUser·p0.9999: 18.055 ms/op
                 getUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16495
  mean =      1.938 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 15251 
    [ 2.500,  3.750) = 1003 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      1.751 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      4.195 ms/op
     p(99.9000) =     18.006 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.124 ms/op
Iteration   1: 3.426 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   3.420 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.079 ms/op
                 listUser·p0.999:  6.510 ms/op
                 listUser·p0.9999: 8.241 ms/op
                 listUser·p1.00:   8.241 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9329
  mean =      3.426 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 9 
    [1.500, 2.000) = 83 
    [2.000, 2.500) = 621 
    [2.500, 3.000) = 2109 
    [3.000, 3.500) = 2117 
    [3.500, 4.000) = 2489 
    [4.000, 4.500) = 1493 
    [4.500, 5.000) = 307 
    [5.000, 5.500) = 53 
    [5.500, 6.000) = 21 
    [6.000, 6.500) = 17 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =      6.510 ms/op
     p(99.9900) =      8.241 ms/op
     p(99.9990) =      8.241 ms/op
     p(99.9999) =      8.241 ms/op
    p(100.0000) =      8.241 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.636          ops/ms
ClientSimple.existUser                       thrpt         12.143          ops/ms
ClientSimple.getUser                         thrpt         10.357          ops/ms
ClientSimple.listUser                        thrpt          8.439          ops/ms
ClientSimple.createUser                       avgt          1.986           ms/op
ClientSimple.existUser                        avgt          1.848           ms/op
ClientSimple.getUser                          avgt          2.043           ms/op
ClientSimple.listUser                         avgt          3.434           ms/op
ClientSimple.createUser                     sample  13394   2.481 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.678           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.290           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.933           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.229           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.864           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.084           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.252           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.408           ms/op
ClientSimple.existUser                      sample  16080   1.989 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.606           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.894           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.683           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.402           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.236           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.368           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.368           ms/op
ClientSimple.getUser                        sample  16495   1.938 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.795           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.751           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.388           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.195           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.006           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.055           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.055           ms/op
ClientSimple.listUser                       sample   9329   3.426 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.235           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.420           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.079           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.510           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.241           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.241           ms/op

Benchmark result is saved to 1719123117252.json
