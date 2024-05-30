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
# Warmup Iteration   1: 1.984 ops/ms
Iteration   1: 6.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.868 ops/ms


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
# Warmup Iteration   1: 5.081 ops/ms
Iteration   1: 12.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.183 ops/ms


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
# Warmup Iteration   1: 5.534 ops/ms
Iteration   1: 12.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.490 ops/ms


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
# Warmup Iteration   1: 6.020 ops/ms
Iteration   1: 8.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.151 ops/ms


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
# Warmup Iteration   1: 4.481 ±(99.9%) 0.078 ms/op
Iteration   1: 2.194 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.194 ms/op


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
# Warmup Iteration   1: 3.215 ±(99.9%) 0.043 ms/op
Iteration   1: 2.015 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.015 ms/op


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
# Warmup Iteration   1: 3.425 ±(99.9%) 0.049 ms/op
Iteration   1: 2.285 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.285 ms/op


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
# Warmup Iteration   1: 4.449 ±(99.9%) 0.079 ms/op
Iteration   1: 3.958 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.958 ms/op


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
# Warmup Iteration   1: 3.594 ±(99.9%) 0.086 ms/op
Iteration   1: 2.423 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.517 ms/op
                 createUser·p0.50:   2.351 ms/op
                 createUser·p0.90:   2.822 ms/op
                 createUser·p0.95:   3.027 ms/op
                 createUser·p0.99:   5.188 ms/op
                 createUser·p0.999:  17.433 ms/op
                 createUser·p0.9999: 18.472 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13271
  mean =      2.423 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 8880 
    [ 2.500,  3.750) = 4023 
    [ 3.750,  5.000) = 130 
    [ 5.000,  6.250) = 80 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      2.351 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      5.188 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     18.472 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 2.849 ±(99.9%) 0.062 ms/op
Iteration   1: 2.026 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.591 ms/op
                 existUser·p0.50:   1.911 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.556 ms/op
                 existUser·p0.99:   3.392 ms/op
                 existUser·p0.999:  28.129 ms/op
                 existUser·p0.9999: 29.064 ms/op
                 existUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15779
  mean =      2.026 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14803 
    [ 2.500,  5.000) = 884 
    [ 5.000,  7.500) = 28 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      3.392 ms/op
     p(99.9000) =     28.129 ms/op
     p(99.9900) =     29.064 ms/op
     p(99.9990) =     29.196 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 2.938 ±(99.9%) 0.069 ms/op
Iteration   1: 2.026 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.374 ms/op
                 getUser·p0.50:   1.909 ms/op
                 getUser·p0.90:   2.490 ms/op
                 getUser·p0.95:   2.712 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  25.560 ms/op
                 getUser·p0.9999: 26.819 ms/op
                 getUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15985
  mean =      2.026 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14475 
    [ 2.500,  5.000) = 1425 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =     25.560 ms/op
     p(99.9900) =     26.819 ms/op
     p(99.9990) =     27.329 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 4.562 ±(99.9%) 0.128 ms/op
Iteration   1: 3.635 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.896 ms/op
                 listUser·p0.99:   10.240 ms/op
                 listUser·p0.999:  23.495 ms/op
                 listUser·p0.9999: 24.445 ms/op
                 listUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8787
  mean =      3.635 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 370 
    [ 2.500,  5.000) = 8028 
    [ 5.000,  7.500) = 287 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.896 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     23.495 ms/op
     p(99.9900) =     24.445 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.868          ops/ms
ClientSimple.existUser                       thrpt         12.183          ops/ms
ClientSimple.getUser                         thrpt         12.490          ops/ms
ClientSimple.listUser                        thrpt          8.151          ops/ms
ClientSimple.createUser                       avgt          2.194           ms/op
ClientSimple.existUser                        avgt          2.015           ms/op
ClientSimple.getUser                          avgt          2.285           ms/op
ClientSimple.listUser                         avgt          3.958           ms/op
ClientSimple.createUser                     sample  13271   2.423 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.517           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.351           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.027           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.188           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.433           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.472           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.547           ms/op
ClientSimple.existUser                      sample  15779   2.026 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.591           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.911           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.392           ms/op
ClientSimple.existUser:existUser·p0.999     sample         28.129           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.064           ms/op
ClientSimple.existUser:existUser·p1.00      sample         29.196           ms/op
ClientSimple.getUser                        sample  15985   2.026 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.374           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.909           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.490           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.998           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.560           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.819           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.329           ms/op
ClientSimple.listUser                       sample   8787   3.635 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.953           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.539           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.896           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.240           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.495           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.445           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.445           ms/op

Benchmark result is saved to 1717049499700.json
