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
# Warmup Iteration   1: 1.841 ops/ms
Iteration   1: 6.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.762 ops/ms


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
# Warmup Iteration   1: 5.795 ops/ms
Iteration   1: 12.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.492 ops/ms


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
# Warmup Iteration   1: 6.850 ops/ms
Iteration   1: 14.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.238 ops/ms


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
# Warmup Iteration   1: 5.325 ops/ms
Iteration   1: 9.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.588 ops/ms


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
# Warmup Iteration   1: 3.711 ±(99.9%) 0.054 ms/op
Iteration   1: 2.031 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.031 ms/op


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
# Warmup Iteration   1: 3.190 ±(99.9%) 0.046 ms/op
Iteration   1: 1.937 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.937 ms/op


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
# Warmup Iteration   1: 3.130 ±(99.9%) 0.055 ms/op
Iteration   1: 1.902 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.902 ms/op


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
# Warmup Iteration   1: 5.927 ±(99.9%) 0.117 ms/op
Iteration   1: 3.797 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.797 ms/op


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
# Warmup Iteration   1: 3.263 ±(99.9%) 0.080 ms/op
Iteration   1: 2.141 ±(99.9%) 0.055 ms/op
                 createUser·p0.00:   0.514 ms/op
                 createUser·p0.50:   1.937 ms/op
                 createUser·p0.90:   2.576 ms/op
                 createUser·p0.95:   2.761 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  45.941 ms/op
                 createUser·p0.9999: 46.625 ms/op
                 createUser·p1.00:   46.662 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15622
  mean =      2.141 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15438 
    [ 5.000, 10.000) = 146 
    [10.000, 15.000) = 6 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     45.941 ms/op
     p(99.9900) =     46.625 ms/op
     p(99.9990) =     46.662 ms/op
     p(99.9999) =     46.662 ms/op
    p(100.0000) =     46.662 ms/op


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
# Warmup Iteration   1: 3.603 ±(99.9%) 0.132 ms/op
Iteration   1: 1.776 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   1.704 ms/op
                 existUser·p0.90:   2.114 ms/op
                 existUser·p0.95:   2.322 ms/op
                 existUser·p0.99:   3.105 ms/op
                 existUser·p0.999:  10.600 ms/op
                 existUser·p0.9999: 11.295 ms/op
                 existUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17997
  mean =      1.776 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 243 
    [ 1.250,  2.500) = 17347 
    [ 2.500,  3.750) = 290 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      1.704 ms/op
     p(90.0000) =      2.114 ms/op
     p(95.0000) =      2.322 ms/op
     p(99.0000) =      3.105 ms/op
     p(99.9000) =     10.600 ms/op
     p(99.9900) =     11.295 ms/op
     p(99.9990) =     11.387 ms/op
     p(99.9999) =     11.387 ms/op
    p(100.0000) =     11.387 ms/op


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
# Warmup Iteration   1: 3.275 ±(99.9%) 0.078 ms/op
Iteration   1: 1.958 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.618 ms/op
                 getUser·p0.50:   1.817 ms/op
                 getUser·p0.90:   2.281 ms/op
                 getUser·p0.95:   2.494 ms/op
                 getUser·p0.99:   4.152 ms/op
                 getUser·p0.999:  28.465 ms/op
                 getUser·p0.9999: 28.872 ms/op
                 getUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16321
  mean =      1.958 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15517 
    [ 2.500,  5.000) = 698 
    [ 5.000,  7.500) = 44 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.281 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      4.152 ms/op
     p(99.9000) =     28.465 ms/op
     p(99.9900) =     28.872 ms/op
     p(99.9990) =     28.934 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 4.461 ±(99.9%) 0.145 ms/op
Iteration   1: 3.714 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.151 ms/op
                 listUser·p0.999:  9.280 ms/op
                 listUser·p0.9999: 9.454 ms/op
                 listUser·p1.00:   9.454 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8618
  mean =      3.714 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 13 
    [ 1.500,  2.000) = 104 
    [ 2.000,  2.500) = 323 
    [ 2.500,  3.000) = 1137 
    [ 3.000,  3.500) = 1358 
    [ 3.500,  4.000) = 2767 
    [ 4.000,  4.500) = 2170 
    [ 4.500,  5.000) = 499 
    [ 5.000,  5.500) = 90 
    [ 5.500,  6.000) = 46 
    [ 6.000,  6.500) = 40 
    [ 6.500,  7.000) = 6 
    [ 7.000,  7.500) = 8 
    [ 7.500,  8.000) = 7 
    [ 8.000,  8.500) = 18 
    [ 8.500,  9.000) = 4 
    [ 9.000,  9.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.151 ms/op
     p(99.9000) =      9.280 ms/op
     p(99.9900) =      9.454 ms/op
     p(99.9990) =      9.454 ms/op
     p(99.9999) =      9.454 ms/op
    p(100.0000) =      9.454 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.762          ops/ms
ClientSimple.existUser                       thrpt         12.492          ops/ms
ClientSimple.getUser                         thrpt         14.238          ops/ms
ClientSimple.listUser                        thrpt          9.588          ops/ms
ClientSimple.createUser                       avgt          2.031           ms/op
ClientSimple.existUser                        avgt          1.937           ms/op
ClientSimple.getUser                          avgt          1.902           ms/op
ClientSimple.listUser                         avgt          3.797           ms/op
ClientSimple.createUser                     sample  15622   2.141 ± 0.055   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.514           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.937           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.587           ms/op
ClientSimple.createUser:createUser·p0.999   sample         45.941           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         46.625           ms/op
ClientSimple.createUser:createUser·p1.00    sample         46.662           ms/op
ClientSimple.existUser                      sample  17997   1.776 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.614           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.704           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.114           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.105           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.600           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.295           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.387           ms/op
ClientSimple.getUser                        sample  16321   1.958 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.618           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.817           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.281           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.494           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.152           ms/op
ClientSimple.getUser:getUser·p0.999         sample         28.465           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         28.872           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.934           ms/op
ClientSimple.listUser                       sample   8618   3.714 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.087           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.772           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.702           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.151           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.280           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.454           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.454           ms/op

Benchmark result is saved to 1717375084034.json
