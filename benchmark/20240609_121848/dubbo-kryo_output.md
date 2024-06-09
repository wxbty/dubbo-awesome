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
# Warmup Iteration   1: 1.776 ops/ms
Iteration   1: 6.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.868 ops/ms


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
# Warmup Iteration   1: 6.758 ops/ms
Iteration   1: 11.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.670 ops/ms


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
# Warmup Iteration   1: 5.320 ops/ms
Iteration   1: 12.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.930 ops/ms


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
# Warmup Iteration   1: 4.955 ops/ms
Iteration   1: 8.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.654 ops/ms


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.061 ms/op
Iteration   1: 2.095 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.095 ms/op


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
# Warmup Iteration   1: 2.975 ±(99.9%) 0.047 ms/op
Iteration   1: 2.072 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.072 ms/op


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
# Warmup Iteration   1: 3.284 ±(99.9%) 0.062 ms/op
Iteration   1: 2.084 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.084 ms/op


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
# Warmup Iteration   1: 4.752 ±(99.9%) 0.098 ms/op
Iteration   1: 3.216 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.216 ms/op


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
# Warmup Iteration   1: 3.173 ±(99.9%) 0.076 ms/op
Iteration   1: 2.415 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.227 ms/op
                 createUser·p0.50:   2.277 ms/op
                 createUser·p0.90:   2.961 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   6.053 ms/op
                 createUser·p0.999:  21.889 ms/op
                 createUser·p0.9999: 22.140 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13308
  mean =      2.415 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8252 
    [ 2.500,  5.000) = 4898 
    [ 5.000,  7.500) = 29 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.227 ms/op
     p(50.0000) =      2.277 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      6.053 ms/op
     p(99.9000) =     21.889 ms/op
     p(99.9900) =     22.140 ms/op
     p(99.9990) =     22.151 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 2.862 ±(99.9%) 0.075 ms/op
Iteration   1: 1.807 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   1.706 ms/op
                 existUser·p0.90:   2.306 ms/op
                 existUser·p0.95:   2.494 ms/op
                 existUser·p0.99:   3.307 ms/op
                 existUser·p0.999:  10.699 ms/op
                 existUser·p0.9999: 12.107 ms/op
                 existUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17685
  mean =      1.807 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 275 
    [ 1.250,  2.500) = 16534 
    [ 2.500,  3.750) = 761 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      1.706 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      3.307 ms/op
     p(99.9000) =     10.699 ms/op
     p(99.9900) =     12.107 ms/op
     p(99.9990) =     12.321 ms/op
     p(99.9999) =     12.321 ms/op
    p(100.0000) =     12.321 ms/op


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
# Warmup Iteration   1: 3.399 ±(99.9%) 0.079 ms/op
Iteration   1: 2.173 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   2.060 ms/op
                 getUser·p0.90:   2.671 ms/op
                 getUser·p0.95:   2.859 ms/op
                 getUser·p0.99:   3.704 ms/op
                 getUser·p0.999:  21.848 ms/op
                 getUser·p0.9999: 22.902 ms/op
                 getUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15252
  mean =      2.173 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12298 
    [ 2.500,  5.000) = 2879 
    [ 5.000,  7.500) = 11 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      3.704 ms/op
     p(99.9000) =     21.848 ms/op
     p(99.9900) =     22.902 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.112 ms/op
Iteration   1: 3.134 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.083 ms/op
                 listUser·p0.999:  12.203 ms/op
                 listUser·p0.9999: 12.451 ms/op
                 listUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10176
  mean =      3.134 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 210 
    [ 2.500,  3.750) = 8337 
    [ 3.750,  5.000) = 1518 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.083 ms/op
     p(99.9000) =     12.203 ms/op
     p(99.9900) =     12.451 ms/op
     p(99.9990) =     12.452 ms/op
     p(99.9999) =     12.452 ms/op
    p(100.0000) =     12.452 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.868          ops/ms
ClientSimple.existUser                       thrpt         11.670          ops/ms
ClientSimple.getUser                         thrpt         12.930          ops/ms
ClientSimple.listUser                        thrpt          8.654          ops/ms
ClientSimple.createUser                       avgt          2.095           ms/op
ClientSimple.existUser                        avgt          2.072           ms/op
ClientSimple.getUser                          avgt          2.084           ms/op
ClientSimple.listUser                         avgt          3.216           ms/op
ClientSimple.createUser                     sample  13308   2.415 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.227           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.277           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.961           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.162           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.053           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.889           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.140           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.151           ms/op
ClientSimple.existUser                      sample  17685   1.807 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.737           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.706           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.306           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.307           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.699           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.107           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.321           ms/op
ClientSimple.getUser                        sample  15252   2.173 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.699           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.060           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.859           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.704           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.848           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.902           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.970           ms/op
ClientSimple.listUser                       sample  10176   3.134 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.419           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.879           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.039           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.083           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.203           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.451           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.452           ms/op

Benchmark result is saved to 1717935264243.json
