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
# Warmup Iteration   1: 1.695 ops/ms
Iteration   1: 6.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.401 ops/ms


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
# Warmup Iteration   1: 4.883 ops/ms
Iteration   1: 12.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.399 ops/ms


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
# Warmup Iteration   1: 5.216 ops/ms
Iteration   1: 11.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.641 ops/ms


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
# Warmup Iteration   1: 5.087 ops/ms
Iteration   1: 8.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.093 ops/ms


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
# Warmup Iteration   1: 4.261 ±(99.9%) 0.089 ms/op
Iteration   1: 2.361 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.361 ms/op


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
# Warmup Iteration   1: 3.203 ±(99.9%) 0.055 ms/op
Iteration   1: 2.055 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.055 ms/op


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
# Warmup Iteration   1: 3.233 ±(99.9%) 0.062 ms/op
Iteration   1: 1.972 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.972 ms/op


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
# Warmup Iteration   1: 4.224 ±(99.9%) 0.083 ms/op
Iteration   1: 3.092 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.092 ms/op


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
# Warmup Iteration   1: 3.957 ±(99.9%) 0.099 ms/op
Iteration   1: 2.114 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.591 ms/op
                 createUser·p0.50:   1.860 ms/op
                 createUser·p0.90:   2.544 ms/op
                 createUser·p0.95:   2.863 ms/op
                 createUser·p0.99:   9.057 ms/op
                 createUser·p0.999:  15.811 ms/op
                 createUser·p0.9999: 19.653 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15122
  mean =      2.114 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 13356 
    [ 2.500,  3.750) = 1405 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      9.057 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     19.653 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 2.942 ±(99.9%) 0.077 ms/op
Iteration   1: 1.880 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.526 ms/op
                 existUser·p0.50:   1.767 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.449 ms/op
                 existUser·p0.99:   4.018 ms/op
                 existUser·p0.999:  14.696 ms/op
                 existUser·p0.9999: 14.942 ms/op
                 existUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17002
  mean =      1.880 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 866 
    [ 1.250,  2.500) = 15409 
    [ 2.500,  3.750) = 534 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      1.767 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.449 ms/op
     p(99.0000) =      4.018 ms/op
     p(99.9000) =     14.696 ms/op
     p(99.9900) =     14.942 ms/op
     p(99.9990) =     14.942 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 3.473 ±(99.9%) 0.094 ms/op
Iteration   1: 2.169 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.617 ms/op
                 getUser·p0.50:   2.089 ms/op
                 getUser·p0.90:   2.609 ms/op
                 getUser·p0.95:   2.900 ms/op
                 getUser·p0.99:   3.944 ms/op
                 getUser·p0.999:  18.678 ms/op
                 getUser·p0.9999: 18.974 ms/op
                 getUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14803
  mean =      2.169 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 12539 
    [ 2.500,  3.750) = 2024 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      2.089 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     18.974 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.120 ms/op
Iteration   1: 3.638 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  24.805 ms/op
                 listUser·p0.9999: 25.166 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8820
  mean =      3.638 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 516 
    [ 2.500,  5.000) = 8041 
    [ 5.000,  7.500) = 218 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     24.805 ms/op
     p(99.9900) =     25.166 ms/op
     p(99.9990) =     25.166 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.401          ops/ms
ClientSimple.existUser                       thrpt         12.399          ops/ms
ClientSimple.getUser                         thrpt         11.641          ops/ms
ClientSimple.listUser                        thrpt          8.093          ops/ms
ClientSimple.createUser                       avgt          2.361           ms/op
ClientSimple.existUser                        avgt          2.055           ms/op
ClientSimple.getUser                          avgt          1.972           ms/op
ClientSimple.listUser                         avgt          3.092           ms/op
ClientSimple.createUser                     sample  15122   2.114 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.591           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.860           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.544           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.863           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.057           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.811           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.653           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.988           ms/op
ClientSimple.existUser                      sample  17002   1.880 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.526           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.767           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.018           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.696           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.942           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.942           ms/op
ClientSimple.getUser                        sample  14803   2.169 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.617           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.089           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.944           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.678           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.974           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.005           ms/op
ClientSimple.listUser                       sample   8820   3.638 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.846           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.547           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.801           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.758           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.805           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.166           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.166           ms/op

Benchmark result is saved to 1717265422675.json
