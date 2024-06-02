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
# Warmup Iteration   1: 1.818 ops/ms
Iteration   1: 6.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.518 ops/ms


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
# Warmup Iteration   1: 5.633 ops/ms
Iteration   1: 12.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.518 ops/ms


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
# Warmup Iteration   1: 5.544 ops/ms
Iteration   1: 12.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.848 ops/ms


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
# Warmup Iteration   1: 5.127 ops/ms
Iteration   1: 8.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.567 ops/ms


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.084 ms/op
Iteration   1: 2.259 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.259 ms/op


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
# Warmup Iteration   1: 3.074 ±(99.9%) 0.049 ms/op
Iteration   1: 1.818 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.818 ms/op


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
# Warmup Iteration   1: 3.153 ±(99.9%) 0.054 ms/op
Iteration   1: 2.198 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.198 ms/op


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.101 ms/op
Iteration   1: 3.291 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.291 ms/op


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
# Warmup Iteration   1: 3.446 ±(99.9%) 0.093 ms/op
Iteration   1: 2.232 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.418 ms/op
                 createUser·p0.50:   2.159 ms/op
                 createUser·p0.90:   2.707 ms/op
                 createUser·p0.95:   2.929 ms/op
                 createUser·p0.99:   5.798 ms/op
                 createUser·p0.999:  16.620 ms/op
                 createUser·p0.9999: 17.708 ms/op
                 createUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14323
  mean =      2.232 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1330 
    [ 1.250,  2.500) = 10021 
    [ 2.500,  3.750) = 2612 
    [ 3.750,  5.000) = 159 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 70 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      2.159 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      5.798 ms/op
     p(99.9000) =     16.620 ms/op
     p(99.9900) =     17.708 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 2.908 ±(99.9%) 0.062 ms/op
Iteration   1: 2.090 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.210 ms/op
                 existUser·p0.50:   2.019 ms/op
                 existUser·p0.90:   2.556 ms/op
                 existUser·p0.95:   2.769 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  12.861 ms/op
                 existUser·p0.9999: 14.382 ms/op
                 existUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16013
  mean =      2.090 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 309 
    [ 1.250,  2.500) = 13666 
    [ 2.500,  3.750) = 1941 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.210 ms/op
     p(50.0000) =      2.019 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      3.432 ms/op
     p(99.9000) =     12.861 ms/op
     p(99.9900) =     14.382 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 3.493 ±(99.9%) 0.119 ms/op
Iteration   1: 2.008 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.572 ms/op
                 getUser·p0.50:   1.749 ms/op
                 getUser·p0.90:   2.617 ms/op
                 getUser·p0.95:   2.830 ms/op
                 getUser·p0.99:   3.587 ms/op
                 getUser·p0.999:  29.360 ms/op
                 getUser·p0.9999: 29.767 ms/op
                 getUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15923
  mean =      2.008 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13733 
    [ 2.500,  5.000) = 2124 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      3.587 ms/op
     p(99.9000) =     29.360 ms/op
     p(99.9900) =     29.767 ms/op
     p(99.9990) =     29.786 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 5.822 ±(99.9%) 0.168 ms/op
Iteration   1: 3.548 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.495 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.322 ms/op
                 listUser·p0.999:  14.712 ms/op
                 listUser·p0.9999: 15.614 ms/op
                 listUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9065
  mean =      3.548 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 628 
    [ 2.500,  3.750) = 4878 
    [ 3.750,  5.000) = 3198 
    [ 5.000,  6.250) = 255 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.322 ms/op
     p(99.9000) =     14.712 ms/op
     p(99.9900) =     15.614 ms/op
     p(99.9990) =     15.614 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.518          ops/ms
ClientSimple.existUser                       thrpt         12.518          ops/ms
ClientSimple.getUser                         thrpt         12.848          ops/ms
ClientSimple.listUser                        thrpt          8.567          ops/ms
ClientSimple.createUser                       avgt          2.259           ms/op
ClientSimple.existUser                        avgt          1.818           ms/op
ClientSimple.getUser                          avgt          2.198           ms/op
ClientSimple.listUser                         avgt          3.291           ms/op
ClientSimple.createUser                     sample  14323   2.232 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.418           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.159           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.707           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.929           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.798           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.620           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.708           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.793           ms/op
ClientSimple.existUser                      sample  16013   2.090 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.210           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.019           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.769           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.432           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.861           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.382           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.451           ms/op
ClientSimple.getUser                        sample  15923   2.008 ± 0.039   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.572           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.749           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.587           ms/op
ClientSimple.getUser:getUser·p0.999         sample         29.360           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         29.767           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.786           ms/op
ClientSimple.listUser                       sample   9065   3.548 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.495           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.551           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.322           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.712           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.614           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.614           ms/op

Benchmark result is saved to 1717308734235.json
