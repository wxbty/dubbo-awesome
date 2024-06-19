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
# Warmup Iteration   1: 2.075 ops/ms
Iteration   1: 7.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.639 ops/ms


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
# Warmup Iteration   1: 7.119 ops/ms
Iteration   1: 13.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.528 ops/ms


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
# Warmup Iteration   1: 6.012 ops/ms
Iteration   1: 15.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.099 ops/ms


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
# Warmup Iteration   1: 5.945 ops/ms
Iteration   1: 9.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.171 ops/ms


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.074 ms/op
Iteration   1: 2.560 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.560 ms/op


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
# Warmup Iteration   1: 3.147 ±(99.9%) 0.048 ms/op
Iteration   1: 1.884 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.884 ms/op


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
# Warmup Iteration   1: 3.240 ±(99.9%) 0.053 ms/op
Iteration   1: 1.929 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.929 ms/op


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
# Warmup Iteration   1: 4.169 ±(99.9%) 0.084 ms/op
Iteration   1: 3.549 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.549 ms/op


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
# Warmup Iteration   1: 3.358 ±(99.9%) 0.098 ms/op
Iteration   1: 2.265 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.611 ms/op
                 createUser·p0.50:   2.087 ms/op
                 createUser·p0.90:   2.871 ms/op
                 createUser·p0.95:   3.480 ms/op
                 createUser·p0.99:   5.991 ms/op
                 createUser·p0.999:  16.744 ms/op
                 createUser·p0.9999: 18.735 ms/op
                 createUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14168
  mean =      2.265 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 225 
    [ 1.250,  2.500) = 11163 
    [ 2.500,  3.750) = 2185 
    [ 3.750,  5.000) = 380 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      2.087 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      3.480 ms/op
     p(99.0000) =      5.991 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     18.735 ms/op
     p(99.9990) =     19.104 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 2.893 ±(99.9%) 0.066 ms/op
Iteration   1: 1.996 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.470 ms/op
                 existUser·p0.50:   1.901 ms/op
                 existUser·p0.90:   2.496 ms/op
                 existUser·p0.95:   2.691 ms/op
                 existUser·p0.99:   3.677 ms/op
                 existUser·p0.999:  18.382 ms/op
                 existUser·p0.9999: 18.514 ms/op
                 existUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16025
  mean =      1.996 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 690 
    [ 1.250,  2.500) = 13761 
    [ 2.500,  3.750) = 1429 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.496 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      3.677 ms/op
     p(99.9000) =     18.382 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.122 ms/op
Iteration   1: 2.382 ±(99.9%) 0.059 ms/op
                 getUser·p0.00:   0.521 ms/op
                 getUser·p0.50:   2.159 ms/op
                 getUser·p0.90:   2.802 ms/op
                 getUser·p0.95:   3.198 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  40.277 ms/op
                 getUser·p0.9999: 44.471 ms/op
                 getUser·p1.00:   44.696 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13422
  mean =      2.382 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13136 
    [ 5.000, 10.000) = 192 
    [10.000, 15.000) = 61 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.159 ms/op
     p(90.0000) =      2.802 ms/op
     p(95.0000) =      3.198 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     40.277 ms/op
     p(99.9900) =     44.471 ms/op
     p(99.9990) =     44.696 ms/op
     p(99.9999) =     44.696 ms/op
    p(100.0000) =     44.696 ms/op


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
# Warmup Iteration   1: 4.957 ±(99.9%) 0.166 ms/op
Iteration   1: 3.795 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  19.121 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8465
  mean =      3.795 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 591 
    [ 2.500,  5.000) = 7487 
    [ 5.000,  7.500) = 278 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     19.121 ms/op
     p(99.9900) =     20.447 ms/op
     p(99.9990) =     20.447 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.639          ops/ms
ClientSimple.existUser                       thrpt         13.528          ops/ms
ClientSimple.getUser                         thrpt         15.099          ops/ms
ClientSimple.listUser                        thrpt          9.171          ops/ms
ClientSimple.createUser                       avgt          2.560           ms/op
ClientSimple.existUser                        avgt          1.884           ms/op
ClientSimple.getUser                          avgt          1.929           ms/op
ClientSimple.listUser                         avgt          3.549           ms/op
ClientSimple.createUser                     sample  14168   2.265 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.611           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.087           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.871           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.480           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.991           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.744           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.735           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.104           ms/op
ClientSimple.existUser                      sample  16025   1.996 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.470           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.901           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.496           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.691           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.677           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.382           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.514           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.514           ms/op
ClientSimple.getUser                        sample  13422   2.382 ± 0.059   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.521           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.159           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.802           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.198           ms/op
ClientSimple.getUser:getUser·p0.99          sample          7.348           ms/op
ClientSimple.getUser:getUser·p0.999         sample         40.277           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         44.471           ms/op
ClientSimple.getUser:getUser·p1.00          sample         44.696           ms/op
ClientSimple.listUser                       sample   8465   3.795 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.053           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.813           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.948           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.471           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.121           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.447           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.447           ms/op

Benchmark result is saved to 1718757477974.json
