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
# Warmup Iteration   1: 1.164 ops/ms
Iteration   1: 6.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.016 ops/ms


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
# Warmup Iteration   1: 5.559 ops/ms
Iteration   1: 11.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.495 ops/ms


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
# Warmup Iteration   1: 5.668 ops/ms
Iteration   1: 13.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.251 ops/ms


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
# Warmup Iteration   1: 4.989 ops/ms
Iteration   1: 8.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.827 ops/ms


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
# Warmup Iteration   1: 3.923 ±(99.9%) 0.064 ms/op
Iteration   1: 2.215 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.215 ms/op


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
# Warmup Iteration   1: 3.075 ±(99.9%) 0.051 ms/op
Iteration   1: 2.043 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.043 ms/op


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
# Warmup Iteration   1: 3.421 ±(99.9%) 0.063 ms/op
Iteration   1: 2.042 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.042 ms/op


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
# Warmup Iteration   1: 4.131 ±(99.9%) 0.081 ms/op
Iteration   1: 3.331 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.331 ms/op


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
# Warmup Iteration   1: 3.807 ±(99.9%) 0.189 ms/op
Iteration   1: 2.212 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.500 ms/op
                 createUser·p0.50:   1.952 ms/op
                 createUser·p0.90:   2.806 ms/op
                 createUser·p0.95:   3.019 ms/op
                 createUser·p0.99:   8.014 ms/op
                 createUser·p0.999:  20.285 ms/op
                 createUser·p0.9999: 21.391 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14473
  mean =      2.212 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11171 
    [ 2.500,  5.000) = 3026 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =      8.014 ms/op
     p(99.9000) =     20.285 ms/op
     p(99.9900) =     21.391 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 3.027 ±(99.9%) 0.080 ms/op
Iteration   1: 2.124 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.487 ms/op
                 existUser·p0.50:   2.030 ms/op
                 existUser·p0.90:   2.523 ms/op
                 existUser·p0.95:   2.707 ms/op
                 existUser·p0.99:   3.477 ms/op
                 existUser·p0.999:  24.969 ms/op
                 existUser·p0.9999: 25.885 ms/op
                 existUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15075
  mean =      2.124 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13438 
    [ 2.500,  5.000) = 1527 
    [ 5.000,  7.500) = 46 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      3.477 ms/op
     p(99.9000) =     24.969 ms/op
     p(99.9900) =     25.885 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 3.180 ±(99.9%) 0.081 ms/op
Iteration   1: 1.921 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.594 ms/op
                 getUser·p0.50:   1.718 ms/op
                 getUser·p0.90:   2.593 ms/op
                 getUser·p0.95:   2.810 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  20.513 ms/op
                 getUser·p0.9999: 21.223 ms/op
                 getUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16641
  mean =      1.921 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14740 
    [ 2.500,  5.000) = 1789 
    [ 5.000,  7.500) = 80 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      1.718 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     21.223 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 4.741 ±(99.9%) 0.138 ms/op
Iteration   1: 3.598 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   5.884 ms/op
                 listUser·p0.999:  7.160 ms/op
                 listUser·p0.9999: 7.274 ms/op
                 listUser·p1.00:   7.274 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8892
  mean =      3.598 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 7 
    [1.500, 2.000) = 43 
    [2.000, 2.500) = 442 
    [2.500, 3.000) = 1507 
    [3.000, 3.500) = 1524 
    [3.500, 4.000) = 3240 
    [4.000, 4.500) = 1324 
    [4.500, 5.000) = 625 
    [5.000, 5.500) = 61 
    [5.500, 6.000) = 34 
    [6.000, 6.500) = 6 
    [6.500, 7.000) = 57 
    [7.000, 7.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      5.884 ms/op
     p(99.9000) =      7.160 ms/op
     p(99.9900) =      7.274 ms/op
     p(99.9990) =      7.274 ms/op
     p(99.9999) =      7.274 ms/op
    p(100.0000) =      7.274 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.016          ops/ms
ClientSimple.existUser                       thrpt         11.495          ops/ms
ClientSimple.getUser                         thrpt         13.251          ops/ms
ClientSimple.listUser                        thrpt          8.827          ops/ms
ClientSimple.createUser                       avgt          2.215           ms/op
ClientSimple.existUser                        avgt          2.043           ms/op
ClientSimple.getUser                          avgt          2.042           ms/op
ClientSimple.listUser                         avgt          3.331           ms/op
ClientSimple.createUser                     sample  14473   2.212 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.500           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.952           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.806           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.019           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.014           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.285           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.391           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.889           ms/op
ClientSimple.existUser                      sample  15075   2.124 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.487           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.030           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.523           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.707           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.477           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.969           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.885           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.985           ms/op
ClientSimple.getUser                        sample  16641   1.921 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.594           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.718           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.424           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.513           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.223           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.332           ms/op
ClientSimple.listUser                       sample   8892   3.598 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.214           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.654           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.884           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.160           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.274           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.274           ms/op

Benchmark result is saved to 1716898498350.json
