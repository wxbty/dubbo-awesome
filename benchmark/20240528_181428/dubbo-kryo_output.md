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
# Warmup Iteration   1: 1.807 ops/ms
Iteration   1: 7.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.403 ops/ms


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
# Warmup Iteration   1: 6.541 ops/ms
Iteration   1: 13.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.795 ops/ms


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
# Warmup Iteration   1: 6.280 ops/ms
Iteration   1: 13.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.120 ops/ms


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
# Warmup Iteration   1: 5.475 ops/ms
Iteration   1: 8.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.990 ops/ms


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
# Warmup Iteration   1: 3.813 ±(99.9%) 0.072 ms/op
Iteration   1: 2.224 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.319 ±(99.9%) 0.059 ms/op
Iteration   1: 1.874 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.874 ms/op


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
# Warmup Iteration   1: 3.254 ±(99.9%) 0.061 ms/op
Iteration   1: 2.154 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.154 ms/op


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
# Warmup Iteration   1: 4.796 ±(99.9%) 0.104 ms/op
Iteration   1: 3.207 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.207 ms/op


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
# Warmup Iteration   1: 3.868 ±(99.9%) 0.116 ms/op
Iteration   1: 2.086 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   1.933 ms/op
                 createUser·p0.90:   2.572 ms/op
                 createUser·p0.95:   2.793 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  17.498 ms/op
                 createUser·p0.9999: 18.283 ms/op
                 createUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15280
  mean =      2.086 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 13277 
    [ 2.500,  3.750) = 1688 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      1.933 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     18.283 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 2.957 ±(99.9%) 0.065 ms/op
Iteration   1: 1.947 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.455 ms/op
                 existUser·p0.50:   1.860 ms/op
                 existUser·p0.90:   2.355 ms/op
                 existUser·p0.95:   2.560 ms/op
                 existUser·p0.99:   3.060 ms/op
                 existUser·p0.999:  29.524 ms/op
                 existUser·p0.9999: 30.070 ms/op
                 existUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16652
  mean =      1.947 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15614 
    [ 2.500,  5.000) = 974 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      3.060 ms/op
     p(99.9000) =     29.524 ms/op
     p(99.9900) =     30.070 ms/op
     p(99.9990) =     30.114 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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
# Warmup Iteration   1: 3.111 ±(99.9%) 0.073 ms/op
Iteration   1: 2.075 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.346 ms/op
                 getUser·p0.50:   1.985 ms/op
                 getUser·p0.90:   2.589 ms/op
                 getUser·p0.95:   2.753 ms/op
                 getUser·p0.99:   3.281 ms/op
                 getUser·p0.999:  20.447 ms/op
                 getUser·p0.9999: 22.048 ms/op
                 getUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15399
  mean =      2.075 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13411 
    [ 2.500,  5.000) = 1861 
    [ 5.000,  7.500) = 95 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      3.281 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     22.048 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 4.437 ±(99.9%) 0.120 ms/op
Iteration   1: 3.685 ±(99.9%) 0.090 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   8.145 ms/op
                 listUser·p0.999:  44.126 ms/op
                 listUser·p0.9999: 50.266 ms/op
                 listUser·p1.00:   50.266 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8692
  mean =      3.685 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8401 
    [ 5.000, 10.000) = 214 
    [10.000, 15.000) = 37 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 14 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      8.145 ms/op
     p(99.9000) =     44.126 ms/op
     p(99.9900) =     50.266 ms/op
     p(99.9990) =     50.266 ms/op
     p(99.9999) =     50.266 ms/op
    p(100.0000) =     50.266 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.403          ops/ms
ClientSimple.existUser                       thrpt         13.795          ops/ms
ClientSimple.getUser                         thrpt         13.120          ops/ms
ClientSimple.listUser                        thrpt          8.990          ops/ms
ClientSimple.createUser                       avgt          2.224           ms/op
ClientSimple.existUser                        avgt          1.874           ms/op
ClientSimple.getUser                          avgt          2.154           ms/op
ClientSimple.listUser                         avgt          3.207           ms/op
ClientSimple.createUser                     sample  15280   2.086 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.730           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.933           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.572           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.793           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.005           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.498           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.283           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.317           ms/op
ClientSimple.existUser                      sample  16652   1.947 ± 0.036   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.455           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.860           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.355           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.060           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.524           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         30.070           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.114           ms/op
ClientSimple.getUser                        sample  15399   2.075 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.346           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.985           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.753           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.281           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.447           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.048           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.118           ms/op
ClientSimple.listUser                       sample   8692   3.685 ± 0.090   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.926           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.523           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.145           ms/op
ClientSimple.listUser:listUser·p0.999       sample         44.126           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         50.266           ms/op
ClientSimple.listUser:listUser·p1.00        sample         50.266           ms/op

Benchmark result is saved to 1716919797802.json
