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
# Warmup Iteration   1: 1.278 ops/ms
Iteration   1: 6.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.134 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.534 ops/ms
Iteration   1: 10.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.951 ops/ms


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
# Warmup Iteration   1: 4.996 ops/ms
Iteration   1: 12.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.462 ops/ms


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
# Warmup Iteration   1: 4.842 ops/ms
Iteration   1: 8.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.409 ops/ms


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
# Warmup Iteration   1: 3.700 ±(99.9%) 0.071 ms/op
Iteration   1: 2.227 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.227 ms/op


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
# Warmup Iteration   1: 3.383 ±(99.9%) 0.057 ms/op
Iteration   1: 1.750 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.750 ms/op


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
# Warmup Iteration   1: 3.453 ±(99.9%) 0.074 ms/op
Iteration   1: 2.043 ±(99.9%) 0.008 ms/op


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
# Warmup Iteration   1: 5.194 ±(99.9%) 0.109 ms/op
Iteration   1: 3.787 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.787 ms/op


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
# Warmup Iteration   1: 3.628 ±(99.9%) 0.114 ms/op
Iteration   1: 2.427 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.558 ms/op
                 createUser·p0.50:   2.146 ms/op
                 createUser·p0.90:   2.968 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   10.339 ms/op
                 createUser·p0.999:  17.230 ms/op
                 createUser·p0.9999: 18.100 ms/op
                 createUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13173
  mean =      2.427 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 224 
    [ 1.250,  2.500) = 9789 
    [ 2.500,  3.750) = 2541 
    [ 3.750,  5.000) = 204 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 93 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.968 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =     10.339 ms/op
     p(99.9000) =     17.230 ms/op
     p(99.9900) =     18.100 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 2.991 ±(99.9%) 0.075 ms/op
Iteration   1: 1.887 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   1.710 ms/op
                 existUser·p0.90:   2.490 ms/op
                 existUser·p0.95:   2.796 ms/op
                 existUser·p0.99:   3.852 ms/op
                 existUser·p0.999:  15.237 ms/op
                 existUser·p0.9999: 15.385 ms/op
                 existUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16927
  mean =      1.887 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1030 
    [ 1.250,  2.500) = 14239 
    [ 2.500,  3.750) = 1462 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      1.710 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.796 ms/op
     p(99.0000) =      3.852 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     15.385 ms/op
     p(99.9990) =     15.385 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 3.178 ±(99.9%) 0.078 ms/op
Iteration   1: 2.128 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   1.970 ms/op
                 getUser·p0.90:   2.847 ms/op
                 getUser·p0.95:   3.031 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  16.597 ms/op
                 getUser·p0.9999: 17.530 ms/op
                 getUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15027
  mean =      2.128 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 11947 
    [ 2.500,  3.750) = 2755 
    [ 3.750,  5.000) = 115 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =     16.597 ms/op
     p(99.9900) =     17.530 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 5.123 ±(99.9%) 0.177 ms/op
Iteration   1: 3.571 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   3.449 ms/op
                 listUser·p0.90:   4.353 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.024 ms/op
                 listUser·p0.999:  19.040 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8955
  mean =      3.571 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 386 
    [ 2.500,  5.000) = 8201 
    [ 5.000,  7.500) = 297 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.353 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.024 ms/op
     p(99.9000) =     19.040 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     20.087 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.134          ops/ms
ClientSimple.existUser                       thrpt         10.951          ops/ms
ClientSimple.getUser                         thrpt         12.462          ops/ms
ClientSimple.listUser                        thrpt          8.409          ops/ms
ClientSimple.createUser                       avgt          2.227           ms/op
ClientSimple.existUser                        avgt          1.750           ms/op
ClientSimple.getUser                          avgt          2.043           ms/op
ClientSimple.listUser                         avgt          3.787           ms/op
ClientSimple.createUser                     sample  13173   2.427 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.558           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.146           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.968           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.600           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.339           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.230           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.100           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.121           ms/op
ClientSimple.existUser                      sample  16927   1.887 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.560           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.710           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.796           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.852           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.237           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.385           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.385           ms/op
ClientSimple.getUser                        sample  15027   2.128 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.698           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.970           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.847           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.031           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.293           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.597           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.530           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.629           ms/op
ClientSimple.listUser                       sample   8955   3.571 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.307           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.449           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.353           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.024           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.040           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.087           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.087           ms/op

Benchmark result is saved to 1719490533340.json
