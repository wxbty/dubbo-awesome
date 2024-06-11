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
# Warmup Iteration   1: 2.077 ops/ms
Iteration   1: 7.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.995 ops/ms


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
# Warmup Iteration   1: 6.757 ops/ms
Iteration   1: 12.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.785 ops/ms


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
# Warmup Iteration   1: 6.116 ops/ms
Iteration   1: 14.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.068 ops/ms


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
# Warmup Iteration   1: 4.972 ops/ms
Iteration   1: 8.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.450 ops/ms


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
# Warmup Iteration   1: 3.575 ±(99.9%) 0.073 ms/op
Iteration   1: 2.156 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.156 ms/op


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
# Warmup Iteration   1: 3.650 ±(99.9%) 0.071 ms/op
Iteration   1: 2.041 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.041 ms/op


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
# Warmup Iteration   1: 3.314 ±(99.9%) 0.063 ms/op
Iteration   1: 2.212 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.212 ms/op


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
# Warmup Iteration   1: 4.953 ±(99.9%) 0.107 ms/op
Iteration   1: 3.453 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.453 ms/op


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
# Warmup Iteration   1: 3.287 ±(99.9%) 0.078 ms/op
Iteration   1: 2.122 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   1.839 ms/op
                 createUser·p0.90:   2.654 ms/op
                 createUser·p0.95:   2.890 ms/op
                 createUser·p0.99:   9.099 ms/op
                 createUser·p0.999:  18.055 ms/op
                 createUser·p0.9999: 18.285 ms/op
                 createUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15066
  mean =      2.122 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 261 
    [ 1.250,  2.500) = 12384 
    [ 2.500,  3.750) = 2084 
    [ 3.750,  5.000) = 121 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      2.890 ms/op
     p(99.0000) =      9.099 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     18.285 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 2.876 ±(99.9%) 0.077 ms/op
Iteration   1: 1.892 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   1.778 ms/op
                 existUser·p0.90:   2.232 ms/op
                 existUser·p0.95:   2.433 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  10.143 ms/op
                 existUser·p0.9999: 11.507 ms/op
                 existUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16895
  mean =      1.892 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 16170 
    [ 2.500,  3.750) = 514 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.232 ms/op
     p(95.0000) =      2.433 ms/op
     p(99.0000) =      3.473 ms/op
     p(99.9000) =     10.143 ms/op
     p(99.9900) =     11.507 ms/op
     p(99.9990) =     11.518 ms/op
     p(99.9999) =     11.518 ms/op
    p(100.0000) =     11.518 ms/op


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
# Warmup Iteration   1: 3.163 ±(99.9%) 0.068 ms/op
Iteration   1: 2.266 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.540 ms/op
                 getUser·p0.50:   2.109 ms/op
                 getUser·p0.90:   2.613 ms/op
                 getUser·p0.95:   2.789 ms/op
                 getUser·p0.99:   5.722 ms/op
                 getUser·p0.999:  22.670 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14151
  mean =      2.266 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12030 
    [ 2.500,  5.000) = 1950 
    [ 5.000,  7.500) = 75 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      5.722 ms/op
     p(99.9000) =     22.670 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.115 ms/op
Iteration   1: 3.334 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   3.129 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.404 ms/op
                 listUser·p0.99:   5.825 ms/op
                 listUser·p0.999:  22.519 ms/op
                 listUser·p0.9999: 22.905 ms/op
                 listUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9588
  mean =      3.334 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 848 
    [ 2.500,  5.000) = 8538 
    [ 5.000,  7.500) = 164 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.404 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     22.519 ms/op
     p(99.9900) =     22.905 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.995          ops/ms
ClientSimple.existUser                       thrpt         12.785          ops/ms
ClientSimple.getUser                         thrpt         14.068          ops/ms
ClientSimple.listUser                        thrpt          8.450          ops/ms
ClientSimple.createUser                       avgt          2.156           ms/op
ClientSimple.existUser                        avgt          2.041           ms/op
ClientSimple.getUser                          avgt          2.212           ms/op
ClientSimple.listUser                         avgt          3.453           ms/op
ClientSimple.createUser                     sample  15066   2.122 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.807           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.839           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.654           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.890           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.099           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.055           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.285           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.285           ms/op
ClientSimple.existUser                      sample  16895   1.892 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.638           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.778           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.232           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.473           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.143           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.507           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.518           ms/op
ClientSimple.getUser                        sample  14151   2.266 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.540           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.109           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.613           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.789           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.722           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.670           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.741           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.741           ms/op
ClientSimple.listUser                       sample   9588   3.334 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.282           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.129           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.153           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.404           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.825           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.519           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.905           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.905           ms/op

Benchmark result is saved to 1718129526285.json
