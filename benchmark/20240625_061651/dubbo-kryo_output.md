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
# Warmup Iteration   1: 1.901 ops/ms
Iteration   1: 6.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.404 ops/ms


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
# Warmup Iteration   1: 6.003 ops/ms
Iteration   1: 11.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.966 ops/ms


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
# Warmup Iteration   1: 5.675 ops/ms
Iteration   1: 11.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.800 ops/ms


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
# Warmup Iteration   1: 4.581 ops/ms
Iteration   1: 9.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.042 ops/ms


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.089 ms/op
Iteration   1: 2.158 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.158 ms/op


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
# Warmup Iteration   1: 3.090 ±(99.9%) 0.049 ms/op
Iteration   1: 1.895 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.895 ms/op


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
# Warmup Iteration   1: 3.062 ±(99.9%) 0.049 ms/op
Iteration   1: 2.110 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.110 ms/op


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
# Warmup Iteration   1: 4.597 ±(99.9%) 0.109 ms/op
Iteration   1: 3.317 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.317 ms/op


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
# Warmup Iteration   1: 3.520 ±(99.9%) 0.099 ms/op
Iteration   1: 2.332 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   2.150 ms/op
                 createUser·p0.90:   2.847 ms/op
                 createUser·p0.95:   3.409 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  17.893 ms/op
                 createUser·p0.9999: 17.977 ms/op
                 createUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13933
  mean =      2.332 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 10882 
    [ 2.500,  3.750) = 2444 
    [ 3.750,  5.000) = 303 
    [ 5.000,  6.250) = 81 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      3.409 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     17.893 ms/op
     p(99.9900) =     17.977 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 3.054 ±(99.9%) 0.070 ms/op
Iteration   1: 1.946 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.263 ms/op
                 existUser·p0.50:   1.917 ms/op
                 existUser·p0.90:   2.577 ms/op
                 existUser·p0.95:   2.867 ms/op
                 existUser·p0.99:   3.567 ms/op
                 existUser·p0.999:  11.895 ms/op
                 existUser·p0.9999: 12.179 ms/op
                 existUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16407
  mean =      1.946 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1295 
    [ 1.250,  2.500) = 13106 
    [ 2.500,  3.750) = 1878 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.263 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.577 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      3.567 ms/op
     p(99.9000) =     11.895 ms/op
     p(99.9900) =     12.179 ms/op
     p(99.9990) =     12.190 ms/op
     p(99.9999) =     12.190 ms/op
    p(100.0000) =     12.190 ms/op


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
# Warmup Iteration   1: 3.295 ±(99.9%) 0.081 ms/op
Iteration   1: 2.335 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   2.273 ms/op
                 getUser·p0.90:   2.736 ms/op
                 getUser·p0.95:   2.945 ms/op
                 getUser·p0.99:   4.214 ms/op
                 getUser·p0.999:  28.396 ms/op
                 getUser·p0.9999: 29.322 ms/op
                 getUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13886
  mean =      2.335 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10139 
    [ 2.500,  5.000) = 3638 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      2.273 ms/op
     p(90.0000) =      2.736 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      4.214 ms/op
     p(99.9000) =     28.396 ms/op
     p(99.9900) =     29.322 ms/op
     p(99.9990) =     29.360 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.104 ms/op
Iteration   1: 3.602 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.101 ms/op
                 listUser·p0.999:  20.677 ms/op
                 listUser·p0.9999: 20.906 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8873
  mean =      3.602 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 557 
    [ 2.500,  5.000) = 8129 
    [ 5.000,  7.500) = 132 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      7.101 ms/op
     p(99.9000) =     20.677 ms/op
     p(99.9900) =     20.906 ms/op
     p(99.9990) =     20.906 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.404          ops/ms
ClientSimple.existUser                       thrpt         11.966          ops/ms
ClientSimple.getUser                         thrpt         11.800          ops/ms
ClientSimple.listUser                        thrpt          9.042          ops/ms
ClientSimple.createUser                       avgt          2.158           ms/op
ClientSimple.existUser                        avgt          1.895           ms/op
ClientSimple.getUser                          avgt          2.110           ms/op
ClientSimple.listUser                         avgt          3.317           ms/op
ClientSimple.createUser                     sample  13933   2.332 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.964           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.150           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.847           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.409           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.726           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.893           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.977           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.990           ms/op
ClientSimple.existUser                      sample  16407   1.946 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.263           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.917           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.577           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.867           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.567           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.895           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.179           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.190           ms/op
ClientSimple.getUser                        sample  13886   2.335 ± 0.039   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.779           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.273           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.736           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.945           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.214           ms/op
ClientSimple.getUser:getUser·p0.999         sample         28.396           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         29.322           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.360           ms/op
ClientSimple.listUser                       sample   8873   3.602 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.278           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.527           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.440           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.101           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.677           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.906           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.906           ms/op

Benchmark result is saved to 1719295938824.json
