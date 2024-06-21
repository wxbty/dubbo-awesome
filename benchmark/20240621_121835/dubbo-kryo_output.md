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
# Warmup Iteration   1: 0.765 ops/ms
Iteration   1: 5.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.508 ops/ms


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
# Warmup Iteration   1: 6.104 ops/ms
Iteration   1: 12.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.897 ops/ms


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
# Warmup Iteration   1: 4.882 ops/ms
Iteration   1: 11.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.600 ops/ms


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
# Warmup Iteration   1: 4.317 ops/ms
Iteration   1: 8.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.006 ops/ms


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
# Warmup Iteration   1: 4.294 ±(99.9%) 0.077 ms/op
Iteration   1: 2.336 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.336 ms/op


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
# Warmup Iteration   1: 3.113 ±(99.9%) 0.051 ms/op
Iteration   1: 2.153 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.153 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.055 ms/op
Iteration   1: 2.248 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.248 ms/op


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
# Warmup Iteration   1: 4.328 ±(99.9%) 0.080 ms/op
Iteration   1: 2.954 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.954 ms/op


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
# Warmup Iteration   1: 3.508 ±(99.9%) 0.102 ms/op
Iteration   1: 2.084 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.424 ms/op
                 createUser·p0.50:   1.855 ms/op
                 createUser·p0.90:   2.535 ms/op
                 createUser·p0.95:   2.724 ms/op
                 createUser·p0.99:   9.830 ms/op
                 createUser·p0.999:  17.792 ms/op
                 createUser·p0.9999: 20.702 ms/op
                 createUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15347
  mean =      2.084 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13523 
    [ 2.500,  5.000) = 1555 
    [ 5.000,  7.500) = 42 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     17.792 ms/op
     p(99.9900) =     20.702 ms/op
     p(99.9990) =     21.070 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 2.977 ±(99.9%) 0.076 ms/op
Iteration   1: 2.034 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   1.876 ms/op
                 existUser·p0.90:   2.658 ms/op
                 existUser·p0.95:   3.211 ms/op
                 existUser·p0.99:   4.209 ms/op
                 existUser·p0.999:  21.398 ms/op
                 existUser·p0.9999: 21.909 ms/op
                 existUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15940
  mean =      2.034 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13871 
    [ 2.500,  5.000) = 1973 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      4.209 ms/op
     p(99.9000) =     21.398 ms/op
     p(99.9900) =     21.909 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 3.357 ±(99.9%) 0.108 ms/op
Iteration   1: 1.920 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.591 ms/op
                 getUser·p0.50:   1.855 ms/op
                 getUser·p0.90:   2.404 ms/op
                 getUser·p0.95:   2.593 ms/op
                 getUser·p0.99:   4.122 ms/op
                 getUser·p0.999:  12.567 ms/op
                 getUser·p0.9999: 13.654 ms/op
                 getUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16661
  mean =      1.920 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1123 
    [ 1.250,  2.500) = 14422 
    [ 2.500,  3.750) = 930 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      4.122 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     13.654 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 4.528 ±(99.9%) 0.140 ms/op
Iteration   1: 3.246 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   0.735 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.582 ms/op
                 listUser·p0.999:  29.590 ms/op
                 listUser·p0.9999: 32.604 ms/op
                 listUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9860
  mean =      3.246 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1004 
    [ 2.500,  5.000) = 8672 
    [ 5.000,  7.500) = 152 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.582 ms/op
     p(99.9000) =     29.590 ms/op
     p(99.9900) =     32.604 ms/op
     p(99.9990) =     32.604 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.508          ops/ms
ClientSimple.existUser                       thrpt         12.897          ops/ms
ClientSimple.getUser                         thrpt         11.600          ops/ms
ClientSimple.listUser                        thrpt          8.006          ops/ms
ClientSimple.createUser                       avgt          2.336           ms/op
ClientSimple.existUser                        avgt          2.153           ms/op
ClientSimple.getUser                          avgt          2.248           ms/op
ClientSimple.listUser                         avgt          2.954           ms/op
ClientSimple.createUser                     sample  15347   2.084 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.424           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.855           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.535           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.830           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.792           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.702           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.070           ms/op
ClientSimple.existUser                      sample  15940   2.034 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.537           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.876           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.658           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.211           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.209           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.398           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.909           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.987           ms/op
ClientSimple.getUser                        sample  16661   1.920 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.591           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.855           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.404           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.122           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.567           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.654           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.025           ms/op
ClientSimple.listUser                       sample   9860   3.246 ± 0.055   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.735           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.929           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.088           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.582           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.590           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.604           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.604           ms/op

Benchmark result is saved to 1718972072692.json
