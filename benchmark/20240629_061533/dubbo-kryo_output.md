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
# Warmup Iteration   1: 1.700 ops/ms
Iteration   1: 6.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.933 ops/ms


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
# Warmup Iteration   1: 5.673 ops/ms
Iteration   1: 11.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.711 ops/ms


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
# Warmup Iteration   1: 5.870 ops/ms
Iteration   1: 13.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.302 ops/ms


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
# Warmup Iteration   1: 5.312 ops/ms
Iteration   1: 8.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.334 ops/ms


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
# Warmup Iteration   1: 3.756 ±(99.9%) 0.062 ms/op
Iteration   1: 1.983 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.983 ms/op


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
# Warmup Iteration   1: 2.782 ±(99.9%) 0.055 ms/op
Iteration   1: 2.022 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.022 ms/op


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
# Warmup Iteration   1: 3.347 ±(99.9%) 0.050 ms/op
Iteration   1: 1.915 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.915 ms/op


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
# Warmup Iteration   1: 4.394 ±(99.9%) 0.100 ms/op
Iteration   1: 3.143 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.143 ms/op


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.100 ms/op
Iteration   1: 2.177 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   2.044 ms/op
                 createUser·p0.90:   2.630 ms/op
                 createUser·p0.95:   2.822 ms/op
                 createUser·p0.99:   6.755 ms/op
                 createUser·p0.999:  15.172 ms/op
                 createUser·p0.9999: 15.271 ms/op
                 createUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14691
  mean =      2.177 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 12021 
    [ 2.500,  3.750) = 2310 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.044 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      6.755 ms/op
     p(99.9000) =     15.172 ms/op
     p(99.9900) =     15.271 ms/op
     p(99.9990) =     15.286 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 2.939 ±(99.9%) 0.071 ms/op
Iteration   1: 2.054 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.472 ms/op
                 existUser·p0.50:   1.980 ms/op
                 existUser·p0.90:   2.413 ms/op
                 existUser·p0.95:   2.548 ms/op
                 existUser·p0.99:   4.302 ms/op
                 existUser·p0.999:  21.037 ms/op
                 existUser·p0.9999: 22.630 ms/op
                 existUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15986
  mean =      2.054 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14991 
    [ 2.500,  5.000) = 862 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      4.302 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     22.630 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 3.296 ±(99.9%) 0.076 ms/op
Iteration   1: 1.851 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   1.688 ms/op
                 getUser·p0.90:   2.288 ms/op
                 getUser·p0.95:   2.490 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  26.903 ms/op
                 getUser·p0.9999: 27.894 ms/op
                 getUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17543
  mean =      1.851 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16720 
    [ 2.500,  5.000) = 693 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      1.688 ms/op
     p(90.0000) =      2.288 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =     26.903 ms/op
     p(99.9900) =     27.894 ms/op
     p(99.9990) =     27.918 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 4.182 ±(99.9%) 0.131 ms/op
Iteration   1: 3.163 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   3.068 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.002 ms/op
                 listUser·p0.99:   5.366 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 17.888 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10109
  mean =      3.163 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 1199 
    [ 2.500,  3.750) = 7589 
    [ 3.750,  5.000) = 1117 
    [ 5.000,  6.250) = 145 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     17.888 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.933          ops/ms
ClientSimple.existUser                       thrpt         11.711          ops/ms
ClientSimple.getUser                         thrpt         13.302          ops/ms
ClientSimple.listUser                        thrpt          8.334          ops/ms
ClientSimple.createUser                       avgt          1.983           ms/op
ClientSimple.existUser                        avgt          2.022           ms/op
ClientSimple.getUser                          avgt          1.915           ms/op
ClientSimple.listUser                         avgt          3.143           ms/op
ClientSimple.createUser                     sample  14691   2.177 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.693           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.044           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.755           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.172           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.271           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.286           ms/op
ClientSimple.existUser                      sample  15986   2.054 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.472           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.980           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.413           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.548           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.302           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.037           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.630           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.003           ms/op
ClientSimple.getUser                        sample  17543   1.851 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.646           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.688           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.288           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.490           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.219           ms/op
ClientSimple.getUser:getUser·p0.999         sample         26.903           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.894           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.918           ms/op
ClientSimple.listUser                       sample  10109   3.163 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.760           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.068           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.817           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.002           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.366           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.105           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.888           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.891           ms/op

Benchmark result is saved to 1719641471067.json
