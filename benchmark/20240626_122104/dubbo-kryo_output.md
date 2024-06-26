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
# Warmup Iteration   1: 1.011 ops/ms
Iteration   1: 6.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.277 ops/ms


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
# Warmup Iteration   1: 6.295 ops/ms
Iteration   1: 12.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.085 ops/ms


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
# Warmup Iteration   1: 5.460 ops/ms
Iteration   1: 11.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.775 ops/ms


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
# Warmup Iteration   1: 4.677 ops/ms
Iteration   1: 9.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.178 ops/ms


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.063 ms/op
Iteration   1: 2.210 ±(99.9%) 0.013 ms/op


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
# Warmup Iteration   1: 3.361 ±(99.9%) 0.059 ms/op
Iteration   1: 1.945 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.945 ms/op


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
# Warmup Iteration   1: 3.469 ±(99.9%) 0.089 ms/op
Iteration   1: 2.161 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.161 ms/op


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
# Warmup Iteration   1: 4.393 ±(99.9%) 0.087 ms/op
Iteration   1: 3.222 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.222 ms/op


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
# Warmup Iteration   1: 3.714 ±(99.9%) 0.115 ms/op
Iteration   1: 2.149 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   1.980 ms/op
                 createUser·p0.90:   2.683 ms/op
                 createUser·p0.95:   2.860 ms/op
                 createUser·p0.99:   4.367 ms/op
                 createUser·p0.999:  14.074 ms/op
                 createUser·p0.9999: 16.409 ms/op
                 createUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14896
  mean =      2.149 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 12143 
    [ 2.500,  3.750) = 2461 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.860 ms/op
     p(99.0000) =      4.367 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     16.409 ms/op
     p(99.9990) =     16.417 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


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
# Warmup Iteration   1: 3.176 ±(99.9%) 0.080 ms/op
Iteration   1: 2.219 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.360 ms/op
                 existUser·p0.50:   2.101 ms/op
                 existUser·p0.90:   2.651 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   6.377 ms/op
                 existUser·p0.999:  16.081 ms/op
                 existUser·p0.9999: 17.760 ms/op
                 existUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14486
  mean =      2.219 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 318 
    [ 1.250,  2.500) = 12078 
    [ 2.500,  3.750) = 1579 
    [ 3.750,  5.000) = 218 
    [ 5.000,  6.250) = 113 
    [ 6.250,  7.500) = 130 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.360 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.651 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      6.377 ms/op
     p(99.9000) =     16.081 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.087 ms/op
Iteration   1: 1.901 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.607 ms/op
                 getUser·p0.50:   1.741 ms/op
                 getUser·p0.90:   2.564 ms/op
                 getUser·p0.95:   2.818 ms/op
                 getUser·p0.99:   3.436 ms/op
                 getUser·p0.999:  10.260 ms/op
                 getUser·p0.9999: 11.752 ms/op
                 getUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16806
  mean =      1.901 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 661 
    [ 1.250,  2.500) = 14200 
    [ 2.500,  3.750) = 1809 
    [ 3.750,  5.000) = 56 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      1.741 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      3.436 ms/op
     p(99.9000) =     10.260 ms/op
     p(99.9900) =     11.752 ms/op
     p(99.9990) =     11.796 ms/op
     p(99.9999) =     11.796 ms/op
    p(100.0000) =     11.796 ms/op


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
# Warmup Iteration   1: 5.331 ±(99.9%) 0.205 ms/op
Iteration   1: 3.485 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   3.355 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  24.707 ms/op
                 listUser·p0.9999: 25.264 ms/op
                 listUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9166
  mean =      3.485 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 825 
    [ 2.500,  5.000) = 8041 
    [ 5.000,  7.500) = 204 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      9.912 ms/op
     p(99.9000) =     24.707 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.277          ops/ms
ClientSimple.existUser                       thrpt         12.085          ops/ms
ClientSimple.getUser                         thrpt         11.775          ops/ms
ClientSimple.listUser                        thrpt          9.178          ops/ms
ClientSimple.createUser                       avgt          2.210           ms/op
ClientSimple.existUser                        avgt          1.945           ms/op
ClientSimple.getUser                          avgt          2.161           ms/op
ClientSimple.listUser                         avgt          3.222           ms/op
ClientSimple.createUser                     sample  14896   2.149 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.842           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.980           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.683           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.860           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.367           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.074           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.409           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.417           ms/op
ClientSimple.existUser                      sample  14486   2.219 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.360           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.101           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.651           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.117           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.377           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.081           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.760           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.760           ms/op
ClientSimple.getUser                        sample  16806   1.901 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.607           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.741           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.564           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.818           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.436           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.260           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.752           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.796           ms/op
ClientSimple.listUser                       sample   9166   3.485 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.854           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.355           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.628           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.912           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.707           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.264           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.264           ms/op

Benchmark result is saved to 1719404183605.json
