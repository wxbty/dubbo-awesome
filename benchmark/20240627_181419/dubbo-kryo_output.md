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
# Warmup Iteration   1: 2.080 ops/ms
Iteration   1: 6.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.992 ops/ms


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
# Warmup Iteration   1: 6.561 ops/ms
Iteration   1: 10.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.780 ops/ms


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
# Warmup Iteration   1: 4.630 ops/ms
Iteration   1: 12.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.039 ops/ms


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
# Warmup Iteration   1: 4.135 ops/ms
Iteration   1: 8.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.219 ops/ms


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
# Warmup Iteration   1: 4.132 ±(99.9%) 0.087 ms/op
Iteration   1: 2.494 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.494 ms/op


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
# Warmup Iteration   1: 3.232 ±(99.9%) 0.055 ms/op
Iteration   1: 1.946 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.946 ms/op


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
# Warmup Iteration   1: 3.520 ±(99.9%) 0.067 ms/op
Iteration   1: 1.970 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.970 ms/op


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.107 ms/op
Iteration   1: 3.289 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.289 ms/op


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
# Warmup Iteration   1: 3.675 ±(99.9%) 0.086 ms/op
Iteration   1: 2.415 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   2.224 ms/op
                 createUser·p0.90:   2.851 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   7.383 ms/op
                 createUser·p0.999:  14.516 ms/op
                 createUser·p0.9999: 19.068 ms/op
                 createUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13236
  mean =      2.415 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9920 
    [ 2.500,  5.000) = 2981 
    [ 5.000,  7.500) = 208 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.224 ms/op
     p(90.0000) =      2.851 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      7.383 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     19.068 ms/op
     p(99.9990) =     20.447 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 3.099 ±(99.9%) 0.092 ms/op
Iteration   1: 1.891 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   1.718 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.601 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  16.876 ms/op
                 existUser·p0.9999: 17.031 ms/op
                 existUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16963
  mean =      1.891 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 269 
    [ 1.250,  2.500) = 15468 
    [ 2.500,  3.750) = 974 
    [ 3.750,  5.000) = 154 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      1.718 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     17.031 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 3.569 ±(99.9%) 0.099 ms/op
Iteration   1: 1.825 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   1.747 ms/op
                 getUser·p0.90:   2.175 ms/op
                 getUser·p0.95:   2.441 ms/op
                 getUser·p0.99:   4.169 ms/op
                 getUser·p0.999:  10.404 ms/op
                 getUser·p0.9999: 10.895 ms/op
                 getUser·p1.00:   10.895 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17513
  mean =      1.825 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 191 
    [ 1.250,  2.500) = 16622 
    [ 2.500,  3.750) = 502 
    [ 3.750,  5.000) = 121 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.175 ms/op
     p(95.0000) =      2.441 ms/op
     p(99.0000) =      4.169 ms/op
     p(99.9000) =     10.404 ms/op
     p(99.9900) =     10.895 ms/op
     p(99.9990) =     10.895 ms/op
     p(99.9999) =     10.895 ms/op
    p(100.0000) =     10.895 ms/op


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
# Warmup Iteration   1: 4.281 ±(99.9%) 0.152 ms/op
Iteration   1: 3.348 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.775 ms/op
                 listUser·p0.50:   3.109 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.128 ms/op
                 listUser·p0.999:  8.200 ms/op
                 listUser·p0.9999: 11.895 ms/op
                 listUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9539
  mean =      3.348 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 232 
    [ 2.500,  3.750) = 6771 
    [ 3.750,  5.000) = 2423 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =      8.200 ms/op
     p(99.9900) =     11.895 ms/op
     p(99.9990) =     11.895 ms/op
     p(99.9999) =     11.895 ms/op
    p(100.0000) =     11.895 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.992          ops/ms
ClientSimple.existUser                       thrpt         10.780          ops/ms
ClientSimple.getUser                         thrpt         12.039          ops/ms
ClientSimple.listUser                        thrpt          8.219          ops/ms
ClientSimple.createUser                       avgt          2.494           ms/op
ClientSimple.existUser                        avgt          1.946           ms/op
ClientSimple.getUser                          avgt          1.970           ms/op
ClientSimple.listUser                         avgt          3.289           ms/op
ClientSimple.createUser                     sample  13236   2.415 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.737           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.224           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.851           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.248           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.383           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.516           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.068           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.447           ms/op
ClientSimple.existUser                      sample  16963   1.891 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.717           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.718           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.489           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.876           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.031           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.236           ms/op
ClientSimple.getUser                        sample  17513   1.825 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.829           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.747           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.175           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.441           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.169           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.404           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.895           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.895           ms/op
ClientSimple.listUser                       sample   9539   3.348 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.775           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.109           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.128           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.200           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.895           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.895           ms/op

Benchmark result is saved to 1719511811199.json
