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
# Warmup Iteration   1: 1.690 ops/ms
Iteration   1: 7.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.577 ops/ms


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
# Warmup Iteration   1: 5.414 ops/ms
Iteration   1: 12.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.109 ops/ms


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
# Warmup Iteration   1: 5.329 ops/ms
Iteration   1: 10.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.931 ops/ms


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
# Warmup Iteration   1: 5.382 ops/ms
Iteration   1: 9.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.003 ops/ms


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.070 ms/op
Iteration   1: 2.119 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.119 ms/op


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
# Warmup Iteration   1: 3.069 ±(99.9%) 0.060 ms/op
Iteration   1: 1.901 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.901 ms/op


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
# Warmup Iteration   1: 3.311 ±(99.9%) 0.068 ms/op
Iteration   1: 1.949 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.949 ms/op


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.099 ms/op
Iteration   1: 3.234 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.234 ms/op


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
# Warmup Iteration   1: 3.728 ±(99.9%) 0.086 ms/op
Iteration   1: 2.096 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.646 ms/op
                 createUser·p0.50:   1.878 ms/op
                 createUser·p0.90:   2.613 ms/op
                 createUser·p0.95:   2.916 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  15.958 ms/op
                 createUser·p0.9999: 16.457 ms/op
                 createUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15247
  mean =      2.096 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 330 
    [ 1.250,  2.500) = 12657 
    [ 2.500,  3.750) = 1929 
    [ 3.750,  5.000) = 89 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      1.878 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.916 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     16.457 ms/op
     p(99.9990) =     16.482 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


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
# Warmup Iteration   1: 2.975 ±(99.9%) 0.077 ms/op
Iteration   1: 1.824 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   1.710 ms/op
                 existUser·p0.90:   2.171 ms/op
                 existUser·p0.95:   2.290 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  16.371 ms/op
                 existUser·p0.9999: 17.083 ms/op
                 existUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17800
  mean =      1.824 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 283 
    [ 1.250,  2.500) = 17193 
    [ 2.500,  3.750) = 152 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      1.710 ms/op
     p(90.0000) =      2.171 ms/op
     p(95.0000) =      2.290 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =     16.371 ms/op
     p(99.9900) =     17.083 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 3.419 ±(99.9%) 0.089 ms/op
Iteration   1: 2.056 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   1.989 ms/op
                 getUser·p0.90:   2.720 ms/op
                 getUser·p0.95:   2.941 ms/op
                 getUser·p0.99:   3.461 ms/op
                 getUser·p0.999:  16.417 ms/op
                 getUser·p0.9999: 16.866 ms/op
                 getUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15701
  mean =      2.056 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 204 
    [ 1.250,  2.500) = 12913 
    [ 2.500,  3.750) = 2490 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      3.461 ms/op
     p(99.9000) =     16.417 ms/op
     p(99.9900) =     16.866 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 4.605 ±(99.9%) 0.130 ms/op
Iteration   1: 3.093 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   2.871 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   4.940 ms/op
                 listUser·p0.999:  6.466 ms/op
                 listUser·p0.9999: 8.311 ms/op
                 listUser·p1.00:   8.331 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10335
  mean =      3.093 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 4 
    [1.500, 2.000) = 3 
    [2.000, 2.500) = 274 
    [2.500, 3.000) = 6393 
    [3.000, 3.500) = 1575 
    [3.500, 4.000) = 1054 
    [4.000, 4.500) = 690 
    [4.500, 5.000) = 261 
    [5.000, 5.500) = 37 
    [5.500, 6.000) = 14 
    [6.000, 6.500) = 25 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =      6.466 ms/op
     p(99.9900) =      8.311 ms/op
     p(99.9990) =      8.331 ms/op
     p(99.9999) =      8.331 ms/op
    p(100.0000) =      8.331 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.577          ops/ms
ClientSimple.existUser                       thrpt         12.109          ops/ms
ClientSimple.getUser                         thrpt         10.931          ops/ms
ClientSimple.listUser                        thrpt          9.003          ops/ms
ClientSimple.createUser                       avgt          2.119           ms/op
ClientSimple.existUser                        avgt          1.901           ms/op
ClientSimple.getUser                          avgt          1.949           ms/op
ClientSimple.listUser                         avgt          3.234           ms/op
ClientSimple.createUser                     sample  15247   2.096 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.646           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.878           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.613           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.916           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.389           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.958           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.457           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.482           ms/op
ClientSimple.existUser                      sample  17800   1.824 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.681           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.710           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.171           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.290           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.744           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.371           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.083           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.236           ms/op
ClientSimple.getUser                        sample  15701   2.056 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.734           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.989           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.720           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.941           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.461           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.417           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.866           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.941           ms/op
ClientSimple.listUser                       sample  10335   3.093 ± 0.019   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.818           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.871           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.998           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.940           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.466           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.311           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.331           ms/op

Benchmark result is saved to 1719209542928.json
