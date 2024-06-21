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
# Warmup Iteration   1: 1.870 ops/ms
Iteration   1: 7.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.438 ops/ms


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
# Warmup Iteration   1: 5.808 ops/ms
Iteration   1: 13.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.119 ops/ms


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
# Warmup Iteration   1: 5.572 ops/ms
Iteration   1: 12.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.558 ops/ms


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
# Warmup Iteration   1: 4.542 ops/ms
Iteration   1: 8.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.185 ops/ms


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.063 ms/op
Iteration   1: 1.890 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.890 ms/op


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
# Warmup Iteration   1: 3.721 ±(99.9%) 0.077 ms/op
Iteration   1: 2.133 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.133 ms/op


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
# Warmup Iteration   1: 3.107 ±(99.9%) 0.063 ms/op
Iteration   1: 2.058 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.058 ms/op


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
# Warmup Iteration   1: 4.812 ±(99.9%) 0.085 ms/op
Iteration   1: 3.385 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.385 ms/op


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
# Warmup Iteration   1: 3.411 ±(99.9%) 0.094 ms/op
Iteration   1: 2.109 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   1.987 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   3.006 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  13.910 ms/op
                 createUser·p0.9999: 14.893 ms/op
                 createUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15159
  mean =      2.109 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 12857 
    [ 2.500,  3.750) = 2035 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     14.893 ms/op
     p(99.9990) =     14.893 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 2.874 ±(99.9%) 0.078 ms/op
Iteration   1: 1.874 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   1.780 ms/op
                 existUser·p0.90:   2.310 ms/op
                 existUser·p0.95:   2.519 ms/op
                 existUser·p0.99:   3.199 ms/op
                 existUser·p0.999:  6.085 ms/op
                 existUser·p0.9999: 7.616 ms/op
                 existUser·p1.00:   10.289 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17063
  mean =      1.874 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 42 
    [ 1.000,  2.000) = 11625 
    [ 2.000,  3.000) = 5169 
    [ 3.000,  4.000) = 131 
    [ 4.000,  5.000) = 13 
    [ 5.000,  6.000) = 55 
    [ 6.000,  7.000) = 27 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      3.199 ms/op
     p(99.9000) =      6.085 ms/op
     p(99.9900) =      7.616 ms/op
     p(99.9990) =     10.289 ms/op
     p(99.9999) =     10.289 ms/op
    p(100.0000) =     10.289 ms/op


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
# Warmup Iteration   1: 3.162 ±(99.9%) 0.077 ms/op
Iteration   1: 1.742 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.287 ms/op
                 getUser·p0.50:   1.575 ms/op
                 getUser·p0.90:   2.126 ms/op
                 getUser·p0.95:   2.361 ms/op
                 getUser·p0.99:   3.210 ms/op
                 getUser·p0.999:  31.250 ms/op
                 getUser·p0.9999: 31.801 ms/op
                 getUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18333
  mean =      1.742 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17741 
    [ 2.500,  5.000) = 494 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.287 ms/op
     p(50.0000) =      1.575 ms/op
     p(90.0000) =      2.126 ms/op
     p(95.0000) =      2.361 ms/op
     p(99.0000) =      3.210 ms/op
     p(99.9000) =     31.250 ms/op
     p(99.9900) =     31.801 ms/op
     p(99.9990) =     31.883 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 5.991 ±(99.9%) 0.165 ms/op
Iteration   1: 3.622 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.313 ms/op
                 listUser·p0.999:  13.618 ms/op
                 listUser·p0.9999: 13.664 ms/op
                 listUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8831
  mean =      3.622 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 323 
    [ 2.500,  3.750) = 5344 
    [ 3.750,  5.000) = 2809 
    [ 5.000,  6.250) = 261 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.313 ms/op
     p(99.9000) =     13.618 ms/op
     p(99.9900) =     13.664 ms/op
     p(99.9990) =     13.664 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.438          ops/ms
ClientSimple.existUser                       thrpt         13.119          ops/ms
ClientSimple.getUser                         thrpt         12.558          ops/ms
ClientSimple.listUser                        thrpt          8.185          ops/ms
ClientSimple.createUser                       avgt          1.890           ms/op
ClientSimple.existUser                        avgt          2.133           ms/op
ClientSimple.getUser                          avgt          2.058           ms/op
ClientSimple.listUser                         avgt          3.385           ms/op
ClientSimple.createUser                     sample  15159   2.109 ± 0.020   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.648           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.987           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.006           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.617           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.910           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.893           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.893           ms/op
ClientSimple.existUser                      sample  17063   1.874 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.578           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.780           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.310           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.199           ms/op
ClientSimple.existUser:existUser·p0.999     sample          6.085           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          7.616           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.289           ms/op
ClientSimple.getUser                        sample  18333   1.742 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.287           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.575           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.126           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.361           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.210           ms/op
ClientSimple.getUser:getUser·p0.999         sample         31.250           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         31.801           ms/op
ClientSimple.getUser:getUser·p1.00          sample         31.883           ms/op
ClientSimple.listUser                       sample   8831   3.622 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.325           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.588           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.313           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.618           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.664           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.664           ms/op

Benchmark result is saved to 1718930226929.json
