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
# Warmup Iteration   1: 1.328 ops/ms
Iteration   1: 6.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.286 ops/ms


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
# Warmup Iteration   1: 5.930 ops/ms
Iteration   1: 12.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.363 ops/ms


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
# Warmup Iteration   1: 5.949 ops/ms
Iteration   1: 13.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.760 ops/ms


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
# Warmup Iteration   1: 4.899 ops/ms
Iteration   1: 8.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.579 ops/ms


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
# Warmup Iteration   1: 3.562 ±(99.9%) 0.065 ms/op
Iteration   1: 2.241 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.241 ms/op


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
# Warmup Iteration   1: 3.042 ±(99.9%) 0.050 ms/op
Iteration   1: 1.718 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.718 ms/op


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
# Warmup Iteration   1: 2.993 ±(99.9%) 0.053 ms/op
Iteration   1: 1.888 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.888 ms/op


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
# Warmup Iteration   1: 4.882 ±(99.9%) 0.113 ms/op
Iteration   1: 3.322 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.322 ms/op


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
# Warmup Iteration   1: 3.196 ±(99.9%) 0.079 ms/op
Iteration   1: 2.173 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.404 ms/op
                 createUser·p0.50:   2.017 ms/op
                 createUser·p0.90:   2.679 ms/op
                 createUser·p0.95:   2.900 ms/op
                 createUser·p0.99:   9.058 ms/op
                 createUser·p0.999:  15.071 ms/op
                 createUser·p0.9999: 15.988 ms/op
                 createUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14713
  mean =      2.173 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 344 
    [ 1.250,  2.500) = 12182 
    [ 2.500,  3.750) = 1866 
    [ 3.750,  5.000) = 91 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      9.058 ms/op
     p(99.9000) =     15.071 ms/op
     p(99.9900) =     15.988 ms/op
     p(99.9990) =     16.073 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


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
# Warmup Iteration   1: 3.027 ±(99.9%) 0.078 ms/op
Iteration   1: 1.914 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.474 ms/op
                 existUser·p0.50:   1.839 ms/op
                 existUser·p0.90:   2.425 ms/op
                 existUser·p0.95:   2.572 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  10.027 ms/op
                 existUser·p0.9999: 11.179 ms/op
                 existUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16699
  mean =      1.914 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 412 
    [ 1.250,  2.500) = 15086 
    [ 2.500,  3.750) = 1080 
    [ 3.750,  5.000) = 56 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      3.469 ms/op
     p(99.9000) =     10.027 ms/op
     p(99.9900) =     11.179 ms/op
     p(99.9990) =     11.223 ms/op
     p(99.9999) =     11.223 ms/op
    p(100.0000) =     11.223 ms/op


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
# Warmup Iteration   1: 3.205 ±(99.9%) 0.093 ms/op
Iteration   1: 2.076 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.615 ms/op
                 getUser·p0.50:   1.966 ms/op
                 getUser·p0.90:   2.490 ms/op
                 getUser·p0.95:   2.736 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  14.083 ms/op
                 getUser·p0.9999: 15.243 ms/op
                 getUser·p1.00:   15.270 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15454
  mean =      2.076 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 13810 
    [ 2.500,  3.750) = 1280 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =     14.083 ms/op
     p(99.9900) =     15.243 ms/op
     p(99.9990) =     15.270 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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
# Warmup Iteration   1: 4.233 ±(99.9%) 0.115 ms/op
Iteration   1: 3.030 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.582 ms/op
                 listUser·p0.999:  6.438 ms/op
                 listUser·p0.9999: 6.607 ms/op
                 listUser·p1.00:   6.611 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10563
  mean =      3.030 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 20 
    [1.500, 2.000) = 87 
    [2.000, 2.500) = 1510 
    [2.500, 3.000) = 5031 
    [3.000, 3.500) = 2158 
    [3.500, 4.000) = 927 
    [4.000, 4.500) = 475 
    [4.500, 5.000) = 148 
    [5.000, 5.500) = 85 
    [5.500, 6.000) = 60 
    [6.000, 6.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.582 ms/op
     p(99.9000) =      6.438 ms/op
     p(99.9900) =      6.607 ms/op
     p(99.9990) =      6.611 ms/op
     p(99.9999) =      6.611 ms/op
    p(100.0000) =      6.611 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.286          ops/ms
ClientSimple.existUser                       thrpt         12.363          ops/ms
ClientSimple.getUser                         thrpt         13.760          ops/ms
ClientSimple.listUser                        thrpt          8.579          ops/ms
ClientSimple.createUser                       avgt          2.241           ms/op
ClientSimple.existUser                        avgt          1.718           ms/op
ClientSimple.getUser                          avgt          1.888           ms/op
ClientSimple.listUser                         avgt          3.322           ms/op
ClientSimple.createUser                     sample  14713   2.173 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.404           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.017           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.900           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.058           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.071           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.988           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.073           ms/op
ClientSimple.existUser                      sample  16699   1.914 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.474           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.839           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.425           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.572           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.469           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.027           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.179           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.223           ms/op
ClientSimple.getUser                        sample  15454   2.076 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.615           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.966           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.490           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.736           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.817           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.083           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.243           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.270           ms/op
ClientSimple.listUser                       sample  10563   3.030 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.894           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.908           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.867           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.582           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.438           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.607           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.611           ms/op

Benchmark result is saved to 1717330412723.json
