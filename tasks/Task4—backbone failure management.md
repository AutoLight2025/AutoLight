**Task Description**

This task emulates active failure handling in backbone links.<br>
Backbone Domain2 continuously monitors signal quality of transmission (QoT) at the receiver, and when measurements fall below the warning threshold, the system initiates failure localization procedures. If Domain2 determines that no failure exists within its region, it notifies Domain1 to perform failure localization, thereby enabling cross-domain troubleshooting.

**Checkpoints Defination**

Checkpoint-1: Domain 2 self-diagnose completed.<br>
Checkpoint-2: Domain 1 failure handling request received.<br>
Checkpoint-3: Failure successfully localized.<br>

**Scoring Criteria for Task Completion Rates**

| Event | Completion rate |
| :----: | :----: |
| QoT decrease identified | 25% |
| Domain 2 self-diagnose completed | 50% |
| Domain 1 failure handling request received | 75% |
| Failure successfully localized | 100% |
