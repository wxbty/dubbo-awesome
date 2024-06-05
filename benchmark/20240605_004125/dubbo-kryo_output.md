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
# Warmup Iteration   1: 1.575 ops/ms
Iteration   1: 6.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.280 ops/ms


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
# Warmup Iteration   1: 4.943 ops/ms
Iteration   1: 9.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  9.501 ops/ms


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
# Warmup Iteration   1: 5.357 ops/ms
Iteration   1: 11.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.939 ops/ms


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
# Warmup Iteration   1: 4.701 ops/ms
Iteration   1: 9.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.068 ops/ms


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
# Warmup Iteration   1: 4.673 ±(99.9%) 0.092 ms/op
Iteration   1: 2.294 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.294 ms/op


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
# Warmup Iteration   1: 3.116 ±(99.9%) 0.063 ms/op
Iteration   1: 1.871 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.871 ms/op


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
# Warmup Iteration   1: 3.169 ±(99.9%) 0.055 ms/op
Iteration   1: 2.021 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.021 ms/op


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
# Warmup Iteration   1: 4.820 ±(99.9%) 0.150 ms/op
Iteration   1: 3.950 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.950 ms/op


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
# Warmup Iteration   1: 3.811 ±(99.9%) 0.102 ms/op
Iteration   1: 2.308 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   1.993 ms/op
                 createUser·p0.90:   2.896 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   13.745 ms/op
                 createUser·p0.999:  21.299 ms/op
                 createUser·p0.9999: 21.503 ms/op
                 createUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13905
  mean =      2.308 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10876 
    [ 2.500,  5.000) = 2736 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =     13.745 ms/op
     p(99.9000) =     21.299 ms/op
     p(99.9900) =     21.503 ms/op
     p(99.9990) =     21.529 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 3.123 ±(99.9%) 0.096 ms/op
Iteration   1: 1.941 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   1.841 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.642 ms/op
                 existUser·p0.99:   4.016 ms/op
                 existUser·p0.999:  10.405 ms/op
                 existUser·p0.9999: 10.912 ms/op
                 existUser·p1.00:   10.912 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16472
  mean =      1.941 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 261 
    [ 1.250,  2.500) = 15010 
    [ 2.500,  3.750) = 1022 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      1.841 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      4.016 ms/op
     p(99.9000) =     10.405 ms/op
     p(99.9900) =     10.912 ms/op
     p(99.9990) =     10.912 ms/op
     p(99.9999) =     10.912 ms/op
    p(100.0000) =     10.912 ms/op


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
# Warmup Iteration   1: 3.050 ±(99.9%) 0.077 ms/op
Iteration   1: 2.034 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   1.939 ms/op
                 getUser·p0.90:   2.413 ms/op
                 getUser·p0.95:   2.576 ms/op
                 getUser·p0.99:   3.240 ms/op
                 getUser·p0.999:  24.314 ms/op
                 getUser·p0.9999: 25.076 ms/op
                 getUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15797
  mean =      2.034 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14746 
    [ 2.500,  5.000) = 975 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      3.240 ms/op
     p(99.9000) =     24.314 ms/op
     p(99.9900) =     25.076 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 4.231 ±(99.9%) 0.117 ms/op
Iteration   1: 3.211 ±(99.9%) 0.090 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   2.798 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.482 ms/op
                 listUser·p0.999:  50.219 ms/op
                 listUser·p0.9999: 60.752 ms/op
                 listUser·p1.00:   60.752 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10240
  mean =      3.211 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10092 
    [ 5.000, 10.000) = 115 
    [10.000, 15.000) = 1 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 20 
    [50.000, 55.000) = 8 
    [55.000, 60.000) = 1 
    [60.000, 65.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.482 ms/op
     p(99.9000) =     50.219 ms/op
     p(99.9900) =     60.752 ms/op
     p(99.9990) =     60.752 ms/op
     p(99.9999) =     60.752 ms/op
    p(100.0000) =     60.752 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.280          ops/ms
ClientSimple.existUser                       thrpt          9.501          ops/ms
ClientSimple.getUser                         thrpt         11.939          ops/ms
ClientSimple.listUser                        thrpt          9.068          ops/ms
ClientSimple.createUser                       avgt          2.294           ms/op
ClientSimple.existUser                        avgt          1.871           ms/op
ClientSimple.getUser                          avgt          2.021           ms/op
ClientSimple.listUser                         avgt          3.950           ms/op
ClientSimple.createUser                     sample  13905   2.308 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.561           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.993           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.896           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.138           ms/op
ClientSimple.createUser:createUser·p0.99    sample         13.745           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.299           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.503           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.529           ms/op
ClientSimple.existUser                      sample  16472   1.941 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.653           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.841           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.642           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.016           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.405           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.912           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.912           ms/op
ClientSimple.getUser                        sample  15797   2.034 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.672           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.939           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.413           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.240           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.314           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.076           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.494           ms/op
ClientSimple.listUser                       sample  10240   3.211 ± 0.090   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.165           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.798           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.969           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.482           ms/op
ClientSimple.listUser:listUser·p0.999       sample         50.219           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         60.752           ms/op
ClientSimple.listUser:listUser·p1.00        sample         60.752           ms/op

Benchmark result is saved to 1717547817884.json
