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
# Warmup Iteration   1: 1.855 ops/ms
Iteration   1: 7.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.551 ops/ms


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
# Warmup Iteration   1: 6.291 ops/ms
Iteration   1: 13.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.551 ops/ms


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
# Warmup Iteration   1: 6.025 ops/ms
Iteration   1: 12.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.297 ops/ms


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
# Warmup Iteration   1: 5.066 ops/ms
Iteration   1: 8.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.122 ops/ms


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
# Warmup Iteration   1: 4.369 ±(99.9%) 0.074 ms/op
Iteration   1: 2.308 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.308 ms/op


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
# Warmup Iteration   1: 3.061 ±(99.9%) 0.056 ms/op
Iteration   1: 1.714 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.714 ms/op


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
# Warmup Iteration   1: 3.172 ±(99.9%) 0.059 ms/op
Iteration   1: 2.122 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.122 ms/op


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
# Warmup Iteration   1: 4.747 ±(99.9%) 0.121 ms/op
Iteration   1: 3.516 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.516 ms/op


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
# Warmup Iteration   1: 3.698 ±(99.9%) 0.090 ms/op
Iteration   1: 2.199 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.463 ms/op
                 createUser·p0.50:   2.032 ms/op
                 createUser·p0.90:   2.773 ms/op
                 createUser·p0.95:   2.978 ms/op
                 createUser·p0.99:   4.771 ms/op
                 createUser·p0.999:  23.921 ms/op
                 createUser·p0.9999: 24.433 ms/op
                 createUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14556
  mean =      2.199 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11563 
    [ 2.500,  5.000) = 2857 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.773 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      4.771 ms/op
     p(99.9000) =     23.921 ms/op
     p(99.9900) =     24.433 ms/op
     p(99.9990) =     24.478 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 2.900 ±(99.9%) 0.062 ms/op
Iteration   1: 1.827 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   1.751 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.433 ms/op
                 existUser·p0.99:   3.351 ms/op
                 existUser·p0.999:  10.494 ms/op
                 existUser·p0.9999: 11.162 ms/op
                 existUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17497
  mean =      1.827 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 426 
    [ 1.250,  2.500) = 16363 
    [ 2.500,  3.750) = 610 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      1.751 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.433 ms/op
     p(99.0000) =      3.351 ms/op
     p(99.9000) =     10.494 ms/op
     p(99.9900) =     11.162 ms/op
     p(99.9990) =     11.272 ms/op
     p(99.9999) =     11.272 ms/op
    p(100.0000) =     11.272 ms/op


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
# Warmup Iteration   1: 3.258 ±(99.9%) 0.103 ms/op
Iteration   1: 1.828 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   1.661 ms/op
                 getUser·p0.90:   2.384 ms/op
                 getUser·p0.95:   2.580 ms/op
                 getUser·p0.99:   3.195 ms/op
                 getUser·p0.999:  16.573 ms/op
                 getUser·p0.9999: 16.955 ms/op
                 getUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17804
  mean =      1.828 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 355 
    [ 1.250,  2.500) = 16270 
    [ 2.500,  3.750) = 1093 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      1.661 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      3.195 ms/op
     p(99.9000) =     16.573 ms/op
     p(99.9900) =     16.955 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 4.402 ±(99.9%) 0.140 ms/op
Iteration   1: 3.635 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.763 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8941
  mean =      3.635 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 493 
    [ 2.500,  3.750) = 4589 
    [ 3.750,  5.000) = 3515 
    [ 5.000,  6.250) = 235 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.763 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     17.957 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.551          ops/ms
ClientSimple.existUser                       thrpt         13.551          ops/ms
ClientSimple.getUser                         thrpt         12.297          ops/ms
ClientSimple.listUser                        thrpt          8.122          ops/ms
ClientSimple.createUser                       avgt          2.308           ms/op
ClientSimple.existUser                        avgt          1.714           ms/op
ClientSimple.getUser                          avgt          2.122           ms/op
ClientSimple.listUser                         avgt          3.516           ms/op
ClientSimple.createUser                     sample  14556   2.199 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.463           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.032           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.773           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.978           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.771           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.921           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.433           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.478           ms/op
ClientSimple.existUser                      sample  17497   1.827 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.673           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.751           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.351           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.494           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.162           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.272           ms/op
ClientSimple.getUser                        sample  17804   1.828 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.584           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.661           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.384           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.195           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.573           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.955           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.007           ms/op
ClientSimple.listUser                       sample   8941   3.635 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.104           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.555           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.833           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.763           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.793           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.957           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.957           ms/op

Benchmark result is saved to 1718108143624.json
