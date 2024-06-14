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
# Warmup Iteration   1: 1.707 ops/ms
Iteration   1: 6.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.344 ops/ms


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
# Warmup Iteration   1: 5.983 ops/ms
Iteration   1: 11.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.694 ops/ms


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
# Warmup Iteration   1: 5.600 ops/ms
Iteration   1: 13.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.000 ops/ms


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
# Warmup Iteration   1: 5.180 ops/ms
Iteration   1: 7.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.889 ops/ms


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.062 ms/op
Iteration   1: 1.967 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.967 ms/op


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
# Warmup Iteration   1: 3.129 ±(99.9%) 0.052 ms/op
Iteration   1: 1.876 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.876 ms/op


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
# Warmup Iteration   1: 3.125 ±(99.9%) 0.058 ms/op
Iteration   1: 2.030 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.030 ms/op


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
# Warmup Iteration   1: 4.515 ±(99.9%) 0.090 ms/op
Iteration   1: 3.488 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.488 ms/op


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
# Warmup Iteration   1: 3.444 ±(99.9%) 0.078 ms/op
Iteration   1: 2.133 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   1.970 ms/op
                 createUser·p0.90:   2.585 ms/op
                 createUser·p0.95:   2.908 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  17.564 ms/op
                 createUser·p0.9999: 18.548 ms/op
                 createUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14982
  mean =      2.133 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 12959 
    [ 2.500,  3.750) = 1752 
    [ 3.750,  5.000) = 140 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     18.548 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 3.207 ±(99.9%) 0.095 ms/op
Iteration   1: 1.906 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.424 ms/op
                 existUser·p0.50:   1.792 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.560 ms/op
                 existUser·p0.99:   3.277 ms/op
                 existUser·p0.999:  25.788 ms/op
                 existUser·p0.9999: 25.887 ms/op
                 existUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16760
  mean =      1.906 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15756 
    [ 2.500,  5.000) = 909 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      1.792 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      3.277 ms/op
     p(99.9000) =     25.788 ms/op
     p(99.9900) =     25.887 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 3.095 ±(99.9%) 0.074 ms/op
Iteration   1: 1.882 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   1.772 ms/op
                 getUser·p0.90:   2.331 ms/op
                 getUser·p0.95:   2.540 ms/op
                 getUser·p0.99:   3.900 ms/op
                 getUser·p0.999:  17.007 ms/op
                 getUser·p0.9999: 17.836 ms/op
                 getUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16984
  mean =      1.882 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 15884 
    [ 2.500,  3.750) = 781 
    [ 3.750,  5.000) = 111 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      3.900 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     17.836 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 4.541 ±(99.9%) 0.153 ms/op
Iteration   1: 3.268 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   3.105 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  21.077 ms/op
                 listUser·p0.9999: 21.266 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9776
  mean =      3.268 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1351 
    [ 2.500,  5.000) = 8170 
    [ 5.000,  7.500) = 142 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      8.151 ms/op
     p(99.9000) =     21.077 ms/op
     p(99.9900) =     21.266 ms/op
     p(99.9990) =     21.266 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.344          ops/ms
ClientSimple.existUser                       thrpt         11.694          ops/ms
ClientSimple.getUser                         thrpt         13.000          ops/ms
ClientSimple.listUser                        thrpt          7.889          ops/ms
ClientSimple.createUser                       avgt          1.967           ms/op
ClientSimple.existUser                        avgt          1.876           ms/op
ClientSimple.getUser                          avgt          2.030           ms/op
ClientSimple.listUser                         avgt          3.488           ms/op
ClientSimple.createUser                     sample  14982   2.133 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.988           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.970           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.585           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.908           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.456           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.564           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.548           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.842           ms/op
ClientSimple.existUser                      sample  16760   1.906 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.424           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.792           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.277           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.788           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.887           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.887           ms/op
ClientSimple.getUser                        sample  16984   1.882 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.646           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.772           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.331           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.540           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.900           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.007           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.836           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.859           ms/op
ClientSimple.listUser                       sample   9776   3.268 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.810           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.105           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.166           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.151           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.077           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.266           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.266           ms/op

Benchmark result is saved to 1718325432604.json
