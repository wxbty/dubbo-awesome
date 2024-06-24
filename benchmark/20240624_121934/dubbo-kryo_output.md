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
# Warmup Iteration   1: 1.046 ops/ms
Iteration   1: 5.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.717 ops/ms


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
# Warmup Iteration   1: 5.508 ops/ms
Iteration   1: 12.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.398 ops/ms


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
# Warmup Iteration   1: 4.937 ops/ms
Iteration   1: 14.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.987 ops/ms


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
# Warmup Iteration   1: 4.806 ops/ms
Iteration   1: 7.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.257 ops/ms


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.067 ms/op
Iteration   1: 2.209 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.209 ms/op


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
# Warmup Iteration   1: 3.386 ±(99.9%) 0.059 ms/op
Iteration   1: 1.881 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.731 ±(99.9%) 0.062 ms/op
Iteration   1: 2.236 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.236 ms/op


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
# Warmup Iteration   1: 4.452 ±(99.9%) 0.085 ms/op
Iteration   1: 3.444 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.444 ms/op


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
# Warmup Iteration   1: 4.122 ±(99.9%) 0.115 ms/op
Iteration   1: 2.120 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.562 ms/op
                 createUser·p0.50:   1.874 ms/op
                 createUser·p0.90:   2.830 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  13.106 ms/op
                 createUser·p0.9999: 13.991 ms/op
                 createUser·p1.00:   14.090 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15069
  mean =      2.120 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 286 
    [ 1.250,  2.500) = 12071 
    [ 2.500,  3.750) = 2405 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      1.874 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     13.106 ms/op
     p(99.9900) =     13.991 ms/op
     p(99.9990) =     14.090 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


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
# Warmup Iteration   1: 3.246 ±(99.9%) 0.078 ms/op
Iteration   1: 1.809 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   1.653 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.626 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  19.431 ms/op
                 existUser·p0.9999: 19.726 ms/op
                 existUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17719
  mean =      1.809 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2200 
    [ 1.250,  2.500) = 14321 
    [ 2.500,  3.750) = 951 
    [ 3.750,  5.000) = 112 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      1.653 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     19.726 ms/op
     p(99.9990) =     19.726 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 3.362 ±(99.9%) 0.079 ms/op
Iteration   1: 2.213 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   2.028 ms/op
                 getUser·p0.90:   2.847 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  17.727 ms/op
                 getUser·p0.9999: 18.172 ms/op
                 getUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14456
  mean =      2.213 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 199 
    [ 1.250,  2.500) = 10907 
    [ 2.500,  3.750) = 3108 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     18.172 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 4.524 ±(99.9%) 0.123 ms/op
Iteration   1: 3.502 ±(99.9%) 0.062 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   3.342 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  31.116 ms/op
                 listUser·p0.9999: 31.457 ms/op
                 listUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9135
  mean =      3.502 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1043 
    [ 2.500,  5.000) = 7731 
    [ 5.000,  7.500) = 317 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     31.116 ms/op
     p(99.9900) =     31.457 ms/op
     p(99.9990) =     31.457 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.717          ops/ms
ClientSimple.existUser                       thrpt         12.398          ops/ms
ClientSimple.getUser                         thrpt         14.987          ops/ms
ClientSimple.listUser                        thrpt          7.257          ops/ms
ClientSimple.createUser                       avgt          2.209           ms/op
ClientSimple.existUser                        avgt          1.881           ms/op
ClientSimple.getUser                          avgt          2.236           ms/op
ClientSimple.listUser                         avgt          3.444           ms/op
ClientSimple.createUser                     sample  15069   2.120 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.562           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.874           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.072           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.775           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.106           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.991           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.090           ms/op
ClientSimple.existUser                      sample  17719   1.809 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.638           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.653           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.626           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.547           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.431           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.726           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.726           ms/op
ClientSimple.getUser                        sample  14456   2.213 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.735           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.028           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.847           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.105           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.308           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.727           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.172           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.186           ms/op
ClientSimple.listUser                       sample   9135   3.502 ± 0.062   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.174           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.342           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.439           ms/op
ClientSimple.listUser:listUser·p0.999       sample         31.116           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         31.457           ms/op
ClientSimple.listUser:listUser·p1.00        sample         31.457           ms/op

Benchmark result is saved to 1719231337587.json
