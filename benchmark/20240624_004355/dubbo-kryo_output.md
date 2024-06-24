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
# Warmup Iteration   1: 2.035 ops/ms
Iteration   1: 6.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.473 ops/ms


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
# Warmup Iteration   1: 6.007 ops/ms
Iteration   1: 12.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.202 ops/ms


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
# Warmup Iteration   1: 5.956 ops/ms
Iteration   1: 13.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.567 ops/ms


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
# Warmup Iteration   1: 5.166 ops/ms
Iteration   1: 8.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.286 ops/ms


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
# Warmup Iteration   1: 3.698 ±(99.9%) 0.063 ms/op
Iteration   1: 2.180 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.180 ms/op


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
# Warmup Iteration   1: 3.156 ±(99.9%) 0.056 ms/op
Iteration   1: 1.854 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.854 ms/op


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
# Warmup Iteration   1: 3.401 ±(99.9%) 0.055 ms/op
Iteration   1: 2.113 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.113 ms/op


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
# Warmup Iteration   1: 4.826 ±(99.9%) 0.112 ms/op
Iteration   1: 3.577 ±(99.9%) 0.021 ms/op


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
# Warmup Iteration   1: 3.734 ±(99.9%) 0.107 ms/op
Iteration   1: 2.071 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.450 ms/op
                 createUser·p0.50:   1.839 ms/op
                 createUser·p0.90:   2.339 ms/op
                 createUser·p0.95:   2.943 ms/op
                 createUser·p0.99:   9.861 ms/op
                 createUser·p0.999:  17.911 ms/op
                 createUser·p0.9999: 19.167 ms/op
                 createUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15410
  mean =      2.071 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 631 
    [ 1.250,  2.500) = 13758 
    [ 2.500,  3.750) = 558 
    [ 3.750,  5.000) = 135 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.943 ms/op
     p(99.0000) =      9.861 ms/op
     p(99.9000) =     17.911 ms/op
     p(99.9900) =     19.167 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.050 ±(99.9%) 0.073 ms/op
Iteration   1: 1.929 ±(99.9%) 0.041 ms/op
                 existUser·p0.00:   0.413 ms/op
                 existUser·p0.50:   1.675 ms/op
                 existUser·p0.90:   2.494 ms/op
                 existUser·p0.95:   2.740 ms/op
                 existUser·p0.99:   3.916 ms/op
                 existUser·p0.999:  33.306 ms/op
                 existUser·p0.9999: 33.642 ms/op
                 existUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16567
  mean =      1.929 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14938 
    [ 2.500,  5.000) = 1498 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.413 ms/op
     p(50.0000) =      1.675 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =     33.306 ms/op
     p(99.9900) =     33.642 ms/op
     p(99.9990) =     33.686 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 3.214 ±(99.9%) 0.072 ms/op
Iteration   1: 2.187 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   2.142 ms/op
                 getUser·p0.90:   2.687 ms/op
                 getUser·p0.95:   2.839 ms/op
                 getUser·p0.99:   3.334 ms/op
                 getUser·p0.999:  10.469 ms/op
                 getUser·p0.9999: 11.681 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14616
  mean =      2.187 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 11575 
    [ 2.500,  3.750) = 2848 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.142 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      3.334 ms/op
     p(99.9000) =     10.469 ms/op
     p(99.9900) =     11.681 ms/op
     p(99.9990) =     11.764 ms/op
     p(99.9999) =     11.764 ms/op
    p(100.0000) =     11.764 ms/op


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
# Warmup Iteration   1: 4.650 ±(99.9%) 0.166 ms/op
Iteration   1: 3.494 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   3.142 ms/op
                 listUser·p0.90:   4.287 ms/op
                 listUser·p0.95:   4.761 ms/op
                 listUser·p0.99:   11.489 ms/op
                 listUser·p0.999:  26.608 ms/op
                 listUser·p0.9999: 26.640 ms/op
                 listUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9196
  mean =      3.494 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 515 
    [ 2.500,  5.000) = 8336 
    [ 5.000,  7.500) = 239 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      4.287 ms/op
     p(95.0000) =      4.761 ms/op
     p(99.0000) =     11.489 ms/op
     p(99.9000) =     26.608 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.473          ops/ms
ClientSimple.existUser                       thrpt         12.202          ops/ms
ClientSimple.getUser                         thrpt         13.567          ops/ms
ClientSimple.listUser                        thrpt          8.286          ops/ms
ClientSimple.createUser                       avgt          2.180           ms/op
ClientSimple.existUser                        avgt          1.854           ms/op
ClientSimple.getUser                          avgt          2.113           ms/op
ClientSimple.listUser                         avgt          3.577           ms/op
ClientSimple.createUser                     sample  15410   2.071 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.450           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.839           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.339           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.943           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.861           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.911           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.167           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.202           ms/op
ClientSimple.existUser                      sample  16567   1.929 ± 0.041   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.413           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.675           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.740           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.916           ms/op
ClientSimple.existUser:existUser·p0.999     sample         33.306           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         33.642           ms/op
ClientSimple.existUser:existUser·p1.00      sample         33.686           ms/op
ClientSimple.getUser                        sample  14616   2.187 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.745           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.142           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.839           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.334           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.469           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.681           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.764           ms/op
ClientSimple.listUser                       sample   9196   3.494 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.035           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.142           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.287           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.761           ms/op
ClientSimple.listUser:listUser·p0.99        sample         11.489           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.608           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.640           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.640           ms/op

Benchmark result is saved to 1719189566722.json
