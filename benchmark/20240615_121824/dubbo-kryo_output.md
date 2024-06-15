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
# Warmup Iteration   1: 1.721 ops/ms
Iteration   1: 5.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.356 ops/ms


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
# Warmup Iteration   1: 6.182 ops/ms
Iteration   1: 13.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.096 ops/ms


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
# Warmup Iteration   1: 6.451 ops/ms
Iteration   1: 13.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.632 ops/ms


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
# Warmup Iteration   1: 4.740 ops/ms
Iteration   1: 9.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.091 ops/ms


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.075 ms/op
Iteration   1: 2.443 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.443 ms/op


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
# Warmup Iteration   1: 3.576 ±(99.9%) 0.059 ms/op
Iteration   1: 1.870 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.870 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.067 ms/op
Iteration   1: 2.155 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.155 ms/op


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.075 ms/op
Iteration   1: 3.453 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.453 ms/op


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
# Warmup Iteration   1: 3.598 ±(99.9%) 0.085 ms/op
Iteration   1: 2.514 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   2.400 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  19.726 ms/op
                 createUser·p0.9999: 19.816 ms/op
                 createUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12699
  mean =      2.514 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 7121 
    [ 2.500,  3.750) = 5033 
    [ 3.750,  5.000) = 383 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.400 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.874 ms/op
     p(99.9000) =     19.726 ms/op
     p(99.9900) =     19.816 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 3.107 ±(99.9%) 0.082 ms/op
Iteration   1: 1.963 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   1.898 ms/op
                 existUser·p0.90:   2.351 ms/op
                 existUser·p0.95:   2.515 ms/op
                 existUser·p0.99:   3.854 ms/op
                 existUser·p0.999:  12.501 ms/op
                 existUser·p0.9999: 13.551 ms/op
                 existUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16402
  mean =      1.963 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 188 
    [ 1.250,  2.500) = 15338 
    [ 2.500,  3.750) = 687 
    [ 3.750,  5.000) = 151 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      1.898 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.515 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =     12.501 ms/op
     p(99.9900) =     13.551 ms/op
     p(99.9990) =     13.844 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


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
# Warmup Iteration   1: 3.251 ±(99.9%) 0.073 ms/op
Iteration   1: 1.950 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.559 ms/op
                 getUser·p0.50:   1.720 ms/op
                 getUser·p0.90:   2.572 ms/op
                 getUser·p0.95:   2.772 ms/op
                 getUser·p0.99:   3.379 ms/op
                 getUser·p0.999:  22.315 ms/op
                 getUser·p0.9999: 23.451 ms/op
                 getUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16442
  mean =      1.950 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14465 
    [ 2.500,  5.000) = 1911 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      1.720 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.772 ms/op
     p(99.0000) =      3.379 ms/op
     p(99.9000) =     22.315 ms/op
     p(99.9900) =     23.451 ms/op
     p(99.9990) =     24.084 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.145 ms/op
Iteration   1: 3.226 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   0.683 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.413 ms/op
                 listUser·p0.99:   8.099 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9905
  mean =      3.226 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 561 
    [ 2.500,  3.750) = 7842 
    [ 3.750,  5.000) = 1182 
    [ 5.000,  6.250) = 160 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.413 ms/op
     p(99.0000) =      8.099 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.356          ops/ms
ClientSimple.existUser                       thrpt         13.096          ops/ms
ClientSimple.getUser                         thrpt         13.632          ops/ms
ClientSimple.listUser                        thrpt          9.091          ops/ms
ClientSimple.createUser                       avgt          2.443           ms/op
ClientSimple.existUser                        avgt          1.870           ms/op
ClientSimple.getUser                          avgt          2.155           ms/op
ClientSimple.listUser                         avgt          3.453           ms/op
ClientSimple.createUser                     sample  12699   2.514 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.834           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.400           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.420           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.650           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.874           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.726           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.816           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.825           ms/op
ClientSimple.existUser                      sample  16402   1.963 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.835           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.898           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.351           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.854           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.501           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.551           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.844           ms/op
ClientSimple.getUser                        sample  16442   1.950 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.559           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.720           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.772           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.379           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.315           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.451           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.084           ms/op
ClientSimple.listUser                       sample   9905   3.226 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.683           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.912           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.059           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.413           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.099           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.236           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.400           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.400           ms/op

Benchmark result is saved to 1718453665592.json
