# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.809 ops/ms
Iteration   1: 1.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.939 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 3.230 ops/ms
Iteration   1: 7.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  7.279 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.321 ops/ms
Iteration   1: 3.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  3.811 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.027 ops/ms
Iteration   1: 2.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.545 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 10.650 ±(99.9%) 0.190 ms/op
Iteration   1: 6.540 ±(99.9%) 0.068 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.540 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.555 ±(99.9%) 0.073 ms/op
Iteration   1: 3.452 ±(99.9%) 0.050 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  3.452 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.608 ±(99.9%) 0.219 ms/op
Iteration   1: 7.529 ±(99.9%) 0.062 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  7.529 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.244 ±(99.9%) 0.202 ms/op
Iteration   1: 10.730 ±(99.9%) 0.131 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  10.730 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.839 ±(99.9%) 0.301 ms/op
Iteration   1: 7.685 ±(99.9%) 0.147 ms/op
                 createUser·p0.00:   2.302 ms/op
                 createUser·p0.50:   6.840 ms/op
                 createUser·p0.90:   10.735 ms/op
                 createUser·p0.95:   12.534 ms/op
                 createUser·p0.99:   22.086 ms/op
                 createUser·p0.999:  25.166 ms/op
                 createUser·p0.9999: 25.428 ms/op
                 createUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 4167
  mean =      7.685 ±(99.9%) 0.147 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 134 
    [ 5.000,  7.500) = 2840 
    [ 7.500, 10.000) = 644 
    [10.000, 12.500) = 336 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      2.302 ms/op
     p(50.0000) =      6.840 ms/op
     p(90.0000) =     10.735 ms/op
     p(95.0000) =     12.534 ms/op
     p(99.0000) =     22.086 ms/op
     p(99.9000) =     25.166 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     25.428 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.058 ±(99.9%) 0.115 ms/op
Iteration   1: 3.559 ±(99.9%) 0.052 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   5.256 ms/op
                 existUser·p0.99:   10.879 ms/op
                 existUser·p0.999:  19.759 ms/op
                 existUser·p0.9999: 19.890 ms/op
                 existUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 8986
  mean =      3.559 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 1015 
    [ 2.500,  3.750) = 5324 
    [ 3.750,  5.000) = 2040 
    [ 5.000,  6.250) = 252 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 121 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.256 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 10.079 ±(99.9%) 0.326 ms/op
Iteration   1: 6.640 ±(99.9%) 0.065 ms/op
                 getUser·p0.00:   2.236 ms/op
                 getUser·p0.50:   6.607 ms/op
                 getUser·p0.90:   8.372 ms/op
                 getUser·p0.95:   8.946 ms/op
                 getUser·p0.99:   10.158 ms/op
                 getUser·p0.999:  12.517 ms/op
                 getUser·p0.9999: 12.911 ms/op
                 getUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 4824
  mean =      6.640 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2 
    [ 2.500,  3.750) = 25 
    [ 3.750,  5.000) = 565 
    [ 5.000,  6.250) = 1365 
    [ 6.250,  7.500) = 1545 
    [ 7.500,  8.750) = 1024 
    [ 8.750, 10.000) = 240 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.236 ms/op
     p(50.0000) =      6.607 ms/op
     p(90.0000) =      8.372 ms/op
     p(95.0000) =      8.946 ms/op
     p(99.0000) =     10.158 ms/op
     p(99.9000) =     12.517 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     12.911 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 13.108 ±(99.9%) 0.522 ms/op
