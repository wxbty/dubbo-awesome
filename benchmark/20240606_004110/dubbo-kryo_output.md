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
# Warmup Iteration   1: 1.682 ops/ms
Iteration   1: 7.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.597 ops/ms


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
# Warmup Iteration   1: 5.966 ops/ms
Iteration   1: 12.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.618 ops/ms


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
# Warmup Iteration   1: 5.807 ops/ms
Iteration   1: 14.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.141 ops/ms


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
# Warmup Iteration   1: 5.600 ops/ms
Iteration   1: 8.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.904 ops/ms


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
# Warmup Iteration   1: 3.761 ±(99.9%) 0.067 ms/op
Iteration   1: 2.210 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.210 ms/op


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
# Warmup Iteration   1: 3.149 ±(99.9%) 0.055 ms/op
Iteration   1: 2.134 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.134 ms/op


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
# Warmup Iteration   1: 3.680 ±(99.9%) 0.057 ms/op
Iteration   1: 2.291 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.291 ms/op


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
# Warmup Iteration   1: 4.393 ±(99.9%) 0.095 ms/op
Iteration   1: 3.494 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.494 ms/op


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
# Warmup Iteration   1: 3.583 ±(99.9%) 0.090 ms/op
Iteration   1: 2.230 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   2.034 ms/op
                 createUser·p0.90:   2.478 ms/op
                 createUser·p0.95:   2.904 ms/op
                 createUser·p0.99:   7.152 ms/op
                 createUser·p0.999:  36.569 ms/op
                 createUser·p0.9999: 37.102 ms/op
                 createUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14344
  mean =      2.230 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13004 
    [ 2.500,  5.000) = 1160 
    [ 5.000,  7.500) = 68 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     36.569 ms/op
     p(99.9900) =     37.102 ms/op
     p(99.9990) =     37.159 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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
# Warmup Iteration   1: 3.148 ±(99.9%) 0.072 ms/op
Iteration   1: 2.134 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.464 ms/op
                 existUser·p0.50:   2.064 ms/op
                 existUser·p0.90:   2.671 ms/op
                 existUser·p0.95:   2.905 ms/op
                 existUser·p0.99:   4.181 ms/op
                 existUser·p0.999:  15.745 ms/op
                 existUser·p0.9999: 15.933 ms/op
                 existUser·p1.00:   15.942 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14976
  mean =      2.134 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 269 
    [ 1.250,  2.500) = 12330 
    [ 2.500,  3.750) = 2162 
    [ 3.750,  5.000) = 120 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.905 ms/op
     p(99.0000) =      4.181 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     15.933 ms/op
     p(99.9990) =     15.942 ms/op
     p(99.9999) =     15.942 ms/op
    p(100.0000) =     15.942 ms/op


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
# Warmup Iteration   1: 3.592 ±(99.9%) 0.094 ms/op
Iteration   1: 2.302 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   2.232 ms/op
                 getUser·p0.90:   2.826 ms/op
                 getUser·p0.95:   3.047 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  11.165 ms/op
                 getUser·p0.9999: 12.125 ms/op
                 getUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13930
  mean =      2.302 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 10158 
    [ 2.500,  3.750) = 3469 
    [ 3.750,  5.000) = 115 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.232 ms/op
     p(90.0000) =      2.826 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =     11.165 ms/op
     p(99.9900) =     12.125 ms/op
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
# Warmup Iteration   1: 4.637 ±(99.9%) 0.123 ms/op
Iteration   1: 3.869 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.468 ms/op
                 listUser·p0.99:   8.090 ms/op
                 listUser·p0.999:  19.333 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8269
  mean =      3.869 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 669 
    [ 2.500,  3.750) = 3458 
    [ 3.750,  5.000) = 3553 
    [ 5.000,  6.250) = 264 
    [ 6.250,  7.500) = 182 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.468 ms/op
     p(99.0000) =      8.090 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.597          ops/ms
ClientSimple.existUser                       thrpt         12.618          ops/ms
ClientSimple.getUser                         thrpt         14.141          ops/ms
ClientSimple.listUser                        thrpt          8.904          ops/ms
ClientSimple.createUser                       avgt          2.210           ms/op
ClientSimple.existUser                        avgt          2.134           ms/op
ClientSimple.getUser                          avgt          2.291           ms/op
ClientSimple.listUser                         avgt          3.494           ms/op
ClientSimple.createUser                     sample  14344   2.230 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.665           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.034           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.478           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.152           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.569           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.102           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.159           ms/op
ClientSimple.existUser                      sample  14976   2.134 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.464           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.064           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.671           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.905           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.181           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.745           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.933           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.942           ms/op
ClientSimple.getUser                        sample  13930   2.302 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.744           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.232           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.826           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.047           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.399           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.165           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.125           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.190           ms/op
ClientSimple.listUser                       sample   8269   3.869 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.106           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.752           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.468           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.090           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.333           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.366           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.366           ms/op

Benchmark result is saved to 1717634216133.json
