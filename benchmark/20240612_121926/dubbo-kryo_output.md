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
# Warmup Iteration   1: 1.789 ops/ms
Iteration   1: 7.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.223 ops/ms


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
# Warmup Iteration   1: 6.388 ops/ms
Iteration   1: 12.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.032 ops/ms


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
# Warmup Iteration   1: 4.915 ops/ms
Iteration   1: 10.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.568 ops/ms


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
# Warmup Iteration   1: 3.664 ops/ms
Iteration   1: 8.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.477 ops/ms


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.084 ms/op
Iteration   1: 2.356 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.356 ms/op


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
# Warmup Iteration   1: 3.162 ±(99.9%) 0.054 ms/op
Iteration   1: 1.991 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.991 ms/op


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
# Warmup Iteration   1: 3.574 ±(99.9%) 0.069 ms/op
Iteration   1: 2.028 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.028 ms/op


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
# Warmup Iteration   1: 4.466 ±(99.9%) 0.092 ms/op
Iteration   1: 3.301 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.301 ms/op


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.087 ms/op
Iteration   1: 2.505 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.363 ms/op
                 createUser·p0.50:   2.232 ms/op
                 createUser·p0.90:   3.337 ms/op
                 createUser·p0.95:   3.543 ms/op
                 createUser·p0.99:   7.262 ms/op
                 createUser·p0.999:  29.901 ms/op
                 createUser·p0.9999: 30.733 ms/op
                 createUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12752
  mean =      2.505 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8442 
    [ 2.500,  5.000) = 4123 
    [ 5.000,  7.500) = 76 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.363 ms/op
     p(50.0000) =      2.232 ms/op
     p(90.0000) =      3.337 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      7.262 ms/op
     p(99.9000) =     29.901 ms/op
     p(99.9900) =     30.733 ms/op
     p(99.9990) =     30.769 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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
# Warmup Iteration   1: 2.963 ±(99.9%) 0.064 ms/op
Iteration   1: 1.840 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.429 ms/op
                 existUser·p0.50:   1.655 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.568 ms/op
                 existUser·p0.99:   4.674 ms/op
                 existUser·p0.999:  20.827 ms/op
                 existUser·p0.9999: 21.439 ms/op
                 existUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17413
  mean =      1.840 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16388 
    [ 2.500,  5.000) = 866 
    [ 5.000,  7.500) = 55 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      1.655 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      4.674 ms/op
     p(99.9000) =     20.827 ms/op
     p(99.9900) =     21.439 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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
# Warmup Iteration   1: 3.322 ±(99.9%) 0.089 ms/op
Iteration   1: 2.101 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.393 ms/op
                 getUser·p0.50:   2.042 ms/op
                 getUser·p0.90:   2.523 ms/op
                 getUser·p0.95:   2.715 ms/op
                 getUser·p0.99:   5.053 ms/op
                 getUser·p0.999:  9.978 ms/op
                 getUser·p0.9999: 10.910 ms/op
                 getUser·p1.00:   10.945 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15220
  mean =      2.101 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 168 
    [ 1.250,  2.500) = 13409 
    [ 2.500,  3.750) = 1343 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.393 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.715 ms/op
     p(99.0000) =      5.053 ms/op
     p(99.9000) =      9.978 ms/op
     p(99.9900) =     10.910 ms/op
     p(99.9990) =     10.945 ms/op
     p(99.9999) =     10.945 ms/op
    p(100.0000) =     10.945 ms/op


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
# Warmup Iteration   1: 5.143 ±(99.9%) 0.187 ms/op
Iteration   1: 3.310 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.712 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  25.800 ms/op
                 listUser·p0.9999: 27.394 ms/op
                 listUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9655
  mean =      3.310 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2096 
    [ 2.500,  5.000) = 7150 
    [ 5.000,  7.500) = 341 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.712 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     25.800 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.223          ops/ms
ClientSimple.existUser                       thrpt         12.032          ops/ms
ClientSimple.getUser                         thrpt         10.568          ops/ms
ClientSimple.listUser                        thrpt          8.477          ops/ms
ClientSimple.createUser                       avgt          2.356           ms/op
ClientSimple.existUser                        avgt          1.991           ms/op
ClientSimple.getUser                          avgt          2.028           ms/op
ClientSimple.listUser                         avgt          3.301           ms/op
ClientSimple.createUser                     sample  12752   2.505 ± 0.048   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.363           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.232           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.337           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.543           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.262           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.901           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.733           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.769           ms/op
ClientSimple.existUser                      sample  17413   1.840 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.429           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.655           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.674           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.827           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.439           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.463           ms/op
ClientSimple.getUser                        sample  15220   2.101 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.393           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.042           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.523           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.715           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.053           ms/op
ClientSimple.getUser:getUser·p0.999         sample          9.978           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.910           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.945           ms/op
ClientSimple.listUser                       sample   9655   3.310 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.106           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.039           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.712           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.102           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.800           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.394           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.394           ms/op

Benchmark result is saved to 1718194510766.json
