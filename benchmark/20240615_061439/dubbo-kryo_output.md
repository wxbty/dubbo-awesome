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
# Warmup Iteration   1: 1.006 ops/ms
Iteration   1: 6.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.807 ops/ms


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
# Warmup Iteration   1: 6.230 ops/ms
Iteration   1: 13.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.095 ops/ms


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
# Warmup Iteration   1: 6.934 ops/ms
Iteration   1: 14.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.014 ops/ms


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
# Warmup Iteration   1: 5.795 ops/ms
Iteration   1: 8.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.425 ops/ms


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.066 ms/op
Iteration   1: 2.052 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.052 ms/op


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
# Warmup Iteration   1: 3.166 ±(99.9%) 0.050 ms/op
Iteration   1: 1.774 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.774 ms/op


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
# Warmup Iteration   1: 3.067 ±(99.9%) 0.050 ms/op
Iteration   1: 1.917 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.917 ms/op


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
# Warmup Iteration   1: 4.530 ±(99.9%) 0.090 ms/op
Iteration   1: 3.309 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.309 ms/op


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
# Warmup Iteration   1: 3.493 ±(99.9%) 0.081 ms/op
Iteration   1: 1.945 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.522 ms/op
                 createUser·p0.50:   1.782 ms/op
                 createUser·p0.90:   2.273 ms/op
                 createUser·p0.95:   2.594 ms/op
                 createUser·p0.99:   6.835 ms/op
                 createUser·p0.999:  17.450 ms/op
                 createUser·p0.9999: 23.724 ms/op
                 createUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16473
  mean =      1.945 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15495 
    [ 2.500,  5.000) = 748 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      1.782 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.594 ms/op
     p(99.0000) =      6.835 ms/op
     p(99.9000) =     17.450 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 3.093 ±(99.9%) 0.094 ms/op
Iteration   1: 1.903 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   1.853 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.494 ms/op
                 existUser·p0.99:   3.138 ms/op
                 existUser·p0.999:  12.898 ms/op
                 existUser·p0.9999: 13.042 ms/op
                 existUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16798
  mean =      1.903 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 571 
    [ 1.250,  2.500) = 15405 
    [ 2.500,  3.750) = 711 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      3.138 ms/op
     p(99.9000) =     12.898 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     13.042 ms/op
     p(99.9999) =     13.042 ms/op
    p(100.0000) =     13.042 ms/op


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
# Warmup Iteration   1: 3.152 ±(99.9%) 0.075 ms/op
Iteration   1: 2.159 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.539 ms/op
                 getUser·p0.50:   2.126 ms/op
                 getUser·p0.90:   2.671 ms/op
                 getUser·p0.95:   2.806 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  18.612 ms/op
                 getUser·p0.9999: 18.940 ms/op
                 getUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14928
  mean =      2.159 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 369 
    [ 1.250,  2.500) = 11363 
    [ 2.500,  3.750) = 3059 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.126 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     18.940 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 4.551 ±(99.9%) 0.116 ms/op
Iteration   1: 3.065 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   0.536 ms/op
                 listUser·p0.50:   2.855 ms/op
                 listUser·p0.90:   3.736 ms/op
                 listUser·p0.95:   3.932 ms/op
                 listUser·p0.99:   4.817 ms/op
                 listUser·p0.999:  19.005 ms/op
                 listUser·p0.9999: 19.232 ms/op
                 listUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10462
  mean =      3.065 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 623 
    [ 2.500,  3.750) = 8834 
    [ 3.750,  5.000) = 912 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =     19.005 ms/op
     p(99.9900) =     19.232 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.807          ops/ms
ClientSimple.existUser                       thrpt         13.095          ops/ms
ClientSimple.getUser                         thrpt         14.014          ops/ms
ClientSimple.listUser                        thrpt          8.425          ops/ms
ClientSimple.createUser                       avgt          2.052           ms/op
ClientSimple.existUser                        avgt          1.774           ms/op
ClientSimple.getUser                          avgt          1.917           ms/op
ClientSimple.listUser                         avgt          3.309           ms/op
ClientSimple.createUser                     sample  16473   1.945 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.522           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.782           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.273           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.594           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.835           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.450           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.724           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.724           ms/op
ClientSimple.existUser                      sample  16798   1.903 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.780           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.853           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.138           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.898           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.042           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.042           ms/op
ClientSimple.getUser                        sample  14928   2.159 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.539           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.126           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.637           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.612           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.940           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.973           ms/op
ClientSimple.listUser                       sample  10462   3.065 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.536           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.855           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.736           ms/op
ClientSimple.listUser:listUser·p0.95        sample          3.932           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.817           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.005           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.232           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.235           ms/op

Benchmark result is saved to 1718431846247.json
