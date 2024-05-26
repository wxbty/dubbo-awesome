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
# Warmup Iteration   1: 1.578 ops/ms
Iteration   1: 5.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.846 ops/ms


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
# Warmup Iteration   1: 6.781 ops/ms
Iteration   1: 12.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.802 ops/ms


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
# Warmup Iteration   1: 4.454 ops/ms
Iteration   1: 12.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.950 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.854 ops/ms
Iteration   1: 7.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.257 ops/ms


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
# Warmup Iteration   1: 4.347 ±(99.9%) 0.088 ms/op
Iteration   1: 2.256 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.256 ms/op


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
# Warmup Iteration   1: 3.449 ±(99.9%) 0.067 ms/op
Iteration   1: 2.202 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.202 ms/op


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
# Warmup Iteration   1: 3.297 ±(99.9%) 0.061 ms/op
Iteration   1: 2.066 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.066 ms/op


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
# Warmup Iteration   1: 4.354 ±(99.9%) 0.098 ms/op
Iteration   1: 3.527 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.527 ms/op


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
# Warmup Iteration   1: 3.249 ±(99.9%) 0.079 ms/op
Iteration   1: 2.129 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.587 ms/op
                 createUser·p0.50:   1.915 ms/op
                 createUser·p0.90:   2.597 ms/op
                 createUser·p0.95:   3.027 ms/op
                 createUser·p0.99:   8.806 ms/op
                 createUser·p0.999:  19.001 ms/op
                 createUser·p0.9999: 26.886 ms/op
                 createUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15049
  mean =      2.129 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13178 
    [ 2.500,  5.000) = 1512 
    [ 5.000,  7.500) = 197 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      8.806 ms/op
     p(99.9000) =     19.001 ms/op
     p(99.9900) =     26.886 ms/op
     p(99.9990) =     26.903 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 3.124 ±(99.9%) 0.076 ms/op
Iteration   1: 1.775 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   1.628 ms/op
                 existUser·p0.90:   2.171 ms/op
                 existUser·p0.95:   2.380 ms/op
                 existUser·p0.99:   2.928 ms/op
                 existUser·p0.999:  16.417 ms/op
                 existUser·p0.9999: 16.502 ms/op
                 existUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18021
  mean =      1.775 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 136 
    [ 1.250,  2.500) = 17252 
    [ 2.500,  3.750) = 534 
    [ 3.750,  5.000) = 3 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      1.628 ms/op
     p(90.0000) =      2.171 ms/op
     p(95.0000) =      2.380 ms/op
     p(99.0000) =      2.928 ms/op
     p(99.9000) =     16.417 ms/op
     p(99.9900) =     16.502 ms/op
     p(99.9990) =     16.515 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.089 ms/op
Iteration   1: 2.116 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   2.030 ms/op
                 getUser·p0.90:   2.601 ms/op
                 getUser·p0.95:   2.782 ms/op
                 getUser·p0.99:   3.614 ms/op
                 getUser·p0.999:  11.223 ms/op
                 getUser·p0.9999: 11.434 ms/op
                 getUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15173
  mean =      2.116 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 199 
    [ 1.250,  2.500) = 12741 
    [ 2.500,  3.750) = 2097 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.782 ms/op
     p(99.0000) =      3.614 ms/op
     p(99.9000) =     11.223 ms/op
     p(99.9900) =     11.434 ms/op
     p(99.9990) =     11.485 ms/op
     p(99.9999) =     11.485 ms/op
    p(100.0000) =     11.485 ms/op


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
# Warmup Iteration   1: 4.542 ±(99.9%) 0.137 ms/op
Iteration   1: 3.361 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.457 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   6.126 ms/op
                 listUser·p0.999:  7.643 ms/op
                 listUser·p0.9999: 9.388 ms/op
                 listUser·p1.00:   9.388 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9521
  mean =      3.361 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 88 
    [ 1.500,  2.000) = 440 
    [ 2.000,  2.500) = 1392 
    [ 2.500,  3.000) = 1433 
    [ 3.000,  3.500) = 1596 
    [ 3.500,  4.000) = 2490 
    [ 4.000,  4.500) = 1441 
    [ 4.500,  5.000) = 287 
    [ 5.000,  5.500) = 180 
    [ 5.500,  6.000) = 62 
    [ 6.000,  6.500) = 46 
    [ 6.500,  7.000) = 42 
    [ 7.000,  7.500) = 11 
    [ 7.500,  8.000) = 12 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.126 ms/op
     p(99.9000) =      7.643 ms/op
     p(99.9900) =      9.388 ms/op
     p(99.9990) =      9.388 ms/op
     p(99.9999) =      9.388 ms/op
    p(100.0000) =      9.388 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.846          ops/ms
ClientSimple.existUser                       thrpt         12.802          ops/ms
ClientSimple.getUser                         thrpt         12.950          ops/ms
ClientSimple.listUser                        thrpt          7.257          ops/ms
ClientSimple.createUser                       avgt          2.256           ms/op
ClientSimple.existUser                        avgt          2.202           ms/op
ClientSimple.getUser                          avgt          2.066           ms/op
ClientSimple.listUser                         avgt          3.527           ms/op
ClientSimple.createUser                     sample  15049   2.129 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.587           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.915           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.597           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.027           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.806           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.001           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.886           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.903           ms/op
ClientSimple.existUser                      sample  18021   1.775 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.939           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.628           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.171           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.928           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.417           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.502           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.515           ms/op
ClientSimple.getUser                        sample  15173   2.116 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.690           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.030           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.782           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.614           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.223           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.434           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.485           ms/op
ClientSimple.listUser                       sample   9521   3.361 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.057           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.457           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.710           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.126           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.643           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.388           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.388           ms/op

Benchmark result is saved to 1716725596324.json
