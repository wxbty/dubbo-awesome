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
# Warmup Iteration   1: 2.047 ops/ms
Iteration   1: 7.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.768 ops/ms


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
# Warmup Iteration   1: 5.831 ops/ms
Iteration   1: 12.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.271 ops/ms


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
# Warmup Iteration   1: 6.210 ops/ms
Iteration   1: 14.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.924 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.751 ops/ms
Iteration   1: 9.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.133 ops/ms


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
# Warmup Iteration   1: 4.727 ±(99.9%) 0.086 ms/op
Iteration   1: 2.251 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.251 ms/op


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
# Warmup Iteration   1: 3.100 ±(99.9%) 0.058 ms/op
Iteration   1: 1.913 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.913 ms/op


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
# Warmup Iteration   1: 3.527 ±(99.9%) 0.072 ms/op
Iteration   1: 2.093 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.093 ms/op


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
# Warmup Iteration   1: 4.174 ±(99.9%) 0.086 ms/op
Iteration   1: 3.159 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.159 ms/op


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
# Warmup Iteration   1: 3.635 ±(99.9%) 0.093 ms/op
Iteration   1: 2.186 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   0.541 ms/op
                 createUser·p0.50:   1.911 ms/op
                 createUser·p0.90:   2.572 ms/op
                 createUser·p0.95:   2.802 ms/op
                 createUser·p0.99:   10.093 ms/op
                 createUser·p0.999:  30.631 ms/op
                 createUser·p0.9999: 30.769 ms/op
                 createUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14606
  mean =      2.186 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12818 
    [ 2.500,  5.000) = 1570 
    [ 5.000,  7.500) = 20 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     30.631 ms/op
     p(99.9900) =     30.769 ms/op
     p(99.9990) =     30.769 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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
# Warmup Iteration   1: 2.987 ±(99.9%) 0.081 ms/op
Iteration   1: 1.647 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.414 ms/op
                 existUser·p0.50:   1.559 ms/op
                 existUser·p0.90:   1.876 ms/op
                 existUser·p0.95:   2.025 ms/op
                 existUser·p0.99:   3.066 ms/op
                 existUser·p0.999:  11.921 ms/op
                 existUser·p0.9999: 13.062 ms/op
                 existUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19424
  mean =      1.647 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 478 
    [ 1.250,  2.500) = 18589 
    [ 2.500,  3.750) = 253 
    [ 3.750,  5.000) = 0 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.414 ms/op
     p(50.0000) =      1.559 ms/op
     p(90.0000) =      1.876 ms/op
     p(95.0000) =      2.025 ms/op
     p(99.0000) =      3.066 ms/op
     p(99.9000) =     11.921 ms/op
     p(99.9900) =     13.062 ms/op
     p(99.9990) =     13.124 ms/op
     p(99.9999) =     13.124 ms/op
    p(100.0000) =     13.124 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.289 ±(99.9%) 0.090 ms/op
Iteration   1: 2.228 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.467 ms/op
                 getUser·p0.50:   2.150 ms/op
                 getUser·p0.90:   2.687 ms/op
                 getUser·p0.95:   2.884 ms/op
                 getUser·p0.99:   4.991 ms/op
                 getUser·p0.999:  12.347 ms/op
                 getUser·p0.9999: 13.287 ms/op
                 getUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14369
  mean =      2.228 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 162 
    [ 1.250,  2.500) = 11155 
    [ 2.500,  3.750) = 2852 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      4.991 ms/op
     p(99.9000) =     12.347 ms/op
     p(99.9900) =     13.287 ms/op
     p(99.9990) =     13.287 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.250 ±(99.9%) 0.126 ms/op
Iteration   1: 3.497 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   3.420 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   8.710 ms/op
                 listUser·p0.999:  16.328 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9208
  mean =      3.497 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 702 
    [ 2.500,  3.750) = 5886 
    [ 3.750,  5.000) = 2270 
    [ 5.000,  6.250) = 193 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      8.710 ms/op
     p(99.9000) =     16.328 ms/op
     p(99.9900) =     17.138 ms/op
     p(99.9990) =     17.138 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.768          ops/ms
ClientSimple.existUser                       thrpt         12.271          ops/ms
ClientSimple.getUser                         thrpt         14.924          ops/ms
ClientSimple.listUser                        thrpt          9.133          ops/ms
ClientSimple.createUser                       avgt          2.251           ms/op
ClientSimple.existUser                        avgt          1.913           ms/op
ClientSimple.getUser                          avgt          2.093           ms/op
ClientSimple.listUser                         avgt          3.159           ms/op
ClientSimple.createUser                     sample  14606   2.186 ± 0.054   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.541           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.911           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.572           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.802           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.093           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.631           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.769           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.769           ms/op
ClientSimple.existUser                      sample  19424   1.647 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.414           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.559           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.876           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.025           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.066           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.921           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.062           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.124           ms/op
ClientSimple.getUser                        sample  14369   2.228 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.467           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.150           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.884           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.991           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.347           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.287           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.287           ms/op
ClientSimple.listUser                       sample   9208   3.497 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.912           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.420           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.710           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.328           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.138           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.138           ms/op

Benchmark result is saved to 1717654315546.json
