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
# Warmup Iteration   1: 2.233 ops/ms
Iteration   1: 7.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.804 ops/ms


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
# Warmup Iteration   1: 5.733 ops/ms
Iteration   1: 12.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.347 ops/ms


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
# Warmup Iteration   1: 5.631 ops/ms
Iteration   1: 12.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.271 ops/ms


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
# Warmup Iteration   1: 4.731 ops/ms
Iteration   1: 8.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.310 ops/ms


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.085 ms/op
Iteration   1: 2.228 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.228 ms/op


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
# Warmup Iteration   1: 3.178 ±(99.9%) 0.047 ms/op
Iteration   1: 1.666 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.666 ms/op


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
# Warmup Iteration   1: 3.308 ±(99.9%) 0.054 ms/op
Iteration   1: 2.063 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.063 ms/op


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
# Warmup Iteration   1: 4.350 ±(99.9%) 0.090 ms/op
Iteration   1: 3.956 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.956 ms/op


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
# Warmup Iteration   1: 3.351 ±(99.9%) 0.083 ms/op
Iteration   1: 2.280 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.150 ms/op
                 createUser·p0.90:   2.687 ms/op
                 createUser·p0.95:   2.900 ms/op
                 createUser·p0.99:   5.658 ms/op
                 createUser·p0.999:  14.500 ms/op
                 createUser·p0.9999: 15.493 ms/op
                 createUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14018
  mean =      2.280 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 11537 
    [ 2.500,  3.750) = 2152 
    [ 3.750,  5.000) = 89 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      5.658 ms/op
     p(99.9000) =     14.500 ms/op
     p(99.9900) =     15.493 ms/op
     p(99.9990) =     15.499 ms/op
     p(99.9999) =     15.499 ms/op
    p(100.0000) =     15.499 ms/op


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
# Warmup Iteration   1: 2.930 ±(99.9%) 0.063 ms/op
Iteration   1: 2.119 ±(99.9%) 0.051 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   2.019 ms/op
                 existUser·p0.90:   2.417 ms/op
                 existUser·p0.95:   2.623 ms/op
                 existUser·p0.99:   3.471 ms/op
                 existUser·p0.999:  33.807 ms/op
                 existUser·p0.9999: 34.599 ms/op
                 existUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15149
  mean =      2.119 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14047 
    [ 2.500,  5.000) = 998 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      2.019 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.623 ms/op
     p(99.0000) =      3.471 ms/op
     p(99.9000) =     33.807 ms/op
     p(99.9900) =     34.599 ms/op
     p(99.9990) =     34.734 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 3.251 ±(99.9%) 0.099 ms/op
Iteration   1: 1.935 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   1.817 ms/op
                 getUser·p0.90:   2.314 ms/op
                 getUser·p0.95:   2.544 ms/op
                 getUser·p0.99:   3.314 ms/op
                 getUser·p0.999:  14.466 ms/op
                 getUser·p0.9999: 14.779 ms/op
                 getUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16519
  mean =      1.935 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 15520 
    [ 2.500,  3.750) = 841 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =      3.314 ms/op
     p(99.9000) =     14.466 ms/op
     p(99.9900) =     14.779 ms/op
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
# Warmup Iteration   1: 4.718 ±(99.9%) 0.144 ms/op
Iteration   1: 4.017 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   11.574 ms/op
                 listUser·p0.999:  19.628 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7954
  mean =      4.017 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 372 
    [ 2.500,  5.000) = 7071 
    [ 5.000,  7.500) = 382 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =     11.574 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     20.349 ms/op
     p(99.9990) =     20.349 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.804          ops/ms
ClientSimple.existUser                       thrpt         12.347          ops/ms
ClientSimple.getUser                         thrpt         12.271          ops/ms
ClientSimple.listUser                        thrpt          8.310          ops/ms
ClientSimple.createUser                       avgt          2.228           ms/op
ClientSimple.existUser                        avgt          1.666           ms/op
ClientSimple.getUser                          avgt          2.063           ms/op
ClientSimple.listUser                         avgt          3.956           ms/op
ClientSimple.createUser                     sample  14018   2.280 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.933           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.150           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.687           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.900           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.658           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.500           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.493           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.499           ms/op
ClientSimple.existUser                      sample  15149   2.119 ± 0.051   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.627           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.019           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.623           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.471           ms/op
ClientSimple.existUser:existUser·p0.999     sample         33.807           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         34.599           ms/op
ClientSimple.existUser:existUser·p1.00      sample         34.734           ms/op
ClientSimple.getUser                        sample  16519   1.935 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.714           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.817           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.314           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.544           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.314           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.466           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.779           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.811           ms/op
ClientSimple.listUser                       sample   7954   4.017 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.384           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.895           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.743           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.251           ms/op
ClientSimple.listUser:listUser·p0.99        sample         11.574           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.628           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.349           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.349           ms/op

Benchmark result is saved to 1717848810200.json
