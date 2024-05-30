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
# Warmup Iteration   1: 1.703 ops/ms
Iteration   1: 6.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.415 ops/ms


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
# Warmup Iteration   1: 6.401 ops/ms
Iteration   1: 12.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.729 ops/ms


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
# Warmup Iteration   1: 5.498 ops/ms
Iteration   1: 13.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.181 ops/ms


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
# Warmup Iteration   1: 4.675 ops/ms
Iteration   1: 9.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.136 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.557 ±(99.9%) 0.064 ms/op
Iteration   1: 2.186 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.186 ms/op


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
# Warmup Iteration   1: 3.415 ±(99.9%) 0.056 ms/op
Iteration   1: 1.992 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.992 ms/op


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
# Warmup Iteration   1: 3.305 ±(99.9%) 0.051 ms/op
Iteration   1: 2.325 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.325 ms/op


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
# Warmup Iteration   1: 4.284 ±(99.9%) 0.091 ms/op
Iteration   1: 4.111 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.111 ms/op


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
# Warmup Iteration   1: 3.560 ±(99.9%) 0.089 ms/op
Iteration   1: 2.310 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   2.093 ms/op
                 createUser·p0.90:   2.863 ms/op
                 createUser·p0.95:   3.189 ms/op
                 createUser·p0.99:   6.523 ms/op
                 createUser·p0.999:  15.876 ms/op
                 createUser·p0.9999: 16.054 ms/op
                 createUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13846
  mean =      2.310 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 10627 
    [ 2.500,  3.750) = 2790 
    [ 3.750,  5.000) = 129 
    [ 5.000,  6.250) = 98 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      2.093 ms/op
     p(90.0000) =      2.863 ms/op
     p(95.0000) =      3.189 ms/op
     p(99.0000) =      6.523 ms/op
     p(99.9000) =     15.876 ms/op
     p(99.9900) =     16.054 ms/op
     p(99.9990) =     16.073 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


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
# Warmup Iteration   1: 3.134 ±(99.9%) 0.084 ms/op
Iteration   1: 1.888 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.591 ms/op
                 existUser·p0.50:   1.747 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.408 ms/op
                 existUser·p0.99:   4.319 ms/op
                 existUser·p0.999:  28.083 ms/op
                 existUser·p0.9999: 28.836 ms/op
                 existUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16975
  mean =      1.888 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16302 
    [ 2.500,  5.000) = 518 
    [ 5.000,  7.500) = 27 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      4.319 ms/op
     p(99.9000) =     28.083 ms/op
     p(99.9900) =     28.836 ms/op
     p(99.9990) =     28.836 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.080 ms/op
Iteration   1: 2.437 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.314 ms/op
                 getUser·p0.50:   2.376 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.101 ms/op
                 getUser·p0.999:  19.268 ms/op
                 getUser·p0.9999: 20.723 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13181
  mean =      2.437 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7991 
    [ 2.500,  5.000) = 5124 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.314 ms/op
     p(50.0000) =      2.376 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.293 ms/op
     p(99.0000) =      4.101 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     20.723 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 5.408 ±(99.9%) 0.307 ms/op
Iteration   1: 4.154 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  16.045 ms/op
                 listUser·p0.9999: 16.286 ms/op
                 listUser·p1.00:   16.286 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7696
  mean =      4.154 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 219 
    [ 2.500,  3.750) = 1846 
    [ 3.750,  5.000) = 4795 
    [ 5.000,  6.250) = 710 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     16.045 ms/op
     p(99.9900) =     16.286 ms/op
     p(99.9990) =     16.286 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.415          ops/ms
ClientSimple.existUser                       thrpt         12.729          ops/ms
ClientSimple.getUser                         thrpt         13.181          ops/ms
ClientSimple.listUser                        thrpt          9.136          ops/ms
ClientSimple.createUser                       avgt          2.186           ms/op
ClientSimple.existUser                        avgt          1.992           ms/op
ClientSimple.getUser                          avgt          2.325           ms/op
ClientSimple.listUser                         avgt          4.111           ms/op
ClientSimple.createUser                     sample  13846   2.310 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.909           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.093           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.863           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.189           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.523           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.876           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.054           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.073           ms/op
ClientSimple.existUser                      sample  16975   1.888 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.591           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.747           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.183           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.319           ms/op
ClientSimple.existUser:existUser·p0.999     sample         28.083           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.836           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.836           ms/op
ClientSimple.getUser                        sample  13181   2.437 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.314           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.966           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.293           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.101           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.268           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.723           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.775           ms/op
ClientSimple.listUser                       sample   7696   4.154 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.296           ms/op
ClientSimple.listUser:listUser·p0.50        sample          4.092           ms/op
ClientSimple.listUser:listUser·p0.90        sample          5.054           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.497           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.799           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.045           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.286           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.286           ms/op

Benchmark result is saved to 1717092746816.json
