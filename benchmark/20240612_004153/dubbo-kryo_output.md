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
# Warmup Iteration   1: 1.785 ops/ms
Iteration   1: 6.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.921 ops/ms


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
# Warmup Iteration   1: 5.616 ops/ms
Iteration   1: 13.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.609 ops/ms


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
# Warmup Iteration   1: 5.602 ops/ms
Iteration   1: 13.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.653 ops/ms


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
# Warmup Iteration   1: 5.485 ops/ms
Iteration   1: 7.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.538 ops/ms


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
# Warmup Iteration   1: 4.543 ±(99.9%) 0.097 ms/op
Iteration   1: 2.291 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.291 ms/op


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
# Warmup Iteration   1: 3.643 ±(99.9%) 0.064 ms/op
Iteration   1: 2.143 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.143 ms/op


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
# Warmup Iteration   1: 3.279 ±(99.9%) 0.052 ms/op
Iteration   1: 2.026 ±(99.9%) 0.005 ms/op


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
# Warmup Iteration   1: 4.872 ±(99.9%) 0.107 ms/op
Iteration   1: 3.504 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.504 ms/op


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
# Warmup Iteration   1: 3.812 ±(99.9%) 0.112 ms/op
Iteration   1: 2.505 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   0.498 ms/op
                 createUser·p0.50:   2.269 ms/op
                 createUser·p0.90:   2.929 ms/op
                 createUser·p0.95:   3.355 ms/op
                 createUser·p0.99:   11.411 ms/op
                 createUser·p0.999:  27.263 ms/op
                 createUser·p0.9999: 27.489 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12744
  mean =      2.505 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8616 
    [ 2.500,  5.000) = 3861 
    [ 5.000,  7.500) = 60 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      2.269 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.355 ms/op
     p(99.0000) =     11.411 ms/op
     p(99.9000) =     27.263 ms/op
     p(99.9900) =     27.489 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 2.894 ±(99.9%) 0.069 ms/op
Iteration   1: 1.942 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   1.847 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.494 ms/op
                 existUser·p0.99:   5.046 ms/op
                 existUser·p0.999:  20.172 ms/op
                 existUser·p0.9999: 21.458 ms/op
                 existUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16461
  mean =      1.942 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15673 
    [ 2.500,  5.000) = 620 
    [ 5.000,  7.500) = 96 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      1.847 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      5.046 ms/op
     p(99.9000) =     20.172 ms/op
     p(99.9900) =     21.458 ms/op
     p(99.9990) =     22.348 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 3.567 ±(99.9%) 0.120 ms/op
Iteration   1: 2.181 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   2.079 ms/op
                 getUser·p0.90:   2.593 ms/op
                 getUser·p0.95:   2.785 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  16.679 ms/op
                 getUser·p0.9999: 17.072 ms/op
                 getUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14657
  mean =      2.181 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 212 
    [ 1.250,  2.500) = 12502 
    [ 2.500,  3.750) = 1740 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.079 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =     16.679 ms/op
     p(99.9900) =     17.072 ms/op
     p(99.9990) =     17.072 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.557 ±(99.9%) 0.143 ms/op
Iteration   1: 3.668 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.884 ms/op
                 listUser·p0.50:   3.518 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   8.010 ms/op
                 listUser·p0.999:  12.866 ms/op
                 listUser·p0.9999: 14.205 ms/op
                 listUser·p1.00:   14.205 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8717
  mean =      3.668 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 216 
    [ 2.500,  3.750) = 5058 
    [ 3.750,  5.000) = 3045 
    [ 5.000,  6.250) = 277 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.884 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      8.010 ms/op
     p(99.9000) =     12.866 ms/op
     p(99.9900) =     14.205 ms/op
     p(99.9990) =     14.205 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.921          ops/ms
ClientSimple.existUser                       thrpt         13.609          ops/ms
ClientSimple.getUser                         thrpt         13.653          ops/ms
ClientSimple.listUser                        thrpt          7.538          ops/ms
ClientSimple.createUser                       avgt          2.291           ms/op
ClientSimple.existUser                        avgt          2.143           ms/op
ClientSimple.getUser                          avgt          2.026           ms/op
ClientSimple.listUser                         avgt          3.504           ms/op
ClientSimple.createUser                     sample  12744   2.505 ± 0.053   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.498           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.269           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.929           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.355           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.411           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.263           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.489           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.525           ms/op
ClientSimple.existUser                      sample  16461   1.942 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.618           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.847           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.046           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.172           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.458           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.348           ms/op
ClientSimple.getUser                        sample  14657   2.181 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.695           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.079           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.785           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.899           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.679           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.072           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.072           ms/op
ClientSimple.listUser                       sample   8717   3.668 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.884           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.518           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.948           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.010           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.866           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.205           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.205           ms/op

Benchmark result is saved to 1718152667963.json
