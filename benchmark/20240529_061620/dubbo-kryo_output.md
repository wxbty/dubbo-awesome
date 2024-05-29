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
# Warmup Iteration   1: 1.598 ops/ms
Iteration   1: 7.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.015 ops/ms


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
# Warmup Iteration   1: 5.305 ops/ms
Iteration   1: 13.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.377 ops/ms


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
# Warmup Iteration   1: 5.755 ops/ms
Iteration   1: 12.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.493 ops/ms


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
# Warmup Iteration   1: 4.624 ops/ms
Iteration   1: 7.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.979 ops/ms


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
# Warmup Iteration   1: 4.839 ±(99.9%) 0.091 ms/op
Iteration   1: 2.248 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.248 ms/op


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
# Warmup Iteration   1: 3.225 ±(99.9%) 0.058 ms/op
Iteration   1: 1.857 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.857 ms/op


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
# Warmup Iteration   1: 3.308 ±(99.9%) 0.052 ms/op
Iteration   1: 2.080 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.080 ms/op


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
# Warmup Iteration   1: 4.287 ±(99.9%) 0.074 ms/op
Iteration   1: 3.320 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.320 ms/op


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
# Warmup Iteration   1: 3.554 ±(99.9%) 0.104 ms/op
Iteration   1: 2.199 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.714 ms/op
                 createUser·p0.50:   1.985 ms/op
                 createUser·p0.90:   2.683 ms/op
                 createUser·p0.95:   3.039 ms/op
                 createUser·p0.99:   8.936 ms/op
                 createUser·p0.999:  27.241 ms/op
                 createUser·p0.9999: 27.787 ms/op
                 createUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14559
  mean =      2.199 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12350 
    [ 2.500,  5.000) = 1926 
    [ 5.000,  7.500) = 115 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      8.936 ms/op
     p(99.9000) =     27.241 ms/op
     p(99.9900) =     27.787 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.094 ±(99.9%) 0.067 ms/op
Iteration   1: 2.404 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.562 ms/op
                 existUser·p0.50:   2.322 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.240 ms/op
                 existUser·p0.99:   4.562 ms/op
                 existUser·p0.999:  18.547 ms/op
                 existUser·p0.9999: 18.733 ms/op
                 existUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 13307
  mean =      2.404 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 175 
    [ 1.250,  2.500) = 8990 
    [ 2.500,  3.750) = 3908 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      2.322 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      4.562 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     18.733 ms/op
     p(99.9990) =     18.776 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 3.319 ±(99.9%) 0.083 ms/op
Iteration   1: 1.860 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   1.788 ms/op
                 getUser·p0.90:   2.142 ms/op
                 getUser·p0.95:   2.327 ms/op
                 getUser·p0.99:   2.884 ms/op
                 getUser·p0.999:  12.972 ms/op
                 getUser·p0.9999: 13.481 ms/op
                 getUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17238
  mean =      1.860 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 16679 
    [ 2.500,  3.750) = 449 
    [ 3.750,  5.000) = 25 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.142 ms/op
     p(95.0000) =      2.327 ms/op
     p(99.0000) =      2.884 ms/op
     p(99.9000) =     12.972 ms/op
     p(99.9900) =     13.481 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.190 ±(99.9%) 0.113 ms/op
Iteration   1: 3.200 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.080 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.403 ms/op
                 listUser·p0.99:   7.013 ms/op
                 listUser·p0.999:  24.216 ms/op
                 listUser·p0.9999: 24.609 ms/op
                 listUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9989
  mean =      3.200 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1983 
    [ 2.500,  5.000) = 7699 
    [ 5.000,  7.500) = 223 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.403 ms/op
     p(99.0000) =      7.013 ms/op
     p(99.9000) =     24.216 ms/op
     p(99.9900) =     24.609 ms/op
     p(99.9990) =     24.609 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.015          ops/ms
ClientSimple.existUser                       thrpt         13.377          ops/ms
ClientSimple.getUser                         thrpt         12.493          ops/ms
ClientSimple.listUser                        thrpt          7.979          ops/ms
ClientSimple.createUser                       avgt          2.248           ms/op
ClientSimple.existUser                        avgt          1.857           ms/op
ClientSimple.getUser                          avgt          2.080           ms/op
ClientSimple.listUser                         avgt          3.320           ms/op
ClientSimple.createUser                     sample  14559   2.199 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.714           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.985           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.683           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.039           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.936           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.241           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.787           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.787           ms/op
ClientSimple.existUser                      sample  13307   2.404 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.562           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.937           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.240           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.562           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.547           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.733           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.776           ms/op
ClientSimple.getUser                        sample  17238   1.860 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.546           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.788           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.142           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.327           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.884           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.972           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.481           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.517           ms/op
ClientSimple.listUser                       sample   9989   3.200 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.094           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.080           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.953           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.403           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.013           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.216           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.609           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.609           ms/op

Benchmark result is saved to 1716963115327.json
