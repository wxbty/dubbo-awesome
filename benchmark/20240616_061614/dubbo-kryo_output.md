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
# Warmup Iteration   1: 2.163 ops/ms
Iteration   1: 7.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.002 ops/ms


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
# Warmup Iteration   1: 5.978 ops/ms
Iteration   1: 11.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.903 ops/ms


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
# Warmup Iteration   1: 6.368 ops/ms
Iteration   1: 13.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.919 ops/ms


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
# Warmup Iteration   1: 4.013 ops/ms
Iteration   1: 7.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.975 ops/ms


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
# Warmup Iteration   1: 3.541 ±(99.9%) 0.063 ms/op
Iteration   1: 1.935 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.935 ms/op


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
# Warmup Iteration   1: 3.535 ±(99.9%) 0.056 ms/op
Iteration   1: 1.869 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.869 ms/op


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
# Warmup Iteration   1: 3.258 ±(99.9%) 0.058 ms/op
Iteration   1: 2.150 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.150 ms/op


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
# Warmup Iteration   1: 4.923 ±(99.9%) 0.104 ms/op
Iteration   1: 3.560 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.560 ms/op


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
# Warmup Iteration   1: 3.530 ±(99.9%) 0.092 ms/op
Iteration   1: 2.268 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   2.105 ms/op
                 createUser·p0.90:   2.716 ms/op
                 createUser·p0.95:   2.949 ms/op
                 createUser·p0.99:   9.667 ms/op
                 createUser·p0.999:  18.022 ms/op
                 createUser·p0.9999: 22.225 ms/op
                 createUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14085
  mean =      2.268 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11777 
    [ 2.500,  5.000) = 2147 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      2.949 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     22.225 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.413 ±(99.9%) 0.101 ms/op
Iteration   1: 2.094 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.467 ms/op
                 existUser·p0.50:   1.968 ms/op
                 existUser·p0.90:   2.691 ms/op
                 existUser·p0.95:   2.945 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  12.304 ms/op
                 existUser·p0.9999: 12.778 ms/op
                 existUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15285
  mean =      2.094 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 236 
    [ 1.250,  2.500) = 12402 
    [ 2.500,  3.750) = 2435 
    [ 3.750,  5.000) = 106 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =     12.304 ms/op
     p(99.9900) =     12.778 ms/op
     p(99.9990) =     13.107 ms/op
     p(99.9999) =     13.107 ms/op
    p(100.0000) =     13.107 ms/op


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
# Warmup Iteration   1: 3.368 ±(99.9%) 0.075 ms/op
Iteration   1: 1.857 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.415 ms/op
                 getUser·p0.50:   1.726 ms/op
                 getUser·p0.90:   2.339 ms/op
                 getUser·p0.95:   2.499 ms/op
                 getUser·p0.99:   3.054 ms/op
                 getUser·p0.999:  15.679 ms/op
                 getUser·p0.9999: 16.465 ms/op
                 getUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17238
  mean =      1.857 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 167 
    [ 1.250,  2.500) = 16230 
    [ 2.500,  3.750) = 755 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.499 ms/op
     p(99.0000) =      3.054 ms/op
     p(99.9000) =     15.679 ms/op
     p(99.9900) =     16.465 ms/op
     p(99.9990) =     16.548 ms/op
     p(99.9999) =     16.548 ms/op
    p(100.0000) =     16.548 ms/op


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
# Warmup Iteration   1: 4.441 ±(99.9%) 0.173 ms/op
Iteration   1: 3.326 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.310 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  6.988 ms/op
                 listUser·p0.9999: 7.709 ms/op
                 listUser·p1.00:   7.709 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9646
  mean =      3.326 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 8 
    [1.500, 2.000) = 74 
    [2.000, 2.500) = 1002 
    [2.500, 3.000) = 2874 
    [3.000, 3.500) = 1552 
    [3.500, 4.000) = 2362 
    [4.000, 4.500) = 1367 
    [4.500, 5.000) = 280 
    [5.000, 5.500) = 20 
    [5.500, 6.000) = 56 
    [6.000, 6.500) = 5 
    [6.500, 7.000) = 38 
    [7.000, 7.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      6.988 ms/op
     p(99.9900) =      7.709 ms/op
     p(99.9990) =      7.709 ms/op
     p(99.9999) =      7.709 ms/op
    p(100.0000) =      7.709 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.002          ops/ms
ClientSimple.existUser                       thrpt         11.903          ops/ms
ClientSimple.getUser                         thrpt         13.919          ops/ms
ClientSimple.listUser                        thrpt          7.975          ops/ms
ClientSimple.createUser                       avgt          1.935           ms/op
ClientSimple.existUser                        avgt          1.869           ms/op
ClientSimple.getUser                          avgt          2.150           ms/op
ClientSimple.listUser                         avgt          3.560           ms/op
ClientSimple.createUser                     sample  14085   2.268 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.733           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.105           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.716           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.949           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.667           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.022           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.225           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.019           ms/op
ClientSimple.existUser                      sample  15285   2.094 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.467           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.968           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.691           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.945           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.325           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.304           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.778           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.107           ms/op
ClientSimple.getUser                        sample  17238   1.857 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.415           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.726           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.339           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.499           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.054           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.679           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.465           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.548           ms/op
ClientSimple.listUser                       sample   9646   3.326 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.061           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.310           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.562           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.988           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.709           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.709           ms/op

Benchmark result is saved to 1718518300637.json
