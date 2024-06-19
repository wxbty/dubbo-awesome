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
# Warmup Iteration   1: 1.335 ops/ms
Iteration   1: 6.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.722 ops/ms


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
# Warmup Iteration   1: 5.460 ops/ms
Iteration   1: 11.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.475 ops/ms


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
# Warmup Iteration   1: 5.364 ops/ms
Iteration   1: 12.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.410 ops/ms


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
# Warmup Iteration   1: 4.667 ops/ms
Iteration   1: 8.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.369 ops/ms


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.071 ms/op
Iteration   1: 2.176 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.176 ms/op


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
# Warmup Iteration   1: 2.910 ±(99.9%) 0.049 ms/op
Iteration   1: 1.697 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.697 ms/op


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
# Warmup Iteration   1: 3.642 ±(99.9%) 0.070 ms/op
Iteration   1: 2.146 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.146 ms/op


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
# Warmup Iteration   1: 4.543 ±(99.9%) 0.091 ms/op
Iteration   1: 3.328 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.328 ms/op


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
# Warmup Iteration   1: 3.448 ±(99.9%) 0.081 ms/op
Iteration   1: 2.490 ±(99.9%) 0.077 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   2.150 ms/op
                 createUser·p0.90:   2.780 ms/op
                 createUser·p0.95:   3.452 ms/op
                 createUser·p0.99:   13.058 ms/op
                 createUser·p0.999:  51.053 ms/op
                 createUser·p0.9999: 54.771 ms/op
                 createUser·p1.00:   55.050 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12842
  mean =      2.490 ±(99.9%) 0.077 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12532 
    [ 5.000, 10.000) = 107 
    [10.000, 15.000) = 126 
    [15.000, 20.000) = 42 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 4 
    [50.000, 55.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.780 ms/op
     p(95.0000) =      3.452 ms/op
     p(99.0000) =     13.058 ms/op
     p(99.9000) =     51.053 ms/op
     p(99.9900) =     54.771 ms/op
     p(99.9990) =     55.050 ms/op
     p(99.9999) =     55.050 ms/op
    p(100.0000) =     55.050 ms/op


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
# Warmup Iteration   1: 3.036 ±(99.9%) 0.074 ms/op
Iteration   1: 1.937 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   1.878 ms/op
                 existUser·p0.90:   2.449 ms/op
                 existUser·p0.95:   2.601 ms/op
                 existUser·p0.99:   3.178 ms/op
                 existUser·p0.999:  11.411 ms/op
                 existUser·p0.9999: 11.601 ms/op
                 existUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16511
  mean =      1.937 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 392 
    [ 1.250,  2.500) = 14771 
    [ 2.500,  3.750) = 1228 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      1.878 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.178 ms/op
     p(99.9000) =     11.411 ms/op
     p(99.9900) =     11.601 ms/op
     p(99.9990) =     11.633 ms/op
     p(99.9999) =     11.633 ms/op
    p(100.0000) =     11.633 ms/op


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
# Warmup Iteration   1: 3.084 ±(99.9%) 0.078 ms/op
Iteration   1: 1.998 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   1.972 ms/op
                 getUser·p0.90:   2.499 ms/op
                 getUser·p0.95:   2.617 ms/op
                 getUser·p0.99:   3.223 ms/op
                 getUser·p0.999:  11.239 ms/op
                 getUser·p0.9999: 11.606 ms/op
                 getUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16224
  mean =      1.998 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 266 
    [ 1.250,  2.500) = 14346 
    [ 2.500,  3.750) = 1514 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      3.223 ms/op
     p(99.9000) =     11.239 ms/op
     p(99.9900) =     11.606 ms/op
     p(99.9990) =     11.698 ms/op
     p(99.9999) =     11.698 ms/op
    p(100.0000) =     11.698 ms/op


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
# Warmup Iteration   1: 4.561 ±(99.9%) 0.172 ms/op
Iteration   1: 3.547 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   3.428 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  14.729 ms/op
                 listUser·p0.9999: 15.188 ms/op
                 listUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9001
  mean =      3.547 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 271 
    [ 2.500,  3.750) = 6183 
    [ 3.750,  5.000) = 2144 
    [ 5.000,  6.250) = 265 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      7.741 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     15.188 ms/op
     p(99.9990) =     15.188 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.722          ops/ms
ClientSimple.existUser                       thrpt         11.475          ops/ms
ClientSimple.getUser                         thrpt         12.410          ops/ms
ClientSimple.listUser                        thrpt          8.369          ops/ms
ClientSimple.createUser                       avgt          2.176           ms/op
ClientSimple.existUser                        avgt          1.697           ms/op
ClientSimple.getUser                          avgt          2.146           ms/op
ClientSimple.listUser                         avgt          3.328           ms/op
ClientSimple.createUser                     sample  12842   2.490 ± 0.077   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.634           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.150           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.780           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.452           ms/op
ClientSimple.createUser:createUser·p0.99    sample         13.058           ms/op
ClientSimple.createUser:createUser·p0.999   sample         51.053           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         54.771           ms/op
ClientSimple.createUser:createUser·p1.00    sample         55.050           ms/op
ClientSimple.existUser                      sample  16511   1.937 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.627           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.878           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.178           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.411           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.601           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.633           ms/op
ClientSimple.getUser                        sample  16224   1.998 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.672           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.972           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.499           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.223           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.239           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.606           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.698           ms/op
ClientSimple.listUser                       sample   9001   3.547 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.920           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.428           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.907           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.741           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.729           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.188           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.188           ms/op

Benchmark result is saved to 1718799318725.json
