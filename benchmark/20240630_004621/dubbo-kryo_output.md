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
# Warmup Iteration   1: 1.959 ops/ms
Iteration   1: 7.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.414 ops/ms


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
# Warmup Iteration   1: 7.472 ops/ms
Iteration   1: 12.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.674 ops/ms


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
# Warmup Iteration   1: 5.321 ops/ms
Iteration   1: 14.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.005 ops/ms


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
# Warmup Iteration   1: 4.897 ops/ms
Iteration   1: 8.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.610 ops/ms


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.076 ms/op
Iteration   1: 2.111 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.111 ms/op


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
# Warmup Iteration   1: 3.185 ±(99.9%) 0.045 ms/op
Iteration   1: 1.860 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.860 ms/op


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
# Warmup Iteration   1: 3.124 ±(99.9%) 0.048 ms/op
Iteration   1: 1.973 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.055 ±(99.9%) 0.098 ms/op
Iteration   1: 3.932 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.932 ms/op


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
# Warmup Iteration   1: 3.185 ±(99.9%) 0.072 ms/op
Iteration   1: 2.295 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.650 ms/op
                 createUser·p0.50:   2.101 ms/op
                 createUser·p0.90:   2.617 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  21.659 ms/op
                 createUser·p0.9999: 29.720 ms/op
                 createUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14010
  mean =      2.295 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11929 
    [ 2.500,  5.000) = 1804 
    [ 5.000,  7.500) = 138 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     21.659 ms/op
     p(99.9900) =     29.720 ms/op
     p(99.9990) =     29.852 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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
# Warmup Iteration   1: 2.896 ±(99.9%) 0.070 ms/op
Iteration   1: 1.914 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.444 ms/op
                 existUser·p0.50:   1.796 ms/op
                 existUser·p0.90:   2.340 ms/op
                 existUser·p0.95:   2.568 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  27.099 ms/op
                 existUser·p0.9999: 29.350 ms/op
                 existUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17065
  mean =      1.914 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15991 
    [ 2.500,  5.000) = 1008 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.340 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =     27.099 ms/op
     p(99.9900) =     29.350 ms/op
     p(99.9990) =     30.114 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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
# Warmup Iteration   1: 3.388 ±(99.9%) 0.075 ms/op
Iteration   1: 2.120 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   2.001 ms/op
                 getUser·p0.90:   2.658 ms/op
                 getUser·p0.95:   2.818 ms/op
                 getUser·p0.99:   3.536 ms/op
                 getUser·p0.999:  11.731 ms/op
                 getUser·p0.9999: 12.673 ms/op
                 getUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15073
  mean =      2.120 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 12448 
    [ 2.500,  3.750) = 2399 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      3.536 ms/op
     p(99.9000) =     11.731 ms/op
     p(99.9900) =     12.673 ms/op
     p(99.9990) =     12.681 ms/op
     p(99.9999) =     12.681 ms/op
    p(100.0000) =     12.681 ms/op


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
# Warmup Iteration   1: 4.574 ±(99.9%) 0.145 ms/op
Iteration   1: 3.162 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.112 ms/op
                 listUser·p0.99:   5.455 ms/op
                 listUser·p0.999:  24.762 ms/op
                 listUser·p0.9999: 28.540 ms/op
                 listUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10107
  mean =      3.162 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1761 
    [ 2.500,  5.000) = 8182 
    [ 5.000,  7.500) = 86 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.455 ms/op
     p(99.9000) =     24.762 ms/op
     p(99.9900) =     28.540 ms/op
     p(99.9990) =     28.541 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.414          ops/ms
ClientSimple.existUser                       thrpt         12.674          ops/ms
ClientSimple.getUser                         thrpt         14.005          ops/ms
ClientSimple.listUser                        thrpt          8.610          ops/ms
ClientSimple.createUser                       avgt          2.111           ms/op
ClientSimple.existUser                        avgt          1.860           ms/op
ClientSimple.getUser                          avgt          1.973           ms/op
ClientSimple.listUser                         avgt          3.932           ms/op
ClientSimple.createUser                     sample  14010   2.295 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.650           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.101           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.617           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.084           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.414           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.659           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.720           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.852           ms/op
ClientSimple.existUser                      sample  17065   1.914 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.444           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.796           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.340           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.817           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.099           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.350           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.114           ms/op
ClientSimple.getUser                        sample  15073   2.120 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.851           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.001           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.818           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.536           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.731           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.673           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.681           ms/op
ClientSimple.listUser                       sample  10107   3.162 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.049           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.912           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.871           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.112           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.455           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.762           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.540           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.541           ms/op

Benchmark result is saved to 1719708110312.json
