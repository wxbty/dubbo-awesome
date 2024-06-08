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
# Warmup Iteration   1: 1.823 ops/ms
Iteration   1: 8.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.014 ops/ms


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
# Warmup Iteration   1: 6.528 ops/ms
Iteration   1: 13.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.427 ops/ms


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
# Warmup Iteration   1: 5.010 ops/ms
Iteration   1: 13.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.569 ops/ms


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
# Warmup Iteration   1: 5.832 ops/ms
Iteration   1: 9.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.725 ops/ms


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
# Warmup Iteration   1: 4.502 ±(99.9%) 0.090 ms/op
Iteration   1: 2.301 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.301 ms/op


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
# Warmup Iteration   1: 3.051 ±(99.9%) 0.046 ms/op
Iteration   1: 1.795 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.795 ms/op


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
# Warmup Iteration   1: 3.381 ±(99.9%) 0.058 ms/op
Iteration   1: 2.224 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.224 ms/op


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
# Warmup Iteration   1: 4.631 ±(99.9%) 0.085 ms/op
Iteration   1: 3.535 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.535 ms/op


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
# Warmup Iteration   1: 3.341 ±(99.9%) 0.081 ms/op
Iteration   1: 2.177 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.567 ms/op
                 createUser·p0.50:   2.066 ms/op
                 createUser·p0.90:   2.683 ms/op
                 createUser·p0.95:   2.875 ms/op
                 createUser·p0.99:   5.694 ms/op
                 createUser·p0.999:  19.540 ms/op
                 createUser·p0.9999: 20.956 ms/op
                 createUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14688
  mean =      2.177 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12016 
    [ 2.500,  5.000) = 2522 
    [ 5.000,  7.500) = 54 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      5.694 ms/op
     p(99.9000) =     19.540 ms/op
     p(99.9900) =     20.956 ms/op
     p(99.9990) =     20.972 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 2.964 ±(99.9%) 0.078 ms/op
Iteration   1: 2.019 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.198 ms/op
                 existUser·p0.50:   1.956 ms/op
                 existUser·p0.90:   2.552 ms/op
                 existUser·p0.95:   2.842 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  19.595 ms/op
                 existUser·p0.9999: 20.072 ms/op
                 existUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15841
  mean =      2.019 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13901 
    [ 2.500,  5.000) = 1844 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.198 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.842 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =     19.595 ms/op
     p(99.9900) =     20.072 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 3.184 ±(99.9%) 0.078 ms/op
Iteration   1: 2.092 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.463 ms/op
                 getUser·p0.50:   1.884 ms/op
                 getUser·p0.90:   2.613 ms/op
                 getUser·p0.95:   2.933 ms/op
                 getUser·p0.99:   5.134 ms/op
                 getUser·p0.999:  18.792 ms/op
                 getUser·p0.9999: 19.112 ms/op
                 getUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15524
  mean =      2.092 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 237 
    [ 1.250,  2.500) = 13086 
    [ 2.500,  3.750) = 1868 
    [ 3.750,  5.000) = 153 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      5.134 ms/op
     p(99.9000) =     18.792 ms/op
     p(99.9900) =     19.112 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.602 ±(99.9%) 0.130 ms/op
Iteration   1: 3.459 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.734 ms/op
                 listUser·p0.50:   3.334 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.539 ms/op
                 listUser·p0.999:  10.959 ms/op
                 listUser·p0.9999: 11.256 ms/op
                 listUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9370
  mean =      3.459 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 448 
    [ 2.500,  3.750) = 6690 
    [ 3.750,  5.000) = 1815 
    [ 5.000,  6.250) = 275 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.539 ms/op
     p(99.9000) =     10.959 ms/op
     p(99.9900) =     11.256 ms/op
     p(99.9990) =     11.256 ms/op
     p(99.9999) =     11.256 ms/op
    p(100.0000) =     11.256 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.014          ops/ms
ClientSimple.existUser                       thrpt         13.427          ops/ms
ClientSimple.getUser                         thrpt         13.569          ops/ms
ClientSimple.listUser                        thrpt          9.725          ops/ms
ClientSimple.createUser                       avgt          2.301           ms/op
ClientSimple.existUser                        avgt          1.795           ms/op
ClientSimple.getUser                          avgt          2.224           ms/op
ClientSimple.listUser                         avgt          3.535           ms/op
ClientSimple.createUser                     sample  14688   2.177 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.567           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.066           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.683           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.875           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.694           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.540           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.956           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.972           ms/op
ClientSimple.existUser                      sample  15841   2.019 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.198           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.956           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.552           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.842           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.744           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.595           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.072           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.513           ms/op
ClientSimple.getUser                        sample  15524   2.092 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.463           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.884           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.613           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.933           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.134           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.792           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.112           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.202           ms/op
ClientSimple.listUser                       sample   9370   3.459 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.734           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.334           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.166           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.719           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.539           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.959           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.256           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.256           ms/op

Benchmark result is saved to 1717870193365.json
