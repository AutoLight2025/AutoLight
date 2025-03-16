**Task Description**

This task emulates the active failure handling in data center interconnection (DCI).

The quality of transmission (QoT) of optical links in the DCI is continuously monitored. Once it falls below the alarm threshold, the system analyzes the fault type and reconfigures network-layer routing. If the rerouting outcomes are unacceptable, the system initiates training mode degradation until the failure is resolved.

**Checkpoints Defination**

Checkpoint-1: Failure classified.<br>
Checkpoint-2: Network re-routing with potential blink completed.<br>
Checkpoint-3: Transmission mode downgraded.<br>

**Scoring Criteria for Task Completion Rates**

| Event | Completion rate |
| :----: | :----: |
| QoT decrease identified | 25% |
| Failure classified | 50% |
| Network re-routing with potential blink completed| 75% |
| Transmission mode downgraded | 100% |