Iteration   1: 9.836 ±(99.9%) 0.186 ms/op
                 listUser·p0.00:   3.400 ms/op
                 listUser·p0.50:   9.413 ms/op
                 listUser·p0.90:   12.730 ms/op
                 listUser·p0.95:   13.992 ms/op
                 listUser·p0.99:   23.355 ms/op
                 listUser·p0.999:  32.937 ms/op
                 listUser·p0.9999: 34.669 ms/op
                 listUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 3314
  mean =      9.836 ±(99.9%) 0.186 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 64 
    [ 5.000,  7.500) = 455 
    [ 7.500, 10.000) = 1472 
    [10.000, 12.500) = 935 
    [12.500, 15.000) = 273 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.400 ms/op
     p(50.0000) =      9.413 ms/op
     p(90.0000) =     12.730 ms/op
     p(95.0000) =     13.992 ms/op
     p(99.0000) =     23.355 ms/op
     p(99.9000) =     32.937 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     34.669 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode   Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt         1.939          ops/ms
ClientSimple.existUser                       thrpt         7.279          ops/ms
ClientSimple.getUser                         thrpt         3.811          ops/ms
ClientSimple.listUser                        thrpt         2.545          ops/ms
ClientSimple.createUser                       avgt         6.540           ms/op
ClientSimple.existUser                        avgt         3.452           ms/op
ClientSimple.getUser                          avgt         7.529           ms/op
ClientSimple.listUser                         avgt        10.730           ms/op
ClientSimple.createUser                     sample  4167   7.685 ± 0.147   ms/op
ClientSimple.createUser:createUser·p0.00    sample         2.302           ms/op
ClientSimple.createUser:createUser·p0.50    sample         6.840           ms/op
ClientSimple.createUser:createUser·p0.90    sample        10.735           ms/op
ClientSimple.createUser:createUser·p0.95    sample        12.534           ms/op
ClientSimple.createUser:createUser·p0.99    sample        22.086           ms/op
ClientSimple.createUser:createUser·p0.999   sample        25.166           ms/op
ClientSimple.createUser:createUser·p0.9999  sample        25.428           ms/op
ClientSimple.createUser:createUser·p1.00    sample        25.428           ms/op
ClientSimple.existUser                      sample  8986   3.559 ± 0.052   ms/op
ClientSimple.existUser:existUser·p0.00      sample         0.673           ms/op
ClientSimple.existUser:existUser·p0.50      sample         3.260           ms/op
ClientSimple.existUser:existUser·p0.90      sample         4.653           ms/op
ClientSimple.existUser:existUser·p0.95      sample         5.256           ms/op
ClientSimple.existUser:existUser·p0.99      sample        10.879           ms/op
ClientSimple.existUser:existUser·p0.999     sample        19.759           ms/op
ClientSimple.existUser:existUser·p0.9999    sample        19.890           ms/op
ClientSimple.existUser:existUser·p1.00      sample        19.890           ms/op
ClientSimple.getUser                        sample  4824   6.640 ± 0.065   ms/op
ClientSimple.getUser:getUser·p0.00          sample         2.236           ms/op
ClientSimple.getUser:getUser·p0.50          sample         6.607           ms/op
ClientSimple.getUser:getUser·p0.90          sample         8.372           ms/op
ClientSimple.getUser:getUser·p0.95          sample         8.946           ms/op
ClientSimple.getUser:getUser·p0.99          sample        10.158           ms/op
ClientSimple.getUser:getUser·p0.999         sample        12.517           ms/op
ClientSimple.getUser:getUser·p0.9999        sample        12.911           ms/op
ClientSimple.getUser:getUser·p1.00          sample        12.911           ms/op
ClientSimple.listUser                       sample  3314   9.836 ± 0.186   ms/op
ClientSimple.listUser:listUser·p0.00        sample         3.400           ms/op
ClientSimple.listUser:listUser·p0.50        sample         9.413           ms/op
ClientSimple.listUser:listUser·p0.90        sample        12.730           ms/op
ClientSimple.listUser:listUser·p0.95        sample        13.992           ms/op
ClientSimple.listUser:listUser·p0.99        sample        23.355           ms/op
ClientSimple.listUser:listUser·p0.999       sample        32.937           ms/op
ClientSimple.listUser:listUser·p0.9999      sample        34.669           ms/op
ClientSimple.listUser:listUser·p1.00        sample        34.669           ms/op

Benchmark result is saved to 1718066261904.json
