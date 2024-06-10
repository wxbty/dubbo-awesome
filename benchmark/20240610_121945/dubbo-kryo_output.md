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
# Warmup Iteration   1: 1.783 ops/ms
Iteration   1: 6.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.803 ops/ms


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
# Warmup Iteration   1: 5.198 ops/ms
Iteration   1: 11.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.284 ops/ms


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
# Warmup Iteration   1: 5.099 ops/ms
Iteration   1: 11.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.763 ops/ms


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
# Warmup Iteration   1: 5.008 ops/ms
Iteration   1: 9.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.225 ops/ms


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.076 ms/op
Iteration   1: 2.348 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.348 ms/op


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
# Warmup Iteration   1: 3.322 ±(99.9%) 0.065 ms/op
Iteration   1: 2.010 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.010 ms/op


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
# Warmup Iteration   1: 3.643 ±(99.9%) 0.082 ms/op
Iteration   1: 2.158 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.158 ms/op


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
# Warmup Iteration   1: 4.462 ±(99.9%) 0.096 ms/op
Iteration   1: 3.215 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.215 ms/op


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
# Warmup Iteration   1: 3.691 ±(99.9%) 0.092 ms/op
Iteration   1: 2.019 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.347 ms/op
                 createUser·p0.50:   1.866 ms/op
                 createUser·p0.90:   2.400 ms/op
                 createUser·p0.95:   2.585 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  21.103 ms/op
                 createUser·p0.9999: 23.770 ms/op
                 createUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15832
  mean =      2.019 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14818 
    [ 2.500,  5.000) = 802 
    [ 5.000,  7.500) = 77 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.347 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     21.103 ms/op
     p(99.9900) =     23.770 ms/op
     p(99.9990) =     23.790 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 2.877 ±(99.9%) 0.066 ms/op
Iteration   1: 2.005 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.443 ms/op
                 existUser·p0.50:   1.890 ms/op
                 existUser·p0.90:   2.531 ms/op
                 existUser·p0.95:   2.687 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  16.089 ms/op
                 existUser·p0.9999: 16.935 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15960
  mean =      2.005 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 373 
    [ 1.250,  2.500) = 13780 
    [ 2.500,  3.750) = 1646 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.443 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =     16.089 ms/op
     p(99.9900) =     16.935 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 3.372 ±(99.9%) 0.100 ms/op
Iteration   1: 2.129 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.243 ms/op
                 getUser·p0.50:   2.034 ms/op
                 getUser·p0.90:   2.748 ms/op
                 getUser·p0.95:   2.970 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  11.370 ms/op
                 getUser·p0.9999: 12.049 ms/op
                 getUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15047
  mean =      2.129 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 241 
    [ 1.250,  2.500) = 12157 
    [ 2.500,  3.750) = 2521 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.243 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.748 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =     11.370 ms/op
     p(99.9900) =     12.049 ms/op
     p(99.9990) =     12.157 ms/op
     p(99.9999) =     12.157 ms/op
    p(100.0000) =     12.157 ms/op


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
# Warmup Iteration   1: 4.194 ±(99.9%) 0.187 ms/op
Iteration   1: 3.705 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   5.830 ms/op
                 listUser·p0.999:  17.756 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8626
  mean =      3.705 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 595 
    [ 2.500,  5.000) = 7694 
    [ 5.000,  7.500) = 273 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      5.830 ms/op
     p(99.9000) =     17.756 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.803          ops/ms
ClientSimple.existUser                       thrpt         11.284          ops/ms
ClientSimple.getUser                         thrpt         11.763          ops/ms
ClientSimple.listUser                        thrpt          9.225          ops/ms
ClientSimple.createUser                       avgt          2.348           ms/op
ClientSimple.existUser                        avgt          2.010           ms/op
ClientSimple.getUser                          avgt          2.158           ms/op
ClientSimple.listUser                         avgt          3.215           ms/op
ClientSimple.createUser                     sample  15832   2.019 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.347           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.866           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.400           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.585           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.226           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.103           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.770           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.790           ms/op
ClientSimple.existUser                      sample  15960   2.005 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.443           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.890           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.531           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.687           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.781           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.089           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.935           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.974           ms/op
ClientSimple.getUser                        sample  15047   2.129 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.243           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.034           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.970           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.617           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.370           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.049           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.157           ms/op
ClientSimple.listUser                       sample   8626   3.705 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.141           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.645           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.497           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.841           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.830           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.756           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.218           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.218           ms/op

Benchmark result is saved to 1718021723021.json
