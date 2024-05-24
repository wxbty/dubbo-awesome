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
# Warmup Iteration   1: 1.547 ops/ms
Iteration   1: 7.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.097 ops/ms


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
# Warmup Iteration   1: 5.451 ops/ms
Iteration   1: 12.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.065 ops/ms


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
# Warmup Iteration   1: 5.202 ops/ms
Iteration   1: 11.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.390 ops/ms


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
# Warmup Iteration   1: 5.043 ops/ms
Iteration   1: 8.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.204 ops/ms


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
# Warmup Iteration   1: 4.592 ±(99.9%) 0.073 ms/op
Iteration   1: 2.348 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.348 ms/op


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
# Warmup Iteration   1: 3.502 ±(99.9%) 0.058 ms/op
Iteration   1: 2.039 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.039 ms/op


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
# Warmup Iteration   1: 3.275 ±(99.9%) 0.056 ms/op
Iteration   1: 1.887 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.887 ms/op


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
# Warmup Iteration   1: 4.702 ±(99.9%) 0.108 ms/op
Iteration   1: 3.561 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.561 ms/op


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
# Warmup Iteration   1: 3.504 ±(99.9%) 0.084 ms/op
Iteration   1: 2.036 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   1.815 ms/op
                 createUser·p0.90:   2.380 ms/op
                 createUser·p0.95:   2.572 ms/op
                 createUser·p0.99:   4.156 ms/op
                 createUser·p0.999:  27.656 ms/op
                 createUser·p0.9999: 27.801 ms/op
                 createUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15747
  mean =      2.036 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14739 
    [ 2.500,  5.000) = 876 
    [ 5.000,  7.500) = 4 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      4.156 ms/op
     p(99.9000) =     27.656 ms/op
     p(99.9900) =     27.801 ms/op
     p(99.9990) =     27.820 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 3.096 ±(99.9%) 0.074 ms/op
Iteration   1: 1.943 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   1.817 ms/op
                 existUser·p0.90:   2.482 ms/op
                 existUser·p0.95:   2.712 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  15.493 ms/op
                 existUser·p0.9999: 17.051 ms/op
                 existUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16400
  mean =      1.943 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 174 
    [ 1.250,  2.500) = 14659 
    [ 2.500,  3.750) = 1450 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =     15.493 ms/op
     p(99.9900) =     17.051 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 3.241 ±(99.9%) 0.074 ms/op
Iteration   1: 2.187 ±(99.9%) 0.057 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   2.081 ms/op
                 getUser·p0.90:   2.613 ms/op
                 getUser·p0.95:   2.806 ms/op
                 getUser·p0.99:   5.005 ms/op
                 getUser·p0.999:  38.360 ms/op
                 getUser·p0.9999: 39.230 ms/op
                 getUser·p1.00:   39.322 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14665
  mean =      2.187 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12292 
    [ 2.500,  5.000) = 2226 
    [ 5.000,  7.500) = 83 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      2.081 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =     38.360 ms/op
     p(99.9900) =     39.230 ms/op
     p(99.9990) =     39.322 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


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
# Warmup Iteration   1: 4.778 ±(99.9%) 0.183 ms/op
Iteration   1: 3.507 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.305 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  25.723 ms/op
                 listUser·p0.9999: 25.919 ms/op
                 listUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9123
  mean =      3.507 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 992 
    [ 2.500,  5.000) = 7910 
    [ 5.000,  7.500) = 187 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     25.723 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     25.919 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.097          ops/ms
ClientSimple.existUser                       thrpt         12.065          ops/ms
ClientSimple.getUser                         thrpt         11.390          ops/ms
ClientSimple.listUser                        thrpt          8.204          ops/ms
ClientSimple.createUser                       avgt          2.348           ms/op
ClientSimple.existUser                        avgt          2.039           ms/op
ClientSimple.getUser                          avgt          1.887           ms/op
ClientSimple.listUser                         avgt          3.561           ms/op
ClientSimple.createUser                     sample  15747   2.036 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.616           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.815           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.380           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.572           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.156           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.656           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.801           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.820           ms/op
ClientSimple.existUser                      sample  16400   1.943 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.571           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.817           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.482           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.712           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.596           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.493           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.051           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.907           ms/op
ClientSimple.getUser                        sample  14665   2.187 ± 0.057   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.707           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.081           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.613           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.005           ms/op
ClientSimple.getUser:getUser·p0.999         sample         38.360           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         39.230           ms/op
ClientSimple.getUser:getUser·p1.00          sample         39.322           ms/op
ClientSimple.listUser                       sample   9123   3.507 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.212           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.305           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.588           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.768           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.620           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.723           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.919           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.919           ms/op

Benchmark result is saved to 1716574273714.json
