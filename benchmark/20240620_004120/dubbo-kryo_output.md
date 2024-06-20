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
# Warmup Iteration   1: 1.781 ops/ms
Iteration   1: 6.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.868 ops/ms


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
# Warmup Iteration   1: 5.884 ops/ms
Iteration   1: 13.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.177 ops/ms


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
# Warmup Iteration   1: 5.475 ops/ms
Iteration   1: 11.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.395 ops/ms


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
# Warmup Iteration   1: 4.935 ops/ms
Iteration   1: 8.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.229 ops/ms


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.074 ms/op
Iteration   1: 2.343 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.343 ms/op


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
# Warmup Iteration   1: 3.209 ±(99.9%) 0.047 ms/op
Iteration   1: 1.860 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.860 ms/op


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
# Warmup Iteration   1: 3.467 ±(99.9%) 0.073 ms/op
Iteration   1: 2.413 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.413 ms/op


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
# Warmup Iteration   1: 4.958 ±(99.9%) 0.093 ms/op
Iteration   1: 2.997 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.997 ms/op


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
# Warmup Iteration   1: 3.730 ±(99.9%) 0.114 ms/op
Iteration   1: 2.341 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.404 ms/op
                 createUser·p0.50:   2.036 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.424 ms/op
                 createUser·p0.99:   5.036 ms/op
                 createUser·p0.999:  20.873 ms/op
                 createUser·p0.9999: 21.430 ms/op
                 createUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13664
  mean =      2.341 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9736 
    [ 2.500,  5.000) = 3784 
    [ 5.000,  7.500) = 16 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      3.162 ms/op
     p(95.0000) =      3.424 ms/op
     p(99.0000) =      5.036 ms/op
     p(99.9000) =     20.873 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     21.430 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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
# Warmup Iteration   1: 2.999 ±(99.9%) 0.073 ms/op
Iteration   1: 1.897 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   1.819 ms/op
                 existUser·p0.90:   2.441 ms/op
                 existUser·p0.95:   2.707 ms/op
                 existUser·p0.99:   3.177 ms/op
                 existUser·p0.999:  12.380 ms/op
                 existUser·p0.9999: 13.339 ms/op
                 existUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16845
  mean =      1.897 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 462 
    [ 1.250,  2.500) = 14991 
    [ 2.500,  3.750) = 1270 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      1.819 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      3.177 ms/op
     p(99.9000) =     12.380 ms/op
     p(99.9900) =     13.339 ms/op
     p(99.9990) =     13.451 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


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
# Warmup Iteration   1: 3.105 ±(99.9%) 0.079 ms/op
Iteration   1: 2.105 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.526 ms/op
                 getUser·p0.50:   2.011 ms/op
                 getUser·p0.90:   2.720 ms/op
                 getUser·p0.95:   2.916 ms/op
                 getUser·p0.99:   3.732 ms/op
                 getUser·p0.999:  25.002 ms/op
                 getUser·p0.9999: 25.461 ms/op
                 getUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15180
  mean =      2.105 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11956 
    [ 2.500,  5.000) = 3159 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.916 ms/op
     p(99.0000) =      3.732 ms/op
     p(99.9000) =     25.002 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     25.461 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 4.691 ±(99.9%) 0.186 ms/op
Iteration   1: 3.198 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.988 ms/op
                 listUser·p0.999:  13.828 ms/op
                 listUser·p0.9999: 14.041 ms/op
                 listUser·p1.00:   14.041 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10066
  mean =      3.198 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 291 
    [ 2.500,  3.750) = 8525 
    [ 3.750,  5.000) = 1075 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     14.041 ms/op
     p(99.9990) =     14.041 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.868          ops/ms
ClientSimple.existUser                       thrpt         13.177          ops/ms
ClientSimple.getUser                         thrpt         11.395          ops/ms
ClientSimple.listUser                        thrpt          8.229          ops/ms
ClientSimple.createUser                       avgt          2.343           ms/op
ClientSimple.existUser                        avgt          1.860           ms/op
ClientSimple.getUser                          avgt          2.413           ms/op
ClientSimple.listUser                         avgt          2.997           ms/op
ClientSimple.createUser                     sample  13664   2.341 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.404           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.036           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.162           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.424           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.036           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.873           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.430           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.430           ms/op
ClientSimple.existUser                      sample  16845   1.897 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.671           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.819           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.441           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.707           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.177           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.380           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.339           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.451           ms/op
ClientSimple.getUser                        sample  15180   2.105 ± 0.034   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.526           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.011           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.720           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.916           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.732           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.002           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.461           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.461           ms/op
ClientSimple.listUser                       sample  10066   3.198 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.818           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.015           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.912           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.988           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.828           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.041           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.041           ms/op

Benchmark result is saved to 1718843816219.json
