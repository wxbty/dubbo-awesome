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
# Warmup Iteration   1: 1.845 ops/ms
Iteration   1: 6.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.963 ops/ms


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
# Warmup Iteration   1: 6.380 ops/ms
Iteration   1: 11.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.552 ops/ms


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
# Warmup Iteration   1: 5.610 ops/ms
Iteration   1: 12.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.722 ops/ms


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
# Warmup Iteration   1: 5.302 ops/ms
Iteration   1: 8.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.835 ops/ms


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
# Warmup Iteration   1: 4.756 ±(99.9%) 0.077 ms/op
Iteration   1: 2.393 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.393 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.056 ms/op
Iteration   1: 1.879 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.879 ms/op


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
# Warmup Iteration   1: 3.506 ±(99.9%) 0.071 ms/op
Iteration   1: 2.006 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.006 ms/op


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
# Warmup Iteration   1: 5.933 ±(99.9%) 0.155 ms/op
Iteration   1: 3.339 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.339 ms/op


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
# Warmup Iteration   1: 3.303 ±(99.9%) 0.100 ms/op
Iteration   1: 2.142 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   1.997 ms/op
                 createUser·p0.90:   2.593 ms/op
                 createUser·p0.95:   2.859 ms/op
                 createUser·p0.99:   4.012 ms/op
                 createUser·p0.999:  17.835 ms/op
                 createUser·p0.9999: 18.809 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14923
  mean =      2.142 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 12956 
    [ 2.500,  3.750) = 1734 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      4.012 ms/op
     p(99.9000) =     17.835 ms/op
     p(99.9900) =     18.809 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 3.098 ±(99.9%) 0.076 ms/op
Iteration   1: 2.062 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.574 ms/op
                 existUser·p0.50:   2.083 ms/op
                 existUser·p0.90:   2.531 ms/op
                 existUser·p0.95:   2.663 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  10.887 ms/op
                 existUser·p0.9999: 11.567 ms/op
                 existUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15498
  mean =      2.062 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 566 
    [ 1.250,  2.500) = 13027 
    [ 2.500,  3.750) = 1791 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      2.083 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.663 ms/op
     p(99.0000) =      3.482 ms/op
     p(99.9000) =     10.887 ms/op
     p(99.9900) =     11.567 ms/op
     p(99.9990) =     11.567 ms/op
     p(99.9999) =     11.567 ms/op
    p(100.0000) =     11.567 ms/op


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
# Warmup Iteration   1: 3.588 ±(99.9%) 0.100 ms/op
Iteration   1: 2.412 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   2.322 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   5.128 ms/op
                 getUser·p0.999:  16.248 ms/op
                 getUser·p0.9999: 16.351 ms/op
                 getUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13278
  mean =      2.412 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 8163 
    [ 2.500,  3.750) = 4658 
    [ 3.750,  5.000) = 196 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      2.322 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =     16.248 ms/op
     p(99.9900) =     16.351 ms/op
     p(99.9990) =     16.351 ms/op
     p(99.9999) =     16.351 ms/op
    p(100.0000) =     16.351 ms/op


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
# Warmup Iteration   1: 4.304 ±(99.9%) 0.130 ms/op
Iteration   1: 3.380 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   3.305 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.371 ms/op
                 listUser·p0.999:  19.777 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9464
  mean =      3.380 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1482 
    [ 2.500,  3.750) = 5244 
    [ 3.750,  5.000) = 2447 
    [ 5.000,  6.250) = 191 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.371 ms/op
     p(99.9000) =     19.777 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.963          ops/ms
ClientSimple.existUser                       thrpt         11.552          ops/ms
ClientSimple.getUser                         thrpt         12.722          ops/ms
ClientSimple.listUser                        thrpt          8.835          ops/ms
ClientSimple.createUser                       avgt          2.393           ms/op
ClientSimple.existUser                        avgt          1.879           ms/op
ClientSimple.getUser                          avgt          2.006           ms/op
ClientSimple.listUser                         avgt          3.339           ms/op
ClientSimple.createUser                     sample  14923   2.142 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.750           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.997           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.593           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.859           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.012           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.835           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.809           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.809           ms/op
ClientSimple.existUser                      sample  15498   2.062 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.574           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.083           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.531           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.663           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.482           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.887           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.567           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.567           ms/op
ClientSimple.getUser                        sample  13278   2.412 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.920           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.322           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.002           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.211           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.128           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.248           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.351           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.351           ms/op
ClientSimple.listUser                       sample   9464   3.380 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.859           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.305           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.371           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.777           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.890           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.890           ms/op

Benchmark result is saved to 1718367315531.json
