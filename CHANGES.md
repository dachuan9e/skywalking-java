Changes by Version
==================
Release Notes.

8.9.0
------------------

* Support `Transaction` and fix duplicated methods enhancements for `jedis-2.x` plugin.
* Add ConsumerWrapper/FunctionWrapper to support CompletableFuture.x.thenAcceptAsync/thenApplyAsync.
* Build CLI from Docker instead of source codes, add alpine based Docker image.
* Support set instance properties in json format.
* Upgrade grpc-java to 1.42.1 and protoc to 3.17.3 to allow using native Mac osx-aarch_64 artifacts.
* Add doc about system environment variables to configurations.md
* Avoid `ProfileTaskChannelService.addProfilingSnapshot` throw IllegalStateException(Queue full) 
* Increase `ProfileTaskChannelService.snapshotQueue` default size from 50 to 4500
* Support 2.8 and 2.9 of pulsar client.
* Add dubbo 3.x plugin.
* Fix TracePathMatcher should match pattern "**" with paths end by "/"
* Add support `returnedObj` expression for apm-customize-enhance-plugin
* Fix the bug that httpasyncclient-4.x-plugin  puts the dirty tracing context in the connection context
* Compatible with the versions after dubbo-2.7.14
* Follow protocol grammar fix `GCPhrase -> GCPhase`.
* Support ZGC GC time and count metric collect. (Require 9.0.0 OAP)
* Support configuration for collecting redis parameters for jedis-2.x and redisson-3.x plugin.

#### Documentation

* Add a FAQ, `Why is `-Djava.ext.dirs` not supported?`.

All issues and pull requests are [here](https://github.com/apache/skywalking/milestone/99?closed=1)

------------------
Find change logs of all versions [here](changes).
