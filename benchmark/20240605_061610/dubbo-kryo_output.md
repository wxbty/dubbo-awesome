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
# Warmup Iteration   1: 1.485 ops/ms
Iteration   1: 6.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.483 ops/ms


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
# Warmup Iteration   1: 5.736 ops/ms
Iteration   1: 12.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.124 ops/ms


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
# Warmup Iteration   1: 5.951 ops/ms
Iteration   1: 12.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.857 ops/ms


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
# Warmup Iteration   1: 4.566 ops/ms
Iteration   1: 8.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.938 ops/ms


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
# Warmup Iteration   1: 3.579 ±(99.9%) 0.060 ms/op
Iteration   1: 2.288 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.288 ms/op


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
# Warmup Iteration   1: 3.011 ±(99.9%) 0.051 ms/op
Iteration   1: 1.852 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.852 ms/op


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
# Warmup Iteration   1: 3.284 ±(99.9%) 0.058 ms/op
Iteration   1: 2.051 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.051 ms/op


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.090 ms/op
Iteration   1: 3.419 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.419 ms/op


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
# Warmup Iteration   1: 3.816 ±(99.9%) 0.109 ms/op
Iteration   1: 2.510 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   2.372 ms/op
                 createUser·p0.90:   2.938 ms/op
                 createUser·p0.95:   3.275 ms/op
                 createUser·p0.99:   6.286 ms/op
                 createUser·p0.999:  26.280 ms/op
                 createUser·p0.9999: 26.762 ms/op
                 createUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12766
  mean =      2.510 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8004 
    [ 2.500,  5.000) = 4589 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.372 ms/op
     p(90.0000) =      2.938 ms/op
     p(95.0000) =      3.275 ms/op
     p(99.0000) =      6.286 ms/op
     p(99.9000) =     26.280 ms/op
     p(99.9900) =     26.762 ms/op
     p(99.9990) =     26.771 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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
# Warmup Iteration   1: 3.212 ±(99.9%) 0.075 ms/op
Iteration   1: 2.279 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   2.245 ms/op
                 existUser·p0.90:   2.679 ms/op
                 existUser·p0.95:   2.871 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  10.943 ms/op
                 existUser·p0.9999: 11.043 ms/op
                 existUser·p1.00:   11.043 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14098
  mean =      2.279 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 10914 
    [ 2.500,  3.750) = 2910 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.245 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =     10.943 ms/op
     p(99.9900) =     11.043 ms/op
     p(99.9990) =     11.043 ms/op
     p(99.9999) =     11.043 ms/op
    p(100.0000) =     11.043 ms/op


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.127 ms/op
Iteration   1: 2.305 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   2.245 ms/op
                 getUser·p0.90:   2.863 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   4.418 ms/op
                 getUser·p0.999:  12.075 ms/op
                 getUser·p0.9999: 12.203 ms/op
                 getUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13872
  mean =      2.305 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 10340 
    [ 2.500,  3.750) = 3232 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      2.245 ms/op
     p(90.0000) =      2.863 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      4.418 ms/op
     p(99.9000) =     12.075 ms/op
     p(99.9900) =     12.203 ms/op
     p(99.9990) =     12.222 ms/op
     p(99.9999) =     12.222 ms/op
    p(100.0000) =     12.222 ms/op


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.148 ms/op
Iteration   1: 3.586 ±(99.9%) 0.079 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.426 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  38.999 ms/op
                 listUser·p0.9999: 39.387 ms/op
                 listUser·p1.00:   39.387 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8922
  mean =      3.586 ±(99.9%) 0.079 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 649 
    [ 2.500,  5.000) = 7878 
    [ 5.000,  7.500) = 330 
    [ 7.500, 10.000) = 20 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.426 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     38.999 ms/op
     p(99.9900) =     39.387 ms/op
     p(99.9990) =     39.387 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.483          ops/ms
ClientSimple.existUser                       thrpt         12.124          ops/ms
ClientSimple.getUser                         thrpt         12.857          ops/ms
ClientSimple.listUser                        thrpt          8.938          ops/ms
ClientSimple.createUser                       avgt          2.288           ms/op
ClientSimple.existUser                        avgt          1.852           ms/op
ClientSimple.getUser                          avgt          2.051           ms/op
ClientSimple.listUser                         avgt          3.419           ms/op
ClientSimple.createUser                     sample  12766   2.510 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.553           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.372           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.938           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.275           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.286           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.280           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.762           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.771           ms/op
ClientSimple.existUser                      sample  14098   2.279 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.539           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.245           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.679           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.871           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.760           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.943           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.043           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.043           ms/op
ClientSimple.getUser                        sample  13872   2.305 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.770           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.245           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.863           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.142           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.418           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.075           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.203           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.222           ms/op
ClientSimple.listUser                       sample   8922   3.586 ± 0.079   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.098           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.426           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.866           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.824           ms/op
ClientSimple.listUser:listUser·p0.999       sample         38.999           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         39.387           ms/op
ClientSimple.listUser:listUser·p1.00        sample         39.387           ms/op

Benchmark result is saved to 1717567922752.json
