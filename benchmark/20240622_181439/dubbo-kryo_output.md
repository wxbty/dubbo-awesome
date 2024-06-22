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
# Warmup Iteration   1: 1.963 ops/ms
Iteration   1: 7.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.409 ops/ms


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
# Warmup Iteration   1: 6.617 ops/ms
Iteration   1: 14.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.181 ops/ms


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
# Warmup Iteration   1: 5.852 ops/ms
Iteration   1: 11.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.793 ops/ms


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
# Warmup Iteration   1: 3.900 ops/ms
Iteration   1: 8.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.144 ops/ms


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.069 ms/op
Iteration   1: 2.138 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.138 ms/op


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
# Warmup Iteration   1: 2.986 ±(99.9%) 0.042 ms/op
Iteration   1: 1.717 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.717 ms/op


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
# Warmup Iteration   1: 3.788 ±(99.9%) 0.067 ms/op
Iteration   1: 2.078 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.078 ms/op


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
# Warmup Iteration   1: 4.366 ±(99.9%) 0.101 ms/op
Iteration   1: 3.485 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.485 ms/op


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
# Warmup Iteration   1: 3.372 ±(99.9%) 0.101 ms/op
Iteration   1: 2.304 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   2.216 ms/op
                 createUser·p0.90:   2.712 ms/op
                 createUser·p0.95:   2.867 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  17.732 ms/op
                 createUser·p0.9999: 18.679 ms/op
                 createUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13874
  mean =      2.304 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 10475 
    [ 2.500,  3.750) = 3148 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.216 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =     17.732 ms/op
     p(99.9900) =     18.679 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 2.896 ±(99.9%) 0.076 ms/op
Iteration   1: 1.817 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   1.737 ms/op
                 existUser·p0.90:   2.224 ms/op
                 existUser·p0.95:   2.462 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  16.974 ms/op
                 existUser·p0.9999: 17.489 ms/op
                 existUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17591
  mean =      1.817 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 772 
    [ 1.250,  2.500) = 16028 
    [ 2.500,  3.750) = 645 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      1.737 ms/op
     p(90.0000) =      2.224 ms/op
     p(95.0000) =      2.462 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     17.489 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 3.153 ±(99.9%) 0.085 ms/op
Iteration   1: 1.881 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   1.808 ms/op
                 getUser·p0.90:   2.314 ms/op
                 getUser·p0.95:   2.454 ms/op
                 getUser·p0.99:   3.701 ms/op
                 getUser·p0.999:  13.697 ms/op
                 getUser·p0.9999: 13.930 ms/op
                 getUser·p1.00:   13.976 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17015
  mean =      1.881 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 344 
    [ 1.250,  2.500) = 15983 
    [ 2.500,  3.750) = 524 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      1.808 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      3.701 ms/op
     p(99.9000) =     13.697 ms/op
     p(99.9900) =     13.930 ms/op
     p(99.9990) =     13.976 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


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
# Warmup Iteration   1: 4.217 ±(99.9%) 0.129 ms/op
Iteration   1: 3.484 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.490 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  7.384 ms/op
                 listUser·p0.9999: 8.847 ms/op
                 listUser·p1.00:   8.847 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9183
  mean =      3.484 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 11 
    [1.500, 2.000) = 84 
    [2.000, 2.500) = 383 
    [2.500, 3.000) = 1463 
    [3.000, 3.500) = 2741 
    [3.500, 4.000) = 2989 
    [4.000, 4.500) = 1123 
    [4.500, 5.000) = 185 
    [5.000, 5.500) = 86 
    [5.500, 6.000) = 60 
    [6.000, 6.500) = 21 
    [6.500, 7.000) = 24 
    [7.000, 7.500) = 5 
    [7.500, 8.000) = 3 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      7.384 ms/op
     p(99.9900) =      8.847 ms/op
     p(99.9990) =      8.847 ms/op
     p(99.9999) =      8.847 ms/op
    p(100.0000) =      8.847 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.409          ops/ms
ClientSimple.existUser                       thrpt         14.181          ops/ms
ClientSimple.getUser                         thrpt         11.793          ops/ms
ClientSimple.listUser                        thrpt          8.144          ops/ms
ClientSimple.createUser                       avgt          2.138           ms/op
ClientSimple.existUser                        avgt          1.717           ms/op
ClientSimple.getUser                          avgt          2.078           ms/op
ClientSimple.listUser                         avgt          3.485           ms/op
ClientSimple.createUser                     sample  13874   2.304 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.809           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.216           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.712           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.489           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.732           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.679           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.907           ms/op
ClientSimple.existUser                      sample  17591   1.817 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.569           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.737           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.224           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.625           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.974           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.489           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.564           ms/op
ClientSimple.getUser                        sample  17015   1.881 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.649           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.808           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.314           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.454           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.701           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.697           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.930           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.976           ms/op
ClientSimple.listUser                       sample   9183   3.484 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.053           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.490           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.644           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.384           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.847           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.847           ms/op

Benchmark result is saved to 1719079839327.json
