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
# Warmup Iteration   1: 1.621 ops/ms
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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.592 ops/ms
Iteration   1: 13.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.023 ops/ms


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
# Warmup Iteration   1: 5.339 ops/ms
Iteration   1: 11.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.778 ops/ms


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
# Warmup Iteration   1: 4.140 ops/ms
Iteration   1: 8.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.166 ops/ms


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
# Warmup Iteration   1: 3.733 ±(99.9%) 0.076 ms/op
Iteration   1: 2.209 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.209 ms/op


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
# Warmup Iteration   1: 3.390 ±(99.9%) 0.056 ms/op
Iteration   1: 2.019 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.019 ms/op


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
# Warmup Iteration   1: 3.487 ±(99.9%) 0.058 ms/op
Iteration   1: 2.023 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.023 ms/op


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
# Warmup Iteration   1: 4.481 ±(99.9%) 0.092 ms/op
Iteration   1: 3.121 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.121 ms/op


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
# Warmup Iteration   1: 3.577 ±(99.9%) 0.091 ms/op
Iteration   1: 2.052 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   1.845 ms/op
                 createUser·p0.90:   2.580 ms/op
                 createUser·p0.95:   2.998 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  15.745 ms/op
                 createUser·p0.9999: 16.377 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15546
  mean =      2.052 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 13709 
    [ 2.500,  3.750) = 1478 
    [ 3.750,  5.000) = 192 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.998 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     16.377 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 2.889 ±(99.9%) 0.066 ms/op
Iteration   1: 1.892 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   1.802 ms/op
                 existUser·p0.90:   2.191 ms/op
                 existUser·p0.95:   2.351 ms/op
                 existUser·p0.99:   3.141 ms/op
                 existUser·p0.999:  27.269 ms/op
                 existUser·p0.9999: 28.148 ms/op
                 existUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16907
  mean =      1.892 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16428 
    [ 2.500,  5.000) = 406 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.191 ms/op
     p(95.0000) =      2.351 ms/op
     p(99.0000) =      3.141 ms/op
     p(99.9000) =     27.269 ms/op
     p(99.9900) =     28.148 ms/op
     p(99.9990) =     28.148 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 3.291 ±(99.9%) 0.078 ms/op
Iteration   1: 2.012 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.635 ms/op
                 getUser·p0.50:   1.911 ms/op
                 getUser·p0.90:   2.519 ms/op
                 getUser·p0.95:   2.650 ms/op
                 getUser·p0.99:   3.843 ms/op
                 getUser·p0.999:  11.354 ms/op
                 getUser·p0.9999: 11.546 ms/op
                 getUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15887
  mean =      2.012 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 14114 
    [ 2.500,  3.750) = 1544 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.843 ms/op
     p(99.9000) =     11.354 ms/op
     p(99.9900) =     11.546 ms/op
     p(99.9990) =     11.633 ms/op
     p(99.9999) =     11.633 ms/op
    p(100.0000) =     11.633 ms/op


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
# Warmup Iteration   1: 4.427 ±(99.9%) 0.136 ms/op
Iteration   1: 3.661 ±(99.9%) 0.270 ms/op
                 listUser·p0.00:   0.451 ms/op
                 listUser·p0.50:   3.170 ms/op
                 listUser·p0.90:   4.048 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.210 ms/op
                 listUser·p0.999:  131.273 ms/op
                 listUser·p0.9999: 134.087 ms/op
                 listUser·p1.00:   134.087 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8746
  mean =      3.661 ±(99.9%) 0.270 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 8683 
    [ 12.500,  25.000) = 31 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 0 
    [112.500, 125.000) = 5 
    [125.000, 137.500) = 27 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      4.048 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =    131.273 ms/op
     p(99.9900) =    134.087 ms/op
     p(99.9990) =    134.087 ms/op
     p(99.9999) =    134.087 ms/op
    p(100.0000) =    134.087 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           6.969          ops/ms
ClientSimple.existUser                       thrpt          13.023          ops/ms
ClientSimple.getUser                         thrpt          11.778          ops/ms
ClientSimple.listUser                        thrpt           8.166          ops/ms
ClientSimple.createUser                       avgt           2.209           ms/op
ClientSimple.existUser                        avgt           2.019           ms/op
ClientSimple.getUser                          avgt           2.023           ms/op
ClientSimple.listUser                         avgt           3.121           ms/op
ClientSimple.createUser                     sample  15546    2.052 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.799           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.845           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.580           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.998           ms/op
ClientSimple.createUser:createUser·p0.99    sample           5.005           ms/op
ClientSimple.createUser:createUser·p0.999   sample          15.745           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          16.377           ms/op
ClientSimple.createUser:createUser·p1.00    sample          16.777           ms/op
ClientSimple.existUser                      sample  16907    1.892 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.579           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.802           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.191           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.351           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.141           ms/op
ClientSimple.existUser:existUser·p0.999     sample          27.269           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          28.148           ms/op
ClientSimple.existUser:existUser·p1.00      sample          28.148           ms/op
ClientSimple.getUser                        sample  15887    2.012 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.635           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.911           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.519           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.650           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.843           ms/op
ClientSimple.getUser:getUser·p0.999         sample          11.354           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          11.546           ms/op
ClientSimple.getUser:getUser·p1.00          sample          11.633           ms/op
ClientSimple.listUser                       sample   8746    3.661 ± 0.270   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.451           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.170           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.048           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.210           ms/op
ClientSimple.listUser:listUser·p0.999       sample         131.273           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         134.087           ms/op
ClientSimple.listUser:listUser·p1.00        sample         134.087           ms/op

Benchmark result is saved to 1718626526895.json
