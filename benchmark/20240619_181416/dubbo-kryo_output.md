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
# Warmup Iteration   1: 1.699 ops/ms
Iteration   1: 6.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.824 ops/ms


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
# Warmup Iteration   1: 5.494 ops/ms
Iteration   1: 11.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.980 ops/ms


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
# Warmup Iteration   1: 5.663 ops/ms
Iteration   1: 11.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.697 ops/ms


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
# Warmup Iteration   1: 5.483 ops/ms
Iteration   1: 8.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.414 ops/ms


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
# Warmup Iteration   1: 4.988 ±(99.9%) 0.098 ms/op
Iteration   1: 2.539 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.539 ms/op


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
# Warmup Iteration   1: 3.187 ±(99.9%) 0.058 ms/op
Iteration   1: 1.712 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.712 ms/op


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
# Warmup Iteration   1: 3.148 ±(99.9%) 0.055 ms/op
Iteration   1: 2.008 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.008 ms/op


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
# Warmup Iteration   1: 4.595 ±(99.9%) 0.083 ms/op
Iteration   1: 3.217 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.217 ms/op


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.122 ms/op
Iteration   1: 2.206 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   1.962 ms/op
                 createUser·p0.90:   2.703 ms/op
                 createUser·p0.95:   2.970 ms/op
                 createUser·p0.99:   10.914 ms/op
                 createUser·p0.999:  14.550 ms/op
                 createUser·p0.9999: 17.550 ms/op
                 createUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14483
  mean =      2.206 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 12265 
    [ 2.500,  3.750) = 1704 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 114 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      1.962 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =     10.914 ms/op
     p(99.9000) =     14.550 ms/op
     p(99.9900) =     17.550 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 3.224 ±(99.9%) 0.080 ms/op
Iteration   1: 1.902 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.542 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.376 ms/op
                 existUser·p0.95:   2.568 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  20.447 ms/op
                 existUser·p0.9999: 20.873 ms/op
                 existUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16812
  mean =      1.902 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15757 
    [ 2.500,  5.000) = 955 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.502 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     20.873 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 3.444 ±(99.9%) 0.090 ms/op
Iteration   1: 1.949 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   1.853 ms/op
                 getUser·p0.90:   2.339 ms/op
                 getUser·p0.95:   2.540 ms/op
                 getUser·p0.99:   3.965 ms/op
                 getUser·p0.999:  12.698 ms/op
                 getUser·p0.9999: 12.904 ms/op
                 getUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16396
  mean =      1.949 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 15344 
    [ 2.500,  3.750) = 727 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =     12.698 ms/op
     p(99.9900) =     12.904 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


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
# Warmup Iteration   1: 4.183 ±(99.9%) 0.116 ms/op
Iteration   1: 3.439 ±(99.9%) 0.062 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   3.244 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.531 ms/op
                 listUser·p0.999:  31.621 ms/op
                 listUser·p0.9999: 31.949 ms/op
                 listUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9289
  mean =      3.439 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 657 
    [ 2.500,  5.000) = 8347 
    [ 5.000,  7.500) = 250 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.531 ms/op
     p(99.9000) =     31.621 ms/op
     p(99.9900) =     31.949 ms/op
     p(99.9990) =     31.949 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.824          ops/ms
ClientSimple.existUser                       thrpt         11.980          ops/ms
ClientSimple.getUser                         thrpt         11.697          ops/ms
ClientSimple.listUser                        thrpt          8.414          ops/ms
ClientSimple.createUser                       avgt          2.539           ms/op
ClientSimple.existUser                        avgt          1.712           ms/op
ClientSimple.getUser                          avgt          2.008           ms/op
ClientSimple.listUser                         avgt          3.217           ms/op
ClientSimple.createUser                     sample  14483   2.206 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.651           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.962           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.970           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.914           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.550           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.550           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.071           ms/op
ClientSimple.existUser                      sample  16812   1.902 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.542           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.788           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.376           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.502           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.447           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.873           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.873           ms/op
ClientSimple.getUser                        sample  16396   1.949 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.009           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.853           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.339           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.540           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.965           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.698           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.904           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.009           ms/op
ClientSimple.listUser                       sample   9289   3.439 ± 0.062   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.044           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.244           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.157           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.719           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.531           ms/op
ClientSimple.listUser:listUser·p0.999       sample         31.621           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         31.949           ms/op
ClientSimple.listUser:listUser·p1.00        sample         31.949           ms/op

Benchmark result is saved to 1718820605033.json
