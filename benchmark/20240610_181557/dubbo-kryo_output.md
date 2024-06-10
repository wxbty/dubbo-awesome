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
# Warmup Iteration   1: 1.564 ops/ms
Iteration   1: 5.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.983 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.387 ops/ms
Iteration   1: 9.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  9.024 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.733 ops/ms
Iteration   1: 9.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.371 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.012 ops/ms
Iteration   1: 7.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.228 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.819 ±(99.9%) 0.150 ms/op
Iteration   1: 2.333 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.333 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.403 ±(99.9%) 0.065 ms/op
Iteration   1: 2.335 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.335 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.210 ±(99.9%) 0.111 ms/op
Iteration   1: 2.231 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.231 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 5.686 ±(99.9%) 0.143 ms/op
Iteration   1: 4.178 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.178 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.105 ±(99.9%) 0.129 ms/op
Iteration   1: 2.426 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   2.171 ms/op
                 createUser·p0.90:   2.840 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   8.986 ms/op
                 createUser·p0.999:  33.063 ms/op
                 createUser·p0.9999: 33.456 ms/op
                 createUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13175
  mean =      2.426 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10261 
    [ 2.500,  5.000) = 2603 
    [ 5.000,  7.500) = 166 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.171 ms/op
     p(90.0000) =      2.840 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      8.986 ms/op
     p(99.9000) =     33.063 ms/op
     p(99.9900) =     33.456 ms/op
     p(99.9990) =     33.456 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 3.507 ±(99.9%) 0.081 ms/op
Iteration   1: 1.987 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   1.810 ms/op
                 existUser·p0.90:   2.544 ms/op
                 existUser·p0.95:   2.879 ms/op
                 existUser·p0.99:   4.524 ms/op
                 existUser·p0.999:  25.625 ms/op
                 existUser·p0.9999: 26.063 ms/op
                 existUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16093
  mean =      1.987 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14323 
    [ 2.500,  5.000) = 1636 
    [ 5.000,  7.500) = 70 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      4.524 ms/op
     p(99.9000) =     25.625 ms/op
     p(99.9900) =     26.063 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 3.631 ±(99.9%) 0.118 ms/op
Iteration   1: 2.231 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   2.085 ms/op
                 getUser·p0.90:   2.744 ms/op
                 getUser·p0.95:   3.043 ms/op
                 getUser·p0.99:   5.122 ms/op
                 getUser·p0.999:  20.076 ms/op
                 getUser·p0.9999: 20.808 ms/op
                 getUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14323
  mean =      2.231 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11828 
    [ 2.500,  5.000) = 2344 
    [ 5.000,  7.500) = 86 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.085 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      5.122 ms/op
     p(99.9000) =     20.076 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 4.893 ±(99.9%) 0.172 ms/op
Iteration   1: 3.838 ±(99.9%) 0.091 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   3.424 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.365 ms/op
                 listUser·p0.99:   9.620 ms/op
                 listUser·p0.999:  33.160 ms/op
                 listUser·p0.9999: 39.191 ms/op
                 listUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8342
  mean =      3.838 ±(99.9%) 0.091 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 172 
    [ 2.500,  5.000) = 7450 
    [ 5.000,  7.500) = 583 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.365 ms/op
     p(99.0000) =      9.620 ms/op
     p(99.9000) =     33.160 ms/op
     p(99.9900) =     39.191 ms/op
     p(99.9990) =     39.191 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


# Run complete. Total time: 00:01:27

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.983          ops/ms
ClientSimple.existUser                       thrpt          9.024          ops/ms
ClientSimple.getUser                         thrpt          9.371          ops/ms
ClientSimple.listUser                        thrpt          7.228          ops/ms
ClientSimple.createUser                       avgt          2.333           ms/op
ClientSimple.existUser                        avgt          2.335           ms/op
ClientSimple.getUser                          avgt          2.231           ms/op
ClientSimple.listUser                         avgt          4.178           ms/op
ClientSimple.createUser                     sample  13175   2.426 ± 0.054   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.740           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.171           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.840           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.162           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.986           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.063           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.456           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.456           ms/op
ClientSimple.existUser                      sample  16093   1.987 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.602           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.810           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.879           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.524           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.625           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.063           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.083           ms/op
ClientSimple.getUser                        sample  14323   2.231 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.672           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.085           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.043           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.122           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.076           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.808           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.808           ms/op
ClientSimple.listUser                       sample   8342   3.838 ± 0.091   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.976           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.424           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.899           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.365           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.620           ms/op
ClientSimple.listUser:listUser·p0.999       sample         33.160           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         39.191           ms/op
ClientSimple.listUser:listUser·p1.00        sample         39.191           ms/op

Benchmark result is saved to 1718043081498.json
