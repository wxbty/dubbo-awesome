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
# Warmup Iteration   1: 1.998 ops/ms
Iteration   1: 8.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.513 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.181 ops/ms
Iteration   1: 13.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.535 ops/ms


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
# Warmup Iteration   1: 7.374 ops/ms
Iteration   1: 15.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.226 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.670 ops/ms
Iteration   1: 8.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.303 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.761 ±(99.9%) 0.072 ms/op
Iteration   1: 2.078 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.078 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.083 ±(99.9%) 0.049 ms/op
Iteration   1: 1.741 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.741 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.301 ±(99.9%) 0.081 ms/op
Iteration   1: 1.771 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.771 ms/op


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.078 ms/op
Iteration   1: 3.668 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.668 ms/op


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
# Warmup Iteration   1: 3.812 ±(99.9%) 0.088 ms/op
Iteration   1: 2.054 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   1.794 ms/op
                 createUser·p0.90:   2.499 ms/op
                 createUser·p0.95:   2.867 ms/op
                 createUser·p0.99:   8.936 ms/op
                 createUser·p0.999:  19.366 ms/op
                 createUser·p0.9999: 19.562 ms/op
                 createUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15557
  mean =      2.054 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 13852 
    [ 2.500,  3.750) = 1183 
    [ 3.750,  5.000) = 140 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      8.936 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.757 ±(99.9%) 0.060 ms/op
Iteration   1: 1.687 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   1.608 ms/op
                 existUser·p0.90:   2.048 ms/op
                 existUser·p0.95:   2.236 ms/op
                 existUser·p0.99:   3.373 ms/op
                 existUser·p0.999:  17.174 ms/op
                 existUser·p0.9999: 18.124 ms/op
                 existUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18875
  mean =      1.687 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 922 
    [ 1.250,  2.500) = 17543 
    [ 2.500,  3.750) = 311 
    [ 3.750,  5.000) = 74 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      1.608 ms/op
     p(90.0000) =      2.048 ms/op
     p(95.0000) =      2.236 ms/op
     p(99.0000) =      3.373 ms/op
     p(99.9000) =     17.174 ms/op
     p(99.9900) =     18.124 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.215 ±(99.9%) 0.097 ms/op
Iteration   1: 2.014 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.499 ms/op
                 getUser·p0.50:   1.892 ms/op
                 getUser·p0.90:   2.558 ms/op
                 getUser·p0.95:   2.773 ms/op
                 getUser·p0.99:   3.614 ms/op
                 getUser·p0.999:  25.629 ms/op
                 getUser·p0.9999: 26.006 ms/op
                 getUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15865
  mean =      2.014 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13985 
    [ 2.500,  5.000) = 1813 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.558 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      3.614 ms/op
     p(99.9000) =     25.629 ms/op
     p(99.9900) =     26.006 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.152 ±(99.9%) 0.111 ms/op
Iteration   1: 3.031 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.039 ms/op
                 listUser·p0.50:   2.753 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   4.157 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  22.020 ms/op
                 listUser·p0.9999: 22.364 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10560
  mean =      3.031 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1055 
    [ 2.500,  5.000) = 9254 
    [ 5.000,  7.500) = 195 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.039 ms/op
     p(50.0000) =      2.753 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     22.020 ms/op
     p(99.9900) =     22.364 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.513          ops/ms
ClientSimple.existUser                       thrpt         13.535          ops/ms
ClientSimple.getUser                         thrpt         15.226          ops/ms
ClientSimple.listUser                        thrpt          8.303          ops/ms
ClientSimple.createUser                       avgt          2.078           ms/op
ClientSimple.existUser                        avgt          1.741           ms/op
ClientSimple.getUser                          avgt          1.771           ms/op
ClientSimple.listUser                         avgt          3.668           ms/op
ClientSimple.createUser                     sample  15557   2.054 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.662           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.794           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.499           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.936           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.366           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.562           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.562           ms/op
ClientSimple.existUser                      sample  18875   1.687 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.536           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.608           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.048           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.236           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.373           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.174           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.124           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.153           ms/op
ClientSimple.getUser                        sample  15865   2.014 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.499           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.892           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.558           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.773           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.614           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.629           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.006           ms/op
ClientSimple.getUser:getUser·p1.00          sample         26.083           ms/op
ClientSimple.listUser                       sample  10560   3.031 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.039           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.753           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.781           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.157           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.898           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.020           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.364           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.381           ms/op

Benchmark result is saved to 1717416929224.json
