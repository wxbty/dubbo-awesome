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
# Warmup Iteration   1: 1.622 ops/ms
Iteration   1: 6.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.779 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.919 ops/ms
Iteration   1: 13.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.190 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.784 ops/ms
Iteration   1: 11.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.137 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.360 ops/ms
Iteration   1: 7.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.658 ops/ms


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.078 ms/op
Iteration   1: 2.172 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.172 ms/op


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
# Warmup Iteration   1: 3.536 ±(99.9%) 0.069 ms/op
Iteration   1: 2.046 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.046 ms/op


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
# Warmup Iteration   1: 3.398 ±(99.9%) 0.057 ms/op
Iteration   1: 1.943 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.943 ms/op


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
# Warmup Iteration   1: 4.772 ±(99.9%) 0.085 ms/op
Iteration   1: 3.290 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.290 ms/op


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.102 ms/op
Iteration   1: 2.361 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   2.142 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.379 ms/op
                 createUser·p0.99:   8.684 ms/op
                 createUser·p0.999:  16.482 ms/op
                 createUser·p0.9999: 16.709 ms/op
                 createUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13537
  mean =      2.361 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 188 
    [ 1.250,  2.500) = 9710 
    [ 2.500,  3.750) = 3244 
    [ 3.750,  5.000) = 178 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      2.142 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.379 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     16.482 ms/op
     p(99.9900) =     16.709 ms/op
     p(99.9990) =     16.761 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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
# Warmup Iteration   1: 2.946 ±(99.9%) 0.074 ms/op
Iteration   1: 1.913 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   1.829 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.437 ms/op
                 existUser·p0.99:   3.825 ms/op
                 existUser·p0.999:  17.901 ms/op
                 existUser·p0.9999: 18.961 ms/op
                 existUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16705
  mean =      1.913 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 593 
    [ 1.250,  2.500) = 15407 
    [ 2.500,  3.750) = 533 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.437 ms/op
     p(99.0000) =      3.825 ms/op
     p(99.9000) =     17.901 ms/op
     p(99.9900) =     18.961 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 3.331 ±(99.9%) 0.092 ms/op
Iteration   1: 1.996 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   1.853 ms/op
                 getUser·p0.90:   2.441 ms/op
                 getUser·p0.95:   2.712 ms/op
                 getUser·p0.99:   3.505 ms/op
                 getUser·p0.999:  18.904 ms/op
                 getUser·p0.9999: 21.218 ms/op
                 getUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16035
  mean =      1.996 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14651 
    [ 2.500,  5.000) = 1319 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      3.505 ms/op
     p(99.9000) =     18.904 ms/op
     p(99.9900) =     21.218 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 4.589 ±(99.9%) 0.124 ms/op
Iteration   1: 3.607 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   6.748 ms/op
                 listUser·p0.999:  16.653 ms/op
                 listUser·p0.9999: 17.367 ms/op
                 listUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8856
  mean =      3.607 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 819 
    [ 2.500,  3.750) = 4532 
    [ 3.750,  5.000) = 3095 
    [ 5.000,  6.250) = 259 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      6.748 ms/op
     p(99.9000) =     16.653 ms/op
     p(99.9900) =     17.367 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.779          ops/ms
ClientSimple.existUser                       thrpt         13.190          ops/ms
ClientSimple.getUser                         thrpt         11.137          ops/ms
ClientSimple.listUser                        thrpt          7.658          ops/ms
ClientSimple.createUser                       avgt          2.172           ms/op
ClientSimple.existUser                        avgt          2.046           ms/op
ClientSimple.getUser                          avgt          1.943           ms/op
ClientSimple.listUser                         avgt          3.290           ms/op
ClientSimple.createUser                     sample  13537   2.361 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.648           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.142           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.068           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.379           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.684           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.482           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.709           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.761           ms/op
ClientSimple.existUser                      sample  16705   1.913 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.700           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.829           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.825           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.901           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.961           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.005           ms/op
ClientSimple.getUser                        sample  16035   1.996 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.977           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.853           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.441           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.505           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.904           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.218           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.594           ms/op
ClientSimple.listUser                       sample   8856   3.607 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.985           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.543           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.748           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.653           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.367           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.367           ms/op

Benchmark result is saved to 1717438299104.json
