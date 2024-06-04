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
# Warmup Iteration   1: 1.867 ops/ms
Iteration   1: 6.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.767 ops/ms


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
# Warmup Iteration   1: 6.041 ops/ms
Iteration   1: 14.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.099 ops/ms


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
# Warmup Iteration   1: 5.318 ops/ms
Iteration   1: 13.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.266 ops/ms


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
# Warmup Iteration   1: 3.965 ops/ms
Iteration   1: 8.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.900 ops/ms


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
# Warmup Iteration   1: 3.420 ±(99.9%) 0.057 ms/op
Iteration   1: 2.096 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.096 ms/op


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
# Warmup Iteration   1: 3.280 ±(99.9%) 0.052 ms/op
Iteration   1: 2.314 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.314 ms/op


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
# Warmup Iteration   1: 3.625 ±(99.9%) 0.069 ms/op
Iteration   1: 2.027 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.027 ms/op


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
# Warmup Iteration   1: 4.489 ±(99.9%) 0.096 ms/op
Iteration   1: 3.284 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.284 ms/op


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
# Warmup Iteration   1: 3.420 ±(99.9%) 0.084 ms/op
Iteration   1: 2.271 ±(99.9%) 0.062 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   2.075 ms/op
                 createUser·p0.90:   2.642 ms/op
                 createUser·p0.95:   2.997 ms/op
                 createUser·p0.99:   5.977 ms/op
                 createUser·p0.999:  38.857 ms/op
                 createUser·p0.9999: 41.091 ms/op
                 createUser·p1.00:   41.091 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14085
  mean =      2.271 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13920 
    [ 5.000, 10.000) = 37 
    [10.000, 15.000) = 12 
    [15.000, 20.000) = 59 
    [20.000, 25.000) = 25 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.997 ms/op
     p(99.0000) =      5.977 ms/op
     p(99.9000) =     38.857 ms/op
     p(99.9900) =     41.091 ms/op
     p(99.9990) =     41.091 ms/op
     p(99.9999) =     41.091 ms/op
    p(100.0000) =     41.091 ms/op


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
# Warmup Iteration   1: 3.155 ±(99.9%) 0.065 ms/op
Iteration   1: 2.009 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   1.919 ms/op
                 existUser·p0.90:   2.531 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  13.469 ms/op
                 existUser·p0.9999: 13.616 ms/op
                 existUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15889
  mean =      2.009 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 814 
    [ 1.250,  2.500) = 13314 
    [ 2.500,  3.750) = 1581 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      4.067 ms/op
     p(99.9000) =     13.469 ms/op
     p(99.9900) =     13.616 ms/op
     p(99.9990) =     13.664 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


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
# Warmup Iteration   1: 3.085 ±(99.9%) 0.076 ms/op
Iteration   1: 2.355 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   2.273 ms/op
                 getUser·p0.90:   2.834 ms/op
                 getUser·p0.95:   3.060 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  24.307 ms/op
                 getUser·p0.9999: 25.056 ms/op
                 getUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13600
  mean =      2.355 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9686 
    [ 2.500,  5.000) = 3795 
    [ 5.000,  7.500) = 54 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.273 ms/op
     p(90.0000) =      2.834 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      4.882 ms/op
     p(99.9000) =     24.307 ms/op
     p(99.9900) =     25.056 ms/op
     p(99.9990) =     25.068 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.117 ms/op
Iteration   1: 3.040 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.669 ms/op
                 listUser·p0.50:   2.851 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.014 ms/op
                 listUser·p0.99:   5.585 ms/op
                 listUser·p0.999:  18.677 ms/op
                 listUser·p0.9999: 19.570 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10508
  mean =      3.040 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 1947 
    [ 2.500,  3.750) = 7249 
    [ 3.750,  5.000) = 1106 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.585 ms/op
     p(99.9000) =     18.677 ms/op
     p(99.9900) =     19.570 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.767          ops/ms
ClientSimple.existUser                       thrpt         14.099          ops/ms
ClientSimple.getUser                         thrpt         13.266          ops/ms
ClientSimple.listUser                        thrpt          8.900          ops/ms
ClientSimple.createUser                       avgt          2.096           ms/op
ClientSimple.existUser                        avgt          2.314           ms/op
ClientSimple.getUser                          avgt          2.027           ms/op
ClientSimple.listUser                         avgt          3.284           ms/op
ClientSimple.createUser                     sample  14085   2.271 ± 0.062   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.710           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.075           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.642           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.997           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.977           ms/op
ClientSimple.createUser:createUser·p0.999   sample         38.857           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         41.091           ms/op
ClientSimple.createUser:createUser·p1.00    sample         41.091           ms/op
ClientSimple.existUser                      sample  15889   2.009 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.668           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.919           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.531           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.067           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.469           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.616           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.664           ms/op
ClientSimple.getUser                        sample  13600   2.355 ± 0.036   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.756           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.273           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.834           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.060           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.882           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.307           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.056           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.068           ms/op
ClientSimple.listUser                       sample  10508   3.040 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.669           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.851           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.805           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.014           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.585           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.677           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.570           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.595           ms/op

Benchmark result is saved to 1717524681674.json
