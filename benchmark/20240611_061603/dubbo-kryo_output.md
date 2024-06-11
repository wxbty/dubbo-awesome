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
# Warmup Iteration   1: 2.035 ops/ms
Iteration   1: 6.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.158 ops/ms


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
# Warmup Iteration   1: 5.648 ops/ms
Iteration   1: 11.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.402 ops/ms


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
# Warmup Iteration   1: 4.962 ops/ms
Iteration   1: 10.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.061 ops/ms


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
# Warmup Iteration   1: 4.157 ops/ms
Iteration   1: 7.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.834 ops/ms


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
# Warmup Iteration   1: 4.507 ±(99.9%) 0.104 ms/op
Iteration   1: 2.372 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.372 ms/op


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
# Warmup Iteration   1: 3.694 ±(99.9%) 0.063 ms/op
Iteration   1: 1.853 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.853 ms/op


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
# Warmup Iteration   1: 3.441 ±(99.9%) 0.059 ms/op
Iteration   1: 2.001 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.001 ms/op


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
# Warmup Iteration   1: 4.584 ±(99.9%) 0.123 ms/op
Iteration   1: 3.770 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.770 ms/op


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
# Warmup Iteration   1: 4.145 ±(99.9%) 0.148 ms/op
Iteration   1: 2.197 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.572 ms/op
                 createUser·p0.50:   1.927 ms/op
                 createUser·p0.90:   2.834 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   8.717 ms/op
                 createUser·p0.999:  17.727 ms/op
                 createUser·p0.9999: 18.448 ms/op
                 createUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14698
  mean =      2.197 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 348 
    [ 1.250,  2.500) = 11714 
    [ 2.500,  3.750) = 2225 
    [ 3.750,  5.000) = 112 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      1.927 ms/op
     p(90.0000) =      2.834 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      8.717 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     18.448 ms/op
     p(99.9990) =     18.448 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 3.481 ±(99.9%) 0.143 ms/op
Iteration   1: 2.076 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   1.894 ms/op
                 existUser·p0.90:   2.454 ms/op
                 existUser·p0.95:   2.719 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  24.052 ms/op
                 existUser·p0.9999: 24.765 ms/op
                 existUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15403
  mean =      2.076 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14080 
    [ 2.500,  5.000) = 1162 
    [ 5.000,  7.500) = 94 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      1.894 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.719 ms/op
     p(99.0000) =      5.161 ms/op
     p(99.9000) =     24.052 ms/op
     p(99.9900) =     24.765 ms/op
     p(99.9990) =     24.871 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 3.632 ±(99.9%) 0.135 ms/op
Iteration   1: 1.947 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   1.853 ms/op
                 getUser·p0.90:   2.388 ms/op
                 getUser·p0.95:   2.531 ms/op
                 getUser·p0.99:   4.017 ms/op
                 getUser·p0.999:  11.855 ms/op
                 getUser·p0.9999: 12.705 ms/op
                 getUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16423
  mean =      1.947 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 229 
    [ 1.250,  2.500) = 15273 
    [ 2.500,  3.750) = 738 
    [ 3.750,  5.000) = 117 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.531 ms/op
     p(99.0000) =      4.017 ms/op
     p(99.9000) =     11.855 ms/op
     p(99.9900) =     12.705 ms/op
     p(99.9990) =     12.747 ms/op
     p(99.9999) =     12.747 ms/op
    p(100.0000) =     12.747 ms/op


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
# Warmup Iteration   1: 4.612 ±(99.9%) 0.135 ms/op
Iteration   1: 3.314 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   0.803 ms/op
                 listUser·p0.50:   3.187 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   8.233 ms/op
                 listUser·p0.999:  23.265 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9648
  mean =      3.314 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1538 
    [ 2.500,  5.000) = 7905 
    [ 5.000,  7.500) = 107 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      8.233 ms/op
     p(99.9000) =     23.265 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.158          ops/ms
ClientSimple.existUser                       thrpt         11.402          ops/ms
ClientSimple.getUser                         thrpt         10.061          ops/ms
ClientSimple.listUser                        thrpt          7.834          ops/ms
ClientSimple.createUser                       avgt          2.372           ms/op
ClientSimple.existUser                        avgt          1.853           ms/op
ClientSimple.getUser                          avgt          2.001           ms/op
ClientSimple.listUser                         avgt          3.770           ms/op
ClientSimple.createUser                     sample  14698   2.197 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.572           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.927           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.834           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.162           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.717           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.727           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.448           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.448           ms/op
ClientSimple.existUser                      sample  15403   2.076 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.878           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.894           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.454           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.719           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.161           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.052           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.765           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.871           ms/op
ClientSimple.getUser                        sample  16423   1.947 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.658           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.853           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.388           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.531           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.017           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.855           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.705           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.747           ms/op
ClientSimple.listUser                       sample   9648   3.314 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.803           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.187           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.084           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.233           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.265           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.019           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.019           ms/op

Benchmark result is saved to 1718086312440.json
