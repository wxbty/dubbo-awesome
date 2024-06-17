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
# Warmup Iteration   1: 1.729 ops/ms
Iteration   1: 7.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.377 ops/ms


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
# Warmup Iteration   1: 5.145 ops/ms
Iteration   1: 11.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.586 ops/ms


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
# Warmup Iteration   1: 6.147 ops/ms
Iteration   1: 14.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.724 ops/ms


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
# Warmup Iteration   1: 5.044 ops/ms
Iteration   1: 8.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.764 ops/ms


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
# Warmup Iteration   1: 4.201 ±(99.9%) 0.073 ms/op
Iteration   1: 2.235 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.235 ms/op


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
# Warmup Iteration   1: 3.255 ±(99.9%) 0.058 ms/op
Iteration   1: 1.821 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.821 ms/op


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
# Warmup Iteration   1: 3.453 ±(99.9%) 0.054 ms/op
Iteration   1: 1.993 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.993 ms/op


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
# Warmup Iteration   1: 4.441 ±(99.9%) 0.105 ms/op
Iteration   1: 3.712 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.712 ms/op


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
# Warmup Iteration   1: 3.489 ±(99.9%) 0.099 ms/op
Iteration   1: 2.175 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   2.013 ms/op
                 createUser·p0.90:   2.540 ms/op
                 createUser·p0.95:   2.753 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  16.667 ms/op
                 createUser·p0.9999: 18.121 ms/op
                 createUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14719
  mean =      2.175 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 12878 
    [ 2.500,  3.750) = 1340 
    [ 3.750,  5.000) = 197 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      2.013 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     16.667 ms/op
     p(99.9900) =     18.121 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 3.001 ±(99.9%) 0.065 ms/op
Iteration   1: 1.684 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   1.589 ms/op
                 existUser·p0.90:   1.936 ms/op
                 existUser·p0.95:   2.257 ms/op
                 existUser·p0.99:   3.056 ms/op
                 existUser·p0.999:  18.579 ms/op
                 existUser·p0.9999: 18.678 ms/op
                 existUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18984
  mean =      1.684 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 533 
    [ 1.250,  2.500) = 17899 
    [ 2.500,  3.750) = 419 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      1.589 ms/op
     p(90.0000) =      1.936 ms/op
     p(95.0000) =      2.257 ms/op
     p(99.0000) =      3.056 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     18.678 ms/op
     p(99.9990) =     18.678 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 3.285 ±(99.9%) 0.077 ms/op
Iteration   1: 2.067 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   1.919 ms/op
                 getUser·p0.90:   2.400 ms/op
                 getUser·p0.95:   2.875 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  18.645 ms/op
                 getUser·p0.9999: 21.588 ms/op
                 getUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15459
  mean =      2.067 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14181 
    [ 2.500,  5.000) = 1133 
    [ 5.000,  7.500) = 45 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     21.588 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 4.612 ±(99.9%) 0.128 ms/op
Iteration   1: 3.535 ±(99.9%) 0.134 ms/op
                 listUser·p0.00:   0.672 ms/op
                 listUser·p0.50:   3.146 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   13.107 ms/op
                 listUser·p0.999:  66.976 ms/op
                 listUser·p0.9999: 81.265 ms/op
                 listUser·p1.00:   81.265 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9020
  mean =      3.535 ±(99.9%) 0.134 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8663 
    [ 5.000, 10.000) = 248 
    [10.000, 15.000) = 39 
    [15.000, 20.000) = 36 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 1 
    [55.000, 60.000) = 7 
    [60.000, 65.000) = 3 
    [65.000, 70.000) = 15 
    [70.000, 75.000) = 3 
    [75.000, 80.000) = 0 
    [80.000, 85.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =     13.107 ms/op
     p(99.9000) =     66.976 ms/op
     p(99.9900) =     81.265 ms/op
     p(99.9990) =     81.265 ms/op
     p(99.9999) =     81.265 ms/op
    p(100.0000) =     81.265 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.377          ops/ms
ClientSimple.existUser                       thrpt         11.586          ops/ms
ClientSimple.getUser                         thrpt         14.724          ops/ms
ClientSimple.listUser                        thrpt          8.764          ops/ms
ClientSimple.createUser                       avgt          2.235           ms/op
ClientSimple.existUser                        avgt          1.821           ms/op
ClientSimple.getUser                          avgt          1.993           ms/op
ClientSimple.listUser                         avgt          3.712           ms/op
ClientSimple.createUser                     sample  14719   2.175 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.700           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.013           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.540           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.753           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.874           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.667           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.121           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.121           ms/op
ClientSimple.existUser                      sample  18984   1.684 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.666           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.589           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.936           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.056           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.579           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.678           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.678           ms/op
ClientSimple.getUser                        sample  15459   2.067 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.738           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.919           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.400           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.424           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.645           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.588           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.660           ms/op
ClientSimple.listUser                       sample   9020   3.535 ± 0.134   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.672           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.146           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample         13.107           ms/op
ClientSimple.listUser:listUser·p0.999       sample         66.976           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         81.265           ms/op
ClientSimple.listUser:listUser·p1.00        sample         81.265           ms/op

Benchmark result is saved to 1718584756021.json
