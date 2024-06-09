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
# Warmup Iteration   1: 1.579 ops/ms
Iteration   1: 6.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.383 ops/ms


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
# Warmup Iteration   1: 5.615 ops/ms
Iteration   1: 11.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.992 ops/ms


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
# Warmup Iteration   1: 6.135 ops/ms
Iteration   1: 13.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.341 ops/ms


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
# Warmup Iteration   1: 3.713 ops/ms
Iteration   1: 8.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.251 ops/ms


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
# Warmup Iteration   1: 4.399 ±(99.9%) 0.070 ms/op
Iteration   1: 2.411 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.411 ms/op


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
# Warmup Iteration   1: 3.584 ±(99.9%) 0.063 ms/op
Iteration   1: 1.930 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.930 ms/op


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
# Warmup Iteration   1: 3.351 ±(99.9%) 0.056 ms/op
Iteration   1: 2.026 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.026 ms/op


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
# Warmup Iteration   1: 4.692 ±(99.9%) 0.086 ms/op
Iteration   1: 3.448 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.448 ms/op


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
# Warmup Iteration   1: 3.567 ±(99.9%) 0.093 ms/op
Iteration   1: 2.211 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   2.054 ms/op
                 createUser·p0.90:   2.642 ms/op
                 createUser·p0.95:   2.906 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  23.462 ms/op
                 createUser·p0.9999: 27.582 ms/op
                 createUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14450
  mean =      2.211 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12100 
    [ 2.500,  5.000) = 2130 
    [ 5.000,  7.500) = 124 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.906 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     23.462 ms/op
     p(99.9900) =     27.582 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 3.537 ±(99.9%) 0.083 ms/op
Iteration   1: 2.086 ±(99.9%) 0.044 ms/op
                 existUser·p0.00:   0.476 ms/op
                 existUser·p0.50:   1.927 ms/op
                 existUser·p0.90:   2.589 ms/op
                 existUser·p0.95:   2.855 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  32.295 ms/op
                 existUser·p0.9999: 32.801 ms/op
                 existUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15432
  mean =      2.086 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13416 
    [ 2.500,  5.000) = 1822 
    [ 5.000,  7.500) = 64 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      1.927 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     32.295 ms/op
     p(99.9900) =     32.801 ms/op
     p(99.9990) =     32.801 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 3.207 ±(99.9%) 0.079 ms/op
Iteration   1: 2.037 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.498 ms/op
                 getUser·p0.50:   1.980 ms/op
                 getUser·p0.90:   2.478 ms/op
                 getUser·p0.95:   2.683 ms/op
                 getUser·p0.99:   3.828 ms/op
                 getUser·p0.999:  13.058 ms/op
                 getUser·p0.9999: 13.381 ms/op
                 getUser·p1.00:   13.418 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15744
  mean =      2.037 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 158 
    [ 1.250,  2.500) = 14125 
    [ 2.500,  3.750) = 1302 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      3.828 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     13.381 ms/op
     p(99.9990) =     13.418 ms/op
     p(99.9999) =     13.418 ms/op
    p(100.0000) =     13.418 ms/op


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
# Warmup Iteration   1: 4.279 ±(99.9%) 0.114 ms/op
Iteration   1: 3.422 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.244 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.304 ms/op
                 listUser·p0.999:  21.976 ms/op
                 listUser·p0.9999: 22.708 ms/op
                 listUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9345
  mean =      3.422 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 423 
    [ 2.500,  5.000) = 8662 
    [ 5.000,  7.500) = 228 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.304 ms/op
     p(99.9000) =     21.976 ms/op
     p(99.9900) =     22.708 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.383          ops/ms
ClientSimple.existUser                       thrpt         11.992          ops/ms
ClientSimple.getUser                         thrpt         13.341          ops/ms
ClientSimple.listUser                        thrpt          8.251          ops/ms
ClientSimple.createUser                       avgt          2.411           ms/op
ClientSimple.existUser                        avgt          1.930           ms/op
ClientSimple.getUser                          avgt          2.026           ms/op
ClientSimple.listUser                         avgt          3.448           ms/op
ClientSimple.createUser                     sample  14450   2.211 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.796           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.054           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.642           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.906           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.136           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.462           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.582           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.180           ms/op
ClientSimple.existUser                      sample  15432   2.086 ± 0.044   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.476           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.927           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.855           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.169           ms/op
ClientSimple.existUser:existUser·p0.999     sample         32.295           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         32.801           ms/op
ClientSimple.existUser:existUser·p1.00      sample         32.801           ms/op
ClientSimple.getUser                        sample  15744   2.037 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.498           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.980           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.828           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.058           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.381           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.418           ms/op
ClientSimple.listUser                       sample   9345   3.422 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.059           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.244           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.170           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.547           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.304           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.976           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.708           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.708           ms/op

Benchmark result is saved to 1717956600207.json
