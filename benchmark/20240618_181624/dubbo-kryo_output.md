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
# Warmup Iteration   1: 1.926 ops/ms
Iteration   1: 6.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.585 ops/ms


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
# Warmup Iteration   1: 6.132 ops/ms
Iteration   1: 12.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.584 ops/ms


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
# Warmup Iteration   1: 5.237 ops/ms
Iteration   1: 12.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.139 ops/ms


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
# Warmup Iteration   1: 5.143 ops/ms
Iteration   1: 8.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.738 ops/ms


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.069 ms/op
Iteration   1: 2.195 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.195 ms/op


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
# Warmup Iteration   1: 3.508 ±(99.9%) 0.065 ms/op
Iteration   1: 1.871 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.871 ms/op


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
# Warmup Iteration   1: 3.392 ±(99.9%) 0.060 ms/op
Iteration   1: 2.157 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.157 ms/op


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.084 ms/op
Iteration   1: 3.608 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.608 ms/op


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
# Warmup Iteration   1: 3.650 ±(99.9%) 0.103 ms/op
Iteration   1: 2.106 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   1.913 ms/op
                 createUser·p0.90:   2.445 ms/op
                 createUser·p0.95:   2.847 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  23.986 ms/op
                 createUser·p0.9999: 26.170 ms/op
                 createUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15196
  mean =      2.106 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13843 
    [ 2.500,  5.000) = 1121 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.847 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     23.986 ms/op
     p(99.9900) =     26.170 ms/op
     p(99.9990) =     26.477 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 2.869 ±(99.9%) 0.063 ms/op
Iteration   1: 1.859 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.432 ms/op
                 existUser·p0.50:   1.731 ms/op
                 existUser·p0.90:   2.286 ms/op
                 existUser·p0.95:   2.531 ms/op
                 existUser·p0.99:   3.265 ms/op
                 existUser·p0.999:  20.513 ms/op
                 existUser·p0.9999: 21.350 ms/op
                 existUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17318
  mean =      1.859 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16377 
    [ 2.500,  5.000) = 818 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      1.731 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.531 ms/op
     p(99.0000) =      3.265 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     21.350 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 3.310 ±(99.9%) 0.096 ms/op
Iteration   1: 1.936 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.614 ms/op
                 getUser·p0.50:   1.823 ms/op
                 getUser·p0.90:   2.388 ms/op
                 getUser·p0.95:   2.642 ms/op
                 getUser·p0.99:   3.965 ms/op
                 getUser·p0.999:  15.448 ms/op
                 getUser·p0.9999: 15.554 ms/op
                 getUser·p1.00:   15.565 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16554
  mean =      1.936 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 15150 
    [ 2.500,  3.750) = 1084 
    [ 3.750,  5.000) = 94 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =     15.448 ms/op
     p(99.9900) =     15.554 ms/op
     p(99.9990) =     15.565 ms/op
     p(99.9999) =     15.565 ms/op
    p(100.0000) =     15.565 ms/op


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.117 ms/op
Iteration   1: 3.613 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  20.389 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8947
  mean =      3.613 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 759 
    [ 2.500,  5.000) = 7822 
    [ 5.000,  7.500) = 331 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     20.389 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     21.103 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.585          ops/ms
ClientSimple.existUser                       thrpt         12.584          ops/ms
ClientSimple.getUser                         thrpt         12.139          ops/ms
ClientSimple.listUser                        thrpt          8.738          ops/ms
ClientSimple.createUser                       avgt          2.195           ms/op
ClientSimple.existUser                        avgt          1.871           ms/op
ClientSimple.getUser                          avgt          2.157           ms/op
ClientSimple.listUser                         avgt          3.608           ms/op
ClientSimple.createUser                     sample  15196   2.106 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.825           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.913           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.445           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.847           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.480           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.986           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.170           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.477           ms/op
ClientSimple.existUser                      sample  17318   1.859 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.432           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.731           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.286           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.531           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.265           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.513           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.350           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.398           ms/op
ClientSimple.getUser                        sample  16554   1.936 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.614           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.823           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.388           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.965           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.448           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.554           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.565           ms/op
ClientSimple.listUser                       sample   8947   3.613 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.766           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.645           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.858           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.759           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.389           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.103           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.103           ms/op

Benchmark result is saved to 1718734324409.json
