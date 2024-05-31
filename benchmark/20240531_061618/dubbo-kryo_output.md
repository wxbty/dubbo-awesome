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
# Warmup Iteration   1: 2.025 ops/ms
Iteration   1: 7.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.304 ops/ms


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
# Warmup Iteration   1: 6.638 ops/ms
Iteration   1: 14.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.046 ops/ms


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
# Warmup Iteration   1: 5.804 ops/ms
Iteration   1: 15.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.338 ops/ms


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
# Warmup Iteration   1: 5.087 ops/ms
Iteration   1: 8.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.170 ops/ms


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.077 ms/op
Iteration   1: 2.165 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.165 ms/op


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
# Warmup Iteration   1: 2.887 ±(99.9%) 0.043 ms/op
Iteration   1: 1.972 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.972 ms/op


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
# Warmup Iteration   1: 3.712 ±(99.9%) 0.069 ms/op
Iteration   1: 1.951 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.951 ms/op


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
# Warmup Iteration   1: 4.284 ±(99.9%) 0.074 ms/op
Iteration   1: 3.175 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.175 ms/op


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
# Warmup Iteration   1: 4.220 ±(99.9%) 0.303 ms/op
Iteration   1: 2.139 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   1.944 ms/op
                 createUser·p0.90:   2.572 ms/op
                 createUser·p0.95:   2.773 ms/op
                 createUser·p0.99:   4.329 ms/op
                 createUser·p0.999:  13.992 ms/op
                 createUser·p0.9999: 14.303 ms/op
                 createUser·p1.00:   14.303 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14958
  mean =      2.139 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 12930 
    [ 2.500,  3.750) = 1831 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      4.329 ms/op
     p(99.9000) =     13.992 ms/op
     p(99.9900) =     14.303 ms/op
     p(99.9990) =     14.303 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 3.108 ±(99.9%) 0.089 ms/op
Iteration   1: 1.843 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.622 ms/op
                 existUser·p0.50:   1.708 ms/op
                 existUser·p0.90:   2.314 ms/op
                 existUser·p0.95:   2.494 ms/op
                 existUser·p0.99:   3.882 ms/op
                 existUser·p0.999:  11.289 ms/op
                 existUser·p0.9999: 11.863 ms/op
                 existUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17328
  mean =      1.843 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 367 
    [ 1.250,  2.500) = 16114 
    [ 2.500,  3.750) = 667 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      1.708 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      3.882 ms/op
     p(99.9000) =     11.289 ms/op
     p(99.9900) =     11.863 ms/op
     p(99.9990) =     11.911 ms/op
     p(99.9999) =     11.911 ms/op
    p(100.0000) =     11.911 ms/op


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
# Warmup Iteration   1: 3.360 ±(99.9%) 0.080 ms/op
Iteration   1: 2.229 ±(99.9%) 0.042 ms/op
                 getUser·p0.00:   0.402 ms/op
                 getUser·p0.50:   2.060 ms/op
                 getUser·p0.90:   2.576 ms/op
                 getUser·p0.95:   2.912 ms/op
                 getUser·p0.99:   5.410 ms/op
                 getUser·p0.999:  30.573 ms/op
                 getUser·p0.9999: 31.531 ms/op
                 getUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14362
  mean =      2.229 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12513 
    [ 2.500,  5.000) = 1700 
    [ 5.000,  7.500) = 85 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.402 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      5.410 ms/op
     p(99.9000) =     30.573 ms/op
     p(99.9900) =     31.531 ms/op
     p(99.9990) =     31.588 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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
# Warmup Iteration   1: 4.642 ±(99.9%) 0.137 ms/op
Iteration   1: 3.857 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.463 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.242 ms/op
                 listUser·p0.999:  13.834 ms/op
                 listUser·p0.9999: 14.270 ms/op
                 listUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8311
  mean =      3.857 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 230 
    [ 2.500,  3.750) = 3618 
    [ 3.750,  5.000) = 4087 
    [ 5.000,  6.250) = 295 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.463 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     13.834 ms/op
     p(99.9900) =     14.270 ms/op
     p(99.9990) =     14.270 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.304          ops/ms
ClientSimple.existUser                       thrpt         14.046          ops/ms
ClientSimple.getUser                         thrpt         15.338          ops/ms
ClientSimple.listUser                        thrpt          8.170          ops/ms
ClientSimple.createUser                       avgt          2.165           ms/op
ClientSimple.existUser                        avgt          1.972           ms/op
ClientSimple.getUser                          avgt          1.951           ms/op
ClientSimple.listUser                         avgt          3.175           ms/op
ClientSimple.createUser                     sample  14958   2.139 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.204           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.944           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.572           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.773           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.329           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.992           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.303           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.303           ms/op
ClientSimple.existUser                      sample  17328   1.843 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.622           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.708           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.314           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.882           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.289           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.863           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.911           ms/op
ClientSimple.getUser                        sample  14362   2.229 ± 0.042   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.402           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.060           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.912           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.410           ms/op
ClientSimple.getUser:getUser·p0.999         sample         30.573           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         31.531           ms/op
ClientSimple.getUser:getUser·p1.00          sample         31.588           ms/op
ClientSimple.listUser                       sample   8311   3.857 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.268           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.797           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.463           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.915           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.242           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.834           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.270           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.270           ms/op

Benchmark result is saved to 1717135933579.json
