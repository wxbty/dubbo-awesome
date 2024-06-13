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
# Warmup Iteration   1: 1.868 ops/ms
Iteration   1: 6.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.582 ops/ms


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
# Warmup Iteration   1: 6.119 ops/ms
Iteration   1: 12.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.388 ops/ms


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
# Warmup Iteration   1: 5.120 ops/ms
Iteration   1: 13.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.273 ops/ms


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
# Warmup Iteration   1: 4.886 ops/ms
Iteration   1: 8.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.842 ops/ms


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.078 ms/op
Iteration   1: 2.384 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.384 ms/op


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
# Warmup Iteration   1: 3.003 ±(99.9%) 0.056 ms/op
Iteration   1: 1.828 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.828 ms/op


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
# Warmup Iteration   1: 3.398 ±(99.9%) 0.061 ms/op
Iteration   1: 2.087 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.087 ms/op


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
# Warmup Iteration   1: 4.585 ±(99.9%) 0.112 ms/op
Iteration   1: 3.409 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.409 ms/op


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
# Warmup Iteration   1: 3.605 ±(99.9%) 0.084 ms/op
Iteration   1: 2.162 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   1.985 ms/op
                 createUser·p0.90:   2.662 ms/op
                 createUser·p0.95:   2.908 ms/op
                 createUser·p0.99:   8.184 ms/op
                 createUser·p0.999:  19.144 ms/op
                 createUser·p0.9999: 21.546 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14785
  mean =      2.162 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12579 
    [ 2.500,  5.000) = 1863 
    [ 5.000,  7.500) = 164 
    [ 7.500, 10.000) = 144 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      8.184 ms/op
     p(99.9000) =     19.144 ms/op
     p(99.9900) =     21.546 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 3.133 ±(99.9%) 0.078 ms/op
Iteration   1: 2.001 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   1.905 ms/op
                 existUser·p0.90:   2.478 ms/op
                 existUser·p0.95:   2.658 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  14.713 ms/op
                 existUser·p0.9999: 15.398 ms/op
                 existUser·p1.00:   15.417 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15979
  mean =      2.001 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 403 
    [ 1.250,  2.500) = 14096 
    [ 2.500,  3.750) = 1250 
    [ 3.750,  5.000) = 126 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     15.398 ms/op
     p(99.9990) =     15.417 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


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
# Warmup Iteration   1: 3.403 ±(99.9%) 0.081 ms/op
Iteration   1: 1.938 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   1.864 ms/op
                 getUser·p0.90:   2.302 ms/op
                 getUser·p0.95:   2.560 ms/op
                 getUser·p0.99:   3.094 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 12.179 ms/op
                 getUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16483
  mean =      1.938 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 15449 
    [ 2.500,  3.750) = 921 
    [ 3.750,  5.000) = 8 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      3.094 ms/op
     p(99.9000) =     12.042 ms/op
     p(99.9900) =     12.179 ms/op
     p(99.9990) =     12.190 ms/op
     p(99.9999) =     12.190 ms/op
    p(100.0000) =     12.190 ms/op


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
# Warmup Iteration   1: 5.201 ±(99.9%) 0.148 ms/op
Iteration   1: 3.730 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.896 ms/op
                 listUser·p0.999:  14.211 ms/op
                 listUser·p0.9999: 16.761 ms/op
                 listUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8604
  mean =      3.730 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 347 
    [ 2.500,  3.750) = 4404 
    [ 3.750,  5.000) = 3464 
    [ 5.000,  6.250) = 153 
    [ 6.250,  7.500) = 127 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.896 ms/op
     p(99.9000) =     14.211 ms/op
     p(99.9900) =     16.761 ms/op
     p(99.9990) =     16.761 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.582          ops/ms
ClientSimple.existUser                       thrpt         12.388          ops/ms
ClientSimple.getUser                         thrpt         13.273          ops/ms
ClientSimple.listUser                        thrpt          8.842          ops/ms
ClientSimple.createUser                       avgt          2.384           ms/op
ClientSimple.existUser                        avgt          1.828           ms/op
ClientSimple.getUser                          avgt          2.087           ms/op
ClientSimple.listUser                         avgt          3.409           ms/op
ClientSimple.createUser                     sample  14785   2.162 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.657           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.985           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.908           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.184           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.144           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.546           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.675           ms/op
ClientSimple.existUser                      sample  15979   2.001 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.647           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.905           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.658           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.432           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.713           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.398           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.417           ms/op
ClientSimple.getUser                        sample  16483   1.938 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.799           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.864           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.302           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.094           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.042           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.179           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.190           ms/op
ClientSimple.listUser                       sample   8604   3.730 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.145           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.674           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.858           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.896           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.211           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.761           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.761           ms/op

Benchmark result is saved to 1718302270234.json
