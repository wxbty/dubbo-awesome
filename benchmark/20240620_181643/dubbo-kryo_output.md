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
# Warmup Iteration   1: 1.609 ops/ms
Iteration   1: 6.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.617 ops/ms


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
# Warmup Iteration   1: 6.255 ops/ms
Iteration   1: 13.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.045 ops/ms


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
# Warmup Iteration   1: 5.909 ops/ms
Iteration   1: 12.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.746 ops/ms


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
# Warmup Iteration   1: 5.104 ops/ms
Iteration   1: 8.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.095 ops/ms


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.086 ms/op
Iteration   1: 2.345 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.345 ms/op


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
# Warmup Iteration   1: 3.463 ±(99.9%) 0.057 ms/op
Iteration   1: 2.184 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.184 ms/op


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
# Warmup Iteration   1: 3.441 ±(99.9%) 0.054 ms/op
Iteration   1: 1.940 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.940 ms/op


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
# Warmup Iteration   1: 5.426 ±(99.9%) 0.126 ms/op
Iteration   1: 3.308 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.308 ms/op


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.107 ms/op
Iteration   1: 2.461 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.569 ms/op
                 createUser·p0.50:   2.310 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   9.261 ms/op
                 createUser·p0.999:  12.632 ms/op
                 createUser·p0.9999: 12.714 ms/op
                 createUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12988
  mean =      2.461 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 234 
    [ 1.250,  2.500) = 7865 
    [ 2.500,  3.750) = 4313 
    [ 3.750,  5.000) = 291 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      2.310 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      9.261 ms/op
     p(99.9000) =     12.632 ms/op
     p(99.9900) =     12.714 ms/op
     p(99.9990) =     12.714 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


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
# Warmup Iteration   1: 3.146 ±(99.9%) 0.069 ms/op
Iteration   1: 1.865 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.518 ms/op
                 existUser·p0.50:   1.690 ms/op
                 existUser·p0.90:   2.195 ms/op
                 existUser·p0.95:   2.446 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  22.638 ms/op
                 existUser·p0.9999: 23.645 ms/op
                 existUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17137
  mean =      1.865 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16441 
    [ 2.500,  5.000) = 548 
    [ 5.000,  7.500) = 79 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      1.690 ms/op
     p(90.0000) =      2.195 ms/op
     p(95.0000) =      2.446 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =     22.638 ms/op
     p(99.9900) =     23.645 ms/op
     p(99.9990) =     23.855 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 3.269 ±(99.9%) 0.079 ms/op
Iteration   1: 2.491 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   3.158 ms/op
                 getUser·p0.95:   3.400 ms/op
                 getUser·p0.99:   4.059 ms/op
                 getUser·p0.999:  13.096 ms/op
                 getUser·p0.9999: 14.151 ms/op
                 getUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 12838
  mean =      2.491 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 6800 
    [ 2.500,  3.750) = 5570 
    [ 3.750,  5.000) = 257 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.449 ms/op
     p(90.0000) =      3.158 ms/op
     p(95.0000) =      3.400 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =     13.096 ms/op
     p(99.9900) =     14.151 ms/op
     p(99.9990) =     14.189 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 4.860 ±(99.9%) 0.157 ms/op
Iteration   1: 3.786 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   3.705 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  23.281 ms/op
                 listUser·p0.9999: 25.100 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8524
  mean =      3.786 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 392 
    [ 2.500,  5.000) = 7732 
    [ 5.000,  7.500) = 338 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.981 ms/op
     p(50.0000) =      3.705 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     23.281 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     25.100 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.617          ops/ms
ClientSimple.existUser                       thrpt         13.045          ops/ms
ClientSimple.getUser                         thrpt         12.746          ops/ms
ClientSimple.listUser                        thrpt          8.095          ops/ms
ClientSimple.createUser                       avgt          2.345           ms/op
ClientSimple.existUser                        avgt          2.184           ms/op
ClientSimple.getUser                          avgt          1.940           ms/op
ClientSimple.listUser                         avgt          3.308           ms/op
ClientSimple.createUser                     sample  12988   2.461 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.569           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.310           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.998           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.596           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.261           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.632           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         12.714           ms/op
ClientSimple.createUser:createUser·p1.00    sample         12.714           ms/op
ClientSimple.existUser                      sample  17137   1.865 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.518           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.690           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.195           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.446           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.899           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.638           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.645           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.855           ms/op
ClientSimple.getUser                        sample  12838   2.491 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.672           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.449           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.158           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.400           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.059           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.096           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.151           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.189           ms/op
ClientSimple.listUser                       sample   8524   3.786 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.981           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.705           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.440           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.850           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.012           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.281           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.100           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.100           ms/op

Benchmark result is saved to 1718907142543.json
