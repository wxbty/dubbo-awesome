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
# Warmup Iteration   1: 1.642 ops/ms
Iteration   1: 7.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.020 ops/ms


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
# Warmup Iteration   1: 5.975 ops/ms
Iteration   1: 11.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.695 ops/ms


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
# Warmup Iteration   1: 4.922 ops/ms
Iteration   1: 12.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.485 ops/ms


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
# Warmup Iteration   1: 4.938 ops/ms
Iteration   1: 9.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.384 ops/ms


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.092 ms/op
Iteration   1: 2.041 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.041 ms/op


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
# Warmup Iteration   1: 3.052 ±(99.9%) 0.043 ms/op
Iteration   1: 1.800 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.800 ms/op


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
# Warmup Iteration   1: 3.297 ±(99.9%) 0.052 ms/op
Iteration   1: 2.351 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.351 ms/op


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
# Warmup Iteration   1: 4.579 ±(99.9%) 0.097 ms/op
Iteration   1: 3.579 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.579 ms/op


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
# Warmup Iteration   1: 3.318 ±(99.9%) 0.082 ms/op
Iteration   1: 2.275 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   1.974 ms/op
                 createUser·p0.90:   2.961 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   5.297 ms/op
                 createUser·p0.999:  23.822 ms/op
                 createUser·p0.9999: 23.973 ms/op
                 createUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14041
  mean =      2.275 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10259 
    [ 2.500,  5.000) = 3608 
    [ 5.000,  7.500) = 45 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      1.974 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      5.297 ms/op
     p(99.9000) =     23.822 ms/op
     p(99.9900) =     23.973 ms/op
     p(99.9990) =     23.986 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 2.725 ±(99.9%) 0.057 ms/op
Iteration   1: 1.674 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.382 ms/op
                 existUser·p0.50:   1.597 ms/op
                 existUser·p0.90:   2.150 ms/op
                 existUser·p0.95:   2.454 ms/op
                 existUser·p0.99:   3.101 ms/op
                 existUser·p0.999:  9.567 ms/op
                 existUser·p0.9999: 10.395 ms/op
                 existUser·p1.00:   10.469 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19080
  mean =      1.674 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1819 
    [ 1.250,  2.500) = 16426 
    [ 2.500,  3.750) = 765 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.382 ms/op
     p(50.0000) =      1.597 ms/op
     p(90.0000) =      2.150 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      3.101 ms/op
     p(99.9000) =      9.567 ms/op
     p(99.9900) =     10.395 ms/op
     p(99.9990) =     10.469 ms/op
     p(99.9999) =     10.469 ms/op
    p(100.0000) =     10.469 ms/op


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
# Warmup Iteration   1: 3.228 ±(99.9%) 0.081 ms/op
Iteration   1: 2.048 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.557 ms/op
                 getUser·p0.50:   1.989 ms/op
                 getUser·p0.90:   2.675 ms/op
                 getUser·p0.95:   2.875 ms/op
                 getUser·p0.99:   3.701 ms/op
                 getUser·p0.999:  14.069 ms/op
                 getUser·p0.9999: 15.169 ms/op
                 getUser·p1.00:   15.417 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15612
  mean =      2.048 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 546 
    [ 1.250,  2.500) = 12378 
    [ 2.500,  3.750) = 2544 
    [ 3.750,  5.000) = 96 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.675 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      3.701 ms/op
     p(99.9000) =     14.069 ms/op
     p(99.9900) =     15.169 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.069 ±(99.9%) 0.126 ms/op
Iteration   1: 3.785 ±(99.9%) 0.070 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.414 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.563 ms/op
                 listUser·p0.999:  29.444 ms/op
                 listUser·p0.9999: 29.884 ms/op
                 listUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8441
  mean =      3.785 ±(99.9%) 0.070 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 555 
    [ 2.500,  5.000) = 7534 
    [ 5.000,  7.500) = 267 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.414 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.563 ms/op
     p(99.9000) =     29.444 ms/op
     p(99.9900) =     29.884 ms/op
     p(99.9990) =     29.884 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.020          ops/ms
ClientSimple.existUser                       thrpt         11.695          ops/ms
ClientSimple.getUser                         thrpt         12.485          ops/ms
ClientSimple.listUser                        thrpt          9.384          ops/ms
ClientSimple.createUser                       avgt          2.041           ms/op
ClientSimple.existUser                        avgt          1.800           ms/op
ClientSimple.getUser                          avgt          2.351           ms/op
ClientSimple.listUser                         avgt          3.579           ms/op
ClientSimple.createUser                     sample  14041   2.275 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.777           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.974           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.961           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.121           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.297           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.822           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.973           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.986           ms/op
ClientSimple.existUser                      sample  19080   1.674 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.382           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.597           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.150           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.454           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.101           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.567           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.395           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.469           ms/op
ClientSimple.getUser                        sample  15612   2.048 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.557           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.989           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.675           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.701           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.069           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.169           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.417           ms/op
ClientSimple.listUser                       sample   8441   3.785 ± 0.070   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.861           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.707           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.414           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.850           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.563           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.444           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.884           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.884           ms/op

Benchmark result is saved to 1717807043793.json
