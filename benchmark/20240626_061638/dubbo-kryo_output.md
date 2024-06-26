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
# Warmup Iteration   1: 2.121 ops/ms
Iteration   1: 7.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.149 ops/ms


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
# Warmup Iteration   1: 6.472 ops/ms
Iteration   1: 11.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.537 ops/ms


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
# Warmup Iteration   1: 6.112 ops/ms
Iteration   1: 12.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.451 ops/ms


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
# Warmup Iteration   1: 5.680 ops/ms
Iteration   1: 7.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.998 ops/ms


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
# Warmup Iteration   1: 3.749 ±(99.9%) 0.063 ms/op
Iteration   1: 2.104 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.104 ms/op


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
# Warmup Iteration   1: 3.758 ±(99.9%) 0.067 ms/op
Iteration   1: 1.766 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.766 ms/op


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
# Warmup Iteration   1: 3.246 ±(99.9%) 0.066 ms/op
Iteration   1: 1.838 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.838 ms/op


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
# Warmup Iteration   1: 4.216 ±(99.9%) 0.094 ms/op
Iteration   1: 3.577 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.577 ms/op


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
# Warmup Iteration   1: 3.494 ±(99.9%) 0.101 ms/op
Iteration   1: 2.334 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.600 ms/op
                 createUser·p0.50:   2.204 ms/op
                 createUser·p0.90:   2.900 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   9.159 ms/op
                 createUser·p0.999:  16.290 ms/op
                 createUser·p0.9999: 18.346 ms/op
                 createUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13711
  mean =      2.334 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 376 
    [ 1.250,  2.500) = 9039 
    [ 2.500,  3.750) = 3850 
    [ 3.750,  5.000) = 235 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     16.290 ms/op
     p(99.9900) =     18.346 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 3.279 ±(99.9%) 0.099 ms/op
Iteration   1: 1.832 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   1.653 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.765 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  11.035 ms/op
                 existUser·p0.9999: 11.194 ms/op
                 existUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17481
  mean =      1.832 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1388 
    [ 1.250,  2.500) = 14457 
    [ 2.500,  3.750) = 1366 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      1.653 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =     11.035 ms/op
     p(99.9900) =     11.194 ms/op
     p(99.9990) =     11.207 ms/op
     p(99.9999) =     11.207 ms/op
    p(100.0000) =     11.207 ms/op


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
# Warmup Iteration   1: 3.614 ±(99.9%) 0.097 ms/op
Iteration   1: 1.998 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   1.898 ms/op
                 getUser·p0.90:   2.359 ms/op
                 getUser·p0.95:   2.585 ms/op
                 getUser·p0.99:   4.712 ms/op
                 getUser·p0.999:  13.648 ms/op
                 getUser·p0.9999: 17.243 ms/op
                 getUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15997
  mean =      1.998 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 14886 
    [ 2.500,  3.750) = 803 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      1.898 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      4.712 ms/op
     p(99.9000) =     13.648 ms/op
     p(99.9900) =     17.243 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.721 ±(99.9%) 0.162 ms/op
Iteration   1: 3.248 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.874 ms/op
                 listUser·p0.999:  17.957 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9838
  mean =      3.248 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 657 
    [ 2.500,  3.750) = 7404 
    [ 3.750,  5.000) = 1602 
    [ 5.000,  6.250) = 94 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     18.842 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.149          ops/ms
ClientSimple.existUser                       thrpt         11.537          ops/ms
ClientSimple.getUser                         thrpt         12.451          ops/ms
ClientSimple.listUser                        thrpt          7.998          ops/ms
ClientSimple.createUser                       avgt          2.104           ms/op
ClientSimple.existUser                        avgt          1.766           ms/op
ClientSimple.getUser                          avgt          1.838           ms/op
ClientSimple.listUser                         avgt          3.577           ms/op
ClientSimple.createUser                     sample  13711   2.334 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.600           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.204           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.900           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.203           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.159           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.290           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.346           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.383           ms/op
ClientSimple.existUser                      sample  17481   1.832 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.756           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.653           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.765           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.661           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.035           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.194           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.207           ms/op
ClientSimple.getUser                        sample  15997   1.998 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.988           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.898           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.359           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.712           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.648           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.243           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.302           ms/op
ClientSimple.listUser                       sample   9838   3.248 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.104           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.047           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.080           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.874           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.957           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.842           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.842           ms/op

Benchmark result is saved to 1719382342452.json
