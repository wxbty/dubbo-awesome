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
# Warmup Iteration   1: 1.684 ops/ms
Iteration   1: 7.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.077 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.565 ops/ms
Iteration   1: 13.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.461 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.513 ops/ms
Iteration   1: 11.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.410 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.396 ops/ms
Iteration   1: 8.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.676 ops/ms


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.070 ms/op
Iteration   1: 1.953 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.953 ms/op


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
# Warmup Iteration   1: 3.230 ±(99.9%) 0.048 ms/op
Iteration   1: 1.777 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.777 ms/op


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
# Warmup Iteration   1: 3.156 ±(99.9%) 0.072 ms/op
Iteration   1: 2.121 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.121 ms/op


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
# Warmup Iteration   1: 4.846 ±(99.9%) 0.116 ms/op
Iteration   1: 3.524 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.524 ms/op


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
# Warmup Iteration   1: 3.447 ±(99.9%) 0.088 ms/op
Iteration   1: 2.197 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.582 ms/op
                 createUser·p0.50:   1.985 ms/op
                 createUser·p0.90:   2.654 ms/op
                 createUser·p0.95:   3.066 ms/op
                 createUser·p0.99:   8.196 ms/op
                 createUser·p0.999:  22.358 ms/op
                 createUser·p0.9999: 22.795 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14848
  mean =      2.197 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12424 
    [ 2.500,  5.000) = 2092 
    [ 5.000,  7.500) = 140 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      3.066 ms/op
     p(99.0000) =      8.196 ms/op
     p(99.9000) =     22.358 ms/op
     p(99.9900) =     22.795 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 3.028 ±(99.9%) 0.079 ms/op
Iteration   1: 1.911 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.382 ms/op
                 existUser·p0.50:   1.829 ms/op
                 existUser·p0.90:   2.314 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   4.733 ms/op
                 existUser·p0.999:  20.742 ms/op
                 existUser·p0.9999: 20.958 ms/op
                 existUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16725
  mean =      1.911 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15931 
    [ 2.500,  5.000) = 653 
    [ 5.000,  7.500) = 74 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.382 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      4.733 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     20.958 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 3.246 ±(99.9%) 0.090 ms/op
Iteration   1: 2.113 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   1.948 ms/op
                 getUser·p0.90:   2.548 ms/op
                 getUser·p0.95:   2.802 ms/op
                 getUser·p0.99:   4.378 ms/op
                 getUser·p0.999:  25.461 ms/op
                 getUser·p0.9999: 25.590 ms/op
                 getUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15128
  mean =      2.113 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13364 
    [ 2.500,  5.000) = 1632 
    [ 5.000,  7.500) = 68 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      1.948 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      4.378 ms/op
     p(99.9000) =     25.461 ms/op
     p(99.9900) =     25.590 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.115 ms/op
Iteration   1: 2.859 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.606 ms/op
                 listUser·p0.50:   2.662 ms/op
                 listUser·p0.90:   3.731 ms/op
                 listUser·p0.95:   4.198 ms/op
                 listUser·p0.99:   5.484 ms/op
                 listUser·p0.999:  7.545 ms/op
                 listUser·p0.9999: 9.404 ms/op
                 listUser·p1.00:   9.404 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 11251
  mean =      2.859 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 7 
    [ 1.000,  2.000) = 349 
    [ 2.000,  3.000) = 7330 
    [ 3.000,  4.000) = 2831 
    [ 4.000,  5.000) = 550 
    [ 5.000,  6.000) = 117 
    [ 6.000,  7.000) = 5 
    [ 7.000,  8.000) = 60 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.662 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.198 ms/op
     p(99.0000) =      5.484 ms/op
     p(99.9000) =      7.545 ms/op
     p(99.9900) =      9.404 ms/op
     p(99.9990) =      9.404 ms/op
     p(99.9999) =      9.404 ms/op
    p(100.0000) =      9.404 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.077          ops/ms
ClientSimple.existUser                       thrpt         13.461          ops/ms
ClientSimple.getUser                         thrpt         11.410          ops/ms
ClientSimple.listUser                        thrpt          8.676          ops/ms
ClientSimple.createUser                       avgt          1.953           ms/op
ClientSimple.existUser                        avgt          1.777           ms/op
ClientSimple.getUser                          avgt          2.121           ms/op
ClientSimple.listUser                         avgt          3.524           ms/op
ClientSimple.createUser                     sample  14848   2.197 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.582           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.985           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.654           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.066           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.196           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.358           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.795           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.938           ms/op
ClientSimple.existUser                      sample  16725   1.911 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.382           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.829           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.314           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.733           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.742           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.958           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.201           ms/op
ClientSimple.getUser                        sample  15128   2.113 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.778           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.948           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.548           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.802           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.378           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.461           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.590           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.657           ms/op
ClientSimple.listUser                       sample  11251   2.859 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.606           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.662           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.731           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.198           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.484           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.545           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.404           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.404           ms/op

Benchmark result is saved to 1716617506315.json
