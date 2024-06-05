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
# Warmup Iteration   1: 1.543 ops/ms
Iteration   1: 6.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.610 ops/ms


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
# Warmup Iteration   1: 6.099 ops/ms
Iteration   1: 11.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.280 ops/ms


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
# Warmup Iteration   1: 5.377 ops/ms
Iteration   1: 12.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.728 ops/ms


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
# Warmup Iteration   1: 4.586 ops/ms
Iteration   1: 7.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.273 ops/ms


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
# Warmup Iteration   1: 3.973 ±(99.9%) 0.069 ms/op
Iteration   1: 2.164 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.164 ms/op


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
# Warmup Iteration   1: 3.403 ±(99.9%) 0.062 ms/op
Iteration   1: 1.991 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.991 ms/op


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.070 ms/op
Iteration   1: 1.943 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.943 ms/op


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
# Warmup Iteration   1: 4.695 ±(99.9%) 0.098 ms/op
Iteration   1: 3.144 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.144 ms/op


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
# Warmup Iteration   1: 3.681 ±(99.9%) 0.090 ms/op
Iteration   1: 2.138 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   1.935 ms/op
                 createUser·p0.90:   2.499 ms/op
                 createUser·p0.95:   2.712 ms/op
                 createUser·p0.99:   9.160 ms/op
                 createUser·p0.999:  18.383 ms/op
                 createUser·p0.9999: 19.841 ms/op
                 createUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14993
  mean =      2.138 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13511 
    [ 2.500,  5.000) = 1196 
    [ 5.000,  7.500) = 119 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      9.160 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     19.841 ms/op
     p(99.9990) =     20.021 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 3.081 ±(99.9%) 0.078 ms/op
Iteration   1: 1.684 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.511 ms/op
                 existUser·p0.50:   1.561 ms/op
                 existUser·p0.90:   1.913 ms/op
                 existUser·p0.95:   2.171 ms/op
                 existUser·p0.99:   4.359 ms/op
                 existUser·p0.999:  19.956 ms/op
                 existUser·p0.9999: 20.077 ms/op
                 existUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19186
  mean =      1.684 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18658 
    [ 2.500,  5.000) = 380 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      1.561 ms/op
     p(90.0000) =      1.913 ms/op
     p(95.0000) =      2.171 ms/op
     p(99.0000) =      4.359 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     20.077 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 3.382 ±(99.9%) 0.097 ms/op
Iteration   1: 2.177 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   2.009 ms/op
                 getUser·p0.90:   2.707 ms/op
                 getUser·p0.95:   3.015 ms/op
                 getUser·p0.99:   5.508 ms/op
                 getUser·p0.999:  12.228 ms/op
                 getUser·p0.9999: 13.003 ms/op
                 getUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14685
  mean =      2.177 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 12305 
    [ 2.500,  3.750) = 1988 
    [ 3.750,  5.000) = 94 
    [ 5.000,  6.250) = 122 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.009 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      5.508 ms/op
     p(99.9000) =     12.228 ms/op
     p(99.9900) =     13.003 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.326 ±(99.9%) 0.204 ms/op
Iteration   1: 3.550 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   3.351 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  14.498 ms/op
                 listUser·p0.9999: 14.975 ms/op
                 listUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9003
  mean =      3.550 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 211 
    [ 2.500,  3.750) = 5613 
    [ 3.750,  5.000) = 2675 
    [ 5.000,  6.250) = 306 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.483 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     14.498 ms/op
     p(99.9900) =     14.975 ms/op
     p(99.9990) =     14.975 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.610          ops/ms
ClientSimple.existUser                       thrpt         11.280          ops/ms
ClientSimple.getUser                         thrpt         12.728          ops/ms
ClientSimple.listUser                        thrpt          7.273          ops/ms
ClientSimple.createUser                       avgt          2.164           ms/op
ClientSimple.existUser                        avgt          1.991           ms/op
ClientSimple.getUser                          avgt          1.943           ms/op
ClientSimple.listUser                         avgt          3.144           ms/op
ClientSimple.createUser                     sample  14993   2.138 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.614           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.935           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.499           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.712           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.160           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.383           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.841           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.021           ms/op
ClientSimple.existUser                      sample  19186   1.684 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.511           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.561           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.913           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.171           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.359           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.956           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.077           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.709           ms/op
ClientSimple.getUser                        sample  14685   2.177 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.807           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.009           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.015           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.508           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.228           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.003           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.042           ms/op
ClientSimple.listUser                       sample   9003   3.550 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.483           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.351           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.177           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.717           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.498           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.975           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.975           ms/op

Benchmark result is saved to 1717589693473.json
