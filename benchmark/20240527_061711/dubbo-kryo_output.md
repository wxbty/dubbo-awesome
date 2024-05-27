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
# Warmup Iteration   1: 2.030 ops/ms
Iteration   1: 7.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.332 ops/ms


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
# Warmup Iteration   1: 6.124 ops/ms
Iteration   1: 12.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.032 ops/ms


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
# Warmup Iteration   1: 5.335 ops/ms
Iteration   1: 13.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.602 ops/ms


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
# Warmup Iteration   1: 4.397 ops/ms
Iteration   1: 8.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.550 ops/ms


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
# Warmup Iteration   1: 4.068 ±(99.9%) 0.078 ms/op
Iteration   1: 2.387 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.387 ms/op


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
# Warmup Iteration   1: 3.399 ±(99.9%) 0.064 ms/op
Iteration   1: 1.860 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.860 ms/op


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
# Warmup Iteration   1: 3.451 ±(99.9%) 0.059 ms/op
Iteration   1: 2.103 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.103 ms/op


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
# Warmup Iteration   1: 4.160 ±(99.9%) 0.093 ms/op
Iteration   1: 3.636 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.636 ms/op


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
# Warmup Iteration   1: 3.468 ±(99.9%) 0.084 ms/op
Iteration   1: 2.182 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.484 ms/op
                 createUser·p0.50:   1.923 ms/op
                 createUser·p0.90:   2.482 ms/op
                 createUser·p0.95:   2.834 ms/op
                 createUser·p0.99:   10.191 ms/op
                 createUser·p0.999:  28.705 ms/op
                 createUser·p0.9999: 28.853 ms/op
                 createUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14627
  mean =      2.182 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13253 
    [ 2.500,  5.000) = 1041 
    [ 5.000,  7.500) = 105 
    [ 7.500, 10.000) = 75 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     28.705 ms/op
     p(99.9900) =     28.853 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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
# Warmup Iteration   1: 2.924 ±(99.9%) 0.062 ms/op
Iteration   1: 1.732 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   1.683 ms/op
                 existUser·p0.90:   1.958 ms/op
                 existUser·p0.95:   2.146 ms/op
                 existUser·p0.99:   2.987 ms/op
                 existUser·p0.999:  10.797 ms/op
                 existUser·p0.9999: 11.631 ms/op
                 existUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18484
  mean =      1.732 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 193 
    [ 1.250,  2.500) = 17975 
    [ 2.500,  3.750) = 206 
    [ 3.750,  5.000) = 56 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      1.683 ms/op
     p(90.0000) =      1.958 ms/op
     p(95.0000) =      2.146 ms/op
     p(99.0000) =      2.987 ms/op
     p(99.9000) =     10.797 ms/op
     p(99.9900) =     11.631 ms/op
     p(99.9990) =     11.715 ms/op
     p(99.9999) =     11.715 ms/op
    p(100.0000) =     11.715 ms/op


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
# Warmup Iteration   1: 3.407 ±(99.9%) 0.086 ms/op
Iteration   1: 2.187 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.374 ms/op
                 getUser·p0.50:   1.993 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.330 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  11.076 ms/op
                 getUser·p0.9999: 11.297 ms/op
                 getUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14606
  mean =      2.187 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 212 
    [ 1.250,  2.500) = 10321 
    [ 2.500,  3.750) = 3913 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.330 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =     11.076 ms/op
     p(99.9900) =     11.297 ms/op
     p(99.9990) =     11.305 ms/op
     p(99.9999) =     11.305 ms/op
    p(100.0000) =     11.305 ms/op


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
# Warmup Iteration   1: 4.353 ±(99.9%) 0.132 ms/op
Iteration   1: 3.050 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   0.560 ms/op
                 listUser·p0.50:   2.851 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   4.051 ms/op
                 listUser·p0.99:   5.289 ms/op
                 listUser·p0.999:  24.674 ms/op
                 listUser·p0.9999: 25.965 ms/op
                 listUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10505
  mean =      3.050 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1397 
    [ 2.500,  5.000) = 8990 
    [ 5.000,  7.500) = 60 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.289 ms/op
     p(99.9000) =     24.674 ms/op
     p(99.9900) =     25.965 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.332          ops/ms
ClientSimple.existUser                       thrpt         12.032          ops/ms
ClientSimple.getUser                         thrpt         13.602          ops/ms
ClientSimple.listUser                        thrpt          8.550          ops/ms
ClientSimple.createUser                       avgt          2.387           ms/op
ClientSimple.existUser                        avgt          1.860           ms/op
ClientSimple.getUser                          avgt          2.103           ms/op
ClientSimple.listUser                         avgt          3.636           ms/op
ClientSimple.createUser                     sample  14627   2.182 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.484           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.923           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.482           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.834           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.191           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.705           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.853           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.869           ms/op
ClientSimple.existUser                      sample  18484   1.732 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.696           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.683           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.958           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.146           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.987           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.797           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.631           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.715           ms/op
ClientSimple.getUser                        sample  14606   2.187 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.374           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.993           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.080           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.330           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.797           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.076           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.297           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.305           ms/op
ClientSimple.listUser                       sample  10505   3.050 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.560           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.851           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.781           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.051           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.289           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.674           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.965           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.985           ms/op

Benchmark result is saved to 1716790362496.json
