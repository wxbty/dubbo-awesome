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
# Warmup Iteration   1: 1.676 ops/ms
Iteration   1: 6.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.620 ops/ms


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
# Warmup Iteration   1: 6.222 ops/ms
Iteration   1: 11.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.219 ops/ms


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
# Warmup Iteration   1: 5.019 ops/ms
Iteration   1: 13.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.625 ops/ms


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
# Warmup Iteration   1: 4.951 ops/ms
Iteration   1: 7.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.623 ops/ms


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
# Warmup Iteration   1: 4.504 ±(99.9%) 0.088 ms/op
Iteration   1: 2.160 ±(99.9%) 0.011 ms/op


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
# Warmup Iteration   1: 3.482 ±(99.9%) 0.083 ms/op
Iteration   1: 2.165 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.165 ms/op


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
# Warmup Iteration   1: 3.688 ±(99.9%) 0.105 ms/op
Iteration   1: 1.935 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.935 ms/op


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
# Warmup Iteration   1: 5.136 ±(99.9%) 0.110 ms/op
Iteration   1: 3.560 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.560 ms/op


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
# Warmup Iteration   1: 3.814 ±(99.9%) 0.129 ms/op
Iteration   1: 2.122 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.611 ms/op
                 createUser·p0.50:   1.921 ms/op
                 createUser·p0.90:   2.728 ms/op
                 createUser·p0.95:   3.035 ms/op
                 createUser·p0.99:   5.063 ms/op
                 createUser·p0.999:  16.203 ms/op
                 createUser·p0.9999: 17.170 ms/op
                 createUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15056
  mean =      2.122 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 12783 
    [ 2.500,  3.750) = 1792 
    [ 3.750,  5.000) = 190 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      5.063 ms/op
     p(99.9000) =     16.203 ms/op
     p(99.9900) =     17.170 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 3.191 ±(99.9%) 0.080 ms/op
Iteration   1: 1.956 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   1.821 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.486 ms/op
                 existUser·p0.99:   4.176 ms/op
                 existUser·p0.999:  20.480 ms/op
                 existUser·p0.9999: 21.076 ms/op
                 existUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16337
  mean =      1.956 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15577 
    [ 2.500,  5.000) = 650 
    [ 5.000,  7.500) = 46 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.486 ms/op
     p(99.0000) =      4.176 ms/op
     p(99.9000) =     20.480 ms/op
     p(99.9900) =     21.076 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 3.300 ±(99.9%) 0.079 ms/op
Iteration   1: 2.249 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   2.134 ms/op
                 getUser·p0.90:   2.899 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   5.410 ms/op
                 getUser·p0.999:  11.876 ms/op
                 getUser·p0.9999: 12.478 ms/op
                 getUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14282
  mean =      2.249 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 176 
    [ 1.250,  2.500) = 10817 
    [ 2.500,  3.750) = 2998 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 102 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.134 ms/op
     p(90.0000) =      2.899 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      5.410 ms/op
     p(99.9000) =     11.876 ms/op
     p(99.9900) =     12.478 ms/op
     p(99.9990) =     12.485 ms/op
     p(99.9999) =     12.485 ms/op
    p(100.0000) =     12.485 ms/op


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
# Warmup Iteration   1: 5.652 ±(99.9%) 0.391 ms/op
Iteration   1: 3.599 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   0.717 ms/op
                 listUser·p0.50:   3.269 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.379 ms/op
                 listUser·p0.99:   7.096 ms/op
                 listUser·p0.999:  19.890 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8887
  mean =      3.599 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 490 
    [ 2.500,  5.000) = 7789 
    [ 5.000,  7.500) = 530 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.379 ms/op
     p(99.0000) =      7.096 ms/op
     p(99.9000) =     19.890 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.620          ops/ms
ClientSimple.existUser                       thrpt         11.219          ops/ms
ClientSimple.getUser                         thrpt         13.625          ops/ms
ClientSimple.listUser                        thrpt          7.623          ops/ms
ClientSimple.createUser                       avgt          2.160           ms/op
ClientSimple.existUser                        avgt          2.165           ms/op
ClientSimple.getUser                          avgt          1.935           ms/op
ClientSimple.listUser                         avgt          3.560           ms/op
ClientSimple.createUser                     sample  15056   2.122 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.611           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.921           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.728           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.035           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.063           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.203           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.170           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.170           ms/op
ClientSimple.existUser                      sample  16337   1.956 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.705           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.821           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.176           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.480           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.076           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.201           ms/op
ClientSimple.getUser                        sample  14282   2.249 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.563           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.134           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.899           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.187           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.410           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.876           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.478           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.485           ms/op
ClientSimple.listUser                       sample   8887   3.599 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.717           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.269           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.686           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.379           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.096           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.890           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.840           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.840           ms/op

Benchmark result is saved to 1717202377058.json
