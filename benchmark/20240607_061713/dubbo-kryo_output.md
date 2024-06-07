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
# Warmup Iteration   1: 1.824 ops/ms
Iteration   1: 7.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.019 ops/ms


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
# Warmup Iteration   1: 6.403 ops/ms
Iteration   1: 12.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.818 ops/ms


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
# Warmup Iteration   1: 6.626 ops/ms
Iteration   1: 14.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.947 ops/ms


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
# Warmup Iteration   1: 5.965 ops/ms
Iteration   1: 9.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.060 ops/ms


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.069 ms/op
Iteration   1: 2.160 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.160 ms/op


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
# Warmup Iteration   1: 3.120 ±(99.9%) 0.051 ms/op
Iteration   1: 1.819 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.819 ms/op


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
# Warmup Iteration   1: 3.296 ±(99.9%) 0.057 ms/op
Iteration   1: 2.051 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.051 ms/op


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
# Warmup Iteration   1: 4.303 ±(99.9%) 0.094 ms/op
Iteration   1: 3.335 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.335 ms/op


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
# Warmup Iteration   1: 3.751 ±(99.9%) 0.091 ms/op
Iteration   1: 2.130 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   1.935 ms/op
                 createUser·p0.90:   2.458 ms/op
                 createUser·p0.95:   2.716 ms/op
                 createUser·p0.99:   7.586 ms/op
                 createUser·p0.999:  29.000 ms/op
                 createUser·p0.9999: 29.981 ms/op
                 createUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15012
  mean =      2.130 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13656 
    [ 2.500,  5.000) = 1142 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     29.000 ms/op
     p(99.9900) =     29.981 ms/op
     p(99.9990) =     30.671 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 2.988 ±(99.9%) 0.064 ms/op
Iteration   1: 2.106 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.232 ms/op
                 existUser·p0.50:   2.038 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.744 ms/op
                 existUser·p0.99:   5.343 ms/op
                 existUser·p0.999:  14.844 ms/op
                 existUser·p0.9999: 15.380 ms/op
                 existUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15179
  mean =      2.106 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 301 
    [ 1.250,  2.500) = 13271 
    [ 2.500,  3.750) = 1349 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 83 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.232 ms/op
     p(50.0000) =      2.038 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      5.343 ms/op
     p(99.9000) =     14.844 ms/op
     p(99.9900) =     15.380 ms/op
     p(99.9990) =     15.745 ms/op
     p(99.9999) =     15.745 ms/op
    p(100.0000) =     15.745 ms/op


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
# Warmup Iteration   1: 3.165 ±(99.9%) 0.077 ms/op
Iteration   1: 2.138 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.749 ms/op
                 getUser·p0.50:   1.923 ms/op
                 getUser·p0.90:   2.634 ms/op
                 getUser·p0.95:   3.099 ms/op
                 getUser·p0.99:   8.421 ms/op
                 getUser·p0.999:  16.466 ms/op
                 getUser·p0.9999: 19.408 ms/op
                 getUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15048
  mean =      2.138 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12899 
    [ 2.500,  5.000) = 1873 
    [ 5.000,  7.500) = 100 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      3.099 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     16.466 ms/op
     p(99.9900) =     19.408 ms/op
     p(99.9990) =     20.087 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.117 ms/op
Iteration   1: 3.011 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.864 ms/op
                 listUser·p0.50:   2.818 ms/op
                 listUser·p0.90:   3.744 ms/op
                 listUser·p0.95:   4.170 ms/op
                 listUser·p0.99:   6.357 ms/op
                 listUser·p0.999:  16.682 ms/op
                 listUser·p0.9999: 17.540 ms/op
                 listUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10604
  mean =      3.011 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 2104 
    [ 2.500,  3.750) = 7433 
    [ 3.750,  5.000) = 816 
    [ 5.000,  6.250) = 108 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     16.682 ms/op
     p(99.9900) =     17.540 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.019          ops/ms
ClientSimple.existUser                       thrpt         12.818          ops/ms
ClientSimple.getUser                         thrpt         14.947          ops/ms
ClientSimple.listUser                        thrpt          9.060          ops/ms
ClientSimple.createUser                       avgt          2.160           ms/op
ClientSimple.existUser                        avgt          1.819           ms/op
ClientSimple.getUser                          avgt          2.051           ms/op
ClientSimple.listUser                         avgt          3.335           ms/op
ClientSimple.createUser                     sample  15012   2.130 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.884           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.935           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.458           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.716           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.586           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.000           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.981           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.671           ms/op
ClientSimple.existUser                      sample  15179   2.106 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.232           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.038           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.744           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.343           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.844           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.380           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.745           ms/op
ClientSimple.getUser                        sample  15048   2.138 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.749           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.923           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.634           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.099           ms/op
ClientSimple.getUser:getUser·p0.99          sample          8.421           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.466           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.408           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.087           ms/op
ClientSimple.listUser                       sample  10604   3.011 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.864           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.818           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.744           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.170           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.357           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.682           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.540           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.564           ms/op

Benchmark result is saved to 1717740764322.json
