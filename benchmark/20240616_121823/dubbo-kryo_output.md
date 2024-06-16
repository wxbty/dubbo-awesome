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
# Warmup Iteration   1: 1.642 ops/ms
Iteration   1: 6.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.493 ops/ms


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
# Warmup Iteration   1: 6.157 ops/ms
Iteration   1: 12.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.574 ops/ms


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
# Warmup Iteration   1: 5.212 ops/ms
Iteration   1: 13.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.184 ops/ms


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
# Warmup Iteration   1: 5.142 ops/ms
Iteration   1: 8.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.651 ops/ms


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
# Warmup Iteration   1: 3.842 ±(99.9%) 0.071 ms/op
Iteration   1: 2.106 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.106 ms/op


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
# Warmup Iteration   1: 3.638 ±(99.9%) 0.064 ms/op
Iteration   1: 2.003 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.003 ms/op


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.101 ms/op
Iteration   1: 2.307 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.307 ms/op


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
# Warmup Iteration   1: 4.569 ±(99.9%) 0.097 ms/op
Iteration   1: 3.449 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.449 ms/op


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
# Warmup Iteration   1: 3.820 ±(99.9%) 0.121 ms/op
Iteration   1: 2.250 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   2.066 ms/op
                 createUser·p0.90:   2.720 ms/op
                 createUser·p0.95:   3.002 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  18.140 ms/op
                 createUser·p0.9999: 20.416 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14210
  mean =      2.250 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11731 
    [ 2.500,  5.000) = 2230 
    [ 5.000,  7.500) = 123 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     18.140 ms/op
     p(99.9900) =     20.416 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 3.360 ±(99.9%) 0.094 ms/op
Iteration   1: 1.950 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   1.796 ms/op
                 existUser·p0.90:   2.290 ms/op
                 existUser·p0.95:   2.609 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  13.976 ms/op
                 existUser·p0.9999: 14.615 ms/op
                 existUser·p1.00:   14.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16427
  mean =      1.950 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 15357 
    [ 2.500,  3.750) = 649 
    [ 3.750,  5.000) = 179 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     14.615 ms/op
     p(99.9990) =     14.615 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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
# Warmup Iteration   1: 3.437 ±(99.9%) 0.093 ms/op
Iteration   1: 2.039 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.492 ms/op
                 getUser·p0.50:   1.868 ms/op
                 getUser·p0.90:   2.482 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   4.652 ms/op
                 getUser·p0.999:  23.282 ms/op
                 getUser·p0.9999: 23.921 ms/op
                 getUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15834
  mean =      2.039 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14361 
    [ 2.500,  5.000) = 1344 
    [ 5.000,  7.500) = 17 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      4.652 ms/op
     p(99.9000) =     23.282 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     23.921 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 4.784 ±(99.9%) 0.146 ms/op
Iteration   1: 3.758 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   0.574 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  21.365 ms/op
                 listUser·p0.9999: 21.430 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8496
  mean =      3.758 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 962 
    [ 2.500,  5.000) = 7099 
    [ 5.000,  7.500) = 334 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     21.365 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     21.430 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.493          ops/ms
ClientSimple.existUser                       thrpt         12.574          ops/ms
ClientSimple.getUser                         thrpt         13.184          ops/ms
ClientSimple.listUser                        thrpt          8.651          ops/ms
ClientSimple.createUser                       avgt          2.106           ms/op
ClientSimple.existUser                        avgt          2.003           ms/op
ClientSimple.getUser                          avgt          2.307           ms/op
ClientSimple.listUser                         avgt          3.449           ms/op
ClientSimple.createUser                     sample  14210   2.250 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.722           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.066           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.720           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.002           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.955           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.140           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.416           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.513           ms/op
ClientSimple.existUser                      sample  16427   1.950 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.660           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.796           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.290           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.609           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.571           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.976           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.615           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.615           ms/op
ClientSimple.getUser                        sample  15834   2.039 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.492           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.868           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.652           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.282           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.921           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.921           ms/op
ClientSimple.listUser                       sample   8496   3.758 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.574           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.793           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.014           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.807           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.365           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.430           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.430           ms/op

Benchmark result is saved to 1718540041749.json
