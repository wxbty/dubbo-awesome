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
# Warmup Iteration   1: 1.718 ops/ms
Iteration   1: 6.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.986 ops/ms


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
# Warmup Iteration   1: 6.693 ops/ms
Iteration   1: 11.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.502 ops/ms


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
# Warmup Iteration   1: 5.050 ops/ms
Iteration   1: 12.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.283 ops/ms


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
# Warmup Iteration   1: 5.406 ops/ms
Iteration   1: 8.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.446 ops/ms


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.081 ms/op
Iteration   1: 2.286 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.286 ms/op


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
# Warmup Iteration   1: 3.082 ±(99.9%) 0.054 ms/op
Iteration   1: 1.963 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.963 ms/op


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
# Warmup Iteration   1: 3.052 ±(99.9%) 0.055 ms/op
Iteration   1: 2.013 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.013 ms/op


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
# Warmup Iteration   1: 4.631 ±(99.9%) 0.096 ms/op
Iteration   1: 3.595 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.595 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.629 ±(99.9%) 0.091 ms/op
Iteration   1: 2.048 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.407 ms/op
                 createUser·p0.50:   1.847 ms/op
                 createUser·p0.90:   2.515 ms/op
                 createUser·p0.95:   2.904 ms/op
                 createUser·p0.99:   4.780 ms/op
                 createUser·p0.999:  39.829 ms/op
                 createUser·p0.9999: 40.706 ms/op
                 createUser·p1.00:   40.894 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15753
  mean =      2.048 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15612 
    [ 5.000, 10.000) = 109 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.407 ms/op
     p(50.0000) =      1.847 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      4.780 ms/op
     p(99.9000) =     39.829 ms/op
     p(99.9900) =     40.706 ms/op
     p(99.9990) =     40.894 ms/op
     p(99.9999) =     40.894 ms/op
    p(100.0000) =     40.894 ms/op


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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.087 ms/op
Iteration   1: 1.878 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.591 ms/op
                 existUser·p0.50:   1.784 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   3.330 ms/op
                 existUser·p0.999:  13.515 ms/op
                 existUser·p0.9999: 14.469 ms/op
                 existUser·p1.00:   14.516 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17130
  mean =      1.878 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 993 
    [ 1.250,  2.500) = 14887 
    [ 2.500,  3.750) = 1122 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      3.330 ms/op
     p(99.9000) =     13.515 ms/op
     p(99.9900) =     14.469 ms/op
     p(99.9990) =     14.516 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 3.368 ±(99.9%) 0.090 ms/op
Iteration   1: 2.215 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   2.038 ms/op
                 getUser·p0.90:   2.757 ms/op
                 getUser·p0.95:   3.035 ms/op
                 getUser·p0.99:   5.210 ms/op
                 getUser·p0.999:  13.926 ms/op
                 getUser·p0.9999: 13.992 ms/op
                 getUser·p1.00:   13.992 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14420
  mean =      2.215 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 11765 
    [ 2.500,  3.750) = 2236 
    [ 3.750,  5.000) = 159 
    [ 5.000,  6.250) = 81 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.038 ms/op
     p(90.0000) =      2.757 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     13.992 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.120 ms/op
Iteration   1: 3.373 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   3.351 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  9.397 ms/op
                 listUser·p0.9999: 9.912 ms/op
                 listUser·p1.00:   9.912 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9471
  mean =      3.373 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 30 
    [ 1.500,  2.000) = 116 
    [ 2.000,  2.500) = 1767 
    [ 2.500,  3.000) = 1604 
    [ 3.000,  3.500) = 1772 
    [ 3.500,  4.000) = 2271 
    [ 4.000,  4.500) = 1236 
    [ 4.500,  5.000) = 307 
    [ 5.000,  5.500) = 141 
    [ 5.500,  6.000) = 61 
    [ 6.000,  6.500) = 40 
    [ 6.500,  7.000) = 58 
    [ 7.000,  7.500) = 3 
    [ 7.500,  8.000) = 13 
    [ 8.000,  8.500) = 34 
    [ 8.500,  9.000) = 2 
    [ 9.000,  9.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =      9.397 ms/op
     p(99.9900) =      9.912 ms/op
     p(99.9990) =      9.912 ms/op
     p(99.9999) =      9.912 ms/op
    p(100.0000) =      9.912 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.986          ops/ms
ClientSimple.existUser                       thrpt         11.502          ops/ms
ClientSimple.getUser                         thrpt         12.283          ops/ms
ClientSimple.listUser                        thrpt          8.446          ops/ms
ClientSimple.createUser                       avgt          2.286           ms/op
ClientSimple.existUser                        avgt          1.963           ms/op
ClientSimple.getUser                          avgt          2.013           ms/op
ClientSimple.listUser                         avgt          3.595           ms/op
ClientSimple.createUser                     sample  15753   2.048 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.407           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.847           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.515           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.780           ms/op
ClientSimple.createUser:createUser·p0.999   sample         39.829           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         40.706           ms/op
ClientSimple.createUser:createUser·p1.00    sample         40.894           ms/op
ClientSimple.existUser                      sample  17130   1.878 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.591           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.784           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.330           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.515           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.469           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.516           ms/op
ClientSimple.getUser                        sample  14420   2.215 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.818           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.038           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.757           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.035           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.210           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.926           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.992           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.992           ms/op
ClientSimple.listUser                       sample   9471   3.373 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.020           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.351           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.874           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.873           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.397           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.912           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.912           ms/op

Benchmark result is saved to 1718388724232.json
