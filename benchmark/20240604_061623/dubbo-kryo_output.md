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
# Warmup Iteration   1: 1.666 ops/ms
Iteration   1: 7.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.069 ops/ms


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
# Warmup Iteration   1: 5.476 ops/ms
Iteration   1: 14.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.398 ops/ms


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
# Warmup Iteration   1: 5.640 ops/ms
Iteration   1: 13.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.452 ops/ms


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
# Warmup Iteration   1: 4.717 ops/ms
Iteration   1: 8.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.941 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.120 ±(99.9%) 0.074 ms/op
Iteration   1: 2.072 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.072 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.307 ±(99.9%) 0.054 ms/op
Iteration   1: 1.612 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.612 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.360 ±(99.9%) 0.073 ms/op
Iteration   1: 1.881 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.881 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.761 ±(99.9%) 0.132 ms/op
Iteration   1: 3.580 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.580 ms/op


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
# Warmup Iteration   1: 3.344 ±(99.9%) 0.090 ms/op
Iteration   1: 2.025 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.517 ms/op
                 createUser·p0.50:   1.890 ms/op
                 createUser·p0.90:   2.454 ms/op
                 createUser·p0.95:   2.634 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  18.973 ms/op
                 createUser·p0.9999: 20.939 ms/op
                 createUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15776
  mean =      2.025 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14457 
    [ 2.500,  5.000) = 1144 
    [ 5.000,  7.500) = 46 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.879 ±(99.9%) 0.071 ms/op
Iteration   1: 1.923 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.601 ms/op
                 existUser·p0.50:   1.800 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.548 ms/op
                 existUser·p0.99:   5.081 ms/op
                 existUser·p0.999:  15.839 ms/op
                 existUser·p0.9999: 16.522 ms/op
                 existUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16623
  mean =      1.923 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 420 
    [ 1.250,  2.500) = 15230 
    [ 2.500,  3.750) = 788 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 94 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      5.081 ms/op
     p(99.9000) =     15.839 ms/op
     p(99.9900) =     16.522 ms/op
     p(99.9990) =     16.728 ms/op
     p(99.9999) =     16.728 ms/op
    p(100.0000) =     16.728 ms/op


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
# Warmup Iteration   1: 3.378 ±(99.9%) 0.091 ms/op
Iteration   1: 2.170 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.520 ms/op
                 getUser·p0.50:   2.175 ms/op
                 getUser·p0.90:   2.638 ms/op
                 getUser·p0.95:   2.777 ms/op
                 getUser·p0.99:   3.629 ms/op
                 getUser·p0.999:  13.124 ms/op
                 getUser·p0.9999: 13.584 ms/op
                 getUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14719
  mean =      2.170 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 285 
    [ 1.250,  2.500) = 11640 
    [ 2.500,  3.750) = 2684 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      2.175 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =     13.124 ms/op
     p(99.9900) =     13.584 ms/op
     p(99.9990) =     13.615 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


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
# Warmup Iteration   1: 4.319 ±(99.9%) 0.139 ms/op
Iteration   1: 2.987 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   2.654 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.149 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  20.742 ms/op
                 listUser·p0.9999: 21.728 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10759
  mean =      2.987 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4065 
    [ 2.500,  5.000) = 6528 
    [ 5.000,  7.500) = 132 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.654 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     21.728 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.069          ops/ms
ClientSimple.existUser                       thrpt         14.398          ops/ms
ClientSimple.getUser                         thrpt         13.452          ops/ms
ClientSimple.listUser                        thrpt          8.941          ops/ms
ClientSimple.createUser                       avgt          2.072           ms/op
ClientSimple.existUser                        avgt          1.612           ms/op
ClientSimple.getUser                          avgt          1.881           ms/op
ClientSimple.listUser                         avgt          3.580           ms/op
ClientSimple.createUser                     sample  15776   2.025 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.517           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.890           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.454           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.634           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.169           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.973           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.939           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.939           ms/op
ClientSimple.existUser                      sample  16623   1.923 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.601           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.800           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.548           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.081           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.839           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.522           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.728           ms/op
ClientSimple.getUser                        sample  14719   2.170 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.520           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.175           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.629           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.124           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.584           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.615           ms/op
ClientSimple.listUser                       sample  10759   2.987 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.940           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.654           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.895           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.149           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.374           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.742           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.728           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.758           ms/op

Benchmark result is saved to 1717481501875.json
