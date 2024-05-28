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
# Warmup Iteration   1: 0.819 ops/ms
Iteration   1: 6.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.816 ops/ms


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
# Warmup Iteration   1: 6.040 ops/ms
Iteration   1: 11.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.250 ops/ms


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
# Warmup Iteration   1: 5.915 ops/ms
Iteration   1: 13.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.773 ops/ms


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
# Warmup Iteration   1: 4.477 ops/ms
Iteration   1: 8.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.864 ops/ms


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
# Warmup Iteration   1: 4.368 ±(99.9%) 0.086 ms/op
Iteration   1: 2.377 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.377 ms/op


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
# Warmup Iteration   1: 3.197 ±(99.9%) 0.065 ms/op
Iteration   1: 2.132 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.132 ms/op


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
# Warmup Iteration   1: 3.389 ±(99.9%) 0.063 ms/op
Iteration   1: 2.122 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.122 ms/op


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
# Warmup Iteration   1: 4.533 ±(99.9%) 0.099 ms/op
Iteration   1: 3.201 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.201 ms/op


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
# Warmup Iteration   1: 4.146 ±(99.9%) 0.128 ms/op
Iteration   1: 2.161 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   2.028 ms/op
                 createUser·p0.90:   2.662 ms/op
                 createUser·p0.95:   2.912 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  14.720 ms/op
                 createUser·p0.9999: 17.964 ms/op
                 createUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14796
  mean =      2.161 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 12234 
    [ 2.500,  3.750) = 2312 
    [ 3.750,  5.000) = 175 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =     14.720 ms/op
     p(99.9900) =     17.964 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 3.331 ±(99.9%) 0.079 ms/op
Iteration   1: 1.835 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.511 ms/op
                 existUser·p0.50:   1.739 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.523 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  11.603 ms/op
                 existUser·p0.9999: 12.420 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17448
  mean =      1.835 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 768 
    [ 1.250,  2.500) = 15751 
    [ 2.500,  3.750) = 715 
    [ 3.750,  5.000) = 126 
    [ 5.000,  6.250) = 51 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      1.739 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =     11.603 ms/op
     p(99.9900) =     12.420 ms/op
     p(99.9990) =     12.517 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


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
# Warmup Iteration   1: 3.239 ±(99.9%) 0.080 ms/op
Iteration   1: 1.957 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   1.788 ms/op
                 getUser·p0.90:   2.449 ms/op
                 getUser·p0.95:   2.597 ms/op
                 getUser·p0.99:   3.550 ms/op
                 getUser·p0.999:  15.838 ms/op
                 getUser·p0.9999: 16.535 ms/op
                 getUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16341
  mean =      1.957 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 14934 
    [ 2.500,  3.750) = 1158 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      3.550 ms/op
     p(99.9000) =     15.838 ms/op
     p(99.9900) =     16.535 ms/op
     p(99.9990) =     16.597 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


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
# Warmup Iteration   1: 4.526 ±(99.9%) 0.115 ms/op
Iteration   1: 3.465 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.432 ms/op
                 listUser·p0.50:   3.146 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.840 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  19.587 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9243
  mean =      3.465 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 246 
    [ 2.500,  3.750) = 6464 
    [ 3.750,  5.000) = 2203 
    [ 5.000,  6.250) = 152 
    [ 6.250,  7.500) = 109 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.432 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.840 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     19.587 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.816          ops/ms
ClientSimple.existUser                       thrpt         11.250          ops/ms
ClientSimple.getUser                         thrpt         13.773          ops/ms
ClientSimple.listUser                        thrpt          8.864          ops/ms
ClientSimple.createUser                       avgt          2.377           ms/op
ClientSimple.existUser                        avgt          2.132           ms/op
ClientSimple.getUser                          avgt          2.122           ms/op
ClientSimple.listUser                         avgt          3.201           ms/op
ClientSimple.createUser                     sample  14796   2.161 ± 0.022   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.028           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.028           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.912           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.424           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.720           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.964           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.121           ms/op
ClientSimple.existUser                      sample  17448   1.835 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.511           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.739           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.523           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.268           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.603           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.420           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.517           ms/op
ClientSimple.getUser                        sample  16341   1.957 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.604           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.788           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.449           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.597           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.550           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.838           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.535           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.597           ms/op
ClientSimple.listUser                       sample   9243   3.465 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.432           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.146           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.840           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.062           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.587           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.792           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.792           ms/op

Benchmark result is saved to 1716856603767.json
