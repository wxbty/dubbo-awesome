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
# Warmup Iteration   1: 1.260 ops/ms
Iteration   1: 5.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.785 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.214 ops/ms
Iteration   1: 13.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.197 ops/ms


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
# Warmup Iteration   1: 5.766 ops/ms
Iteration   1: 12.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.751 ops/ms


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
# Warmup Iteration   1: 4.832 ops/ms
Iteration   1: 8.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.249 ops/ms


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
# Warmup Iteration   1: 3.615 ±(99.9%) 0.071 ms/op
Iteration   1: 2.294 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.294 ms/op


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
# Warmup Iteration   1: 3.347 ±(99.9%) 0.055 ms/op
Iteration   1: 2.087 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.087 ms/op


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
# Warmup Iteration   1: 3.425 ±(99.9%) 0.060 ms/op
Iteration   1: 2.271 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.271 ms/op


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
# Warmup Iteration   1: 5.056 ±(99.9%) 0.121 ms/op
Iteration   1: 4.210 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.210 ms/op


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
# Warmup Iteration   1: 3.462 ±(99.9%) 0.081 ms/op
Iteration   1: 2.416 ±(99.9%) 0.056 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   2.204 ms/op
                 createUser·p0.90:   2.875 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   9.758 ms/op
                 createUser·p0.999:  34.401 ms/op
                 createUser·p0.9999: 34.931 ms/op
                 createUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13539
  mean =      2.416 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10082 
    [ 2.500,  5.000) = 3186 
    [ 5.000,  7.500) = 115 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      9.758 ms/op
     p(99.9000) =     34.401 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 2.976 ±(99.9%) 0.070 ms/op
Iteration   1: 1.790 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.520 ms/op
                 existUser·p0.50:   1.634 ms/op
                 existUser·p0.90:   2.384 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   2.994 ms/op
                 existUser·p0.999:  9.837 ms/op
                 existUser·p0.9999: 10.935 ms/op
                 existUser·p1.00:   10.961 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17893
  mean =      1.790 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 187 
    [ 1.250,  2.500) = 16525 
    [ 2.500,  3.750) = 1101 
    [ 3.750,  5.000) = 6 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      1.634 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      2.994 ms/op
     p(99.9000) =      9.837 ms/op
     p(99.9900) =     10.935 ms/op
     p(99.9990) =     10.961 ms/op
     p(99.9999) =     10.961 ms/op
    p(100.0000) =     10.961 ms/op


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
# Warmup Iteration   1: 3.243 ±(99.9%) 0.078 ms/op
Iteration   1: 2.055 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   1.937 ms/op
                 getUser·p0.90:   2.605 ms/op
                 getUser·p0.95:   2.884 ms/op
                 getUser·p0.99:   4.192 ms/op
                 getUser·p0.999:  18.904 ms/op
                 getUser·p0.9999: 19.104 ms/op
                 getUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15554
  mean =      2.055 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 296 
    [ 1.250,  2.500) = 13262 
    [ 2.500,  3.750) = 1811 
    [ 3.750,  5.000) = 110 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      4.192 ms/op
     p(99.9000) =     18.904 ms/op
     p(99.9900) =     19.104 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.810 ±(99.9%) 0.147 ms/op
Iteration   1: 3.347 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   3.142 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   5.852 ms/op
                 listUser·p0.999:  6.687 ms/op
                 listUser·p0.9999: 10.240 ms/op
                 listUser·p1.00:   10.240 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9565
  mean =      3.347 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 55 
    [ 2.000,  3.000) = 4083 
    [ 3.000,  4.000) = 3323 
    [ 4.000,  5.000) = 1857 
    [ 5.000,  6.000) = 183 
    [ 6.000,  7.000) = 61 
    [ 7.000,  8.000) = 2 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.852 ms/op
     p(99.9000) =      6.687 ms/op
     p(99.9900) =     10.240 ms/op
     p(99.9990) =     10.240 ms/op
     p(99.9999) =     10.240 ms/op
    p(100.0000) =     10.240 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.785          ops/ms
ClientSimple.existUser                       thrpt         13.197          ops/ms
ClientSimple.getUser                         thrpt         12.751          ops/ms
ClientSimple.listUser                        thrpt          8.249          ops/ms
ClientSimple.createUser                       avgt          2.294           ms/op
ClientSimple.existUser                        avgt          2.087           ms/op
ClientSimple.getUser                          avgt          2.271           ms/op
ClientSimple.listUser                         avgt          4.210           ms/op
ClientSimple.createUser                     sample  13539   2.416 ± 0.056   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.686           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.204           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.875           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.195           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.758           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.401           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.931           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.931           ms/op
ClientSimple.existUser                      sample  17893   1.790 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.520           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.634           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.384           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.994           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.837           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.935           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.961           ms/op
ClientSimple.getUser                        sample  15554   2.055 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.690           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.937           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.884           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.192           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.904           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.104           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.104           ms/op
ClientSimple.listUser                       sample   9565   3.347 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.223           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.142           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.852           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.687           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.240           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.240           ms/op

Benchmark result is saved to 1718172731596.json
