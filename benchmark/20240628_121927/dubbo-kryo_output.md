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
# Warmup Iteration   1: 1.604 ops/ms
Iteration   1: 6.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.211 ops/ms


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
# Warmup Iteration   1: 6.087 ops/ms
Iteration   1: 11.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.377 ops/ms


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
# Warmup Iteration   1: 5.651 ops/ms
Iteration   1: 12.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.835 ops/ms


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
# Warmup Iteration   1: 3.915 ops/ms
Iteration   1: 7.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.873 ops/ms


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.084 ms/op
Iteration   1: 2.169 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.169 ms/op


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
# Warmup Iteration   1: 3.264 ±(99.9%) 0.079 ms/op
Iteration   1: 2.136 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.136 ms/op


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
# Warmup Iteration   1: 3.251 ±(99.9%) 0.066 ms/op
Iteration   1: 2.159 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.159 ms/op


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
# Warmup Iteration   1: 5.063 ±(99.9%) 0.133 ms/op
Iteration   1: 3.701 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.701 ms/op


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
# Warmup Iteration   1: 3.518 ±(99.9%) 0.109 ms/op
Iteration   1: 2.168 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.498 ms/op
                 createUser·p0.50:   1.855 ms/op
                 createUser·p0.90:   2.879 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   6.811 ms/op
                 createUser·p0.999:  16.391 ms/op
                 createUser·p0.9999: 17.160 ms/op
                 createUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14797
  mean =      2.168 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 247 
    [ 1.250,  2.500) = 10876 
    [ 2.500,  3.750) = 3270 
    [ 3.750,  5.000) = 159 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      6.811 ms/op
     p(99.9000) =     16.391 ms/op
     p(99.9900) =     17.160 ms/op
     p(99.9990) =     17.302 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 3.372 ±(99.9%) 0.113 ms/op
Iteration   1: 1.939 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.407 ms/op
                 existUser·p0.50:   1.798 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  32.047 ms/op
                 existUser·p0.9999: 32.375 ms/op
                 existUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16612
  mean =      1.939 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15142 
    [ 2.500,  5.000) = 1349 
    [ 5.000,  7.500) = 57 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.407 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =     32.047 ms/op
     p(99.9900) =     32.375 ms/op
     p(99.9990) =     32.440 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 3.212 ±(99.9%) 0.078 ms/op
Iteration   1: 2.121 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   2.048 ms/op
                 getUser·p0.90:   2.679 ms/op
                 getUser·p0.95:   2.998 ms/op
                 getUser·p0.99:   5.226 ms/op
                 getUser·p0.999:  12.435 ms/op
                 getUser·p0.9999: 13.613 ms/op
                 getUser·p1.00:   13.795 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15065
  mean =      2.121 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 247 
    [ 1.250,  2.500) = 12605 
    [ 2.500,  3.750) = 1966 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 128 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.048 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.998 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     12.435 ms/op
     p(99.9900) =     13.613 ms/op
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
# Warmup Iteration   1: 4.208 ±(99.9%) 0.118 ms/op
Iteration   1: 3.424 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   0.724 ms/op
                 listUser·p0.50:   3.359 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   5.882 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9347
  mean =      3.424 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 704 
    [ 2.500,  3.750) = 6097 
    [ 3.750,  5.000) = 2260 
    [ 5.000,  6.250) = 239 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     16.876 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.211          ops/ms
ClientSimple.existUser                       thrpt         11.377          ops/ms
ClientSimple.getUser                         thrpt         12.835          ops/ms
ClientSimple.listUser                        thrpt          7.873          ops/ms
ClientSimple.createUser                       avgt          2.169           ms/op
ClientSimple.existUser                        avgt          2.136           ms/op
ClientSimple.getUser                          avgt          2.159           ms/op
ClientSimple.listUser                         avgt          3.701           ms/op
ClientSimple.createUser                     sample  14797   2.168 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.498           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.855           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.879           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.174           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.811           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.391           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.160           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.302           ms/op
ClientSimple.existUser                      sample  16612   1.939 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.407           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.798           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.260           ms/op
ClientSimple.existUser:existUser·p0.999     sample         32.047           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         32.375           ms/op
ClientSimple.existUser:existUser·p1.00      sample         32.440           ms/op
ClientSimple.getUser                        sample  15065   2.121 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.708           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.048           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.679           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.998           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.226           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.435           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.613           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.795           ms/op
ClientSimple.listUser                       sample   9347   3.424 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.724           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.359           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.563           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.882           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.744           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.876           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.876           ms/op

Benchmark result is saved to 1719576906716.json
