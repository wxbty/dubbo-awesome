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
# Warmup Iteration   1: 2.009 ops/ms
Iteration   1: 6.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.777 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 7.095 ops/ms
Iteration   1: 11.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.598 ops/ms


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
# Warmup Iteration   1: 5.607 ops/ms
Iteration   1: 12.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.714 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.133 ops/ms
Iteration   1: 8.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.732 ops/ms


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
# Warmup Iteration   1: 4.048 ±(99.9%) 0.065 ms/op
Iteration   1: 1.988 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.988 ms/op


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
# Warmup Iteration   1: 3.558 ±(99.9%) 0.056 ms/op
Iteration   1: 2.016 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.016 ms/op


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
# Warmup Iteration   1: 3.347 ±(99.9%) 0.058 ms/op
Iteration   1: 1.847 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.847 ms/op


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
# Warmup Iteration   1: 4.584 ±(99.9%) 0.100 ms/op
Iteration   1: 3.231 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.231 ms/op


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
# Warmup Iteration   1: 3.425 ±(99.9%) 0.084 ms/op
Iteration   1: 2.560 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.649 ms/op
                 createUser·p0.50:   2.433 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   6.529 ms/op
                 createUser·p0.999:  23.036 ms/op
                 createUser·p0.9999: 23.192 ms/op
                 createUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12472
  mean =      2.560 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7126 
    [ 2.500,  5.000) = 5140 
    [ 5.000,  7.500) = 140 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.277 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     23.036 ms/op
     p(99.9900) =     23.192 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 3.152 ±(99.9%) 0.084 ms/op
Iteration   1: 2.121 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.550 ms/op
                 existUser·p0.50:   2.023 ms/op
                 existUser·p0.90:   2.572 ms/op
                 existUser·p0.95:   2.757 ms/op
                 existUser·p0.99:   3.708 ms/op
                 existUser·p0.999:  19.452 ms/op
                 existUser·p0.9999: 20.538 ms/op
                 existUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15359
  mean =      2.121 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13173 
    [ 2.500,  5.000) = 2087 
    [ 5.000,  7.500) = 35 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      3.708 ms/op
     p(99.9000) =     19.452 ms/op
     p(99.9900) =     20.538 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.881 ±(99.9%) 0.252 ms/op
Iteration   1: 1.970 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.388 ms/op
                 getUser·p0.50:   1.925 ms/op
                 getUser·p0.90:   2.433 ms/op
                 getUser·p0.95:   2.658 ms/op
                 getUser·p0.99:   3.424 ms/op
                 getUser·p0.999:  10.875 ms/op
                 getUser·p0.9999: 11.072 ms/op
                 getUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16231
  mean =      1.970 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 688 
    [ 1.250,  2.500) = 14200 
    [ 2.500,  3.750) = 1242 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 2 
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
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      1.925 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      3.424 ms/op
     p(99.9000) =     10.875 ms/op
     p(99.9900) =     11.072 ms/op
     p(99.9990) =     11.092 ms/op
     p(99.9999) =     11.092 ms/op
    p(100.0000) =     11.092 ms/op


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.146 ms/op
Iteration   1: 3.567 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.034 ms/op
                 listUser·p0.50:   3.490 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  12.237 ms/op
                 listUser·p0.9999: 12.567 ms/op
                 listUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9097
  mean =      3.567 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 199 
    [ 2.500,  3.750) = 5612 
    [ 3.750,  5.000) = 2950 
    [ 5.000,  6.250) = 183 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     12.237 ms/op
     p(99.9900) =     12.567 ms/op
     p(99.9990) =     12.567 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.777          ops/ms
ClientSimple.existUser                       thrpt         11.598          ops/ms
ClientSimple.getUser                         thrpt         12.714          ops/ms
ClientSimple.listUser                        thrpt          8.732          ops/ms
ClientSimple.createUser                       avgt          1.988           ms/op
ClientSimple.existUser                        avgt          2.016           ms/op
ClientSimple.getUser                          avgt          1.847           ms/op
ClientSimple.listUser                         avgt          3.231           ms/op
ClientSimple.createUser                     sample  12472   2.560 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.649           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.433           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.027           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.277           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.529           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.036           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.192           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.200           ms/op
ClientSimple.existUser                      sample  15359   2.121 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.550           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.023           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.572           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.757           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.708           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.452           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.538           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.644           ms/op
ClientSimple.getUser                        sample  16231   1.970 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.388           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.925           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.433           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.424           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.875           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.072           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.092           ms/op
ClientSimple.listUser                       sample   9097   3.567 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.034           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.490           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.825           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.545           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.237           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.567           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.567           ms/op

Benchmark result is saved to 1719166220981.json
