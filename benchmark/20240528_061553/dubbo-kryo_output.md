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
# Warmup Iteration   1: 1.966 ops/ms
Iteration   1: 6.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.793 ops/ms


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
# Warmup Iteration   1: 6.487 ops/ms
Iteration   1: 13.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.337 ops/ms


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
# Warmup Iteration   1: 5.441 ops/ms
Iteration   1: 13.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.722 ops/ms


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
# Warmup Iteration   1: 4.992 ops/ms
Iteration   1: 8.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.839 ops/ms


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
# Warmup Iteration   1: 3.805 ±(99.9%) 0.070 ms/op
Iteration   1: 2.108 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.108 ms/op


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
# Warmup Iteration   1: 3.141 ±(99.9%) 0.043 ms/op
Iteration   1: 1.883 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.883 ms/op


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
# Warmup Iteration   1: 3.255 ±(99.9%) 0.065 ms/op
Iteration   1: 2.077 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.077 ms/op


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
# Warmup Iteration   1: 4.323 ±(99.9%) 0.096 ms/op
Iteration   1: 3.278 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.278 ms/op


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
# Warmup Iteration   1: 3.708 ±(99.9%) 0.103 ms/op
Iteration   1: 2.081 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.414 ms/op
                 createUser·p0.50:   1.939 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.716 ms/op
                 createUser·p0.99:   8.900 ms/op
                 createUser·p0.999:  15.073 ms/op
                 createUser·p0.9999: 16.349 ms/op
                 createUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15377
  mean =      2.081 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 330 
    [ 1.250,  2.500) = 13331 
    [ 2.500,  3.750) = 1415 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.414 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      8.900 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     16.349 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.862 ±(99.9%) 0.076 ms/op
Iteration   1: 1.905 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.481 ms/op
                 existUser·p0.50:   1.798 ms/op
                 existUser·p0.90:   2.212 ms/op
                 existUser·p0.95:   2.376 ms/op
                 existUser·p0.99:   4.932 ms/op
                 existUser·p0.999:  22.905 ms/op
                 existUser·p0.9999: 23.079 ms/op
                 existUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16792
  mean =      1.905 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16251 
    [ 2.500,  5.000) = 375 
    [ 5.000,  7.500) = 35 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.376 ms/op
     p(99.0000) =      4.932 ms/op
     p(99.9000) =     22.905 ms/op
     p(99.9900) =     23.079 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 3.327 ±(99.9%) 0.077 ms/op
Iteration   1: 2.261 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   2.204 ms/op
                 getUser·p0.90:   2.798 ms/op
                 getUser·p0.95:   3.052 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  11.895 ms/op
                 getUser·p0.9999: 13.123 ms/op
                 getUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14194
  mean =      2.261 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 224 
    [ 1.250,  2.500) = 9510 
    [ 2.500,  3.750) = 4345 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.798 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =     11.895 ms/op
     p(99.9900) =     13.123 ms/op
     p(99.9990) =     13.206 ms/op
     p(99.9999) =     13.206 ms/op
    p(100.0000) =     13.206 ms/op


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
# Warmup Iteration   1: 4.876 ±(99.9%) 0.151 ms/op
Iteration   1: 3.600 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   3.506 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   10.886 ms/op
                 listUser·p0.999:  18.285 ms/op
                 listUser·p0.9999: 18.350 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8955
  mean =      3.600 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 746 
    [ 2.500,  3.750) = 5439 
    [ 3.750,  5.000) = 2429 
    [ 5.000,  6.250) = 184 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =     10.886 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.793          ops/ms
ClientSimple.existUser                       thrpt         13.337          ops/ms
ClientSimple.getUser                         thrpt         13.722          ops/ms
ClientSimple.listUser                        thrpt          8.839          ops/ms
ClientSimple.createUser                       avgt          2.108           ms/op
ClientSimple.existUser                        avgt          1.883           ms/op
ClientSimple.getUser                          avgt          2.077           ms/op
ClientSimple.listUser                         avgt          3.278           ms/op
ClientSimple.createUser                     sample  15377   2.081 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.414           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.939           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.716           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.900           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.073           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.349           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.728           ms/op
ClientSimple.existUser                      sample  16792   1.905 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.481           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.798           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.212           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.376           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.932           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.905           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.079           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.101           ms/op
ClientSimple.getUser                        sample  14194   2.261 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.765           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.204           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.798           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.052           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.650           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.895           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.123           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.206           ms/op
ClientSimple.listUser                       sample   8955   3.600 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.186           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.506           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.886           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.285           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.350           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.350           ms/op

Benchmark result is saved to 1716876707912.json
