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
# Warmup Iteration   1: 1.613 ops/ms
Iteration   1: 6.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.524 ops/ms


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
# Warmup Iteration   1: 5.822 ops/ms
Iteration   1: 11.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.520 ops/ms


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
# Warmup Iteration   1: 5.874 ops/ms
Iteration   1: 13.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.762 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.849 ops/ms
Iteration   1: 8.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.232 ops/ms


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
# Warmup Iteration   1: 4.132 ±(99.9%) 0.092 ms/op
Iteration   1: 2.210 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.210 ms/op


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
# Warmup Iteration   1: 3.157 ±(99.9%) 0.052 ms/op
Iteration   1: 1.777 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.777 ms/op


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
# Warmup Iteration   1: 3.405 ±(99.9%) 0.056 ms/op
Iteration   1: 1.993 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.993 ms/op


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
# Warmup Iteration   1: 4.856 ±(99.9%) 0.117 ms/op
Iteration   1: 3.265 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.265 ms/op


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
# Warmup Iteration   1: 3.663 ±(99.9%) 0.094 ms/op
Iteration   1: 2.352 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   2.236 ms/op
                 createUser·p0.90:   2.785 ms/op
                 createUser·p0.95:   3.052 ms/op
                 createUser·p0.99:   5.736 ms/op
                 createUser·p0.999:  25.952 ms/op
                 createUser·p0.9999: 26.888 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13587
  mean =      2.352 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10343 
    [ 2.500,  5.000) = 3077 
    [ 5.000,  7.500) = 39 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.236 ms/op
     p(90.0000) =      2.785 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      5.736 ms/op
     p(99.9000) =     25.952 ms/op
     p(99.9900) =     26.888 ms/op
     p(99.9990) =     26.935 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 3.308 ±(99.9%) 0.084 ms/op
Iteration   1: 1.904 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   1.792 ms/op
                 existUser·p0.90:   2.335 ms/op
                 existUser·p0.95:   2.568 ms/op
                 existUser·p0.99:   3.454 ms/op
                 existUser·p0.999:  14.467 ms/op
                 existUser·p0.9999: 15.046 ms/op
                 existUser·p1.00:   15.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16768
  mean =      1.904 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 272 
    [ 1.250,  2.500) = 15508 
    [ 2.500,  3.750) = 844 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      1.792 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.454 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     15.046 ms/op
     p(99.9990) =     15.057 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 3.146 ±(99.9%) 0.076 ms/op
Iteration   1: 2.137 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   1.937 ms/op
                 getUser·p0.90:   2.728 ms/op
                 getUser·p0.95:   2.929 ms/op
                 getUser·p0.99:   4.874 ms/op
                 getUser·p0.999:  23.891 ms/op
                 getUser·p0.9999: 24.840 ms/op
                 getUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14952
  mean =      2.137 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12652 
    [ 2.500,  5.000) = 2161 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      4.874 ms/op
     p(99.9000) =     23.891 ms/op
     p(99.9900) =     24.840 ms/op
     p(99.9990) =     25.035 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 4.399 ±(99.9%) 0.133 ms/op
Iteration   1: 3.700 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.022 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.078 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  8.552 ms/op
                 listUser·p0.9999: 9.830 ms/op
                 listUser·p1.00:   9.830 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8641
  mean =      3.700 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 11 
    [ 1.500,  2.000) = 100 
    [ 2.000,  2.500) = 532 
    [ 2.500,  3.000) = 826 
    [ 3.000,  3.500) = 2087 
    [ 3.500,  4.000) = 2721 
    [ 4.000,  4.500) = 1119 
    [ 4.500,  5.000) = 734 
    [ 5.000,  5.500) = 255 
    [ 5.500,  6.000) = 68 
    [ 6.000,  6.500) = 53 
    [ 6.500,  7.000) = 95 
    [ 7.000,  7.500) = 7 
    [ 7.500,  8.000) = 0 
    [ 8.000,  8.500) = 19 
    [ 8.500,  9.000) = 13 
    [ 9.000,  9.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.078 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =      9.830 ms/op
     p(99.9990) =      9.830 ms/op
     p(99.9999) =      9.830 ms/op
    p(100.0000) =      9.830 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.524          ops/ms
ClientSimple.existUser                       thrpt         11.520          ops/ms
ClientSimple.getUser                         thrpt         13.762          ops/ms
ClientSimple.listUser                        thrpt          8.232          ops/ms
ClientSimple.createUser                       avgt          2.210           ms/op
ClientSimple.existUser                        avgt          1.777           ms/op
ClientSimple.getUser                          avgt          1.993           ms/op
ClientSimple.listUser                         avgt          3.265           ms/op
ClientSimple.createUser                     sample  13587   2.352 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.597           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.236           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.785           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.052           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.736           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.952           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.888           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.935           ms/op
ClientSimple.existUser                      sample  16768   1.904 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.737           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.792           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.454           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.467           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.046           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.057           ms/op
ClientSimple.getUser                        sample  14952   2.137 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.643           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.937           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.929           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.874           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.891           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.840           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.035           ms/op
ClientSimple.listUser                       sample   8641   3.700 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.022           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.654           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.784           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.078           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.668           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.552           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.830           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.830           ms/op

Benchmark result is saved to 1717222244181.json
