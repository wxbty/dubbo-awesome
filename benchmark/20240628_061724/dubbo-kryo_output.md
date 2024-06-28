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
# Warmup Iteration   1: 1.666 ops/ms
Iteration   1: 6.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.883 ops/ms


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
# Warmup Iteration   1: 6.148 ops/ms
Iteration   1: 11.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.774 ops/ms


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
# Warmup Iteration   1: 6.492 ops/ms
Iteration   1: 13.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.690 ops/ms


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
# Warmup Iteration   1: 5.467 ops/ms
Iteration   1: 8.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.415 ops/ms


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
# Warmup Iteration   1: 3.686 ±(99.9%) 0.063 ms/op
Iteration   1: 2.078 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.078 ms/op


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
# Warmup Iteration   1: 2.955 ±(99.9%) 0.045 ms/op
Iteration   1: 1.709 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.709 ms/op


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
# Warmup Iteration   1: 3.217 ±(99.9%) 0.064 ms/op
Iteration   1: 2.081 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.081 ms/op


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.105 ms/op
Iteration   1: 3.375 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.375 ms/op


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
# Warmup Iteration   1: 3.284 ±(99.9%) 0.090 ms/op
Iteration   1: 2.289 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.552 ms/op
                 createUser·p0.50:   2.126 ms/op
                 createUser·p0.90:   2.847 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   6.981 ms/op
                 createUser·p0.999:  15.303 ms/op
                 createUser·p0.9999: 15.591 ms/op
                 createUser·p1.00:   15.663 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13982
  mean =      2.289 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 428 
    [ 1.250,  2.500) = 9767 
    [ 2.500,  3.750) = 3406 
    [ 3.750,  5.000) = 120 
    [ 5.000,  6.250) = 69 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      2.126 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      6.981 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     15.591 ms/op
     p(99.9990) =     15.663 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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
# Warmup Iteration   1: 3.084 ±(99.9%) 0.091 ms/op
Iteration   1: 1.942 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   1.751 ms/op
                 existUser·p0.90:   2.482 ms/op
                 existUser·p0.95:   2.675 ms/op
                 existUser·p0.99:   3.605 ms/op
                 existUser·p0.999:  22.544 ms/op
                 existUser·p0.9999: 22.610 ms/op
                 existUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16498
  mean =      1.942 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14966 
    [ 2.500,  5.000) = 1435 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      1.751 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      3.605 ms/op
     p(99.9000) =     22.544 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     22.610 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.087 ms/op
Iteration   1: 1.982 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.538 ms/op
                 getUser·p0.50:   1.880 ms/op
                 getUser·p0.90:   2.417 ms/op
                 getUser·p0.95:   2.631 ms/op
                 getUser·p0.99:   5.104 ms/op
                 getUser·p0.999:  10.974 ms/op
                 getUser·p0.9999: 11.973 ms/op
                 getUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16173
  mean =      1.982 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 195 
    [ 1.250,  2.500) = 14767 
    [ 2.500,  3.750) = 966 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.631 ms/op
     p(99.0000) =      5.104 ms/op
     p(99.9000) =     10.974 ms/op
     p(99.9900) =     11.973 ms/op
     p(99.9990) =     11.993 ms/op
     p(99.9999) =     11.993 ms/op
    p(100.0000) =     11.993 ms/op


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
# Warmup Iteration   1: 4.563 ±(99.9%) 0.120 ms/op
Iteration   1: 3.646 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  17.448 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8765
  mean =      3.646 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 489 
    [ 2.500,  3.750) = 4974 
    [ 3.750,  5.000) = 2990 
    [ 5.000,  6.250) = 172 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     17.448 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.883          ops/ms
ClientSimple.existUser                       thrpt         11.774          ops/ms
ClientSimple.getUser                         thrpt         13.690          ops/ms
ClientSimple.listUser                        thrpt          8.415          ops/ms
ClientSimple.createUser                       avgt          2.078           ms/op
ClientSimple.existUser                        avgt          1.709           ms/op
ClientSimple.getUser                          avgt          2.081           ms/op
ClientSimple.listUser                         avgt          3.375           ms/op
ClientSimple.createUser                     sample  13982   2.289 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.552           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.126           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.847           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.207           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.981           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.303           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.591           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.663           ms/op
ClientSimple.existUser                      sample  16498   1.942 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.905           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.751           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.482           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.675           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.605           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.544           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.610           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.610           ms/op
ClientSimple.getUser                        sample  16173   1.982 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.538           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.880           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.417           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.631           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.104           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.974           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.973           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.993           ms/op
ClientSimple.listUser                       sample   8765   3.646 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.237           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.580           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.849           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.448           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.088           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.088           ms/op

Benchmark result is saved to 1719555140969.json
