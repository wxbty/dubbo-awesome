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
# Warmup Iteration   1: 0.920 ops/ms
Iteration   1: 6.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.819 ops/ms


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
# Warmup Iteration   1: 5.007 ops/ms
Iteration   1: 13.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.007 ops/ms


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
# Warmup Iteration   1: 6.122 ops/ms
Iteration   1: 11.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.872 ops/ms


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
# Warmup Iteration   1: 3.927 ops/ms
Iteration   1: 9.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.255 ops/ms


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
# Warmup Iteration   1: 4.821 ±(99.9%) 0.115 ms/op
Iteration   1: 2.124 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.124 ms/op


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
# Warmup Iteration   1: 3.473 ±(99.9%) 0.061 ms/op
Iteration   1: 2.016 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.016 ms/op


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
# Warmup Iteration   1: 3.668 ±(99.9%) 0.066 ms/op
Iteration   1: 2.146 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.146 ms/op


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
# Warmup Iteration   1: 4.456 ±(99.9%) 0.091 ms/op
Iteration   1: 3.233 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.233 ms/op


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
# Warmup Iteration   1: 3.563 ±(99.9%) 0.092 ms/op
Iteration   1: 2.387 ±(99.9%) 0.055 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   2.183 ms/op
                 createUser·p0.90:   2.597 ms/op
                 createUser·p0.95:   2.803 ms/op
                 createUser·p0.99:   11.578 ms/op
                 createUser·p0.999:  30.952 ms/op
                 createUser·p0.9999: 33.227 ms/op
                 createUser·p1.00:   33.227 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13432
  mean =      2.387 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11467 
    [ 2.500,  5.000) = 1740 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      2.183 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.803 ms/op
     p(99.0000) =     11.578 ms/op
     p(99.9000) =     30.952 ms/op
     p(99.9900) =     33.227 ms/op
     p(99.9990) =     33.227 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


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
# Warmup Iteration   1: 2.878 ±(99.9%) 0.064 ms/op
Iteration   1: 1.795 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.290 ms/op
                 existUser·p0.50:   1.698 ms/op
                 existUser·p0.90:   2.232 ms/op
                 existUser·p0.95:   2.396 ms/op
                 existUser·p0.99:   2.810 ms/op
                 existUser·p0.999:  25.368 ms/op
                 existUser·p0.9999: 27.252 ms/op
                 existUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17821
  mean =      1.795 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17290 
    [ 2.500,  5.000) = 484 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.290 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.232 ms/op
     p(95.0000) =      2.396 ms/op
     p(99.0000) =      2.810 ms/op
     p(99.9000) =     25.368 ms/op
     p(99.9900) =     27.252 ms/op
     p(99.9990) =     27.918 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 3.216 ±(99.9%) 0.078 ms/op
Iteration   1: 1.970 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   1.901 ms/op
                 getUser·p0.90:   2.228 ms/op
                 getUser·p0.95:   2.470 ms/op
                 getUser·p0.99:   3.763 ms/op
                 getUser·p0.999:  20.087 ms/op
                 getUser·p0.9999: 21.894 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16409
  mean =      1.970 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15637 
    [ 2.500,  5.000) = 679 
    [ 5.000,  7.500) = 55 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.228 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      3.763 ms/op
     p(99.9000) =     20.087 ms/op
     p(99.9900) =     21.894 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 4.709 ±(99.9%) 0.146 ms/op
Iteration   1: 3.193 ±(99.9%) 0.106 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   2.818 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.129 ms/op
                 listUser·p0.99:   5.031 ms/op
                 listUser·p0.999:  60.683 ms/op
                 listUser·p0.9999: 61.669 ms/op
                 listUser·p1.00:   61.669 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10028
  mean =      3.193 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9926 
    [ 5.000, 10.000) = 67 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 6 
    [60.000, 65.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      5.031 ms/op
     p(99.9000) =     60.683 ms/op
     p(99.9900) =     61.669 ms/op
     p(99.9990) =     61.669 ms/op
     p(99.9999) =     61.669 ms/op
    p(100.0000) =     61.669 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.819          ops/ms
ClientSimple.existUser                       thrpt         13.007          ops/ms
ClientSimple.getUser                         thrpt         11.872          ops/ms
ClientSimple.listUser                        thrpt          9.255          ops/ms
ClientSimple.createUser                       avgt          2.124           ms/op
ClientSimple.existUser                        avgt          2.016           ms/op
ClientSimple.getUser                          avgt          2.146           ms/op
ClientSimple.listUser                         avgt          3.233           ms/op
ClientSimple.createUser                     sample  13432   2.387 ± 0.055   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.872           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.183           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.597           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.803           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.578           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.952           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.227           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.227           ms/op
ClientSimple.existUser                      sample  17821   1.795 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.290           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.698           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.232           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.810           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.368           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.252           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.918           ms/op
ClientSimple.getUser                        sample  16409   1.970 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.764           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.901           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.228           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.470           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.763           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.087           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.894           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.020           ms/op
ClientSimple.listUser                       sample  10028   3.193 ± 0.106   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.862           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.818           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.936           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.129           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.031           ms/op
ClientSimple.listUser:listUser·p0.999       sample         60.683           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         61.669           ms/op
ClientSimple.listUser:listUser·p1.00        sample         61.669           ms/op

Benchmark result is saved to 1719103233280.json
