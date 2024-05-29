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
# Warmup Iteration   1: 1.552 ops/ms
Iteration   1: 6.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.953 ops/ms


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
# Warmup Iteration   1: 5.560 ops/ms
Iteration   1: 12.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.142 ops/ms


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
# Warmup Iteration   1: 5.869 ops/ms
Iteration   1: 12.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.937 ops/ms


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
# Warmup Iteration   1: 5.673 ops/ms
Iteration   1: 9.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.109 ops/ms


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.072 ms/op
Iteration   1: 2.076 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.076 ms/op


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
# Warmup Iteration   1: 2.858 ±(99.9%) 0.045 ms/op
Iteration   1: 1.795 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.795 ms/op


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
# Warmup Iteration   1: 2.949 ±(99.9%) 0.056 ms/op
Iteration   1: 2.016 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.016 ms/op


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
# Warmup Iteration   1: 4.356 ±(99.9%) 0.092 ms/op
Iteration   1: 3.432 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.432 ms/op


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
# Warmup Iteration   1: 3.259 ±(99.9%) 0.081 ms/op
Iteration   1: 2.004 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.781 ms/op
                 createUser·p0.50:   1.837 ms/op
                 createUser·p0.90:   2.310 ms/op
                 createUser·p0.95:   2.572 ms/op
                 createUser·p0.99:   7.397 ms/op
                 createUser·p0.999:  15.844 ms/op
                 createUser·p0.9999: 16.823 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15950
  mean =      2.004 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 179 
    [ 1.250,  2.500) = 14815 
    [ 2.500,  3.750) = 776 
    [ 3.750,  5.000) = 19 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     15.844 ms/op
     p(99.9900) =     16.823 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 2.929 ±(99.9%) 0.065 ms/op
Iteration   1: 1.915 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   1.661 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.613 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  18.317 ms/op
                 existUser·p0.9999: 18.611 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16709
  mean =      1.915 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 516 
    [ 1.250,  2.500) = 14757 
    [ 2.500,  3.750) = 1255 
    [ 3.750,  5.000) = 6 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      1.661 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     18.611 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 3.117 ±(99.9%) 0.074 ms/op
Iteration   1: 1.729 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.575 ms/op
                 getUser·p0.50:   1.618 ms/op
                 getUser·p0.90:   2.134 ms/op
                 getUser·p0.95:   2.355 ms/op
                 getUser·p0.99:   2.904 ms/op
                 getUser·p0.999:  10.920 ms/op
                 getUser·p0.9999: 11.179 ms/op
                 getUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18488
  mean =      1.729 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 313 
    [ 1.250,  2.500) = 17654 
    [ 2.500,  3.750) = 440 
    [ 3.750,  5.000) = 9 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      1.618 ms/op
     p(90.0000) =      2.134 ms/op
     p(95.0000) =      2.355 ms/op
     p(99.0000) =      2.904 ms/op
     p(99.9000) =     10.920 ms/op
     p(99.9900) =     11.179 ms/op
     p(99.9990) =     11.207 ms/op
     p(99.9999) =     11.207 ms/op
    p(100.0000) =     11.207 ms/op


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.136 ms/op
Iteration   1: 3.051 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.791 ms/op
                 listUser·p0.50:   2.814 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   4.884 ms/op
                 listUser·p0.999:  14.304 ms/op
                 listUser·p0.9999: 14.877 ms/op
                 listUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10480
  mean =      3.051 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1058 
    [ 2.500,  3.750) = 7890 
    [ 3.750,  5.000) = 1435 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      4.884 ms/op
     p(99.9000) =     14.304 ms/op
     p(99.9900) =     14.877 ms/op
     p(99.9990) =     14.893 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.953          ops/ms
ClientSimple.existUser                       thrpt         12.142          ops/ms
ClientSimple.getUser                         thrpt         12.937          ops/ms
ClientSimple.listUser                        thrpt          9.109          ops/ms
ClientSimple.createUser                       avgt          2.076           ms/op
ClientSimple.existUser                        avgt          1.795           ms/op
ClientSimple.getUser                          avgt          2.016           ms/op
ClientSimple.listUser                         avgt          3.432           ms/op
ClientSimple.createUser                     sample  15950   2.004 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.781           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.837           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.310           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.572           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.397           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.844           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.823           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.843           ms/op
ClientSimple.existUser                      sample  16709   1.915 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.669           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.661           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.613           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.300           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.317           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.611           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.743           ms/op
ClientSimple.getUser                        sample  18488   1.729 ± 0.013   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.575           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.618           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.134           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.355           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.904           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.920           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.179           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.207           ms/op
ClientSimple.listUser                       sample  10480   3.051 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.791           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.814           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.953           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.186           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.884           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.304           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.877           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.893           ms/op

Benchmark result is saved to 1716984895947.json
