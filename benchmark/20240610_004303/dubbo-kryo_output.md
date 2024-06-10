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
# Warmup Iteration   1: 1.815 ops/ms
Iteration   1: 7.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.587 ops/ms


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
# Warmup Iteration   1: 6.368 ops/ms
Iteration   1: 13.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.799 ops/ms


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
# Warmup Iteration   1: 6.188 ops/ms
Iteration   1: 12.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.662 ops/ms


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
# Warmup Iteration   1: 5.724 ops/ms
Iteration   1: 7.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.824 ops/ms


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.069 ms/op
Iteration   1: 2.005 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.005 ms/op


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
# Warmup Iteration   1: 3.494 ±(99.9%) 0.049 ms/op
Iteration   1: 2.092 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.092 ms/op


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
# Warmup Iteration   1: 3.712 ±(99.9%) 0.076 ms/op
Iteration   1: 2.053 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.053 ms/op


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
# Warmup Iteration   1: 5.023 ±(99.9%) 0.099 ms/op
Iteration   1: 3.286 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.286 ms/op


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
# Warmup Iteration   1: 3.583 ±(99.9%) 0.086 ms/op
Iteration   1: 2.052 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.418 ms/op
                 createUser·p0.50:   1.853 ms/op
                 createUser·p0.90:   2.597 ms/op
                 createUser·p0.95:   2.789 ms/op
                 createUser·p0.99:   6.834 ms/op
                 createUser·p0.999:  16.742 ms/op
                 createUser·p0.9999: 16.941 ms/op
                 createUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15581
  mean =      2.052 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 365 
    [ 1.250,  2.500) = 13243 
    [ 2.500,  3.750) = 1741 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      6.834 ms/op
     p(99.9000) =     16.742 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 3.056 ±(99.9%) 0.075 ms/op
Iteration   1: 1.900 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.413 ms/op
                 existUser·p0.95:   2.861 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  13.074 ms/op
                 existUser·p0.9999: 13.377 ms/op
                 existUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16830
  mean =      1.900 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 361 
    [ 1.250,  2.500) = 14990 
    [ 2.500,  3.750) = 1353 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.861 ms/op
     p(99.0000) =      3.506 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     13.377 ms/op
     p(99.9990) =     13.500 ms/op
     p(99.9999) =     13.500 ms/op
    p(100.0000) =     13.500 ms/op


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
# Warmup Iteration   1: 3.572 ±(99.9%) 0.090 ms/op
Iteration   1: 2.118 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   2.056 ms/op
                 getUser·p0.90:   2.638 ms/op
                 getUser·p0.95:   2.806 ms/op
                 getUser·p0.99:   3.518 ms/op
                 getUser·p0.999:  12.399 ms/op
                 getUser·p0.9999: 13.054 ms/op
                 getUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15104
  mean =      2.118 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 192 
    [ 1.250,  2.500) = 12536 
    [ 2.500,  3.750) = 2259 
    [ 3.750,  5.000) = 23 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.056 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      3.518 ms/op
     p(99.9000) =     12.399 ms/op
     p(99.9900) =     13.054 ms/op
     p(99.9990) =     13.255 ms/op
     p(99.9999) =     13.255 ms/op
    p(100.0000) =     13.255 ms/op


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
# Warmup Iteration   1: 4.432 ±(99.9%) 0.148 ms/op
Iteration   1: 3.206 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.667 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.596 ms/op
                 listUser·p0.999:  12.068 ms/op
                 listUser·p0.9999: 19.324 ms/op
                 listUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10036
  mean =      3.206 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 1446 
    [ 2.500,  3.750) = 6542 
    [ 3.750,  5.000) = 1713 
    [ 5.000,  6.250) = 129 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.596 ms/op
     p(99.9000) =     12.068 ms/op
     p(99.9900) =     19.324 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.587          ops/ms
ClientSimple.existUser                       thrpt         13.799          ops/ms
ClientSimple.getUser                         thrpt         12.662          ops/ms
ClientSimple.listUser                        thrpt          7.824          ops/ms
ClientSimple.createUser                       avgt          2.005           ms/op
ClientSimple.existUser                        avgt          2.092           ms/op
ClientSimple.getUser                          avgt          2.053           ms/op
ClientSimple.listUser                         avgt          3.286           ms/op
ClientSimple.createUser                     sample  15581   2.052 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.418           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.853           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.597           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.834           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.742           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.941           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.941           ms/op
ClientSimple.existUser                      sample  16830   1.900 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.658           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.769           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.413           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.861           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.506           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.074           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.377           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.500           ms/op
ClientSimple.getUser                        sample  15104   2.118 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.756           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.056           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.518           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.399           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.054           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.255           ms/op
ClientSimple.listUser                       sample  10036   3.206 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.667           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.929           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.133           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.596           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.068           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.324           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.333           ms/op

Benchmark result is saved to 1717979942555.json
