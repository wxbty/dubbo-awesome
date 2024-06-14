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
# Warmup Iteration   1: 1.853 ops/ms
Iteration   1: 7.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.578 ops/ms


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
# Warmup Iteration   1: 6.144 ops/ms
Iteration   1: 13.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.650 ops/ms


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
# Warmup Iteration   1: 6.148 ops/ms
Iteration   1: 13.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.218 ops/ms


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
# Warmup Iteration   1: 5.575 ops/ms
Iteration   1: 8.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.640 ops/ms


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
# Warmup Iteration   1: 3.821 ±(99.9%) 0.063 ms/op
Iteration   1: 2.151 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.151 ms/op


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
# Warmup Iteration   1: 2.762 ±(99.9%) 0.051 ms/op
Iteration   1: 1.839 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.839 ms/op


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
# Warmup Iteration   1: 3.192 ±(99.9%) 0.060 ms/op
Iteration   1: 1.897 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.897 ms/op


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.077 ms/op
Iteration   1: 3.243 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.243 ms/op


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
# Warmup Iteration   1: 3.779 ±(99.9%) 0.127 ms/op
Iteration   1: 2.271 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   2.171 ms/op
                 createUser·p0.90:   2.748 ms/op
                 createUser·p0.95:   2.920 ms/op
                 createUser·p0.99:   7.135 ms/op
                 createUser·p0.999:  14.647 ms/op
                 createUser·p0.9999: 14.811 ms/op
                 createUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14332
  mean =      2.271 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 11221 
    [ 2.500,  3.750) = 2734 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.171 ms/op
     p(90.0000) =      2.748 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     14.647 ms/op
     p(99.9900) =     14.811 ms/op
     p(99.9990) =     14.811 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 3.110 ±(99.9%) 0.069 ms/op
Iteration   1: 1.956 ±(99.9%) 0.117 ms/op
                 existUser·p0.00:   0.340 ms/op
                 existUser·p0.50:   1.538 ms/op
                 existUser·p0.90:   2.054 ms/op
                 existUser·p0.95:   2.335 ms/op
                 existUser·p0.99:   8.174 ms/op
                 existUser·p0.999:  91.885 ms/op
                 existUser·p0.9999: 129.331 ms/op
                 existUser·p1.00:   129.499 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16421
  mean =      1.956 ±(99.9%) 0.117 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 16333 
    [ 12.500,  25.000) = 7 
    [ 25.000,  37.500) = 37 
    [ 37.500,  50.000) = 6 
    [ 50.000,  62.500) = 8 
    [ 62.500,  75.000) = 7 
    [ 75.000,  87.500) = 5 
    [ 87.500, 100.000) = 6 
    [100.000, 112.500) = 5 
    [112.500, 125.000) = 4 
    [125.000, 137.500) = 3 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.340 ms/op
     p(50.0000) =      1.538 ms/op
     p(90.0000) =      2.054 ms/op
     p(95.0000) =      2.335 ms/op
     p(99.0000) =      8.174 ms/op
     p(99.9000) =     91.885 ms/op
     p(99.9900) =    129.331 ms/op
     p(99.9990) =    129.499 ms/op
     p(99.9999) =    129.499 ms/op
    p(100.0000) =    129.499 ms/op


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
# Warmup Iteration   1: 3.263 ±(99.9%) 0.085 ms/op
Iteration   1: 2.209 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.612 ms/op
                 getUser·p0.50:   2.167 ms/op
                 getUser·p0.90:   2.765 ms/op
                 getUser·p0.95:   2.941 ms/op
                 getUser·p0.99:   5.229 ms/op
                 getUser·p0.999:  12.313 ms/op
                 getUser·p0.9999: 12.905 ms/op
                 getUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14463
  mean =      2.209 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 213 
    [ 1.250,  2.500) = 11116 
    [ 2.500,  3.750) = 2926 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 104 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      5.229 ms/op
     p(99.9000) =     12.313 ms/op
     p(99.9900) =     12.905 ms/op
     p(99.9990) =     13.271 ms/op
     p(99.9999) =     13.271 ms/op
    p(100.0000) =     13.271 ms/op


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
# Warmup Iteration   1: 4.479 ±(99.9%) 0.137 ms/op
Iteration   1: 3.158 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.017 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.289 ms/op
                 listUser·p0.999:  8.077 ms/op
                 listUser·p0.9999: 8.379 ms/op
                 listUser·p1.00:   8.380 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10116
  mean =      3.158 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 16 
    [1.500, 2.000) = 107 
    [2.000, 2.500) = 986 
    [2.500, 3.000) = 4401 
    [3.000, 3.500) = 1746 
    [3.500, 4.000) = 1755 
    [4.000, 4.500) = 724 
    [4.500, 5.000) = 230 
    [5.000, 5.500) = 60 
    [5.500, 6.000) = 38 
    [6.000, 6.500) = 13 
    [6.500, 7.000) = 7 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 10 
    [8.000, 8.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.289 ms/op
     p(99.9000) =      8.077 ms/op
     p(99.9900) =      8.379 ms/op
     p(99.9990) =      8.380 ms/op
     p(99.9999) =      8.380 ms/op
    p(100.0000) =      8.380 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.578          ops/ms
ClientSimple.existUser                       thrpt          13.650          ops/ms
ClientSimple.getUser                         thrpt          13.218          ops/ms
ClientSimple.listUser                        thrpt           8.640          ops/ms
ClientSimple.createUser                       avgt           2.151           ms/op
ClientSimple.existUser                        avgt           1.839           ms/op
ClientSimple.getUser                          avgt           1.897           ms/op
ClientSimple.listUser                         avgt           3.243           ms/op
ClientSimple.createUser                     sample  14332    2.271 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.744           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.171           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.748           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.920           ms/op
ClientSimple.createUser:createUser·p0.99    sample           7.135           ms/op
ClientSimple.createUser:createUser·p0.999   sample          14.647           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          14.811           ms/op
ClientSimple.createUser:createUser·p1.00    sample          14.811           ms/op
ClientSimple.existUser                      sample  16421    1.956 ± 0.117   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.340           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.538           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.054           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.335           ms/op
ClientSimple.existUser:existUser·p0.99      sample           8.174           ms/op
ClientSimple.existUser:existUser·p0.999     sample          91.885           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         129.331           ms/op
ClientSimple.existUser:existUser·p1.00      sample         129.499           ms/op
ClientSimple.getUser                        sample  14463    2.209 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.612           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.167           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.765           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.941           ms/op
ClientSimple.getUser:getUser·p0.99          sample           5.229           ms/op
ClientSimple.getUser:getUser·p0.999         sample          12.313           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          12.905           ms/op
ClientSimple.getUser:getUser·p1.00          sample          13.271           ms/op
ClientSimple.listUser                       sample  10116    3.158 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.017           ms/op
ClientSimple.listUser:listUser·p0.50        sample           2.941           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.039           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.391           ms/op
ClientSimple.listUser:listUser·p0.99        sample           5.289           ms/op
ClientSimple.listUser:listUser·p0.999       sample           8.077           ms/op
ClientSimple.listUser:listUser·p0.9999      sample           8.379           ms/op
ClientSimple.listUser:listUser·p1.00        sample           8.380           ms/op

Benchmark result is saved to 1718345557779.json
