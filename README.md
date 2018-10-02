# Spring Boot Hazelcast Example

Run this project by run this command :

`mvn clean spring-boot:run`

```
  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::       (v1.5.16.RELEASE)

INFO  - Starting Application on Hendis-MacBook-Pro.local with PID 19590 (/Users/hendisantika/Documents/IdeaProjects/hazelcast/target/classes started by hendisantika in /Users/hendisantika/Documents/IdeaProjects/hazelcast)
INFO  - No active profile set, falling back to default profiles: default
INFO  - Refreshing org.springframework.context.annotation.AnnotationConfigApplicationContext@69faf26c: startup date [Wed Oct 03 06:19:49 WIB 2018]; root of context hierarchy
INFO  - [LOCAL] [dev] [3.7.8] Prefer IPv4 stack is true.
INFO  - [LOCAL] [dev] [3.7.8] Picked [192.168.100.3]:5701, using socket ServerSocket[addr=/0:0:0:0:0:0:0:0,localport=5701], bind any local is true
INFO  - [192.168.100.3]:5701 [dev] [3.7.8] Hazelcast 3.7.8 (20170525 - 4e820fa) starting at [192.168.100.3]:5701
INFO  - [192.168.100.3]:5701 [dev] [3.7.8] Copyright (c) 2008-2016, Hazelcast, Inc. All Rights Reserved.
INFO  - [192.168.100.3]:5701 [dev] [3.7.8] Configured Hazelcast Serialization version : 1
INFO  - [192.168.100.3]:5701 [dev] [3.7.8] Backpressure is disabled
INFO  - [192.168.100.3]:5701 [dev] [3.7.8] Creating MulticastJoiner
INFO  - [192.168.100.3]:5701 [dev] [3.7.8] Starting 8 partition threads
INFO  - [192.168.100.3]:5701 [dev] [3.7.8] Starting 5 generic threads (1 dedicated for priority tasks)
INFO  - [192.168.100.3]:5701 [dev] [3.7.8] [192.168.100.3]:5701 is STARTING
INFO  - [192.168.100.3]:5701 [dev] [3.7.8] TcpIpConnectionManager configured with Non Blocking IO-threading model: 3 input threads and 3 output threads
INFO  - [192.168.100.3]:5701 [dev] [3.7.8]


Members [1] {
	Member [192.168.100.3]:5701 - 7e6d4c47-d22f-4a03-92fe-ae1eee7107a9 this
}

INFO  - [192.168.100.3]:5701 [dev] [3.7.8] [192.168.100.3]:5701 is STARTED
INFO  - Registering beans for JMX exposure on startup
INFO  - Spring Boot Hazelcast Caching Example Configuration
INFO  - Using cache manager: com.hazelcast.spring.cache.HazelcastCacheManager
INFO  - [192.168.100.3]:5701 [dev] [3.7.8] Initializing cluster partition table arrangement...
INFO  - Calling: MusicService.play("trombone");
INFO  - Executing: MusicService.play("trombone");
INFO  - Calling: MusicService.play("guitar");
INFO  - Executing: MusicService.play("guitar");
INFO  - Calling: MusicService.play("trombone");
INFO  - Calling: MusicService.play("bass");
INFO  - Executing: MusicService.play("bass");
INFO  - Calling: MusicService.play("trombone");
INFO  - Started Application in 4.358 seconds (JVM running for 7.862)
```