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
# Warmup Iteration   1: 0.977 ops/ms
Iteration   1: 4.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  4.169 ops/ms


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
# Warmup Iteration   1: 5.138 ops/ms
Iteration   1: 11.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.362 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.080 ops/ms
Iteration   1: 11.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.943 ops/ms


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
# Warmup Iteration   1: 4.550 ops/ms
Iteration   1: 7.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.422 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.437 ±(99.9%) 0.082 ms/op
Iteration   1: 2.407 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.407 ms/op


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
# Warmup Iteration   1: 3.258 ±(99.9%) 0.052 ms/op
Iteration   1: 1.888 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.888 ms/op


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
# Warmup Iteration   1: 3.774 ±(99.9%) 0.072 ms/op
Iteration   1: 2.481 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.481 ms/op


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
# Warmup Iteration   1: 5.392 ±(99.9%) 0.140 ms/op
Iteration   1: 4.220 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.220 ms/op


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.113 ms/op
Iteration   1: 2.302 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.654 ms/op
                 createUser·p0.50:   2.015 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.539 ms/op
                 createUser·p0.99:   9.295 ms/op
                 createUser·p0.999:  19.137 ms/op
                 createUser·p0.9999: 19.328 ms/op
                 createUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13868
  mean =      2.302 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 10006 
    [ 2.500,  3.750) = 3103 
    [ 3.750,  5.000) = 314 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      9.295 ms/op
     p(99.9000) =     19.137 ms/op
     p(99.9900) =     19.328 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 3.542 ±(99.9%) 0.098 ms/op
Iteration   1: 2.002 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.346 ms/op
                 existUser·p0.50:   1.831 ms/op
                 existUser·p0.90:   2.601 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  11.910 ms/op
                 existUser·p0.9999: 13.388 ms/op
                 existUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16041
  mean =      2.002 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 653 
    [ 1.250,  2.500) = 13459 
    [ 2.500,  3.750) = 1648 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 87 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      1.831 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     11.910 ms/op
     p(99.9900) =     13.388 ms/op
     p(99.9990) =     13.517 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


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
# Warmup Iteration   1: 3.523 ±(99.9%) 0.091 ms/op
Iteration   1: 2.072 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   1.845 ms/op
                 getUser·p0.90:   2.642 ms/op
                 getUser·p0.95:   2.884 ms/op
                 getUser·p0.99:   4.900 ms/op
                 getUser·p0.999:  19.956 ms/op
                 getUser·p0.9999: 20.214 ms/op
                 getUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15597
  mean =      2.072 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13374 
    [ 2.500,  5.000) = 2071 
    [ 5.000,  7.500) = 78 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      4.900 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     20.214 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 5.592 ±(99.9%) 0.179 ms/op
Iteration   1: 4.050 ±(99.9%) 0.069 ms/op
                 listUser·p0.00:   1.034 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.953 ms/op
                 listUser·p0.95:   5.876 ms/op
                 listUser·p0.99:   9.144 ms/op
                 listUser·p0.999:  23.465 ms/op
                 listUser·p0.9999: 28.672 ms/op
                 listUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7893
  mean =      4.050 ±(99.9%) 0.069 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 304 
    [ 2.500,  5.000) = 6842 
    [ 5.000,  7.500) = 592 
    [ 7.500, 10.000) = 83 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.953 ms/op
     p(95.0000) =      5.876 ms/op
     p(99.0000) =      9.144 ms/op
     p(99.9000) =     23.465 ms/op
     p(99.9900) =     28.672 ms/op
     p(99.9990) =     28.672 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          4.169          ops/ms
ClientSimple.existUser                       thrpt         11.362          ops/ms
ClientSimple.getUser                         thrpt         11.943          ops/ms
ClientSimple.listUser                        thrpt          7.422          ops/ms
ClientSimple.createUser                       avgt          2.407           ms/op
ClientSimple.existUser                        avgt          1.888           ms/op
ClientSimple.getUser                          avgt          2.481           ms/op
ClientSimple.listUser                         avgt          4.220           ms/op
ClientSimple.createUser                     sample  13868   2.302 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.654           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.015           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.539           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.295           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.137           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.328           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.366           ms/op
ClientSimple.existUser                      sample  16041   2.002 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.346           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.831           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.092           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.808           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.910           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.388           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.517           ms/op
ClientSimple.getUser                        sample  15597   2.072 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.957           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.845           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.884           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.900           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.956           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.214           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.251           ms/op
ClientSimple.listUser                       sample   7893   4.050 ± 0.069   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.034           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.940           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.953           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.876           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.144           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.465           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.672           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.672           ms/op

Benchmark result is saved to 1719362259225.json
