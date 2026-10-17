# streamproof

A correctness test harness for Apache Flink jobs, under development. It will run a job against seeded, adversarial input with injected faults (task kills, network faults, savepoint/rescale), then compare the output to an executable reference model that acts as the oracle.

**Status:** early design. No code or release yet. The plan is to start with JUnit 5 integration on Flink's MiniCluster.

Companion project: [stream-patterns](https://github.com/abolfazlmadanii/stream-patterns). Each pattern's reference model doubles as a streamproof oracle.

Licensed under the [Apache License 2.0](LICENSE).
