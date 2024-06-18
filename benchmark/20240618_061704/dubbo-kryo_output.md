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
# Warmup Iteration   1: 0.886 ops/ms
Iteration   1: 5.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.845 ops/ms


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
# Warmup Iteration   1: 5.239 ops/ms
Iteration   1: 11.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.413 ops/ms


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
# Warmup Iteration   1: 5.736 ops/ms
Iteration   1: 12.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.780 ops/ms


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
# Warmup Iteration   1: 4.999 ops/ms
Iteration   1: 8.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.968 ops/ms


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
# Warmup Iteration   1: 4.176 ±(99.9%) 0.086 ms/op
Iteration   1: 2.126 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.126 ms/op


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
# Warmup Iteration   1: 3.116 ±(99.9%) 0.048 ms/op
Iteration   1: 1.960 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.960 ms/op


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
# Warmup Iteration   1: 3.388 ±(99.9%) 0.062 ms/op
Iteration   1: 1.955 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.955 ms/op


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.144 ms/op
Iteration   1: 3.969 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.969 ms/op


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
# Warmup Iteration   1: 3.550 ±(99.9%) 0.083 ms/op
Iteration   1: 2.100 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.458 ms/op
                 createUser·p0.50:   1.985 ms/op
                 createUser·p0.90:   2.466 ms/op
                 createUser·p0.95:   2.716 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  16.821 ms/op
                 createUser·p0.9999: 21.858 ms/op
                 createUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15336
  mean =      2.100 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13977 
    [ 2.500,  5.000) = 1180 
    [ 5.000,  7.500) = 81 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     16.821 ms/op
     p(99.9900) =     21.858 ms/op
     p(99.9990) =     22.348 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 3.038 ±(99.9%) 0.066 ms/op
Iteration   1: 1.837 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.442 ms/op
                 existUser·p0.50:   1.653 ms/op
                 existUser·p0.90:   2.454 ms/op
                 existUser·p0.95:   2.626 ms/op
                 existUser·p0.99:   4.825 ms/op
                 existUser·p0.999:  18.809 ms/op
                 existUser·p0.9999: 19.129 ms/op
                 existUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17398
  mean =      1.837 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1876 
    [ 1.250,  2.500) = 14011 
    [ 2.500,  3.750) = 1250 
    [ 3.750,  5.000) = 140 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      1.653 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      4.825 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     19.129 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 3.288 ±(99.9%) 0.085 ms/op
Iteration   1: 2.114 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   2.019 ms/op
                 getUser·p0.90:   2.757 ms/op
                 getUser·p0.95:   2.937 ms/op
                 getUser·p0.99:   3.538 ms/op
                 getUser·p0.999:  11.137 ms/op
                 getUser·p0.9999: 16.325 ms/op
                 getUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15123
  mean =      2.114 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 158 
    [ 1.250,  2.500) = 11773 
    [ 2.500,  3.750) = 3079 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      2.019 ms/op
     p(90.0000) =      2.757 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      3.538 ms/op
     p(99.9000) =     11.137 ms/op
     p(99.9900) =     16.325 ms/op
     p(99.9990) =     16.384 ms/op
     p(99.9999) =     16.384 ms/op
    p(100.0000) =     16.384 ms/op


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.127 ms/op
Iteration   1: 3.374 ±(99.9%) 0.231 ms/op
                 listUser·p0.00:   0.407 ms/op
                 listUser·p0.50:   2.789 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   12.128 ms/op
                 listUser·p0.999:  121.509 ms/op
                 listUser·p0.9999: 131.990 ms/op
                 listUser·p1.00:   131.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9478
  mean =      3.374 ±(99.9%) 0.231 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 9404 
    [ 12.500,  25.000) = 42 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 0 
    [112.500, 125.000) = 28 
    [125.000, 137.500) = 4 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.407 ms/op
     p(50.0000) =      2.789 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =     12.128 ms/op
     p(99.9000) =    121.509 ms/op
     p(99.9900) =    131.990 ms/op
     p(99.9990) =    131.990 ms/op
     p(99.9999) =    131.990 ms/op
    p(100.0000) =    131.990 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           5.845          ops/ms
ClientSimple.existUser                       thrpt          11.413          ops/ms
ClientSimple.getUser                         thrpt          12.780          ops/ms
ClientSimple.listUser                        thrpt           8.968          ops/ms
ClientSimple.createUser                       avgt           2.126           ms/op
ClientSimple.existUser                        avgt           1.960           ms/op
ClientSimple.getUser                          avgt           1.955           ms/op
ClientSimple.listUser                         avgt           3.969           ms/op
ClientSimple.createUser                     sample  15336    2.100 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.458           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.985           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.466           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.716           ms/op
ClientSimple.createUser:createUser·p0.99    sample           6.152           ms/op
ClientSimple.createUser:createUser·p0.999   sample          16.821           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          21.858           ms/op
ClientSimple.createUser:createUser·p1.00    sample          22.348           ms/op
ClientSimple.existUser                      sample  17398    1.837 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.442           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.653           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.454           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.626           ms/op
ClientSimple.existUser:existUser·p0.99      sample           4.825           ms/op
ClientSimple.existUser:existUser·p0.999     sample          18.809           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          19.129           ms/op
ClientSimple.existUser:existUser·p1.00      sample          19.202           ms/op
ClientSimple.getUser                        sample  15123    2.114 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.780           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.019           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.757           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.937           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.538           ms/op
ClientSimple.getUser:getUser·p0.999         sample          11.137           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          16.325           ms/op
ClientSimple.getUser:getUser·p1.00          sample          16.384           ms/op
ClientSimple.listUser                       sample   9478    3.374 ± 0.231   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.407           ms/op
ClientSimple.listUser:listUser·p0.50        sample           2.789           ms/op
ClientSimple.listUser:listUser·p0.90        sample           3.863           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.211           ms/op
ClientSimple.listUser:listUser·p0.99        sample          12.128           ms/op
ClientSimple.listUser:listUser·p0.999       sample         121.509           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         131.990           ms/op
ClientSimple.listUser:listUser·p1.00        sample         131.990           ms/op

Benchmark result is saved to 1718691127403.json
