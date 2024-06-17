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
# Warmup Iteration   1: 1.914 ops/ms
Iteration   1: 7.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.161 ops/ms


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
# Warmup Iteration   1: 6.432 ops/ms
Iteration   1: 13.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.033 ops/ms


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
# Warmup Iteration   1: 6.130 ops/ms
Iteration   1: 13.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.321 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.561 ops/ms
Iteration   1: 8.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.093 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.875 ±(99.9%) 0.070 ms/op
Iteration   1: 2.255 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.255 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.693 ±(99.9%) 0.062 ms/op
Iteration   1: 1.868 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.868 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.248 ±(99.9%) 0.054 ms/op
Iteration   1: 1.984 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.984 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.220 ±(99.9%) 0.080 ms/op
Iteration   1: 3.598 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.598 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.745 ±(99.9%) 0.130 ms/op
Iteration   1: 2.264 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.607 ms/op
                 createUser·p0.50:   2.077 ms/op
                 createUser·p0.90:   2.552 ms/op
                 createUser·p0.95:   2.851 ms/op
                 createUser·p0.99:   10.306 ms/op
                 createUser·p0.999:  19.464 ms/op
                 createUser·p0.9999: 20.018 ms/op
                 createUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14179
  mean =      2.264 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12429 
    [ 2.500,  5.000) = 1459 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.077 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =     10.306 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     20.018 ms/op
     p(99.9990) =     20.087 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.826 ±(99.9%) 0.064 ms/op
Iteration   1: 1.918 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.281 ms/op
                 existUser·p0.50:   1.845 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   3.043 ms/op
                 existUser·p0.999:  17.378 ms/op
                 existUser·p0.9999: 18.547 ms/op
                 existUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16660
  mean =      1.918 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1131 
    [ 1.250,  2.500) = 14118 
    [ 2.500,  3.750) = 1300 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.281 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.043 ms/op
     p(99.9000) =     17.378 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     18.678 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 3.363 ±(99.9%) 0.086 ms/op
Iteration   1: 2.162 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.612 ms/op
                 getUser·p0.50:   2.122 ms/op
                 getUser·p0.90:   2.609 ms/op
                 getUser·p0.95:   2.753 ms/op
                 getUser·p0.99:   3.757 ms/op
                 getUser·p0.999:  10.620 ms/op
                 getUser·p0.9999: 10.946 ms/op
                 getUser·p1.00:   10.977 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14833
  mean =      2.162 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 12453 
    [ 2.500,  3.750) = 2104 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      3.757 ms/op
     p(99.9000) =     10.620 ms/op
     p(99.9900) =     10.946 ms/op
     p(99.9990) =     10.977 ms/op
     p(99.9999) =     10.977 ms/op
    p(100.0000) =     10.977 ms/op


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
# Warmup Iteration   1: 5.014 ±(99.9%) 0.340 ms/op
Iteration   1: 3.732 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   10.378 ms/op
                 listUser·p0.999:  22.160 ms/op
                 listUser·p0.9999: 22.839 ms/op
                 listUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8579
  mean =      3.732 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 665 
    [ 2.500,  5.000) = 7527 
    [ 5.000,  7.500) = 242 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =     10.378 ms/op
     p(99.9000) =     22.160 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     22.839 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.161          ops/ms
ClientSimple.existUser                       thrpt         13.033          ops/ms
ClientSimple.getUser                         thrpt         13.321          ops/ms
ClientSimple.listUser                        thrpt          8.093          ops/ms
ClientSimple.createUser                       avgt          2.255           ms/op
ClientSimple.existUser                        avgt          1.868           ms/op
ClientSimple.getUser                          avgt          1.984           ms/op
ClientSimple.listUser                         avgt          3.598           ms/op
ClientSimple.createUser                     sample  14179   2.264 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.607           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.077           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.552           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.851           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.306           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.464           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.018           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.087           ms/op
ClientSimple.existUser                      sample  16660   1.918 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.281           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.845           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.043           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.378           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.547           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.678           ms/op
ClientSimple.getUser                        sample  14833   2.162 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.612           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.122           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.753           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.757           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.620           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.946           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.977           ms/op
ClientSimple.listUser                       sample   8579   3.732 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.157           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.580           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.956           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.378           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.160           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.839           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.839           ms/op

Benchmark result is saved to 1718604762295.json
