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
# Warmup Iteration   1: 1.770 ops/ms
Iteration   1: 6.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.409 ops/ms


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
# Warmup Iteration   1: 6.090 ops/ms
Iteration   1: 11.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.726 ops/ms


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
# Warmup Iteration   1: 5.110 ops/ms
Iteration   1: 11.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.814 ops/ms


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
# Warmup Iteration   1: 5.647 ops/ms
Iteration   1: 8.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.356 ops/ms


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
# Warmup Iteration   1: 3.963 ±(99.9%) 0.077 ms/op
Iteration   1: 1.957 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.957 ms/op


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
# Warmup Iteration   1: 3.141 ±(99.9%) 0.057 ms/op
Iteration   1: 1.895 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.895 ms/op


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
# Warmup Iteration   1: 3.256 ±(99.9%) 0.059 ms/op
Iteration   1: 2.184 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.184 ms/op


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
# Warmup Iteration   1: 4.402 ±(99.9%) 0.100 ms/op
Iteration   1: 3.239 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.239 ms/op


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
# Warmup Iteration   1: 3.560 ±(99.9%) 0.089 ms/op
Iteration   1: 2.427 ±(99.9%) 0.060 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   2.175 ms/op
                 createUser·p0.90:   2.888 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   9.667 ms/op
                 createUser·p0.999:  30.955 ms/op
                 createUser·p0.9999: 31.578 ms/op
                 createUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13315
  mean =      2.427 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8495 
    [ 2.500,  5.000) = 4598 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      2.175 ms/op
     p(90.0000) =      2.888 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     30.955 ms/op
     p(99.9900) =     31.578 ms/op
     p(99.9990) =     31.621 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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
# Warmup Iteration   1: 2.875 ±(99.9%) 0.075 ms/op
Iteration   1: 1.759 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   1.642 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  11.532 ms/op
                 existUser·p0.9999: 11.786 ms/op
                 existUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18160
  mean =      1.759 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 690 
    [ 1.250,  2.500) = 16545 
    [ 2.500,  3.750) = 759 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      1.642 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =     11.532 ms/op
     p(99.9900) =     11.786 ms/op
     p(99.9990) =     11.813 ms/op
     p(99.9999) =     11.813 ms/op
    p(100.0000) =     11.813 ms/op


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
# Warmup Iteration   1: 3.629 ±(99.9%) 0.087 ms/op
Iteration   1: 2.059 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   1.925 ms/op
                 getUser·p0.90:   2.220 ms/op
                 getUser·p0.95:   2.448 ms/op
                 getUser·p0.99:   5.152 ms/op
                 getUser·p0.999:  32.519 ms/op
                 getUser·p0.9999: 33.321 ms/op
                 getUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15605
  mean =      2.059 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14912 
    [ 2.500,  5.000) = 516 
    [ 5.000,  7.500) = 112 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      1.925 ms/op
     p(90.0000) =      2.220 ms/op
     p(95.0000) =      2.448 ms/op
     p(99.0000) =      5.152 ms/op
     p(99.9000) =     32.519 ms/op
     p(99.9900) =     33.321 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 4.474 ±(99.9%) 0.136 ms/op
Iteration   1: 3.186 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   5.358 ms/op
                 listUser·p0.999:  6.455 ms/op
                 listUser·p0.9999: 9.388 ms/op
                 listUser·p1.00:   9.404 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10097
  mean =      3.186 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 210 
    [ 2.000,  3.000) = 4935 
    [ 3.000,  4.000) = 3173 
    [ 4.000,  5.000) = 1443 
    [ 5.000,  6.000) = 294 
    [ 6.000,  7.000) = 37 
    [ 7.000,  8.000) = 2 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =      6.455 ms/op
     p(99.9900) =      9.388 ms/op
     p(99.9990) =      9.404 ms/op
     p(99.9999) =      9.404 ms/op
    p(100.0000) =      9.404 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.409          ops/ms
ClientSimple.existUser                       thrpt         11.726          ops/ms
ClientSimple.getUser                         thrpt         11.814          ops/ms
ClientSimple.listUser                        thrpt          8.356          ops/ms
ClientSimple.createUser                       avgt          1.957           ms/op
ClientSimple.existUser                        avgt          1.895           ms/op
ClientSimple.getUser                          avgt          2.184           ms/op
ClientSimple.listUser                         avgt          3.239           ms/op
ClientSimple.createUser                     sample  13315   2.427 ± 0.060   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.754           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.175           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.888           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.117           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.667           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.955           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.578           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.621           ms/op
ClientSimple.existUser                      sample  18160   1.759 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.653           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.642           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.666           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.532           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.786           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.813           ms/op
ClientSimple.getUser                        sample  15605   2.059 ± 0.040   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.663           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.925           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.220           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.448           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.152           ms/op
ClientSimple.getUser:getUser·p0.999         sample         32.519           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         33.321           ms/op
ClientSimple.getUser:getUser·p1.00          sample         33.817           ms/op
ClientSimple.listUser                       sample  10097   3.186 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.976           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.974           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.358           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.455           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.388           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.404           ms/op

Benchmark result is saved to 1716597312592.json
