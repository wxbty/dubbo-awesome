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
# Warmup Iteration   1: 1.475 ops/ms
Iteration   1: 6.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.270 ops/ms


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
# Warmup Iteration   1: 5.332 ops/ms
Iteration   1: 11.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.002 ops/ms


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
# Warmup Iteration   1: 4.704 ops/ms
Iteration   1: 10.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.309 ops/ms


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
# Warmup Iteration   1: 3.706 ops/ms
Iteration   1: 8.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.683 ops/ms


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
# Warmup Iteration   1: 3.963 ±(99.9%) 0.077 ms/op
Iteration   1: 2.182 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.182 ms/op


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
# Warmup Iteration   1: 3.663 ±(99.9%) 0.081 ms/op
Iteration   1: 1.850 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.850 ms/op


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
# Warmup Iteration   1: 3.204 ±(99.9%) 0.060 ms/op
Iteration   1: 1.893 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.893 ms/op


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
# Warmup Iteration   1: 4.878 ±(99.9%) 0.109 ms/op
Iteration   1: 3.312 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.312 ms/op


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
# Warmup Iteration   1: 3.491 ±(99.9%) 0.095 ms/op
Iteration   1: 2.290 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   2.138 ms/op
                 createUser·p0.90:   2.630 ms/op
                 createUser·p0.95:   2.867 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  27.899 ms/op
                 createUser·p0.9999: 28.823 ms/op
                 createUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13948
  mean =      2.290 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11328 
    [ 2.500,  5.000) = 2420 
    [ 5.000,  7.500) = 136 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.138 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     27.899 ms/op
     p(99.9900) =     28.823 ms/op
     p(99.9990) =     28.836 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 2.980 ±(99.9%) 0.066 ms/op
Iteration   1: 1.901 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.427 ms/op
                 existUser·p0.50:   1.825 ms/op
                 existUser·p0.90:   2.241 ms/op
                 existUser·p0.95:   2.380 ms/op
                 existUser·p0.99:   3.347 ms/op
                 existUser·p0.999:  16.911 ms/op
                 existUser·p0.9999: 17.677 ms/op
                 existUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16926
  mean =      1.901 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 772 
    [ 1.250,  2.500) = 15584 
    [ 2.500,  3.750) = 424 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.427 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.380 ms/op
     p(99.0000) =      3.347 ms/op
     p(99.9000) =     16.911 ms/op
     p(99.9900) =     17.677 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 3.253 ±(99.9%) 0.081 ms/op
Iteration   1: 2.122 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   1.993 ms/op
                 getUser·p0.90:   2.687 ms/op
                 getUser·p0.95:   2.892 ms/op
                 getUser·p0.99:   4.434 ms/op
                 getUser·p0.999:  11.936 ms/op
                 getUser·p0.9999: 12.099 ms/op
                 getUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15169
  mean =      2.122 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 171 
    [ 1.250,  2.500) = 11751 
    [ 2.500,  3.750) = 3069 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.892 ms/op
     p(99.0000) =      4.434 ms/op
     p(99.9000) =     11.936 ms/op
     p(99.9900) =     12.099 ms/op
     p(99.9990) =     12.108 ms/op
     p(99.9999) =     12.108 ms/op
    p(100.0000) =     12.108 ms/op


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
# Warmup Iteration   1: 4.688 ±(99.9%) 0.142 ms/op
Iteration   1: 3.767 ±(99.9%) 0.070 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.997 ms/op
                 listUser·p0.999:  29.901 ms/op
                 listUser·p0.9999: 30.343 ms/op
                 listUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8486
  mean =      3.767 ±(99.9%) 0.070 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 509 
    [ 2.500,  5.000) = 7589 
    [ 5.000,  7.500) = 324 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.997 ms/op
     p(99.9000) =     29.901 ms/op
     p(99.9900) =     30.343 ms/op
     p(99.9990) =     30.343 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.270          ops/ms
ClientSimple.existUser                       thrpt         11.002          ops/ms
ClientSimple.getUser                         thrpt         10.309          ops/ms
ClientSimple.listUser                        thrpt          8.683          ops/ms
ClientSimple.createUser                       avgt          2.182           ms/op
ClientSimple.existUser                        avgt          1.850           ms/op
ClientSimple.getUser                          avgt          1.893           ms/op
ClientSimple.listUser                         avgt          3.312           ms/op
ClientSimple.createUser                     sample  13948   2.290 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.798           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.138           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.972           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.899           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.823           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.836           ms/op
ClientSimple.existUser                      sample  16926   1.901 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.427           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.825           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.241           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.347           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.911           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.677           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.859           ms/op
ClientSimple.getUser                        sample  15169   2.122 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.682           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.993           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.892           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.434           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.936           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.099           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.108           ms/op
ClientSimple.listUser                       sample   8486   3.767 ± 0.070   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.945           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.625           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.915           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.997           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.901           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         30.343           ms/op
ClientSimple.listUser:listUser·p1.00        sample         30.343           ms/op

Benchmark result is saved to 1716683981516.json
