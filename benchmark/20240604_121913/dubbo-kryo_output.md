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
# Warmup Iteration   1: 1.628 ops/ms
Iteration   1: 6.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.376 ops/ms


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
# Warmup Iteration   1: 5.740 ops/ms
Iteration   1: 10.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.316 ops/ms


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
# Warmup Iteration   1: 5.897 ops/ms
Iteration   1: 12.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.967 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.447 ops/ms
Iteration   1: 7.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.674 ops/ms


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.078 ms/op
Iteration   1: 2.268 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.268 ms/op


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
# Warmup Iteration   1: 3.079 ±(99.9%) 0.050 ms/op
Iteration   1: 1.933 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.933 ms/op


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
# Warmup Iteration   1: 3.361 ±(99.9%) 0.062 ms/op
Iteration   1: 2.179 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.748 ±(99.9%) 0.095 ms/op
Iteration   1: 3.572 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.572 ms/op


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
# Warmup Iteration   1: 3.358 ±(99.9%) 0.081 ms/op
Iteration   1: 2.206 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.441 ms/op
                 createUser·p0.50:   1.954 ms/op
                 createUser·p0.90:   2.834 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  36.504 ms/op
                 createUser·p0.9999: 38.622 ms/op
                 createUser·p1.00:   40.305 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14583
  mean =      2.206 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14404 
    [ 5.000, 10.000) = 132 
    [10.000, 15.000) = 15 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 14 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.441 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.834 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     36.504 ms/op
     p(99.9900) =     38.622 ms/op
     p(99.9990) =     40.305 ms/op
     p(99.9999) =     40.305 ms/op
    p(100.0000) =     40.305 ms/op


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
# Warmup Iteration   1: 3.036 ±(99.9%) 0.072 ms/op
Iteration   1: 1.861 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   1.720 ms/op
                 existUser·p0.90:   2.212 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   3.208 ms/op
                 existUser·p0.999:  16.974 ms/op
                 existUser·p0.9999: 17.151 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17187
  mean =      1.861 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 16271 
    [ 2.500,  3.750) = 677 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      1.720 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      3.208 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     17.151 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 3.473 ±(99.9%) 0.094 ms/op
Iteration   1: 2.033 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.525 ms/op
                 getUser·p0.50:   1.942 ms/op
                 getUser·p0.90:   2.642 ms/op
                 getUser·p0.95:   2.798 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  10.996 ms/op
                 getUser·p0.9999: 12.550 ms/op
                 getUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15846
  mean =      2.033 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 445 
    [ 1.250,  2.500) = 12882 
    [ 2.500,  3.750) = 2329 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      1.942 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =     10.996 ms/op
     p(99.9900) =     12.550 ms/op
     p(99.9990) =     12.550 ms/op
     p(99.9999) =     12.550 ms/op
    p(100.0000) =     12.550 ms/op


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
# Warmup Iteration   1: 4.874 ±(99.9%) 0.165 ms/op
Iteration   1: 3.524 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   5.876 ms/op
                 listUser·p0.999:  6.674 ms/op
                 listUser·p0.9999: 8.258 ms/op
                 listUser·p1.00:   8.258 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9069
  mean =      3.524 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 12 
    [1.500, 2.000) = 111 
    [2.000, 2.500) = 598 
    [2.500, 3.000) = 2081 
    [3.000, 3.500) = 1589 
    [3.500, 4.000) = 2245 
    [4.000, 4.500) = 1463 
    [4.500, 5.000) = 558 
    [5.000, 5.500) = 287 
    [5.500, 6.000) = 53 
    [6.000, 6.500) = 59 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      5.876 ms/op
     p(99.9000) =      6.674 ms/op
     p(99.9900) =      8.258 ms/op
     p(99.9990) =      8.258 ms/op
     p(99.9999) =      8.258 ms/op
    p(100.0000) =      8.258 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.376          ops/ms
ClientSimple.existUser                       thrpt         10.316          ops/ms
ClientSimple.getUser                         thrpt         12.967          ops/ms
ClientSimple.listUser                        thrpt          7.674          ops/ms
ClientSimple.createUser                       avgt          2.268           ms/op
ClientSimple.existUser                        avgt          1.933           ms/op
ClientSimple.getUser                          avgt          2.179           ms/op
ClientSimple.listUser                         avgt          3.572           ms/op
ClientSimple.createUser                     sample  14583   2.206 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.441           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.954           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.834           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.203           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.276           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.504           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.622           ms/op
ClientSimple.createUser:createUser·p1.00    sample         40.305           ms/op
ClientSimple.existUser                      sample  17187   1.861 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.820           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.720           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.212           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.208           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.974           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.151           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.269           ms/op
ClientSimple.getUser                        sample  15846   2.033 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.525           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.942           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.798           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.186           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.996           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.550           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.550           ms/op
ClientSimple.listUser                       sample   9069   3.524 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.280           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.543           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.940           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.876           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.674           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.258           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.258           ms/op

Benchmark result is saved to 1717503295435.json
