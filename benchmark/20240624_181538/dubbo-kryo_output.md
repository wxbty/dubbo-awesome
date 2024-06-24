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
# Warmup Iteration   1: 1.135 ops/ms
Iteration   1: 5.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.629 ops/ms


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
# Warmup Iteration   1: 5.341 ops/ms
Iteration   1: 11.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.691 ops/ms


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
# Warmup Iteration   1: 6.986 ops/ms
Iteration   1: 12.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.448 ops/ms


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
# Warmup Iteration   1: 3.832 ops/ms
Iteration   1: 8.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.402 ops/ms


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
# Warmup Iteration   1: 3.874 ±(99.9%) 0.077 ms/op
Iteration   1: 2.407 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.407 ms/op


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
# Warmup Iteration   1: 3.644 ±(99.9%) 0.053 ms/op
Iteration   1: 1.956 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.956 ms/op


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
# Warmup Iteration   1: 3.622 ±(99.9%) 0.063 ms/op
Iteration   1: 2.203 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.203 ms/op


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
# Warmup Iteration   1: 4.069 ±(99.9%) 0.091 ms/op
Iteration   1: 3.162 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.162 ms/op


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
# Warmup Iteration   1: 3.633 ±(99.9%) 0.105 ms/op
Iteration   1: 2.163 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   2.048 ms/op
                 createUser·p0.90:   2.654 ms/op
                 createUser·p0.95:   2.912 ms/op
                 createUser·p0.99:   5.162 ms/op
                 createUser·p0.999:  14.028 ms/op
                 createUser·p0.9999: 23.265 ms/op
                 createUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14783
  mean =      2.163 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12328 
    [ 2.500,  5.000) = 2288 
    [ 5.000,  7.500) = 64 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      2.048 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      5.162 ms/op
     p(99.9000) =     14.028 ms/op
     p(99.9900) =     23.265 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
Iteration   1: 2.102 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.545 ms/op
                 existUser·p0.50:   2.005 ms/op
                 existUser·p0.90:   2.699 ms/op
                 existUser·p0.95:   2.933 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  18.514 ms/op
                 existUser·p0.9999: 19.037 ms/op
                 existUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15243
  mean =      2.102 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 319 
    [ 1.250,  2.500) = 12328 
    [ 2.500,  3.750) = 2433 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     19.037 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.174 ms/op
Iteration   1: 2.072 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.371 ms/op
                 getUser·p0.50:   1.995 ms/op
                 getUser·p0.90:   2.462 ms/op
                 getUser·p0.95:   2.646 ms/op
                 getUser·p0.99:   4.171 ms/op
                 getUser·p0.999:  15.270 ms/op
                 getUser·p0.9999: 15.877 ms/op
                 getUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15493
  mean =      2.072 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 220 
    [ 1.250,  2.500) = 13952 
    [ 2.500,  3.750) = 1123 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.371 ms/op
     p(50.0000) =      1.995 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      4.171 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     15.877 ms/op
     p(99.9990) =     15.958 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


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
# Warmup Iteration   1: 4.337 ±(99.9%) 0.127 ms/op
Iteration   1: 3.288 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   0.559 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.477 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 18.711 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9765
  mean =      3.288 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 930 
    [ 2.500,  3.750) = 6295 
    [ 3.750,  5.000) = 2305 
    [ 5.000,  6.250) = 110 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.477 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     18.711 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.629          ops/ms
ClientSimple.existUser                       thrpt         11.691          ops/ms
ClientSimple.getUser                         thrpt         12.448          ops/ms
ClientSimple.listUser                        thrpt          8.402          ops/ms
ClientSimple.createUser                       avgt          2.407           ms/op
ClientSimple.existUser                        avgt          1.956           ms/op
ClientSimple.getUser                          avgt          2.203           ms/op
ClientSimple.listUser                         avgt          3.162           ms/op
ClientSimple.createUser                     sample  14783   2.163 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.841           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.048           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.654           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.912           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.162           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.028           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.265           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.265           ms/op
ClientSimple.existUser                      sample  15243   2.102 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.545           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.005           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.699           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.933           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.432           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.514           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.037           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.071           ms/op
ClientSimple.getUser                        sample  15493   2.072 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.371           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.995           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.462           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.646           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.171           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.270           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.877           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.958           ms/op
ClientSimple.listUser                       sample   9765   3.288 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.559           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.002           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.129           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.477           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.072           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.711           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.711           ms/op

Benchmark result is saved to 1719252690495.json
