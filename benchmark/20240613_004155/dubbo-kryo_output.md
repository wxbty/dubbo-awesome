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
# Warmup Iteration   1: 1.848 ops/ms
Iteration   1: 7.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.142 ops/ms


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
# Warmup Iteration   1: 7.446 ops/ms
Iteration   1: 12.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.976 ops/ms


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
# Warmup Iteration   1: 6.027 ops/ms
Iteration   1: 12.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.224 ops/ms


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
# Warmup Iteration   1: 5.310 ops/ms
Iteration   1: 8.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.161 ops/ms


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.086 ms/op
Iteration   1: 2.200 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.200 ms/op


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
# Warmup Iteration   1: 3.315 ±(99.9%) 0.044 ms/op
Iteration   1: 2.080 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.080 ms/op


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
# Warmup Iteration   1: 3.471 ±(99.9%) 0.068 ms/op
Iteration   1: 2.013 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.013 ms/op


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
# Warmup Iteration   1: 5.804 ±(99.9%) 0.106 ms/op
Iteration   1: 3.467 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.467 ms/op


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
# Warmup Iteration   1: 3.536 ±(99.9%) 0.090 ms/op
Iteration   1: 2.088 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   1.909 ms/op
                 createUser·p0.90:   2.605 ms/op
                 createUser·p0.95:   2.830 ms/op
                 createUser·p0.99:   5.081 ms/op
                 createUser·p0.999:  23.560 ms/op
                 createUser·p0.9999: 23.903 ms/op
                 createUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15275
  mean =      2.088 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13298 
    [ 2.500,  5.000) = 1813 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      5.081 ms/op
     p(99.9000) =     23.560 ms/op
     p(99.9900) =     23.903 ms/op
     p(99.9990) =     23.921 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 3.174 ±(99.9%) 0.076 ms/op
Iteration   1: 1.862 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   1.642 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.679 ms/op
                 existUser·p0.99:   4.934 ms/op
                 existUser·p0.999:  20.873 ms/op
                 existUser·p0.9999: 21.037 ms/op
                 existUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17167
  mean =      1.862 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15924 
    [ 2.500,  5.000) = 1077 
    [ 5.000,  7.500) = 67 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      1.642 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      4.934 ms/op
     p(99.9000) =     20.873 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     21.037 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 3.406 ±(99.9%) 0.083 ms/op
Iteration   1: 2.141 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   2.054 ms/op
                 getUser·p0.90:   2.692 ms/op
                 getUser·p0.95:   2.929 ms/op
                 getUser·p0.99:   5.092 ms/op
                 getUser·p0.999:  12.699 ms/op
                 getUser·p0.9999: 13.795 ms/op
                 getUser·p1.00:   13.795 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14936
  mean =      2.141 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 12314 
    [ 2.500,  3.750) = 2219 
    [ 3.750,  5.000) = 94 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.692 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      5.092 ms/op
     p(99.9000) =     12.699 ms/op
     p(99.9900) =     13.795 ms/op
     p(99.9990) =     13.795 ms/op
     p(99.9999) =     13.795 ms/op
    p(100.0000) =     13.795 ms/op


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
# Warmup Iteration   1: 4.914 ±(99.9%) 0.206 ms/op
Iteration   1: 3.648 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  20.480 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8765
  mean =      3.648 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 399 
    [ 2.500,  5.000) = 8060 
    [ 5.000,  7.500) = 205 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     20.480 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.142          ops/ms
ClientSimple.existUser                       thrpt         12.976          ops/ms
ClientSimple.getUser                         thrpt         12.224          ops/ms
ClientSimple.listUser                        thrpt          8.161          ops/ms
ClientSimple.createUser                       avgt          2.200           ms/op
ClientSimple.existUser                        avgt          2.080           ms/op
ClientSimple.getUser                          avgt          2.013           ms/op
ClientSimple.listUser                         avgt          3.467           ms/op
ClientSimple.createUser                     sample  15275   2.088 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.597           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.909           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.605           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.081           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.560           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.903           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.921           ms/op
ClientSimple.existUser                      sample  17167   1.862 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.635           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.642           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.679           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.934           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.873           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.037           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.037           ms/op
ClientSimple.getUser                        sample  14936   2.141 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.874           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.054           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.692           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.929           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.092           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.699           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.795           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.795           ms/op
ClientSimple.listUser                       sample   8765   3.648 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.940           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.564           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.889           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.480           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.889           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.889           ms/op

Benchmark result is saved to 1718239050035.json
