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
# Warmup Iteration   1: 1.241 ops/ms
Iteration   1: 5.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.740 ops/ms


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
# Warmup Iteration   1: 4.970 ops/ms
Iteration   1: 12.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.653 ops/ms


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
# Warmup Iteration   1: 5.076 ops/ms
Iteration   1: 11.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.107 ops/ms


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
# Warmup Iteration   1: 4.465 ops/ms
Iteration   1: 8.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.484 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.897 ±(99.9%) 0.062 ms/op
Iteration   1: 2.222 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.222 ms/op


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
# Warmup Iteration   1: 3.108 ±(99.9%) 0.071 ms/op
Iteration   1: 1.801 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.801 ms/op


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
# Warmup Iteration   1: 3.404 ±(99.9%) 0.076 ms/op
Iteration   1: 1.948 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.948 ms/op


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
# Warmup Iteration   1: 5.244 ±(99.9%) 0.105 ms/op
Iteration   1: 3.545 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.545 ms/op


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
# Warmup Iteration   1: 3.562 ±(99.9%) 0.097 ms/op
Iteration   1: 2.301 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.547 ms/op
                 createUser·p0.50:   2.193 ms/op
                 createUser·p0.90:   2.748 ms/op
                 createUser·p0.95:   2.912 ms/op
                 createUser·p0.99:   4.361 ms/op
                 createUser·p0.999:  25.098 ms/op
                 createUser·p0.9999: 26.103 ms/op
                 createUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14062
  mean =      2.301 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10874 
    [ 2.500,  5.000) = 3081 
    [ 5.000,  7.500) = 11 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.193 ms/op
     p(90.0000) =      2.748 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      4.361 ms/op
     p(99.9000) =     25.098 ms/op
     p(99.9900) =     26.103 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 2.972 ±(99.9%) 0.074 ms/op
Iteration   1: 1.954 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.295 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   4.705 ms/op
                 existUser·p0.999:  22.542 ms/op
                 existUser·p0.9999: 23.239 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16355
  mean =      1.954 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15328 
    [ 2.500,  5.000) = 901 
    [ 5.000,  7.500) = 62 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.295 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      4.705 ms/op
     p(99.9000) =     22.542 ms/op
     p(99.9900) =     23.239 ms/op
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
# Warmup Iteration   1: 3.486 ±(99.9%) 0.099 ms/op
Iteration   1: 2.278 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.438 ms/op
                 getUser·p0.50:   2.171 ms/op
                 getUser·p0.90:   2.941 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.798 ms/op
                 getUser·p0.999:  13.189 ms/op
                 getUser·p0.9999: 13.674 ms/op
                 getUser·p1.00:   13.681 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14015
  mean =      2.278 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 179 
    [ 1.250,  2.500) = 9846 
    [ 2.500,  3.750) = 3710 
    [ 3.750,  5.000) = 149 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.438 ms/op
     p(50.0000) =      2.171 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      4.798 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     13.674 ms/op
     p(99.9990) =     13.681 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


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
# Warmup Iteration   1: 5.114 ±(99.9%) 0.168 ms/op
Iteration   1: 3.816 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.959 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   9.815 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 17.793 ms/op
                 listUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8395
  mean =      3.816 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 640 
    [ 2.500,  3.750) = 4066 
    [ 3.750,  5.000) = 2864 
    [ 5.000,  6.250) = 466 
    [ 6.250,  7.500) = 214 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.959 ms/op
     p(95.0000) =      6.054 ms/op
     p(99.0000) =      9.815 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.740          ops/ms
ClientSimple.existUser                       thrpt         12.653          ops/ms
ClientSimple.getUser                         thrpt         11.107          ops/ms
ClientSimple.listUser                        thrpt          8.484          ops/ms
ClientSimple.createUser                       avgt          2.222           ms/op
ClientSimple.existUser                        avgt          1.801           ms/op
ClientSimple.getUser                          avgt          1.948           ms/op
ClientSimple.listUser                         avgt          3.545           ms/op
ClientSimple.createUser                     sample  14062   2.301 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.547           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.193           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.748           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.912           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.361           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.098           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.103           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.116           ms/op
ClientSimple.existUser                      sample  16355   1.954 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.616           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.788           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.295           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.705           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.542           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.239           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.364           ms/op
ClientSimple.getUser                        sample  14015   2.278 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.438           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.171           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.941           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.269           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.798           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.189           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.674           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.681           ms/op
ClientSimple.listUser                       sample   8395   3.816 ± 0.055   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.880           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.645           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.959           ms/op
ClientSimple.listUser:listUser·p0.95        sample          6.054           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.815           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.302           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.793           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.793           ms/op

Benchmark result is saved to 1719836197259.json
