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
# Warmup Iteration   1: 1.699 ops/ms
Iteration   1: 6.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.831 ops/ms


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
# Warmup Iteration   1: 7.010 ops/ms
Iteration   1: 12.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.308 ops/ms


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
# Warmup Iteration   1: 6.397 ops/ms
Iteration   1: 14.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.074 ops/ms


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
# Warmup Iteration   1: 6.085 ops/ms
Iteration   1: 8.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.745 ops/ms


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
# Warmup Iteration   1: 3.675 ±(99.9%) 0.071 ms/op
Iteration   1: 2.206 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.206 ms/op


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
# Warmup Iteration   1: 2.876 ±(99.9%) 0.047 ms/op
Iteration   1: 1.819 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.819 ms/op


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
# Warmup Iteration   1: 2.942 ±(99.9%) 0.051 ms/op
Iteration   1: 2.004 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.004 ms/op


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
# Warmup Iteration   1: 4.506 ±(99.9%) 0.091 ms/op
Iteration   1: 3.431 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.431 ms/op


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
# Warmup Iteration   1: 3.644 ±(99.9%) 0.087 ms/op
Iteration   1: 2.245 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.617 ms/op
                 createUser·p0.50:   2.071 ms/op
                 createUser·p0.90:   2.605 ms/op
                 createUser·p0.95:   2.945 ms/op
                 createUser·p0.99:   6.686 ms/op
                 createUser·p0.999:  15.811 ms/op
                 createUser·p0.9999: 16.776 ms/op
                 createUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14253
  mean =      2.245 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 12064 
    [ 2.500,  3.750) = 1930 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      6.686 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     16.776 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 3.291 ±(99.9%) 0.080 ms/op
Iteration   1: 1.907 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.442 ms/op
                 existUser·p0.50:   1.827 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.556 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  23.298 ms/op
                 existUser·p0.9999: 23.702 ms/op
                 existUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16764
  mean =      1.907 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15775 
    [ 2.500,  5.000) = 876 
    [ 5.000,  7.500) = 49 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =     23.298 ms/op
     p(99.9900) =     23.702 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 3.251 ±(99.9%) 0.087 ms/op
Iteration   1: 2.029 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   1.931 ms/op
                 getUser·p0.90:   2.597 ms/op
                 getUser·p0.95:   2.863 ms/op
                 getUser·p0.99:   3.600 ms/op
                 getUser·p0.999:  12.471 ms/op
                 getUser·p0.9999: 12.878 ms/op
                 getUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15803
  mean =      2.029 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 13734 
    [ 2.500,  3.750) = 1821 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      3.600 ms/op
     p(99.9000) =     12.471 ms/op
     p(99.9900) =     12.878 ms/op
     p(99.9990) =     12.878 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


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
# Warmup Iteration   1: 4.541 ±(99.9%) 0.172 ms/op
Iteration   1: 3.626 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.313 ms/op
                 listUser·p0.999:  12.141 ms/op
                 listUser·p0.9999: 12.419 ms/op
                 listUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8838
  mean =      3.626 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 869 
    [ 2.500,  3.750) = 3773 
    [ 3.750,  5.000) = 3827 
    [ 5.000,  6.250) = 259 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.313 ms/op
     p(99.9000) =     12.141 ms/op
     p(99.9900) =     12.419 ms/op
     p(99.9990) =     12.419 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.831          ops/ms
ClientSimple.existUser                       thrpt         12.308          ops/ms
ClientSimple.getUser                         thrpt         14.074          ops/ms
ClientSimple.listUser                        thrpt          8.745          ops/ms
ClientSimple.createUser                       avgt          2.206           ms/op
ClientSimple.existUser                        avgt          1.819           ms/op
ClientSimple.getUser                          avgt          2.004           ms/op
ClientSimple.listUser                         avgt          3.431           ms/op
ClientSimple.createUser                     sample  14253   2.245 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.617           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.071           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.605           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.945           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.686           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.811           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.776           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.908           ms/op
ClientSimple.existUser                      sample  16764   1.907 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.442           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.827           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.538           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.298           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.702           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.724           ms/op
ClientSimple.getUser                        sample  15803   2.029 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.744           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.931           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.597           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.863           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.600           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.471           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.878           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.878           ms/op
ClientSimple.listUser                       sample   8838   3.626 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.921           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.703           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.563           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.915           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.313           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.141           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.419           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.419           ms/op

Benchmark result is saved to 1719144870113.json
