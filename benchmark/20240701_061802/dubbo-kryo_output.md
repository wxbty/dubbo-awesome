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
# Warmup Iteration   1: 1.890 ops/ms
Iteration   1: 7.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.219 ops/ms


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
# Warmup Iteration   1: 6.571 ops/ms
Iteration   1: 12.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.791 ops/ms


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
# Warmup Iteration   1: 5.879 ops/ms
Iteration   1: 13.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.876 ops/ms


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
# Warmup Iteration   1: 5.532 ops/ms
Iteration   1: 8.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.985 ops/ms


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.077 ms/op
Iteration   1: 2.264 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.264 ms/op


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
# Warmup Iteration   1: 3.423 ±(99.9%) 0.056 ms/op
Iteration   1: 2.026 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.026 ms/op


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
# Warmup Iteration   1: 3.311 ±(99.9%) 0.058 ms/op
Iteration   1: 1.936 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.936 ms/op


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
# Warmup Iteration   1: 4.383 ±(99.9%) 0.082 ms/op
Iteration   1: 3.528 ±(99.9%) 0.046 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.528 ms/op


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.101 ms/op
Iteration   1: 2.096 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   1.980 ms/op
                 createUser·p0.90:   2.470 ms/op
                 createUser·p0.95:   2.757 ms/op
                 createUser·p0.99:   5.100 ms/op
                 createUser·p0.999:  19.792 ms/op
                 createUser·p0.9999: 20.644 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15280
  mean =      2.096 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13846 
    [ 2.500,  5.000) = 1278 
    [ 5.000,  7.500) = 60 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      5.100 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 3.068 ±(99.9%) 0.081 ms/op
Iteration   1: 1.994 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   1.954 ms/op
                 existUser·p0.90:   2.462 ms/op
                 existUser·p0.95:   2.671 ms/op
                 existUser·p0.99:   3.346 ms/op
                 existUser·p0.999:  10.761 ms/op
                 existUser·p0.9999: 10.881 ms/op
                 existUser·p1.00:   10.912 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16219
  mean =      1.994 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 486 
    [ 1.250,  2.500) = 14312 
    [ 2.500,  3.750) = 1303 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      3.346 ms/op
     p(99.9000) =     10.761 ms/op
     p(99.9900) =     10.881 ms/op
     p(99.9990) =     10.912 ms/op
     p(99.9999) =     10.912 ms/op
    p(100.0000) =     10.912 ms/op


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
# Warmup Iteration   1: 3.728 ±(99.9%) 0.139 ms/op
Iteration   1: 1.842 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   1.749 ms/op
                 getUser·p0.90:   2.290 ms/op
                 getUser·p0.95:   2.458 ms/op
                 getUser·p0.99:   2.822 ms/op
                 getUser·p0.999:  11.207 ms/op
                 getUser·p0.9999: 11.503 ms/op
                 getUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17354
  mean =      1.842 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 16531 
    [ 2.500,  3.750) = 643 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      2.822 ms/op
     p(99.9000) =     11.207 ms/op
     p(99.9900) =     11.503 ms/op
     p(99.9990) =     11.600 ms/op
     p(99.9999) =     11.600 ms/op
    p(100.0000) =     11.600 ms/op


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
# Warmup Iteration   1: 4.990 ±(99.9%) 0.212 ms/op
Iteration   1: 3.221 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.344 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  13.927 ms/op
                 listUser·p0.9999: 15.548 ms/op
                 listUser·p1.00:   15.548 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9933
  mean =      3.221 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 457 
    [ 2.500,  3.750) = 7417 
    [ 3.750,  5.000) = 1881 
    [ 5.000,  6.250) = 98 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.344 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     13.927 ms/op
     p(99.9900) =     15.548 ms/op
     p(99.9990) =     15.548 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.219          ops/ms
ClientSimple.existUser                       thrpt         12.791          ops/ms
ClientSimple.getUser                         thrpt         13.876          ops/ms
ClientSimple.listUser                        thrpt          8.985          ops/ms
ClientSimple.createUser                       avgt          2.264           ms/op
ClientSimple.existUser                        avgt          2.026           ms/op
ClientSimple.getUser                          avgt          1.936           ms/op
ClientSimple.listUser                         avgt          3.528           ms/op
ClientSimple.createUser                     sample  15280   2.096 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.688           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.980           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.470           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.757           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.100           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.792           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.644           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.644           ms/op
ClientSimple.existUser                      sample  16219   1.994 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.701           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.954           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.671           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.346           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.761           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.881           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.912           ms/op
ClientSimple.getUser                        sample  17354   1.842 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.861           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.749           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.290           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.207           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.503           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.600           ms/op
ClientSimple.listUser                       sample   9933   3.221 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.331           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.920           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.121           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.344           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.571           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.927           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.548           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.548           ms/op

Benchmark result is saved to 1719814411704.json
