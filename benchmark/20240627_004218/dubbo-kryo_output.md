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
# Warmup Iteration   1: 1.959 ops/ms
Iteration   1: 6.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.962 ops/ms


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
# Warmup Iteration   1: 5.941 ops/ms
Iteration   1: 12.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.237 ops/ms


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
# Warmup Iteration   1: 5.694 ops/ms
Iteration   1: 13.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.741 ops/ms


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
# Warmup Iteration   1: 6.101 ops/ms
Iteration   1: 8.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.099 ops/ms


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
# Warmup Iteration   1: 4.107 ±(99.9%) 0.077 ms/op
Iteration   1: 2.374 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.374 ms/op


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
# Warmup Iteration   1: 3.314 ±(99.9%) 0.065 ms/op
Iteration   1: 1.997 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.997 ms/op


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
# Warmup Iteration   1: 3.453 ±(99.9%) 0.067 ms/op
Iteration   1: 1.944 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.944 ms/op


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.087 ms/op
Iteration   1: 3.316 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.316 ms/op


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
# Warmup Iteration   1: 3.526 ±(99.9%) 0.086 ms/op
Iteration   1: 2.283 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   2.122 ms/op
                 createUser·p0.90:   2.785 ms/op
                 createUser·p0.95:   2.949 ms/op
                 createUser·p0.99:   5.812 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 20.139 ms/op
                 createUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14025
  mean =      2.283 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11114 
    [ 2.500,  5.000) = 2710 
    [ 5.000,  7.500) = 105 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.785 ms/op
     p(95.0000) =      2.949 ms/op
     p(99.0000) =      5.812 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     20.139 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 2.844 ±(99.9%) 0.077 ms/op
Iteration   1: 1.982 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.523 ms/op
                 existUser·p0.50:   1.892 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.589 ms/op
                 existUser·p0.99:   3.097 ms/op
                 existUser·p0.999:  13.252 ms/op
                 existUser·p0.9999: 14.989 ms/op
                 existUser·p1.00:   15.843 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16131
  mean =      1.982 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 203 
    [ 1.250,  2.500) = 14593 
    [ 2.500,  3.750) = 1243 
    [ 3.750,  5.000) = 25 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.097 ms/op
     p(99.9000) =     13.252 ms/op
     p(99.9900) =     14.989 ms/op
     p(99.9990) =     15.843 ms/op
     p(99.9999) =     15.843 ms/op
    p(100.0000) =     15.843 ms/op


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
# Warmup Iteration   1: 3.487 ±(99.9%) 0.083 ms/op
Iteration   1: 2.146 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   2.062 ms/op
                 getUser·p0.90:   2.666 ms/op
                 getUser·p0.95:   2.867 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  11.977 ms/op
                 getUser·p0.9999: 13.002 ms/op
                 getUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14941
  mean =      2.146 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 178 
    [ 1.250,  2.500) = 12002 
    [ 2.500,  3.750) = 2596 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.062 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =     11.977 ms/op
     p(99.9900) =     13.002 ms/op
     p(99.9990) =     13.812 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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
# Warmup Iteration   1: 4.144 ±(99.9%) 0.114 ms/op
Iteration   1: 3.871 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   0.387 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.302 ms/op
                 listUser·p0.99:   6.577 ms/op
                 listUser·p0.999:  9.896 ms/op
                 listUser·p0.9999: 10.027 ms/op
                 listUser·p1.00:   10.027 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8255
  mean =      3.871 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 52 
    [ 2.000,  3.000) = 1982 
    [ 3.000,  4.000) = 2326 
    [ 4.000,  5.000) = 3217 
    [ 5.000,  6.000) = 528 
    [ 6.000,  7.000) = 76 
    [ 7.000,  8.000) = 22 
    [ 8.000,  9.000) = 19 
    [ 9.000, 10.000) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.387 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.302 ms/op
     p(99.0000) =      6.577 ms/op
     p(99.9000) =      9.896 ms/op
     p(99.9900) =     10.027 ms/op
     p(99.9990) =     10.027 ms/op
     p(99.9999) =     10.027 ms/op
    p(100.0000) =     10.027 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.962          ops/ms
ClientSimple.existUser                       thrpt         12.237          ops/ms
ClientSimple.getUser                         thrpt         13.741          ops/ms
ClientSimple.listUser                        thrpt          8.099          ops/ms
ClientSimple.createUser                       avgt          2.374           ms/op
ClientSimple.existUser                        avgt          1.997           ms/op
ClientSimple.getUser                          avgt          1.944           ms/op
ClientSimple.listUser                         avgt          3.316           ms/op
ClientSimple.createUser                     sample  14025   2.283 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.743           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.122           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.785           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.949           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.812           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.300           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.139           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.218           ms/op
ClientSimple.existUser                      sample  16131   1.982 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.523           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.892           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.097           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.252           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.989           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.843           ms/op
ClientSimple.getUser                        sample  14941   2.146 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.690           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.062           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.867           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.506           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.977           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.002           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.812           ms/op
ClientSimple.listUser                       sample   8255   3.871 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.387           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.949           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.923           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.302           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.577           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.896           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.027           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.027           ms/op

Benchmark result is saved to 1719448675421.json
