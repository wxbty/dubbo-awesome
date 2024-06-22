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
# Warmup Iteration   1: 1.773 ops/ms
Iteration   1: 6.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.669 ops/ms


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
# Warmup Iteration   1: 6.496 ops/ms
Iteration   1: 13.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.469 ops/ms


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
# Warmup Iteration   1: 5.377 ops/ms
Iteration   1: 11.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.086 ops/ms


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
# Warmup Iteration   1: 4.651 ops/ms
Iteration   1: 8.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.356 ops/ms


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.085 ms/op
Iteration   1: 2.131 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.131 ms/op


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
# Warmup Iteration   1: 3.622 ±(99.9%) 0.062 ms/op
Iteration   1: 2.007 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.007 ms/op


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
# Warmup Iteration   1: 3.372 ±(99.9%) 0.053 ms/op
Iteration   1: 2.007 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.007 ms/op


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.079 ms/op
Iteration   1: 3.497 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.497 ms/op


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
# Warmup Iteration   1: 3.479 ±(99.9%) 0.093 ms/op
Iteration   1: 2.218 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   2.040 ms/op
                 createUser·p0.90:   2.873 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   4.890 ms/op
                 createUser·p0.999:  17.170 ms/op
                 createUser·p0.9999: 17.240 ms/op
                 createUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14405
  mean =      2.218 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 11261 
    [ 2.500,  3.750) = 2765 
    [ 3.750,  5.000) = 152 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.040 ms/op
     p(90.0000) =      2.873 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      4.890 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     17.240 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 3.252 ±(99.9%) 0.074 ms/op
Iteration   1: 2.232 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.224 ms/op
                 existUser·p0.90:   2.654 ms/op
                 existUser·p0.95:   2.855 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  11.829 ms/op
                 existUser·p0.9999: 12.009 ms/op
                 existUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14475
  mean =      2.232 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 195 
    [ 1.250,  2.500) = 11244 
    [ 2.500,  3.750) = 2788 
    [ 3.750,  5.000) = 174 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.224 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =     11.829 ms/op
     p(99.9900) =     12.009 ms/op
     p(99.9990) =     12.009 ms/op
     p(99.9999) =     12.009 ms/op
    p(100.0000) =     12.009 ms/op


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
# Warmup Iteration   1: 3.215 ±(99.9%) 0.076 ms/op
Iteration   1: 1.993 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   1.884 ms/op
                 getUser·p0.90:   2.494 ms/op
                 getUser·p0.95:   2.703 ms/op
                 getUser·p0.99:   3.354 ms/op
                 getUser·p0.999:  19.202 ms/op
                 getUser·p0.9999: 19.399 ms/op
                 getUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16044
  mean =      1.993 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 251 
    [ 1.250,  2.500) = 14218 
    [ 2.500,  3.750) = 1473 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      3.354 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     19.399 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 4.745 ±(99.9%) 0.137 ms/op
Iteration   1: 3.436 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   3.432 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  9.077 ms/op
                 listUser·p0.9999: 9.765 ms/op
                 listUser·p1.00:   9.765 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9315
  mean =      3.436 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 7 
    [ 1.500,  2.000) = 58 
    [ 2.000,  2.500) = 1137 
    [ 2.500,  3.000) = 2201 
    [ 3.000,  3.500) = 1467 
    [ 3.500,  4.000) = 2432 
    [ 4.000,  4.500) = 1287 
    [ 4.500,  5.000) = 307 
    [ 5.000,  5.500) = 183 
    [ 5.500,  6.000) = 101 
    [ 6.000,  6.500) = 39 
    [ 6.500,  7.000) = 57 
    [ 7.000,  7.500) = 18 
    [ 7.500,  8.000) = 11 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =      9.765 ms/op
     p(99.9990) =      9.765 ms/op
     p(99.9999) =      9.765 ms/op
    p(100.0000) =      9.765 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.669          ops/ms
ClientSimple.existUser                       thrpt         13.469          ops/ms
ClientSimple.getUser                         thrpt         11.086          ops/ms
ClientSimple.listUser                        thrpt          8.356          ops/ms
ClientSimple.createUser                       avgt          2.131           ms/op
ClientSimple.existUser                        avgt          2.007           ms/op
ClientSimple.getUser                          avgt          2.007           ms/op
ClientSimple.listUser                         avgt          3.497           ms/op
ClientSimple.createUser                     sample  14405   2.218 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.706           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.040           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.873           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.133           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.890           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.170           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.240           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.269           ms/op
ClientSimple.existUser                      sample  14475   2.232 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.751           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.224           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.855           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.284           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.829           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.009           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.009           ms/op
ClientSimple.getUser                        sample  16044   1.993 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.656           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.884           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.494           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.703           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.354           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.202           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.399           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.399           ms/op
ClientSimple.listUser                       sample   9315   3.436 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.405           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.432           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.891           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.521           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.077           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.765           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.765           ms/op

Benchmark result is saved to 1719036700255.json
