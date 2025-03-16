**Task Description**

This task emulates the wavelength establishment in backbone link.

When computational resources in a data center interconnection (DCI) region become insufficient, connections must be established with another DCI. The system integrates backbone link information from both domains and performs quality of transmission (QoT) estimation. If transmission metrics are satisfied, new signals are launched and actual performance is verified. 

**Checkpoints Defination**

Checkpoint-1: New connection request received by Backbone.<br>
Checkpoint-2: QoT predicted.<br>
Checkpoint-3: QoT of new wavelength checked by Agent in Domain2.<br>

**Scoring Criteria for Task Completion Rates**

| Event | Completion rate |
| :----: | :----: |
| New connection request received by Backbone | 20% |
| Configuration of two backbone domains gathered | 40% |
| QoT predicted | 60% |
| New wavelength added from Domain1| 80% |
| QoT of new wavelength checked by Agent in Domain2| 100% |