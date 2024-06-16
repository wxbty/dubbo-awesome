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
# Warmup Iteration   1: 1.887 ops/ms
Iteration   1: 6.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.366 ops/ms


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
# Warmup Iteration   1: 6.355 ops/ms
Iteration   1: 13.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.444 ops/ms


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
# Warmup Iteration   1: 5.701 ops/ms
Iteration   1: 13.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.673 ops/ms


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
# Warmup Iteration   1: 4.785 ops/ms
Iteration   1: 8.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.036 ops/ms


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.072 ms/op
Iteration   1: 2.125 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.125 ms/op


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
# Warmup Iteration   1: 3.201 ±(99.9%) 0.059 ms/op
Iteration   1: 1.922 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.922 ms/op


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
# Warmup Iteration   1: 3.329 ±(99.9%) 0.065 ms/op
Iteration   1: 2.182 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.182 ms/op


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
# Warmup Iteration   1: 4.563 ±(99.9%) 0.100 ms/op
Iteration   1: 3.259 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.259 ms/op


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
# Warmup Iteration   1: 3.803 ±(99.9%) 0.099 ms/op
Iteration   1: 1.955 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.391 ms/op
                 createUser·p0.50:   1.821 ms/op
                 createUser·p0.90:   2.249 ms/op
                 createUser·p0.95:   2.523 ms/op
                 createUser·p0.99:   7.174 ms/op
                 createUser·p0.999:  23.472 ms/op
                 createUser·p0.9999: 24.918 ms/op
                 createUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16421
  mean =      1.955 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15568 
    [ 2.500,  5.000) = 580 
    [ 5.000,  7.500) = 131 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.249 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      7.174 ms/op
     p(99.9000) =     23.472 ms/op
     p(99.9900) =     24.918 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 3.119 ±(99.9%) 0.064 ms/op
Iteration   1: 1.793 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.590 ms/op
                 existUser·p0.50:   1.694 ms/op
                 existUser·p0.90:   2.058 ms/op
                 existUser·p0.95:   2.256 ms/op
                 existUser·p0.99:   4.384 ms/op
                 existUser·p0.999:  15.139 ms/op
                 existUser·p0.9999: 16.065 ms/op
                 existUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17841
  mean =      1.793 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 17228 
    [ 2.500,  3.750) = 278 
    [ 3.750,  5.000) = 84 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      1.694 ms/op
     p(90.0000) =      2.058 ms/op
     p(95.0000) =      2.256 ms/op
     p(99.0000) =      4.384 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     16.065 ms/op
     p(99.9990) =     16.155 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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
# Warmup Iteration   1: 3.176 ±(99.9%) 0.079 ms/op
Iteration   1: 2.037 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   1.956 ms/op
                 getUser·p0.90:   2.691 ms/op
                 getUser·p0.95:   3.052 ms/op
                 getUser·p0.99:   4.109 ms/op
                 getUser·p0.999:  16.584 ms/op
                 getUser·p0.9999: 19.281 ms/op
                 getUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15888
  mean =      2.037 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 531 
    [ 1.250,  2.500) = 13127 
    [ 2.500,  3.750) = 2021 
    [ 3.750,  5.000) = 126 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      4.109 ms/op
     p(99.9000) =     16.584 ms/op
     p(99.9900) =     19.281 ms/op
     p(99.9990) =     19.300 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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
# Warmup Iteration   1: 4.415 ±(99.9%) 0.115 ms/op
Iteration   1: 3.645 ±(99.9%) 0.049 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.449 ms/op
                 listUser·p0.999:  20.455 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8770
  mean =      3.645 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1224 
    [ 2.500,  5.000) = 7193 
    [ 5.000,  7.500) = 269 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.449 ms/op
     p(99.9000) =     20.455 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.366          ops/ms
ClientSimple.existUser                       thrpt         13.444          ops/ms
ClientSimple.getUser                         thrpt         13.673          ops/ms
ClientSimple.listUser                        thrpt          8.036          ops/ms
ClientSimple.createUser                       avgt          2.125           ms/op
ClientSimple.existUser                        avgt          1.922           ms/op
ClientSimple.getUser                          avgt          2.182           ms/op
ClientSimple.listUser                         avgt          3.259           ms/op
ClientSimple.createUser                     sample  16421   1.955 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.391           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.821           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.249           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.174           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.472           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.918           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.002           ms/op
ClientSimple.existUser                      sample  17841   1.793 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.590           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.694           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.058           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.256           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.384           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.139           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.065           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.155           ms/op
ClientSimple.getUser                        sample  15888   2.037 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.593           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.956           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.691           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.052           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.109           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.584           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.281           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.300           ms/op
ClientSimple.listUser                       sample   8770   3.645 ± 0.049   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.104           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.752           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.547           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.891           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.449           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.455           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.496           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.496           ms/op

Benchmark result is saved to 1718561416058.json
