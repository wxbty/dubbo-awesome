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
# Warmup Iteration   1: 1.803 ops/ms
Iteration   1: 7.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.512 ops/ms


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
# Warmup Iteration   1: 5.298 ops/ms
Iteration   1: 10.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.998 ops/ms


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
# Warmup Iteration   1: 4.930 ops/ms
Iteration   1: 13.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.431 ops/ms


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
# Warmup Iteration   1: 4.587 ops/ms
Iteration   1: 8.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.489 ops/ms


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
# Warmup Iteration   1: 3.776 ±(99.9%) 0.074 ms/op
Iteration   1: 2.005 ±(99.9%) 0.014 ms/op


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
# Warmup Iteration   1: 3.281 ±(99.9%) 0.056 ms/op
Iteration   1: 2.083 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.083 ms/op


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
# Warmup Iteration   1: 3.273 ±(99.9%) 0.058 ms/op
Iteration   1: 2.028 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.028 ms/op


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.068 ms/op
Iteration   1: 3.222 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.222 ms/op


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
# Warmup Iteration   1: 3.626 ±(99.9%) 0.107 ms/op
Iteration   1: 2.087 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.478 ms/op
                 createUser·p0.50:   1.994 ms/op
                 createUser·p0.90:   2.486 ms/op
                 createUser·p0.95:   2.867 ms/op
                 createUser·p0.99:   3.666 ms/op
                 createUser·p0.999:  21.725 ms/op
                 createUser·p0.9999: 24.288 ms/op
                 createUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15306
  mean =      2.087 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13835 
    [ 2.500,  5.000) = 1396 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      1.994 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =     21.725 ms/op
     p(99.9900) =     24.288 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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
# Warmup Iteration   1: 3.012 ±(99.9%) 0.072 ms/op
Iteration   1: 1.856 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.646 ms/op
                 existUser·p0.50:   1.759 ms/op
                 existUser·p0.90:   2.220 ms/op
                 existUser·p0.95:   2.482 ms/op
                 existUser·p0.99:   4.519 ms/op
                 existUser·p0.999:  16.085 ms/op
                 existUser·p0.9999: 16.241 ms/op
                 existUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17218
  mean =      1.856 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 344 
    [ 1.250,  2.500) = 16064 
    [ 2.500,  3.750) = 541 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.220 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      4.519 ms/op
     p(99.9000) =     16.085 ms/op
     p(99.9900) =     16.241 ms/op
     p(99.9990) =     16.253 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


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
# Warmup Iteration   1: 3.235 ±(99.9%) 0.089 ms/op
Iteration   1: 1.922 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.472 ms/op
                 getUser·p0.50:   1.784 ms/op
                 getUser·p0.90:   2.459 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   3.911 ms/op
                 getUser·p0.999:  13.555 ms/op
                 getUser·p0.9999: 14.800 ms/op
                 getUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16655
  mean =      1.922 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 322 
    [ 1.250,  2.500) = 14866 
    [ 2.500,  3.750) = 1276 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.459 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.911 ms/op
     p(99.9000) =     13.555 ms/op
     p(99.9900) =     14.800 ms/op
     p(99.9990) =     14.811 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 4.590 ±(99.9%) 0.124 ms/op
Iteration   1: 3.244 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   0.822 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.429 ms/op
                 listUser·p0.99:   5.453 ms/op
                 listUser·p0.999:  21.481 ms/op
                 listUser·p0.9999: 25.395 ms/op
                 listUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9865
  mean =      3.244 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1087 
    [ 2.500,  5.000) = 8552 
    [ 5.000,  7.500) = 194 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.429 ms/op
     p(99.0000) =      5.453 ms/op
     p(99.9000) =     21.481 ms/op
     p(99.9900) =     25.395 ms/op
     p(99.9990) =     25.395 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.512          ops/ms
ClientSimple.existUser                       thrpt         10.998          ops/ms
ClientSimple.getUser                         thrpt         13.431          ops/ms
ClientSimple.listUser                        thrpt          8.489          ops/ms
ClientSimple.createUser                       avgt          2.005           ms/op
ClientSimple.existUser                        avgt          2.083           ms/op
ClientSimple.getUser                          avgt          2.028           ms/op
ClientSimple.listUser                         avgt          3.222           ms/op
ClientSimple.createUser                     sample  15306   2.087 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.478           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.994           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.486           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.666           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.725           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.288           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.445           ms/op
ClientSimple.existUser                      sample  17218   1.856 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.646           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.759           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.220           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.482           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.519           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.085           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.241           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.253           ms/op
ClientSimple.getUser                        sample  16655   1.922 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.472           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.784           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.459           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.911           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.555           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.800           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.811           ms/op
ClientSimple.listUser                       sample   9865   3.244 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.822           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.974           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.125           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.429           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.453           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.481           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.395           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.395           ms/op

Benchmark result is saved to 1717071292147.json
