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
# Warmup Iteration   1: 1.600 ops/ms
Iteration   1: 6.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.829 ops/ms


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
# Warmup Iteration   1: 4.778 ops/ms
Iteration   1: 14.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.471 ops/ms


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
# Warmup Iteration   1: 4.850 ops/ms
Iteration   1: 12.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.072 ops/ms


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
# Warmup Iteration   1: 6.139 ops/ms
Iteration   1: 8.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.662 ops/ms


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.068 ms/op
Iteration   1: 2.329 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.329 ms/op


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
# Warmup Iteration   1: 3.217 ±(99.9%) 0.059 ms/op
Iteration   1: 1.887 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.887 ms/op


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
# Warmup Iteration   1: 3.676 ±(99.9%) 0.069 ms/op
Iteration   1: 2.147 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.147 ms/op


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
# Warmup Iteration   1: 5.185 ±(99.9%) 0.102 ms/op
Iteration   1: 3.437 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.437 ms/op


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
# Warmup Iteration   1: 3.560 ±(99.9%) 0.103 ms/op
Iteration   1: 2.196 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   2.016 ms/op
                 createUser·p0.90:   2.519 ms/op
                 createUser·p0.95:   2.765 ms/op
                 createUser·p0.99:   7.561 ms/op
                 createUser·p0.999:  20.263 ms/op
                 createUser·p0.9999: 20.906 ms/op
                 createUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14616
  mean =      2.196 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13043 
    [ 2.500,  5.000) = 1326 
    [ 5.000,  7.500) = 92 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.016 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     20.263 ms/op
     p(99.9900) =     20.906 ms/op
     p(99.9990) =     20.906 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 3.044 ±(99.9%) 0.068 ms/op
Iteration   1: 1.858 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   1.778 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.423 ms/op
                 existUser·p0.99:   3.460 ms/op
                 existUser·p0.999:  14.099 ms/op
                 existUser·p0.9999: 14.378 ms/op
                 existUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17228
  mean =      1.858 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 753 
    [ 1.250,  2.500) = 15800 
    [ 2.500,  3.750) = 520 
    [ 3.750,  5.000) = 59 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.423 ms/op
     p(99.0000) =      3.460 ms/op
     p(99.9000) =     14.099 ms/op
     p(99.9900) =     14.378 ms/op
     p(99.9990) =     14.402 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 3.258 ±(99.9%) 0.085 ms/op
Iteration   1: 2.360 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   2.322 ms/op
                 getUser·p0.90:   2.900 ms/op
                 getUser·p0.95:   3.134 ms/op
                 getUser·p0.99:   5.575 ms/op
                 getUser·p0.999:  11.673 ms/op
                 getUser·p0.9999: 12.778 ms/op
                 getUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13557
  mean =      2.360 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 8238 
    [ 2.500,  3.750) = 5020 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.322 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.134 ms/op
     p(99.0000) =      5.575 ms/op
     p(99.9000) =     11.673 ms/op
     p(99.9900) =     12.778 ms/op
     p(99.9990) =     12.796 ms/op
     p(99.9999) =     12.796 ms/op
    p(100.0000) =     12.796 ms/op


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.157 ms/op
Iteration   1: 3.682 ±(99.9%) 0.090 ms/op
                 listUser·p0.00:   0.681 ms/op
                 listUser·p0.50:   3.486 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.852 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  42.376 ms/op
                 listUser·p0.9999: 43.450 ms/op
                 listUser·p1.00:   43.450 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8694
  mean =      3.682 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8359 
    [ 5.000, 10.000) = 271 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.852 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     42.376 ms/op
     p(99.9900) =     43.450 ms/op
     p(99.9990) =     43.450 ms/op
     p(99.9999) =     43.450 ms/op
    p(100.0000) =     43.450 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.829          ops/ms
ClientSimple.existUser                       thrpt         14.471          ops/ms
ClientSimple.getUser                         thrpt         12.072          ops/ms
ClientSimple.listUser                        thrpt          8.662          ops/ms
ClientSimple.createUser                       avgt          2.329           ms/op
ClientSimple.existUser                        avgt          1.887           ms/op
ClientSimple.getUser                          avgt          2.147           ms/op
ClientSimple.listUser                         avgt          3.437           ms/op
ClientSimple.createUser                     sample  14616   2.196 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.613           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.016           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.519           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.561           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.263           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.906           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.906           ms/op
ClientSimple.existUser                      sample  17228   1.858 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.549           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.778           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.423           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.460           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.099           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.378           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.402           ms/op
ClientSimple.getUser                        sample  13557   2.360 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.850           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.322           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.134           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.575           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.673           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.778           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.796           ms/op
ClientSimple.listUser                       sample   8694   3.682 ± 0.090   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.681           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.486           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.852           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.750           ms/op
ClientSimple.listUser:listUser·p0.999       sample         42.376           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         43.450           ms/op
ClientSimple.listUser:listUser·p1.00        sample         43.450           ms/op

Benchmark result is saved to 1719468752026.json
