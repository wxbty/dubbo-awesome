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
# Warmup Iteration   1: 1.878 ops/ms
Iteration   1: 7.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.810 ops/ms


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
# Warmup Iteration   1: 5.170 ops/ms
Iteration   1: 13.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.219 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.305 ops/ms
Iteration   1: 10.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.990 ops/ms


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
# Warmup Iteration   1: 4.551 ops/ms
Iteration   1: 8.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.828 ops/ms


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
# Warmup Iteration   1: 4.085 ±(99.9%) 0.080 ms/op
Iteration   1: 2.334 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.334 ms/op


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
# Warmup Iteration   1: 3.526 ±(99.9%) 0.061 ms/op
Iteration   1: 1.810 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.810 ms/op


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
# Warmup Iteration   1: 3.064 ±(99.9%) 0.054 ms/op
Iteration   1: 2.043 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.043 ms/op


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
# Warmup Iteration   1: 4.693 ±(99.9%) 0.103 ms/op
Iteration   1: 3.556 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.556 ms/op


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.115 ms/op
Iteration   1: 2.227 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.430 ms/op
                 createUser·p0.50:   2.036 ms/op
                 createUser·p0.90:   2.654 ms/op
                 createUser·p0.95:   3.019 ms/op
                 createUser·p0.99:   7.411 ms/op
                 createUser·p0.999:  27.918 ms/op
                 createUser·p0.9999: 43.975 ms/op
                 createUser·p1.00:   43.975 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14411
  mean =      2.227 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14190 
    [ 5.000, 10.000) = 161 
    [10.000, 15.000) = 7 
    [15.000, 20.000) = 21 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 23 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.430 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =      7.411 ms/op
     p(99.9000) =     27.918 ms/op
     p(99.9900) =     43.975 ms/op
     p(99.9990) =     43.975 ms/op
     p(99.9999) =     43.975 ms/op
    p(100.0000) =     43.975 ms/op


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
# Warmup Iteration   1: 3.040 ±(99.9%) 0.073 ms/op
Iteration   1: 2.114 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.493 ms/op
                 existUser·p0.50:   2.071 ms/op
                 existUser·p0.90:   2.454 ms/op
                 existUser·p0.95:   2.568 ms/op
                 existUser·p0.99:   3.221 ms/op
                 existUser·p0.999:  18.940 ms/op
                 existUser·p0.9999: 19.446 ms/op
                 existUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15185
  mean =      2.114 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 162 
    [ 1.250,  2.500) = 13896 
    [ 2.500,  3.750) = 996 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.493 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.221 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     19.446 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 3.044 ±(99.9%) 0.074 ms/op
Iteration   1: 1.810 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.526 ms/op
                 getUser·p0.50:   1.675 ms/op
                 getUser·p0.90:   2.310 ms/op
                 getUser·p0.95:   2.466 ms/op
                 getUser·p0.99:   3.074 ms/op
                 getUser·p0.999:  15.909 ms/op
                 getUser·p0.9999: 16.892 ms/op
                 getUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17856
  mean =      1.810 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 529 
    [ 1.250,  2.500) = 16521 
    [ 2.500,  3.750) = 728 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      1.675 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      3.074 ms/op
     p(99.9000) =     15.909 ms/op
     p(99.9900) =     16.892 ms/op
     p(99.9990) =     17.072 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.147 ms/op
Iteration   1: 3.336 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   0.779 ms/op
                 listUser·p0.50:   3.084 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.169 ms/op
                 listUser·p0.999:  22.960 ms/op
                 listUser·p0.9999: 24.183 ms/op
                 listUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9581
  mean =      3.336 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1019 
    [ 2.500,  5.000) = 8243 
    [ 5.000,  7.500) = 232 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.169 ms/op
     p(99.9000) =     22.960 ms/op
     p(99.9900) =     24.183 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.810          ops/ms
ClientSimple.existUser                       thrpt         13.219          ops/ms
ClientSimple.getUser                         thrpt         10.990          ops/ms
ClientSimple.listUser                        thrpt          8.828          ops/ms
ClientSimple.createUser                       avgt          2.334           ms/op
ClientSimple.existUser                        avgt          1.810           ms/op
ClientSimple.getUser                          avgt          2.043           ms/op
ClientSimple.listUser                         avgt          3.556           ms/op
ClientSimple.createUser                     sample  14411   2.227 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.430           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.036           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.654           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.019           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.411           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.918           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         43.975           ms/op
ClientSimple.createUser:createUser·p1.00    sample         43.975           ms/op
ClientSimple.existUser                      sample  15185   2.114 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.493           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.071           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.454           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.221           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.940           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.446           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.497           ms/op
ClientSimple.getUser                        sample  17856   1.810 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.526           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.675           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.310           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.074           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.909           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.892           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.072           ms/op
ClientSimple.listUser                       sample   9581   3.336 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.779           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.084           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.170           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.169           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.960           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.183           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.183           ms/op

Benchmark result is saved to 1717676115714.json
