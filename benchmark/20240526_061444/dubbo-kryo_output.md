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
# Warmup Iteration   1: 1.622 ops/ms
Iteration   1: 6.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.485 ops/ms


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
# Warmup Iteration   1: 6.824 ops/ms
Iteration   1: 12.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.993 ops/ms


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
# Warmup Iteration   1: 5.419 ops/ms
Iteration   1: 13.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.120 ops/ms


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
# Warmup Iteration   1: 4.931 ops/ms
Iteration   1: 8.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.613 ops/ms


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
# Warmup Iteration   1: 4.321 ±(99.9%) 0.090 ms/op
Iteration   1: 1.965 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.965 ms/op


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
# Warmup Iteration   1: 3.182 ±(99.9%) 0.048 ms/op
Iteration   1: 1.905 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.905 ms/op


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
# Warmup Iteration   1: 3.245 ±(99.9%) 0.056 ms/op
Iteration   1: 1.822 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.822 ms/op


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
# Warmup Iteration   1: 4.960 ±(99.9%) 0.106 ms/op
Iteration   1: 3.257 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.257 ms/op


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
# Warmup Iteration   1: 3.321 ±(99.9%) 0.090 ms/op
Iteration   1: 2.350 ±(99.9%) 0.061 ms/op
                 createUser·p0.00:   0.436 ms/op
                 createUser·p0.50:   2.050 ms/op
                 createUser·p0.90:   2.728 ms/op
                 createUser·p0.95:   3.123 ms/op
                 createUser·p0.99:   14.548 ms/op
                 createUser·p0.999:  28.803 ms/op
                 createUser·p0.9999: 29.217 ms/op
                 createUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13608
  mean =      2.350 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11121 
    [ 2.500,  5.000) = 2161 
    [ 5.000,  7.500) = 86 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      3.123 ms/op
     p(99.0000) =     14.548 ms/op
     p(99.9000) =     28.803 ms/op
     p(99.9900) =     29.217 ms/op
     p(99.9990) =     29.229 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 2.943 ±(99.9%) 0.071 ms/op
Iteration   1: 1.898 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.570 ms/op
                 existUser·p0.50:   1.772 ms/op
                 existUser·p0.90:   2.400 ms/op
                 existUser·p0.95:   2.593 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  11.866 ms/op
                 existUser·p0.9999: 12.984 ms/op
                 existUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16888
  mean =      1.898 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 399 
    [ 1.250,  2.500) = 15319 
    [ 2.500,  3.750) = 1011 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =     11.866 ms/op
     p(99.9900) =     12.984 ms/op
     p(99.9990) =     13.402 ms/op
     p(99.9999) =     13.402 ms/op
    p(100.0000) =     13.402 ms/op


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
# Warmup Iteration   1: 3.044 ±(99.9%) 0.071 ms/op
Iteration   1: 2.049 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.252 ms/op
                 getUser·p0.50:   1.862 ms/op
                 getUser·p0.90:   2.687 ms/op
                 getUser·p0.95:   2.994 ms/op
                 getUser·p0.99:   3.930 ms/op
                 getUser·p0.999:  24.056 ms/op
                 getUser·p0.9999: 24.622 ms/op
                 getUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15855
  mean =      2.049 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13578 
    [ 2.500,  5.000) = 2172 
    [ 5.000,  7.500) = 31 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.252 ms/op
     p(50.0000) =      1.862 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      3.930 ms/op
     p(99.9000) =     24.056 ms/op
     p(99.9900) =     24.622 ms/op
     p(99.9990) =     24.642 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.145 ms/op
Iteration   1: 3.152 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   4.098 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.104 ms/op
                 listUser·p0.999:  6.319 ms/op
                 listUser·p0.9999: 9.766 ms/op
                 listUser·p1.00:   9.798 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10155
  mean =      3.152 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 273 
    [ 2.000,  3.000) = 4870 
    [ 3.000,  4.000) = 3597 
    [ 4.000,  5.000) = 1290 
    [ 5.000,  6.000) = 108 
    [ 6.000,  7.000) = 11 
    [ 7.000,  8.000) = 4 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      4.098 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.104 ms/op
     p(99.9000) =      6.319 ms/op
     p(99.9900) =      9.766 ms/op
     p(99.9990) =      9.798 ms/op
     p(99.9999) =      9.798 ms/op
    p(100.0000) =      9.798 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.485          ops/ms
ClientSimple.existUser                       thrpt         12.993          ops/ms
ClientSimple.getUser                         thrpt         13.120          ops/ms
ClientSimple.listUser                        thrpt          8.613          ops/ms
ClientSimple.createUser                       avgt          1.965           ms/op
ClientSimple.existUser                        avgt          1.905           ms/op
ClientSimple.getUser                          avgt          1.822           ms/op
ClientSimple.listUser                         avgt          3.257           ms/op
ClientSimple.createUser                     sample  13608   2.350 ± 0.061   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.436           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.050           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.728           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.123           ms/op
ClientSimple.createUser:createUser·p0.99    sample         14.548           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.803           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.217           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.229           ms/op
ClientSimple.existUser                      sample  16888   1.898 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.570           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.772           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.593           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.662           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.866           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.984           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.402           ms/op
ClientSimple.getUser                        sample  15855   2.049 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.252           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.862           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.994           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.930           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.056           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.622           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.642           ms/op
ClientSimple.listUser                       sample  10155   3.152 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.980           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.978           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.098           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.104           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.319           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.766           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.798           ms/op

Benchmark result is saved to 1716703831273.json
