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
# Warmup Iteration   1: 1.537 ops/ms
Iteration   1: 6.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.750 ops/ms


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
# Warmup Iteration   1: 5.257 ops/ms
Iteration   1: 13.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.002 ops/ms


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
# Warmup Iteration   1: 5.246 ops/ms
Iteration   1: 11.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.652 ops/ms


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
# Warmup Iteration   1: 4.634 ops/ms
Iteration   1: 8.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.611 ops/ms


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.070 ms/op
Iteration   1: 2.020 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.020 ms/op


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
# Warmup Iteration   1: 3.147 ±(99.9%) 0.060 ms/op
Iteration   1: 1.838 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.838 ms/op


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
# Warmup Iteration   1: 3.466 ±(99.9%) 0.067 ms/op
Iteration   1: 2.141 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.141 ms/op


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.082 ms/op
Iteration   1: 3.104 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.104 ms/op


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
# Warmup Iteration   1: 3.536 ±(99.9%) 0.085 ms/op
Iteration   1: 2.349 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   2.167 ms/op
                 createUser·p0.90:   2.802 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   7.348 ms/op
                 createUser·p0.999:  23.023 ms/op
                 createUser·p0.9999: 25.154 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13701
  mean =      2.349 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10286 
    [ 2.500,  5.000) = 3207 
    [ 5.000,  7.500) = 92 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.802 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     23.023 ms/op
     p(99.9900) =     25.154 ms/op
     p(99.9990) =     25.166 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 3.099 ±(99.9%) 0.073 ms/op
Iteration   1: 1.716 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.495 ms/op
                 existUser·p0.50:   1.604 ms/op
                 existUser·p0.90:   2.073 ms/op
                 existUser·p0.95:   2.367 ms/op
                 existUser·p0.99:   4.257 ms/op
                 existUser·p0.999:  14.981 ms/op
                 existUser·p0.9999: 15.831 ms/op
                 existUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18632
  mean =      1.716 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1439 
    [ 1.250,  2.500) = 16467 
    [ 2.500,  3.750) = 491 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      1.604 ms/op
     p(90.0000) =      2.073 ms/op
     p(95.0000) =      2.367 ms/op
     p(99.0000) =      4.257 ms/op
     p(99.9000) =     14.981 ms/op
     p(99.9900) =     15.831 ms/op
     p(99.9990) =     15.958 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


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
# Warmup Iteration   1: 3.355 ±(99.9%) 0.082 ms/op
Iteration   1: 1.827 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.477 ms/op
                 getUser·p0.50:   1.708 ms/op
                 getUser·p0.90:   2.236 ms/op
                 getUser·p0.95:   2.400 ms/op
                 getUser·p0.99:   3.330 ms/op
                 getUser·p0.999:  15.322 ms/op
                 getUser·p0.9999: 15.486 ms/op
                 getUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17797
  mean =      1.827 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 403 
    [ 1.250,  2.500) = 16748 
    [ 2.500,  3.750) = 531 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      1.708 ms/op
     p(90.0000) =      2.236 ms/op
     p(95.0000) =      2.400 ms/op
     p(99.0000) =      3.330 ms/op
     p(99.9000) =     15.322 ms/op
     p(99.9900) =     15.486 ms/op
     p(99.9990) =     15.499 ms/op
     p(99.9999) =     15.499 ms/op
    p(100.0000) =     15.499 ms/op


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
# Warmup Iteration   1: 4.661 ±(99.9%) 0.143 ms/op
Iteration   1: 3.411 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   0.473 ms/op
                 listUser·p0.50:   3.133 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.882 ms/op
                 listUser·p0.999:  27.853 ms/op
                 listUser·p0.9999: 28.803 ms/op
                 listUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9372
  mean =      3.411 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 703 
    [ 2.500,  5.000) = 8345 
    [ 5.000,  7.500) = 286 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     27.853 ms/op
     p(99.9900) =     28.803 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.750          ops/ms
ClientSimple.existUser                       thrpt         13.002          ops/ms
ClientSimple.getUser                         thrpt         11.652          ops/ms
ClientSimple.listUser                        thrpt          8.611          ops/ms
ClientSimple.createUser                       avgt          2.020           ms/op
ClientSimple.existUser                        avgt          1.838           ms/op
ClientSimple.getUser                          avgt          2.141           ms/op
ClientSimple.listUser                         avgt          3.104           ms/op
ClientSimple.createUser                     sample  13701   2.349 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.892           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.167           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.802           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.101           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.348           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.023           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.154           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.166           ms/op
ClientSimple.existUser                      sample  18632   1.716 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.495           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.604           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.073           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.257           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.981           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.831           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.958           ms/op
ClientSimple.getUser                        sample  17797   1.827 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.477           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.708           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.236           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.400           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.330           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.322           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.486           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.499           ms/op
ClientSimple.listUser                       sample   9372   3.411 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.473           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.133           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.882           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.853           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.803           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.803           ms/op

Benchmark result is saved to 1718647878724.json
