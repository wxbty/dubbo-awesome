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
# Warmup Iteration   1: 2.060 ops/ms
Iteration   1: 7.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.167 ops/ms


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
# Warmup Iteration   1: 5.445 ops/ms
Iteration   1: 12.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.795 ops/ms


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
# Warmup Iteration   1: 6.279 ops/ms
Iteration   1: 13.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.189 ops/ms


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
# Warmup Iteration   1: 3.914 ops/ms
Iteration   1: 8.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.024 ops/ms


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
# Warmup Iteration   1: 3.711 ±(99.9%) 0.067 ms/op
Iteration   1: 2.287 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.287 ms/op


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
# Warmup Iteration   1: 3.380 ±(99.9%) 0.055 ms/op
Iteration   1: 1.684 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.684 ms/op


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
# Warmup Iteration   1: 3.317 ±(99.9%) 0.054 ms/op
Iteration   1: 1.953 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.953 ms/op


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
# Warmup Iteration   1: 4.911 ±(99.9%) 0.109 ms/op
Iteration   1: 3.119 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.119 ms/op


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.114 ms/op
Iteration   1: 2.205 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   1.963 ms/op
                 createUser·p0.90:   2.769 ms/op
                 createUser·p0.95:   3.465 ms/op
                 createUser·p0.99:   5.998 ms/op
                 createUser·p0.999:  16.212 ms/op
                 createUser·p0.9999: 17.680 ms/op
                 createUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14492
  mean =      2.205 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 173 
    [ 1.250,  2.500) = 11346 
    [ 2.500,  3.750) = 2431 
    [ 3.750,  5.000) = 350 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      1.963 ms/op
     p(90.0000) =      2.769 ms/op
     p(95.0000) =      3.465 ms/op
     p(99.0000) =      5.998 ms/op
     p(99.9000) =     16.212 ms/op
     p(99.9900) =     17.680 ms/op
     p(99.9990) =     17.695 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 2.946 ±(99.9%) 0.062 ms/op
Iteration   1: 1.947 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.646 ms/op
                 existUser·p0.50:   1.825 ms/op
                 existUser·p0.90:   2.437 ms/op
                 existUser·p0.95:   2.675 ms/op
                 existUser·p0.99:   5.901 ms/op
                 existUser·p0.999:  13.337 ms/op
                 existUser·p0.9999: 13.752 ms/op
                 existUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16417
  mean =      1.947 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 423 
    [ 1.250,  2.500) = 14587 
    [ 2.500,  3.750) = 1121 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      5.901 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     13.752 ms/op
     p(99.9990) =     13.763 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


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
# Warmup Iteration   1: 3.173 ±(99.9%) 0.089 ms/op
Iteration   1: 2.182 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.553 ms/op
                 getUser·p0.50:   1.962 ms/op
                 getUser·p0.90:   2.707 ms/op
                 getUser·p0.95:   3.091 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  13.022 ms/op
                 getUser·p0.9999: 15.912 ms/op
                 getUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14704
  mean =      2.182 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 12296 
    [ 2.500,  3.750) = 1932 
    [ 3.750,  5.000) = 196 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      1.962 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      3.091 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     13.022 ms/op
     p(99.9900) =     15.912 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 4.591 ±(99.9%) 0.144 ms/op
Iteration   1: 3.919 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   9.338 ms/op
                 listUser·p0.999:  12.576 ms/op
                 listUser·p0.9999: 12.878 ms/op
                 listUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8204
  mean =      3.919 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 340 
    [ 2.500,  3.750) = 3716 
    [ 3.750,  5.000) = 3532 
    [ 5.000,  6.250) = 411 
    [ 6.250,  7.500) = 107 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      9.338 ms/op
     p(99.9000) =     12.576 ms/op
     p(99.9900) =     12.878 ms/op
     p(99.9990) =     12.878 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.167          ops/ms
ClientSimple.existUser                       thrpt         12.795          ops/ms
ClientSimple.getUser                         thrpt         13.189          ops/ms
ClientSimple.listUser                        thrpt          8.024          ops/ms
ClientSimple.createUser                       avgt          2.287           ms/op
ClientSimple.existUser                        avgt          1.684           ms/op
ClientSimple.getUser                          avgt          1.953           ms/op
ClientSimple.listUser                         avgt          3.119           ms/op
ClientSimple.createUser                     sample  14492   2.205 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.593           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.963           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.769           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.465           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.998           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.212           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.680           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.695           ms/op
ClientSimple.existUser                      sample  16417   1.947 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.646           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.825           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.675           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.901           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.337           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.752           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.763           ms/op
ClientSimple.getUser                        sample  14704   2.182 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.553           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.962           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.091           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.972           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.022           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.912           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.007           ms/op
ClientSimple.listUser                       sample   8204   3.919 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.967           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.764           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.899           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.218           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.338           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.576           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.878           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.878           ms/op

Benchmark result is saved to 1716943134193.json
