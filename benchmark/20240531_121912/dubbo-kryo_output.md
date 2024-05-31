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
# Warmup Iteration   1: 1.958 ops/ms
Iteration   1: 7.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.254 ops/ms


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
# Warmup Iteration   1: 5.902 ops/ms
Iteration   1: 13.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.591 ops/ms


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
# Warmup Iteration   1: 5.823 ops/ms
Iteration   1: 12.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.009 ops/ms


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
# Warmup Iteration   1: 4.926 ops/ms
Iteration   1: 9.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.021 ops/ms


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
# Warmup Iteration   1: 3.533 ±(99.9%) 0.077 ms/op
Iteration   1: 2.179 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.179 ms/op


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
# Warmup Iteration   1: 3.059 ±(99.9%) 0.056 ms/op
Iteration   1: 1.770 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.770 ms/op


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
# Warmup Iteration   1: 3.261 ±(99.9%) 0.053 ms/op
Iteration   1: 2.044 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.044 ms/op


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
# Warmup Iteration   1: 4.776 ±(99.9%) 0.097 ms/op
Iteration   1: 3.581 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.581 ms/op


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
# Warmup Iteration   1: 3.614 ±(99.9%) 0.109 ms/op
Iteration   1: 2.121 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   1.907 ms/op
                 createUser·p0.90:   2.701 ms/op
                 createUser·p0.95:   2.933 ms/op
                 createUser·p0.99:   8.192 ms/op
                 createUser·p0.999:  16.040 ms/op
                 createUser·p0.9999: 16.479 ms/op
                 createUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15075
  mean =      2.121 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 164 
    [ 1.250,  2.500) = 12765 
    [ 2.500,  3.750) = 1906 
    [ 3.750,  5.000) = 59 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.701 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      8.192 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     16.479 ms/op
     p(99.9990) =     16.695 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


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
# Warmup Iteration   1: 3.081 ±(99.9%) 0.070 ms/op
Iteration   1: 1.915 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.514 ms/op
                 existUser·p0.50:   1.782 ms/op
                 existUser·p0.90:   2.208 ms/op
                 existUser·p0.95:   2.343 ms/op
                 existUser·p0.99:   3.737 ms/op
                 existUser·p0.999:  26.552 ms/op
                 existUser·p0.9999: 26.934 ms/op
                 existUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16705
  mean =      1.915 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16194 
    [ 2.500,  5.000) = 445 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      1.782 ms/op
     p(90.0000) =      2.208 ms/op
     p(95.0000) =      2.343 ms/op
     p(99.0000) =      3.737 ms/op
     p(99.9000) =     26.552 ms/op
     p(99.9900) =     26.934 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 3.131 ±(99.9%) 0.069 ms/op
Iteration   1: 2.063 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   1.954 ms/op
                 getUser·p0.90:   2.576 ms/op
                 getUser·p0.95:   2.822 ms/op
                 getUser·p0.99:   4.030 ms/op
                 getUser·p0.999:  10.780 ms/op
                 getUser·p0.9999: 11.264 ms/op
                 getUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15516
  mean =      2.063 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 226 
    [ 1.250,  2.500) = 13250 
    [ 2.500,  3.750) = 1858 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      4.030 ms/op
     p(99.9000) =     10.780 ms/op
     p(99.9900) =     11.264 ms/op
     p(99.9990) =     11.354 ms/op
     p(99.9999) =     11.354 ms/op
    p(100.0000) =     11.354 ms/op


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
# Warmup Iteration   1: 4.508 ±(99.9%) 0.124 ms/op
Iteration   1: 3.272 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.892 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 18.219 ms/op
                 listUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9896
  mean =      3.272 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 594 
    [ 2.500,  3.750) = 7108 
    [ 3.750,  5.000) = 2030 
    [ 5.000,  6.250) = 76 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.892 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     18.219 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.254          ops/ms
ClientSimple.existUser                       thrpt         13.591          ops/ms
ClientSimple.getUser                         thrpt         12.009          ops/ms
ClientSimple.listUser                        thrpt          9.021          ops/ms
ClientSimple.createUser                       avgt          2.179           ms/op
ClientSimple.existUser                        avgt          1.770           ms/op
ClientSimple.getUser                          avgt          2.044           ms/op
ClientSimple.listUser                         avgt          3.581           ms/op
ClientSimple.createUser                     sample  15075   2.121 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.718           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.907           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.701           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.933           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.192           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.040           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.479           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.695           ms/op
ClientSimple.existUser                      sample  16705   1.915 ± 0.039   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.514           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.782           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.208           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.737           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.552           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.934           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.197           ms/op
ClientSimple.getUser                        sample  15516   2.063 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.530           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.954           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.030           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.780           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.264           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.354           ms/op
ClientSimple.listUser                       sample   9896   3.272 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.896           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.047           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.112           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.892           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.138           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.219           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.219           ms/op

Benchmark result is saved to 1717157695008.json
