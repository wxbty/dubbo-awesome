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
# Warmup Iteration   1: 1.659 ops/ms
Iteration   1: 7.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.146 ops/ms


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
# Warmup Iteration   1: 5.516 ops/ms
Iteration   1: 12.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.292 ops/ms


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
# Warmup Iteration   1: 5.855 ops/ms
Iteration   1: 13.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.312 ops/ms


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
# Warmup Iteration   1: 4.476 ops/ms
Iteration   1: 8.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.459 ops/ms


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.067 ms/op
Iteration   1: 2.007 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.007 ms/op


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
# Warmup Iteration   1: 3.114 ±(99.9%) 0.045 ms/op
Iteration   1: 2.031 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.031 ms/op


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
# Warmup Iteration   1: 3.139 ±(99.9%) 0.059 ms/op
Iteration   1: 1.912 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.912 ms/op


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.077 ms/op
Iteration   1: 3.200 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.200 ms/op


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
# Warmup Iteration   1: 3.529 ±(99.9%) 0.083 ms/op
Iteration   1: 1.989 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   1.784 ms/op
                 createUser·p0.90:   2.302 ms/op
                 createUser·p0.95:   2.511 ms/op
                 createUser·p0.99:   8.258 ms/op
                 createUser·p0.999:  15.041 ms/op
                 createUser·p0.9999: 16.517 ms/op
                 createUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16079
  mean =      1.989 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 15185 
    [ 2.500,  3.750) = 562 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.511 ms/op
     p(99.0000) =      8.258 ms/op
     p(99.9000) =     15.041 ms/op
     p(99.9900) =     16.517 ms/op
     p(99.9990) =     16.597 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


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
# Warmup Iteration   1: 3.064 ±(99.9%) 0.086 ms/op
Iteration   1: 1.765 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   1.614 ms/op
                 existUser·p0.90:   2.150 ms/op
                 existUser·p0.95:   2.343 ms/op
                 existUser·p0.99:   3.346 ms/op
                 existUser·p0.999:  22.118 ms/op
                 existUser·p0.9999: 22.645 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18116
  mean =      1.765 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17644 
    [ 2.500,  5.000) = 439 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      1.614 ms/op
     p(90.0000) =      2.150 ms/op
     p(95.0000) =      2.343 ms/op
     p(99.0000) =      3.346 ms/op
     p(99.9000) =     22.118 ms/op
     p(99.9900) =     22.645 ms/op
     p(99.9990) =     23.364 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 3.355 ±(99.9%) 0.071 ms/op
Iteration   1: 2.283 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.439 ms/op
                 getUser·p0.50:   2.232 ms/op
                 getUser·p0.90:   2.781 ms/op
                 getUser·p0.95:   2.916 ms/op
                 getUser·p0.99:   3.712 ms/op
                 getUser·p0.999:  10.832 ms/op
                 getUser·p0.9999: 12.355 ms/op
                 getUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13972
  mean =      2.283 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 183 
    [ 1.250,  2.500) = 9583 
    [ 2.500,  3.750) = 4068 
    [ 3.750,  5.000) = 58 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      2.232 ms/op
     p(90.0000) =      2.781 ms/op
     p(95.0000) =      2.916 ms/op
     p(99.0000) =      3.712 ms/op
     p(99.9000) =     10.832 ms/op
     p(99.9900) =     12.355 ms/op
     p(99.9990) =     12.517 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


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
# Warmup Iteration   1: 4.653 ±(99.9%) 0.158 ms/op
Iteration   1: 3.154 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   6.242 ms/op
                 listUser·p0.999:  7.526 ms/op
                 listUser·p0.9999: 8.643 ms/op
                 listUser·p1.00:   8.651 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10133
  mean =      3.154 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 7 
    [1.500, 2.000) = 81 
    [2.000, 2.500) = 543 
    [2.500, 3.000) = 4636 
    [3.000, 3.500) = 2379 
    [3.500, 4.000) = 1763 
    [4.000, 4.500) = 480 
    [4.500, 5.000) = 71 
    [5.000, 5.500) = 19 
    [5.500, 6.000) = 39 
    [6.000, 6.500) = 26 
    [6.500, 7.000) = 20 
    [7.000, 7.500) = 54 
    [7.500, 8.000) = 11 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =      7.526 ms/op
     p(99.9900) =      8.643 ms/op
     p(99.9990) =      8.651 ms/op
     p(99.9999) =      8.651 ms/op
    p(100.0000) =      8.651 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.146          ops/ms
ClientSimple.existUser                       thrpt         12.292          ops/ms
ClientSimple.getUser                         thrpt         13.312          ops/ms
ClientSimple.listUser                        thrpt          8.459          ops/ms
ClientSimple.createUser                       avgt          2.007           ms/op
ClientSimple.existUser                        avgt          2.031           ms/op
ClientSimple.getUser                          avgt          1.912           ms/op
ClientSimple.listUser                         avgt          3.200           ms/op
ClientSimple.createUser                     sample  16079   1.989 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.976           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.784           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.302           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.511           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.258           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.041           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.517           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.597           ms/op
ClientSimple.existUser                      sample  18116   1.765 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.623           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.614           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.150           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.346           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.118           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.645           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.364           ms/op
ClientSimple.getUser                        sample  13972   2.283 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.439           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.232           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.781           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.916           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.712           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.832           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.355           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.517           ms/op
ClientSimple.listUser                       sample  10133   3.154 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.930           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.966           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.858           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.178           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.242           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.526           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.643           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.651           ms/op

Benchmark result is saved to 1717351869670.json
