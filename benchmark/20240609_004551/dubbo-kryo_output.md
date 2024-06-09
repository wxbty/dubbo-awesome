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
# Warmup Iteration   1: 1.597 ops/ms
Iteration   1: 6.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.879 ops/ms


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
# Warmup Iteration   1: 6.638 ops/ms
Iteration   1: 12.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.139 ops/ms


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
# Warmup Iteration   1: 4.904 ops/ms
Iteration   1: 12.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.750 ops/ms


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
# Warmup Iteration   1: 5.753 ops/ms
Iteration   1: 8.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.814 ops/ms


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
# Warmup Iteration   1: 4.176 ±(99.9%) 0.072 ms/op
Iteration   1: 2.124 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.124 ms/op


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
# Warmup Iteration   1: 3.040 ±(99.9%) 0.046 ms/op
Iteration   1: 1.863 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.863 ms/op


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
# Warmup Iteration   1: 3.107 ±(99.9%) 0.051 ms/op
Iteration   1: 2.002 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.002 ms/op


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
# Warmup Iteration   1: 4.551 ±(99.9%) 0.097 ms/op
Iteration   1: 3.357 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.357 ms/op


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.097 ms/op
Iteration   1: 2.077 ±(99.9%) 0.058 ms/op
                 createUser·p0.00:   0.323 ms/op
                 createUser·p0.50:   1.831 ms/op
                 createUser·p0.90:   2.531 ms/op
                 createUser·p0.95:   2.920 ms/op
                 createUser·p0.99:   8.177 ms/op
                 createUser·p0.999:  43.123 ms/op
                 createUser·p0.9999: 50.977 ms/op
                 createUser·p1.00:   51.118 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15389
  mean =      2.077 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15130 
    [ 5.000, 10.000) = 152 
    [10.000, 15.000) = 69 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 6 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 15 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.323 ms/op
     p(50.0000) =      1.831 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      8.177 ms/op
     p(99.9000) =     43.123 ms/op
     p(99.9900) =     50.977 ms/op
     p(99.9990) =     51.118 ms/op
     p(99.9999) =     51.118 ms/op
    p(100.0000) =     51.118 ms/op


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
# Warmup Iteration   1: 3.087 ±(99.9%) 0.076 ms/op
Iteration   1: 1.885 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   1.733 ms/op
                 existUser·p0.90:   2.392 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   4.554 ms/op
                 existUser·p0.999:  13.485 ms/op
                 existUser·p0.9999: 14.696 ms/op
                 existUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16955
  mean =      1.885 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 407 
    [ 1.250,  2.500) = 15197 
    [ 2.500,  3.750) = 1172 
    [ 3.750,  5.000) = 122 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      1.733 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      4.554 ms/op
     p(99.9000) =     13.485 ms/op
     p(99.9900) =     14.696 ms/op
     p(99.9990) =     14.696 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 3.236 ±(99.9%) 0.085 ms/op
Iteration   1: 2.157 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   2.044 ms/op
                 getUser·p0.90:   2.646 ms/op
                 getUser·p0.95:   2.904 ms/op
                 getUser·p0.99:   5.847 ms/op
                 getUser·p0.999:  21.856 ms/op
                 getUser·p0.9999: 22.036 ms/op
                 getUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15084
  mean =      2.157 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12591 
    [ 2.500,  5.000) = 2314 
    [ 5.000,  7.500) = 83 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.044 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      5.847 ms/op
     p(99.9000) =     21.856 ms/op
     p(99.9900) =     22.036 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 5.199 ±(99.9%) 0.190 ms/op
Iteration   1: 3.295 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   0.680 ms/op
                 listUser·p0.50:   3.058 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.658 ms/op
                 listUser·p0.999:  12.002 ms/op
                 listUser·p0.9999: 12.337 ms/op
                 listUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9726
  mean =      3.295 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 696 
    [ 2.500,  3.750) = 6725 
    [ 3.750,  5.000) = 2062 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.058 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.658 ms/op
     p(99.9000) =     12.002 ms/op
     p(99.9900) =     12.337 ms/op
     p(99.9990) =     12.337 ms/op
     p(99.9999) =     12.337 ms/op
    p(100.0000) =     12.337 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.879          ops/ms
ClientSimple.existUser                       thrpt         12.139          ops/ms
ClientSimple.getUser                         thrpt         12.750          ops/ms
ClientSimple.listUser                        thrpt          8.814          ops/ms
ClientSimple.createUser                       avgt          2.124           ms/op
ClientSimple.existUser                        avgt          1.863           ms/op
ClientSimple.getUser                          avgt          2.002           ms/op
ClientSimple.listUser                         avgt          3.357           ms/op
ClientSimple.createUser                     sample  15389   2.077 ± 0.058   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.323           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.831           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.531           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.920           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.177           ms/op
ClientSimple.createUser:createUser·p0.999   sample         43.123           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         50.977           ms/op
ClientSimple.createUser:createUser·p1.00    sample         51.118           ms/op
ClientSimple.existUser                      sample  16955   1.885 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.585           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.733           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.392           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.554           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.485           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.696           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.696           ms/op
ClientSimple.getUser                        sample  15084   2.157 ± 0.041   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.701           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.044           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.646           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.904           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.847           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.856           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.036           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.053           ms/op
ClientSimple.listUser                       sample   9726   3.295 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.680           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.058           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.166           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.658           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.002           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.337           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.337           ms/op

Benchmark result is saved to 1717893690971.json
