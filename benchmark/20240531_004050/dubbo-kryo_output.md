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
# Warmup Iteration   1: 1.755 ops/ms
Iteration   1: 7.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.581 ops/ms


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
# Warmup Iteration   1: 5.146 ops/ms
Iteration   1: 11.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.557 ops/ms


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
# Warmup Iteration   1: 5.259 ops/ms
Iteration   1: 11.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.122 ops/ms


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
# Warmup Iteration   1: 4.898 ops/ms
Iteration   1: 8.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.422 ops/ms


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.082 ms/op
Iteration   1: 2.270 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.270 ms/op


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
# Warmup Iteration   1: 3.350 ±(99.9%) 0.068 ms/op
Iteration   1: 1.830 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.830 ms/op


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
# Warmup Iteration   1: 3.143 ±(99.9%) 0.063 ms/op
Iteration   1: 2.031 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.031 ms/op


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
# Warmup Iteration   1: 4.411 ±(99.9%) 0.081 ms/op
Iteration   1: 3.398 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.398 ms/op


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.118 ms/op
Iteration   1: 2.321 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.488 ms/op
                 createUser·p0.50:   2.105 ms/op
                 createUser·p0.90:   2.834 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   12.550 ms/op
                 createUser·p0.999:  17.105 ms/op
                 createUser·p0.9999: 17.302 ms/op
                 createUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13770
  mean =      2.321 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 380 
    [ 1.250,  2.500) = 10287 
    [ 2.500,  3.750) = 2715 
    [ 3.750,  5.000) = 136 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.834 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =     12.550 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     17.302 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 2.881 ±(99.9%) 0.062 ms/op
Iteration   1: 2.096 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   1.987 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.728 ms/op
                 existUser·p0.99:   5.304 ms/op
                 existUser·p0.999:  12.042 ms/op
                 existUser·p0.9999: 12.620 ms/op
                 existUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15335
  mean =      2.096 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 13634 
    [ 2.500,  3.750) = 1257 
    [ 3.750,  5.000) = 122 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      5.304 ms/op
     p(99.9000) =     12.042 ms/op
     p(99.9900) =     12.620 ms/op
     p(99.9990) =     12.681 ms/op
     p(99.9999) =     12.681 ms/op
    p(100.0000) =     12.681 ms/op


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
# Warmup Iteration   1: 3.439 ±(99.9%) 0.099 ms/op
Iteration   1: 2.114 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.470 ms/op
                 getUser·p0.50:   1.929 ms/op
                 getUser·p0.90:   2.638 ms/op
                 getUser·p0.95:   2.863 ms/op
                 getUser·p0.99:   6.249 ms/op
                 getUser·p0.999:  11.450 ms/op
                 getUser·p0.9999: 13.072 ms/op
                 getUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15118
  mean =      2.114 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 12738 
    [ 2.500,  3.750) = 1998 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      6.249 ms/op
     p(99.9000) =     11.450 ms/op
     p(99.9900) =     13.072 ms/op
     p(99.9990) =     13.156 ms/op
     p(99.9999) =     13.156 ms/op
    p(100.0000) =     13.156 ms/op


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
# Warmup Iteration   1: 4.887 ±(99.9%) 0.154 ms/op
Iteration   1: 3.380 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   0.799 ms/op
                 listUser·p0.50:   3.207 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   6.326 ms/op
                 listUser·p0.999:  26.575 ms/op
                 listUser·p0.9999: 26.968 ms/op
                 listUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9459
  mean =      3.380 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1610 
    [ 2.500,  5.000) = 7512 
    [ 5.000,  7.500) = 286 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.326 ms/op
     p(99.9000) =     26.575 ms/op
     p(99.9900) =     26.968 ms/op
     p(99.9990) =     26.968 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.581          ops/ms
ClientSimple.existUser                       thrpt         11.557          ops/ms
ClientSimple.getUser                         thrpt         11.122          ops/ms
ClientSimple.listUser                        thrpt          8.422          ops/ms
ClientSimple.createUser                       avgt          2.270           ms/op
ClientSimple.existUser                        avgt          1.830           ms/op
ClientSimple.getUser                          avgt          2.031           ms/op
ClientSimple.listUser                         avgt          3.398           ms/op
ClientSimple.createUser                     sample  13770   2.321 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.488           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.105           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.834           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.162           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.550           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.105           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.302           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.302           ms/op
ClientSimple.existUser                      sample  15335   2.096 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.681           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.987           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.728           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.304           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.042           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.620           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.681           ms/op
ClientSimple.getUser                        sample  15118   2.114 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.470           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.929           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.863           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.249           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.450           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.072           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.156           ms/op
ClientSimple.listUser                       sample   9459   3.380 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.799           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.207           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.833           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.326           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.575           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.968           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.968           ms/op

Benchmark result is saved to 1717115779577.json
