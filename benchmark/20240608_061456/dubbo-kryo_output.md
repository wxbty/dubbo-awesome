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
# Warmup Iteration   1: 1.348 ops/ms
Iteration   1: 7.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.139 ops/ms


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
# Warmup Iteration   1: 5.671 ops/ms
Iteration   1: 11.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.757 ops/ms


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
# Warmup Iteration   1: 4.362 ops/ms
Iteration   1: 12.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.265 ops/ms


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
# Warmup Iteration   1: 5.369 ops/ms
Iteration   1: 9.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.127 ops/ms


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.065 ms/op
Iteration   1: 1.956 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.956 ms/op


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
# Warmup Iteration   1: 3.482 ±(99.9%) 0.071 ms/op
Iteration   1: 1.866 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.866 ms/op


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
# Warmup Iteration   1: 3.541 ±(99.9%) 0.073 ms/op
Iteration   1: 2.101 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.101 ms/op


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
# Warmup Iteration   1: 4.743 ±(99.9%) 0.097 ms/op
Iteration   1: 3.262 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.262 ms/op


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.106 ms/op
Iteration   1: 2.246 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   1.993 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   2.974 ms/op
                 createUser·p0.99:   10.179 ms/op
                 createUser·p0.999:  24.838 ms/op
                 createUser·p0.9999: 24.960 ms/op
                 createUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14225
  mean =      2.246 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12053 
    [ 2.500,  5.000) = 1842 
    [ 5.000,  7.500) = 138 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.974 ms/op
     p(99.0000) =     10.179 ms/op
     p(99.9000) =     24.838 ms/op
     p(99.9900) =     24.960 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 3.212 ±(99.9%) 0.086 ms/op
Iteration   1: 1.811 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   1.778 ms/op
                 existUser·p0.90:   2.142 ms/op
                 existUser·p0.95:   2.290 ms/op
                 existUser·p0.99:   2.700 ms/op
                 existUser·p0.999:  11.551 ms/op
                 existUser·p0.9999: 11.804 ms/op
                 existUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17680
  mean =      1.811 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 416 
    [ 1.250,  2.500) = 16907 
    [ 2.500,  3.750) = 293 
    [ 3.750,  5.000) = 0 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.142 ms/op
     p(95.0000) =      2.290 ms/op
     p(99.0000) =      2.700 ms/op
     p(99.9000) =     11.551 ms/op
     p(99.9900) =     11.804 ms/op
     p(99.9990) =     11.829 ms/op
     p(99.9999) =     11.829 ms/op
    p(100.0000) =     11.829 ms/op


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
# Warmup Iteration   1: 3.170 ±(99.9%) 0.076 ms/op
Iteration   1: 1.950 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.611 ms/op
                 getUser·p0.50:   1.832 ms/op
                 getUser·p0.90:   2.191 ms/op
                 getUser·p0.95:   2.347 ms/op
                 getUser·p0.99:   3.580 ms/op
                 getUser·p0.999:  22.728 ms/op
                 getUser·p0.9999: 24.066 ms/op
                 getUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16388
  mean =      1.950 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15882 
    [ 2.500,  5.000) = 395 
    [ 5.000,  7.500) = 47 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      1.832 ms/op
     p(90.0000) =      2.191 ms/op
     p(95.0000) =      2.347 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =     22.728 ms/op
     p(99.9900) =     24.066 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 4.851 ±(99.9%) 0.144 ms/op
Iteration   1: 3.117 ±(99.9%) 0.067 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   2.757 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.264 ms/op
                 listUser·p0.999:  28.148 ms/op
                 listUser·p0.9999: 29.061 ms/op
                 listUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10264
  mean =      3.117 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2156 
    [ 2.500,  5.000) = 7887 
    [ 5.000,  7.500) = 122 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      2.757 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.264 ms/op
     p(99.9000) =     28.148 ms/op
     p(99.9900) =     29.061 ms/op
     p(99.9990) =     29.065 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.139          ops/ms
ClientSimple.existUser                       thrpt         11.757          ops/ms
ClientSimple.getUser                         thrpt         12.265          ops/ms
ClientSimple.listUser                        thrpt          9.127          ops/ms
ClientSimple.createUser                       avgt          1.956           ms/op
ClientSimple.existUser                        avgt          1.866           ms/op
ClientSimple.getUser                          avgt          2.101           ms/op
ClientSimple.listUser                         avgt          3.262           ms/op
ClientSimple.createUser                     sample  14225   2.246 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.754           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.993           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.974           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.179           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.838           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.960           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.002           ms/op
ClientSimple.existUser                      sample  17680   1.811 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.631           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.778           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.142           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.290           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.700           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.551           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.804           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.829           ms/op
ClientSimple.getUser                        sample  16388   1.950 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.611           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.832           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.191           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.347           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.580           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.728           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.066           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.150           ms/op
ClientSimple.listUser                       sample  10264   3.117 ± 0.067   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.887           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.757           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.977           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.264           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.148           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.061           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.065           ms/op

Benchmark result is saved to 1717827046580.json
