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
# Warmup Iteration   1: 1.671 ops/ms
Iteration   1: 6.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.543 ops/ms


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
# Warmup Iteration   1: 6.559 ops/ms
Iteration   1: 12.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.531 ops/ms


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
# Warmup Iteration   1: 5.935 ops/ms
Iteration   1: 13.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.181 ops/ms


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
# Warmup Iteration   1: 5.569 ops/ms
Iteration   1: 9.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.014 ops/ms


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
# Warmup Iteration   1: 4.278 ±(99.9%) 0.059 ms/op
Iteration   1: 2.052 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.052 ms/op


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
# Warmup Iteration   1: 3.276 ±(99.9%) 0.050 ms/op
Iteration   1: 1.832 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.832 ms/op


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
# Warmup Iteration   1: 3.035 ±(99.9%) 0.052 ms/op
Iteration   1: 1.967 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.967 ms/op


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.092 ms/op
Iteration   1: 3.518 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.518 ms/op


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
# Warmup Iteration   1: 4.294 ±(99.9%) 0.255 ms/op
Iteration   1: 2.097 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.416 ms/op
                 createUser·p0.50:   1.870 ms/op
                 createUser·p0.90:   2.601 ms/op
                 createUser·p0.95:   2.810 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  16.630 ms/op
                 createUser·p0.9999: 16.922 ms/op
                 createUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15220
  mean =      2.097 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 12963 
    [ 2.500,  3.750) = 1941 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.416 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     16.630 ms/op
     p(99.9900) =     16.922 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 3.251 ±(99.9%) 0.083 ms/op
Iteration   1: 2.006 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   1.937 ms/op
                 existUser·p0.90:   2.556 ms/op
                 existUser·p0.95:   2.744 ms/op
                 existUser·p0.99:   3.304 ms/op
                 existUser·p0.999:  11.309 ms/op
                 existUser·p0.9999: 12.880 ms/op
                 existUser·p1.00:   13.910 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15932
  mean =      2.006 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 249 
    [ 1.250,  2.500) = 13775 
    [ 2.500,  3.750) = 1810 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      3.304 ms/op
     p(99.9000) =     11.309 ms/op
     p(99.9900) =     12.880 ms/op
     p(99.9990) =     13.910 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.094 ms/op
Iteration   1: 1.946 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   1.769 ms/op
                 getUser·p0.90:   2.388 ms/op
                 getUser·p0.95:   2.572 ms/op
                 getUser·p0.99:   4.446 ms/op
                 getUser·p0.999:  26.794 ms/op
                 getUser·p0.9999: 27.450 ms/op
                 getUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16432
  mean =      1.946 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15377 
    [ 2.500,  5.000) = 936 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      4.446 ms/op
     p(99.9000) =     26.794 ms/op
     p(99.9900) =     27.450 ms/op
     p(99.9990) =     27.787 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 4.356 ±(99.9%) 0.146 ms/op
Iteration   1: 3.157 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  11.236 ms/op
                 listUser·p0.9999: 11.403 ms/op
                 listUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10208
  mean =      3.157 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 1745 
    [ 2.500,  3.750) = 6316 
    [ 3.750,  5.000) = 1875 
    [ 5.000,  6.250) = 198 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     11.236 ms/op
     p(99.9900) =     11.403 ms/op
     p(99.9990) =     11.403 ms/op
     p(99.9999) =     11.403 ms/op
    p(100.0000) =     11.403 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.543          ops/ms
ClientSimple.existUser                       thrpt         12.531          ops/ms
ClientSimple.getUser                         thrpt         13.181          ops/ms
ClientSimple.listUser                        thrpt          9.014          ops/ms
ClientSimple.createUser                       avgt          2.052           ms/op
ClientSimple.existUser                        avgt          1.832           ms/op
ClientSimple.getUser                          avgt          1.967           ms/op
ClientSimple.listUser                         avgt          3.518           ms/op
ClientSimple.createUser                     sample  15220   2.097 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.416           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.870           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.810           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.521           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.630           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.922           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.974           ms/op
ClientSimple.existUser                      sample  15932   2.006 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.585           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.937           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.744           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.304           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.309           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.880           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.910           ms/op
ClientSimple.getUser                        sample  16432   1.946 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.781           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.769           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.388           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.446           ms/op
ClientSimple.getUser:getUser·p0.999         sample         26.794           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.450           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.787           ms/op
ClientSimple.listUser                       sample  10208   3.157 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.869           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.957           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.149           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.784           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.236           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.403           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.403           ms/op

Benchmark result is saved to 1718498471732.json
