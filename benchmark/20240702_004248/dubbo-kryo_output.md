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
# Warmup Iteration   1: 1.854 ops/ms
Iteration   1: 7.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.425 ops/ms


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
# Warmup Iteration   1: 6.319 ops/ms
Iteration   1: 10.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.697 ops/ms


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
# Warmup Iteration   1: 6.780 ops/ms
Iteration   1: 14.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.001 ops/ms


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
# Warmup Iteration   1: 4.860 ops/ms
Iteration   1: 7.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.985 ops/ms


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
# Warmup Iteration   1: 4.295 ±(99.9%) 0.077 ms/op
Iteration   1: 2.445 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.445 ms/op


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
# Warmup Iteration   1: 3.451 ±(99.9%) 0.057 ms/op
Iteration   1: 1.764 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.764 ms/op


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
# Warmup Iteration   1: 3.326 ±(99.9%) 0.049 ms/op
Iteration   1: 2.171 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.171 ms/op


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
# Warmup Iteration   1: 4.170 ±(99.9%) 0.086 ms/op
Iteration   1: 3.922 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.922 ms/op


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
# Warmup Iteration   1: 3.168 ±(99.9%) 0.079 ms/op
Iteration   1: 2.191 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   2.013 ms/op
                 createUser·p0.90:   2.634 ms/op
                 createUser·p0.95:   2.961 ms/op
                 createUser·p0.99:   6.023 ms/op
                 createUser·p0.999:  18.325 ms/op
                 createUser·p0.9999: 19.236 ms/op
                 createUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14882
  mean =      2.191 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 163 
    [ 1.250,  2.500) = 12725 
    [ 2.500,  3.750) = 1517 
    [ 3.750,  5.000) = 172 
    [ 5.000,  6.250) = 171 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      2.013 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      6.023 ms/op
     p(99.9000) =     18.325 ms/op
     p(99.9900) =     19.236 ms/op
     p(99.9990) =     19.300 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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
# Warmup Iteration   1: 3.060 ±(99.9%) 0.066 ms/op
Iteration   1: 2.098 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   2.075 ms/op
                 existUser·p0.90:   2.597 ms/op
                 existUser·p0.95:   2.781 ms/op
                 existUser·p0.99:   3.819 ms/op
                 existUser·p0.999:  12.829 ms/op
                 existUser·p0.9999: 12.984 ms/op
                 existUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15220
  mean =      2.098 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 304 
    [ 1.250,  2.500) = 12619 
    [ 2.500,  3.750) = 2141 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      3.819 ms/op
     p(99.9000) =     12.829 ms/op
     p(99.9900) =     12.984 ms/op
     p(99.9990) =     12.993 ms/op
     p(99.9999) =     12.993 ms/op
    p(100.0000) =     12.993 ms/op


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
# Warmup Iteration   1: 3.110 ±(99.9%) 0.077 ms/op
Iteration   1: 2.028 ±(99.9%) 0.062 ms/op
                 getUser·p0.00:   0.488 ms/op
                 getUser·p0.50:   1.792 ms/op
                 getUser·p0.90:   2.359 ms/op
                 getUser·p0.95:   2.597 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  49.611 ms/op
                 getUser·p0.9999: 50.807 ms/op
                 getUser·p1.00:   50.921 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15829
  mean =      2.028 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15647 
    [ 5.000, 10.000) = 86 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 21 
    [50.000, 55.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      1.792 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     49.611 ms/op
     p(99.9900) =     50.807 ms/op
     p(99.9990) =     50.921 ms/op
     p(99.9999) =     50.921 ms/op
    p(100.0000) =     50.921 ms/op


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
# Warmup Iteration   1: 4.932 ±(99.9%) 0.357 ms/op
Iteration   1: 3.543 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   0.822 ms/op
                 listUser·p0.50:   3.469 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  25.460 ms/op
                 listUser·p0.9999: 25.657 ms/op
                 listUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9023
  mean =      3.543 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 731 
    [ 2.500,  5.000) = 8050 
    [ 5.000,  7.500) = 176 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     25.460 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.425          ops/ms
ClientSimple.existUser                       thrpt         10.697          ops/ms
ClientSimple.getUser                         thrpt         14.001          ops/ms
ClientSimple.listUser                        thrpt          7.985          ops/ms
ClientSimple.createUser                       avgt          2.445           ms/op
ClientSimple.existUser                        avgt          1.764           ms/op
ClientSimple.getUser                          avgt          2.171           ms/op
ClientSimple.listUser                         avgt          3.922           ms/op
ClientSimple.createUser                     sample  14882   2.191 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.616           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.013           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.634           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.961           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.023           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.325           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.236           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.300           ms/op
ClientSimple.existUser                      sample  15220   2.098 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.750           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.075           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.781           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.819           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.829           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.984           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.993           ms/op
ClientSimple.getUser                        sample  15829   2.028 ± 0.062   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.488           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.792           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.359           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.597           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.521           ms/op
ClientSimple.getUser:getUser·p0.999         sample         49.611           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         50.807           ms/op
ClientSimple.getUser:getUser·p1.00          sample         50.921           ms/op
ClientSimple.listUser                       sample   9023   3.543 ± 0.055   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.822           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.469           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.153           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.127           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.460           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.657           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.657           ms/op

Benchmark result is saved to 1719880692125.json
