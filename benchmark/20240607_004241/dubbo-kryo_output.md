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
# Warmup Iteration   1: 1.661 ops/ms
Iteration   1: 6.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.590 ops/ms


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
# Warmup Iteration   1: 6.257 ops/ms
Iteration   1: 12.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.231 ops/ms


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
# Warmup Iteration   1: 5.968 ops/ms
Iteration   1: 13.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.041 ops/ms


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
# Warmup Iteration   1: 4.314 ops/ms
Iteration   1: 9.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.016 ops/ms


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
# Warmup Iteration   1: 3.444 ±(99.9%) 0.055 ms/op
Iteration   1: 1.962 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.962 ms/op


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
# Warmup Iteration   1: 3.231 ±(99.9%) 0.049 ms/op
Iteration   1: 1.886 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.886 ms/op


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
# Warmup Iteration   1: 2.969 ±(99.9%) 0.046 ms/op
Iteration   1: 1.826 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.826 ms/op


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
# Warmup Iteration   1: 4.812 ±(99.9%) 0.094 ms/op
Iteration   1: 3.135 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.135 ms/op


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
# Warmup Iteration   1: 3.116 ±(99.9%) 0.081 ms/op
Iteration   1: 2.010 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.537 ms/op
                 createUser·p0.50:   1.849 ms/op
                 createUser·p0.90:   2.490 ms/op
                 createUser·p0.95:   2.773 ms/op
                 createUser·p0.99:   4.052 ms/op
                 createUser·p0.999:  18.874 ms/op
                 createUser·p0.9999: 20.115 ms/op
                 createUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15984
  mean =      2.010 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14421 
    [ 2.500,  5.000) = 1422 
    [ 5.000,  7.500) = 38 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      4.052 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     20.115 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 2.985 ±(99.9%) 0.071 ms/op
Iteration   1: 1.887 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.601 ms/op
                 existUser·p0.50:   1.724 ms/op
                 existUser·p0.90:   2.413 ms/op
                 existUser·p0.95:   2.834 ms/op
                 existUser·p0.99:   3.215 ms/op
                 existUser·p0.999:  16.581 ms/op
                 existUser·p0.9999: 16.679 ms/op
                 existUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16934
  mean =      1.887 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 15324 
    [ 2.500,  3.750) = 1457 
    [ 3.750,  5.000) = 7 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      1.724 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      3.215 ms/op
     p(99.9000) =     16.581 ms/op
     p(99.9900) =     16.679 ms/op
     p(99.9990) =     16.679 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


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
# Warmup Iteration   1: 3.377 ±(99.9%) 0.081 ms/op
Iteration   1: 1.966 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.540 ms/op
                 getUser·p0.50:   1.796 ms/op
                 getUser·p0.90:   2.589 ms/op
                 getUser·p0.95:   2.769 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  13.019 ms/op
                 getUser·p0.9999: 13.811 ms/op
                 getUser·p1.00:   13.926 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16408
  mean =      1.966 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 353 
    [ 1.250,  2.500) = 13833 
    [ 2.500,  3.750) = 2062 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =     13.019 ms/op
     p(99.9900) =     13.811 ms/op
     p(99.9990) =     13.926 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


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
# Warmup Iteration   1: 4.469 ±(99.9%) 0.157 ms/op
Iteration   1: 3.437 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.030 ms/op
                 listUser·p0.999:  6.400 ms/op
                 listUser·p0.9999: 7.266 ms/op
                 listUser·p1.00:   7.266 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9406
  mean =      3.437 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 7 
    [1.500, 2.000) = 99 
    [2.000, 2.500) = 844 
    [2.500, 3.000) = 928 
    [3.000, 3.500) = 2638 
    [3.500, 4.000) = 3675 
    [4.000, 4.500) = 953 
    [4.500, 5.000) = 161 
    [5.000, 5.500) = 56 
    [5.500, 6.000) = 26 
    [6.000, 6.500) = 12 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =      6.400 ms/op
     p(99.9900) =      7.266 ms/op
     p(99.9990) =      7.266 ms/op
     p(99.9999) =      7.266 ms/op
    p(100.0000) =      7.266 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.590          ops/ms
ClientSimple.existUser                       thrpt         12.231          ops/ms
ClientSimple.getUser                         thrpt         13.041          ops/ms
ClientSimple.listUser                        thrpt          9.016          ops/ms
ClientSimple.createUser                       avgt          1.962           ms/op
ClientSimple.existUser                        avgt          1.886           ms/op
ClientSimple.getUser                          avgt          1.826           ms/op
ClientSimple.listUser                         avgt          3.135           ms/op
ClientSimple.createUser                     sample  15984   2.010 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.537           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.849           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.490           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.773           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.052           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.874           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.115           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.840           ms/op
ClientSimple.existUser                      sample  16934   1.887 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.601           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.724           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.413           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.834           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.215           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.581           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.679           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.679           ms/op
ClientSimple.getUser                        sample  16408   1.966 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.540           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.796           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.769           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.637           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.019           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.811           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.926           ms/op
ClientSimple.listUser                       sample   9406   3.437 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.100           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.523           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.084           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.030           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.400           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.266           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.266           ms/op

Benchmark result is saved to 1717720686252.json
