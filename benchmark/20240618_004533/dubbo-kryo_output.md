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
# Warmup Iteration   1: 1.638 ops/ms
Iteration   1: 6.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.192 ops/ms


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
# Warmup Iteration   1: 5.574 ops/ms
Iteration   1: 12.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.985 ops/ms


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
# Warmup Iteration   1: 4.126 ops/ms
Iteration   1: 10.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.252 ops/ms


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
# Warmup Iteration   1: 4.277 ops/ms
Iteration   1: 8.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.189 ops/ms


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
# Warmup Iteration   1: 4.812 ±(99.9%) 0.089 ms/op
Iteration   1: 2.283 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.283 ms/op


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
# Warmup Iteration   1: 3.147 ±(99.9%) 0.054 ms/op
Iteration   1: 2.084 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.084 ms/op


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
# Warmup Iteration   1: 3.265 ±(99.9%) 0.068 ms/op
Iteration   1: 2.247 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.247 ms/op


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
# Warmup Iteration   1: 5.791 ±(99.9%) 0.121 ms/op
Iteration   1: 3.442 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.442 ms/op


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
# Warmup Iteration   1: 3.537 ±(99.9%) 0.093 ms/op
Iteration   1: 2.230 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   2.048 ms/op
                 createUser·p0.90:   2.626 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  24.216 ms/op
                 createUser·p0.9999: 24.314 ms/op
                 createUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14637
  mean =      2.230 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12760 
    [ 2.500,  5.000) = 1614 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.048 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     24.216 ms/op
     p(99.9900) =     24.314 ms/op
     p(99.9990) =     24.314 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 3.261 ±(99.9%) 0.081 ms/op
Iteration   1: 2.126 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.267 ms/op
                 existUser·p0.50:   2.134 ms/op
                 existUser·p0.90:   2.695 ms/op
                 existUser·p0.95:   2.888 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  10.633 ms/op
                 existUser·p0.9999: 12.568 ms/op
                 existUser·p1.00:   14.139 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15072
  mean =      2.126 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 600 
    [ 1.250,  2.500) = 11208 
    [ 2.500,  3.750) = 3124 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.267 ms/op
     p(50.0000) =      2.134 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =     10.633 ms/op
     p(99.9900) =     12.568 ms/op
     p(99.9990) =     14.139 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


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
# Warmup Iteration   1: 3.495 ±(99.9%) 0.093 ms/op
Iteration   1: 2.342 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.458 ms/op
                 getUser·p0.50:   2.212 ms/op
                 getUser·p0.90:   2.925 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   8.236 ms/op
                 getUser·p0.999:  22.514 ms/op
                 getUser·p0.9999: 23.614 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13659
  mean =      2.342 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9620 
    [ 2.500,  5.000) = 3814 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      2.212 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      8.236 ms/op
     p(99.9000) =     22.514 ms/op
     p(99.9900) =     23.614 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 4.836 ±(99.9%) 0.155 ms/op
Iteration   1: 3.846 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  12.371 ms/op
                 listUser·p0.9999: 13.631 ms/op
                 listUser·p1.00:   13.631 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8322
  mean =      3.846 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 220 
    [ 2.500,  3.750) = 3166 
    [ 3.750,  5.000) = 4631 
    [ 5.000,  6.250) = 195 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     12.371 ms/op
     p(99.9900) =     13.631 ms/op
     p(99.9990) =     13.631 ms/op
     p(99.9999) =     13.631 ms/op
    p(100.0000) =     13.631 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.192          ops/ms
ClientSimple.existUser                       thrpt         12.985          ops/ms
ClientSimple.getUser                         thrpt         10.252          ops/ms
ClientSimple.listUser                        thrpt          8.189          ops/ms
ClientSimple.createUser                       avgt          2.283           ms/op
ClientSimple.existUser                        avgt          2.084           ms/op
ClientSimple.getUser                          avgt          2.247           ms/op
ClientSimple.listUser                         avgt          3.442           ms/op
ClientSimple.createUser                     sample  14637   2.230 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.775           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.048           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.626           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.199           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.389           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.216           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.314           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.314           ms/op
ClientSimple.existUser                      sample  15072   2.126 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.267           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.134           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.695           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.888           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.723           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.633           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.568           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.139           ms/op
ClientSimple.getUser                        sample  13659   2.342 ± 0.040   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.458           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.212           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.925           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.158           ms/op
ClientSimple.getUser:getUser·p0.99          sample          8.236           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.514           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.614           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.626           ms/op
ClientSimple.listUser                       sample   8322   3.846 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.448           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.867           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.833           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.611           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.371           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.631           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.631           ms/op

Benchmark result is saved to 1718671096864.json
