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
# Warmup Iteration   1: 2.017 ops/ms
Iteration   1: 8.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.010 ops/ms


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
# Warmup Iteration   1: 5.555 ops/ms
Iteration   1: 10.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.648 ops/ms


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
# Warmup Iteration   1: 6.292 ops/ms
Iteration   1: 15.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.294 ops/ms


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
# Warmup Iteration   1: 5.151 ops/ms
Iteration   1: 8.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.917 ops/ms


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
# Warmup Iteration   1: 4.100 ±(99.9%) 0.090 ms/op
Iteration   1: 2.271 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.271 ms/op


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
# Warmup Iteration   1: 2.889 ±(99.9%) 0.045 ms/op
Iteration   1: 1.694 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.694 ms/op


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
# Warmup Iteration   1: 3.279 ±(99.9%) 0.064 ms/op
Iteration   1: 1.928 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.928 ms/op


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
# Warmup Iteration   1: 4.632 ±(99.9%) 0.086 ms/op
Iteration   1: 2.635 ±(99.9%) 0.046 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.635 ms/op


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
# Warmup Iteration   1: 3.583 ±(99.9%) 0.087 ms/op
Iteration   1: 2.001 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.480 ms/op
                 createUser·p0.50:   1.888 ms/op
                 createUser·p0.90:   2.449 ms/op
                 createUser·p0.95:   2.646 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  19.008 ms/op
                 createUser·p0.9999: 21.830 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15964
  mean =      2.001 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14698 
    [ 2.500,  5.000) = 1125 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.480 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =     19.008 ms/op
     p(99.9900) =     21.830 ms/op
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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.081 ±(99.9%) 0.063 ms/op
Iteration   1: 2.006 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.542 ms/op
                 existUser·p0.50:   1.855 ms/op
                 existUser·p0.90:   2.449 ms/op
                 existUser·p0.95:   2.671 ms/op
                 existUser·p0.99:   5.369 ms/op
                 existUser·p0.999:  18.809 ms/op
                 existUser·p0.9999: 19.154 ms/op
                 existUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15930
  mean =      2.006 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 481 
    [ 1.250,  2.500) = 14167 
    [ 2.500,  3.750) = 1002 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      5.369 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     19.154 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 3.288 ±(99.9%) 0.075 ms/op
Iteration   1: 1.601 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   1.456 ms/op
                 getUser·p0.90:   2.245 ms/op
                 getUser·p0.95:   2.466 ms/op
                 getUser·p0.99:   3.331 ms/op
                 getUser·p0.999:  13.617 ms/op
                 getUser·p0.9999: 14.730 ms/op
                 getUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 19979
  mean =      1.601 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4754 
    [ 1.250,  2.500) = 14376 
    [ 2.500,  3.750) = 682 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      1.456 ms/op
     p(90.0000) =      2.245 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      3.331 ms/op
     p(99.9000) =     13.617 ms/op
     p(99.9900) =     14.730 ms/op
     p(99.9990) =     14.893 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 4.442 ±(99.9%) 0.151 ms/op
Iteration   1: 3.690 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.786 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  24.448 ms/op
                 listUser·p0.9999: 26.968 ms/op
                 listUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8841
  mean =      3.690 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 664 
    [ 2.500,  5.000) = 7805 
    [ 5.000,  7.500) = 324 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     24.448 ms/op
     p(99.9900) =     26.968 ms/op
     p(99.9990) =     26.968 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.010          ops/ms
ClientSimple.existUser                       thrpt         10.648          ops/ms
ClientSimple.getUser                         thrpt         15.294          ops/ms
ClientSimple.listUser                        thrpt          8.917          ops/ms
ClientSimple.createUser                       avgt          2.271           ms/op
ClientSimple.existUser                        avgt          1.694           ms/op
ClientSimple.getUser                          avgt          1.928           ms/op
ClientSimple.listUser                         avgt          2.635           ms/op
ClientSimple.createUser                     sample  15964   2.001 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.480           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.888           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.449           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.646           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.391           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.008           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.830           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.889           ms/op
ClientSimple.existUser                      sample  15930   2.006 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.542           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.855           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.671           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.369           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.809           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.154           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.562           ms/op
ClientSimple.getUser                        sample  19979   1.601 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.713           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.456           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.245           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.331           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.617           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.730           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.893           ms/op
ClientSimple.listUser                       sample   8841   3.690 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.786           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.666           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.801           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.004           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.448           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.968           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.968           ms/op

Benchmark result is saved to 1719621434081.json
