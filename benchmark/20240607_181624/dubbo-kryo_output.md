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
# Warmup Iteration   1: 1.772 ops/ms
Iteration   1: 7.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.706 ops/ms


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
# Warmup Iteration   1: 6.241 ops/ms
Iteration   1: 13.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.953 ops/ms


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
# Warmup Iteration   1: 6.064 ops/ms
Iteration   1: 12.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.566 ops/ms


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
# Warmup Iteration   1: 5.537 ops/ms
Iteration   1: 8.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.556 ops/ms


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
# Warmup Iteration   1: 4.036 ±(99.9%) 0.071 ms/op
Iteration   1: 1.997 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.997 ms/op


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
# Warmup Iteration   1: 3.204 ±(99.9%) 0.055 ms/op
Iteration   1: 1.973 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.973 ms/op


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
# Warmup Iteration   1: 3.357 ±(99.9%) 0.058 ms/op
Iteration   1: 2.135 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.135 ms/op


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.087 ms/op
Iteration   1: 3.351 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.351 ms/op


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
# Warmup Iteration   1: 3.523 ±(99.9%) 0.098 ms/op
Iteration   1: 2.264 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.444 ms/op
                 createUser·p0.50:   2.101 ms/op
                 createUser·p0.90:   2.740 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   7.957 ms/op
                 createUser·p0.999:  15.851 ms/op
                 createUser·p0.9999: 18.205 ms/op
                 createUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14132
  mean =      2.264 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 318 
    [ 1.250,  2.500) = 11163 
    [ 2.500,  3.750) = 2260 
    [ 3.750,  5.000) = 149 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      7.957 ms/op
     p(99.9000) =     15.851 ms/op
     p(99.9900) =     18.205 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 2.978 ±(99.9%) 0.064 ms/op
Iteration   1: 1.788 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   1.628 ms/op
                 existUser·p0.90:   2.175 ms/op
                 existUser·p0.95:   2.355 ms/op
                 existUser·p0.99:   3.845 ms/op
                 existUser·p0.999:  27.661 ms/op
                 existUser·p0.9999: 28.443 ms/op
                 existUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17857
  mean =      1.788 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17252 
    [ 2.500,  5.000) = 476 
    [ 5.000,  7.500) = 56 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      1.628 ms/op
     p(90.0000) =      2.175 ms/op
     p(95.0000) =      2.355 ms/op
     p(99.0000) =      3.845 ms/op
     p(99.9000) =     27.661 ms/op
     p(99.9900) =     28.443 ms/op
     p(99.9990) =     28.443 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 3.225 ±(99.9%) 0.072 ms/op
Iteration   1: 2.078 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.393 ms/op
                 getUser·p0.50:   2.023 ms/op
                 getUser·p0.90:   2.613 ms/op
                 getUser·p0.95:   2.753 ms/op
                 getUser·p0.99:   3.339 ms/op
                 getUser·p0.999:  12.547 ms/op
                 getUser·p0.9999: 13.010 ms/op
                 getUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15574
  mean =      2.078 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 243 
    [ 1.250,  2.500) = 13008 
    [ 2.500,  3.750) = 2192 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.393 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      3.339 ms/op
     p(99.9000) =     12.547 ms/op
     p(99.9900) =     13.010 ms/op
     p(99.9990) =     13.074 ms/op
     p(99.9999) =     13.074 ms/op
    p(100.0000) =     13.074 ms/op


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
# Warmup Iteration   1: 4.452 ±(99.9%) 0.119 ms/op
Iteration   1: 3.310 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  19.737 ms/op
                 listUser·p0.9999: 19.857 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9674
  mean =      3.310 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 904 
    [ 2.500,  3.750) = 6579 
    [ 3.750,  5.000) = 1957 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     19.737 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.706          ops/ms
ClientSimple.existUser                       thrpt         13.953          ops/ms
ClientSimple.getUser                         thrpt         12.566          ops/ms
ClientSimple.listUser                        thrpt          8.556          ops/ms
ClientSimple.createUser                       avgt          1.997           ms/op
ClientSimple.existUser                        avgt          1.973           ms/op
ClientSimple.getUser                          avgt          2.135           ms/op
ClientSimple.listUser                         avgt          3.351           ms/op
ClientSimple.createUser                     sample  14132   2.264 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.444           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.101           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.080           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.957           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.851           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.205           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.219           ms/op
ClientSimple.existUser                      sample  17857   1.788 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.602           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.628           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.175           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.355           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.845           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.661           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.443           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.443           ms/op
ClientSimple.getUser                        sample  15574   2.078 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.393           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.023           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.613           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.753           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.339           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.547           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.010           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.074           ms/op
ClientSimple.listUser                       sample   9674   3.310 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.159           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.047           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.010           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.504           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.737           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.857           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.857           ms/op

Benchmark result is saved to 1717783934932.json
