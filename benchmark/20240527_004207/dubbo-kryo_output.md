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
# Warmup Iteration   1: 1.646 ops/ms
Iteration   1: 6.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.655 ops/ms


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
# Warmup Iteration   1: 5.834 ops/ms
Iteration   1: 11.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.284 ops/ms


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
# Warmup Iteration   1: 5.487 ops/ms
Iteration   1: 12.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.413 ops/ms


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
# Warmup Iteration   1: 5.188 ops/ms
Iteration   1: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.203 ops/ms


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
# Warmup Iteration   1: 4.444 ±(99.9%) 0.088 ms/op
Iteration   1: 2.450 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.450 ms/op


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
# Warmup Iteration   1: 4.048 ±(99.9%) 0.066 ms/op
Iteration   1: 2.115 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.115 ms/op


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
# Warmup Iteration   1: 3.224 ±(99.9%) 0.060 ms/op
Iteration   1: 2.280 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.280 ms/op


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
# Warmup Iteration   1: 4.800 ±(99.9%) 0.130 ms/op
Iteration   1: 3.245 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.245 ms/op


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
# Warmup Iteration   1: 3.537 ±(99.9%) 0.095 ms/op
Iteration   1: 2.330 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.150 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.453 ms/op
                 createUser·p0.99:   7.786 ms/op
                 createUser·p0.999:  15.061 ms/op
                 createUser·p0.9999: 17.039 ms/op
                 createUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13727
  mean =      2.330 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 9269 
    [ 2.500,  3.750) = 3822 
    [ 3.750,  5.000) = 194 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.453 ms/op
     p(99.0000) =      7.786 ms/op
     p(99.9000) =     15.061 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 2.938 ±(99.9%) 0.070 ms/op
Iteration   1: 1.948 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.584 ms/op
                 existUser·p0.50:   1.843 ms/op
                 existUser·p0.90:   2.486 ms/op
                 existUser·p0.95:   2.781 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  13.526 ms/op
                 existUser·p0.9999: 14.123 ms/op
                 existUser·p1.00:   14.123 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16414
  mean =      1.948 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 308 
    [ 1.250,  2.500) = 14503 
    [ 2.500,  3.750) = 1470 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      1.843 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      3.527 ms/op
     p(99.9000) =     13.526 ms/op
     p(99.9900) =     14.123 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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
# Warmup Iteration   1: 3.232 ±(99.9%) 0.079 ms/op
Iteration   1: 2.196 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   0.483 ms/op
                 getUser·p0.50:   1.997 ms/op
                 getUser·p0.90:   2.560 ms/op
                 getUser·p0.95:   2.789 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  31.457 ms/op
                 getUser·p0.9999: 32.038 ms/op
                 getUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14561
  mean =      2.196 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12722 
    [ 2.500,  5.000) = 1702 
    [ 5.000,  7.500) = 38 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =     31.457 ms/op
     p(99.9900) =     32.038 ms/op
     p(99.9990) =     32.113 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


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
# Warmup Iteration   1: 4.701 ±(99.9%) 0.147 ms/op
Iteration   1: 3.716 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   3.725 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.091 ms/op
                 listUser·p0.99:   6.291 ms/op
                 listUser·p0.999:  6.968 ms/op
                 listUser·p0.9999: 7.873 ms/op
                 listUser·p1.00:   7.873 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8610
  mean =      3.716 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 10 
    [1.500, 2.000) = 108 
    [2.000, 2.500) = 400 
    [2.500, 3.000) = 842 
    [3.000, 3.500) = 1915 
    [3.500, 4.000) = 2344 
    [4.000, 4.500) = 2027 
    [4.500, 5.000) = 486 
    [5.000, 5.500) = 266 
    [5.500, 6.000) = 100 
    [6.000, 6.500) = 63 
    [6.500, 7.000) = 40 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.725 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.091 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =      6.968 ms/op
     p(99.9900) =      7.873 ms/op
     p(99.9990) =      7.873 ms/op
     p(99.9999) =      7.873 ms/op
    p(100.0000) =      7.873 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.655          ops/ms
ClientSimple.existUser                       thrpt         11.284          ops/ms
ClientSimple.getUser                         thrpt         12.413          ops/ms
ClientSimple.listUser                        thrpt          8.203          ops/ms
ClientSimple.createUser                       avgt          2.450           ms/op
ClientSimple.existUser                        avgt          2.115           ms/op
ClientSimple.getUser                          avgt          2.280           ms/op
ClientSimple.listUser                         avgt          3.245           ms/op
ClientSimple.createUser                     sample  13727   2.330 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.906           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.150           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.092           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.453           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.786           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.061           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.039           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.039           ms/op
ClientSimple.existUser                      sample  16414   1.948 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.584           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.843           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.781           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.527           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.526           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.123           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.123           ms/op
ClientSimple.getUser                        sample  14561   2.196 ± 0.045   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.483           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.997           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.789           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.727           ms/op
ClientSimple.getUser:getUser·p0.999         sample         31.457           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         32.038           ms/op
ClientSimple.getUser:getUser·p1.00          sample         32.113           ms/op
ClientSimple.listUser                       sample   8610   3.716 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.882           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.725           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.563           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.091           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.291           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.968           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.873           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.873           ms/op

Benchmark result is saved to 1716770249057.json
