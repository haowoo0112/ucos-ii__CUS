# ucos-ii_CUS

## What is CUS (Constant Utilization Servers)?

- Based on EDF.

- When an aperiodic job with execution time e arrives at time t to an empty aperiodic job queue,
    - if t<d, do nothing;
    - if t>=d, d = t+e/u

## Result

- Periodic task file

![](https://i.imgur.com/gSbCihL.png)

format- periodic task
|Task ID|Arrive Time|Execution Time|Task Periodic
|-|-|-|-
|##|##|##|##

format- aperiodic task
|Server ID|Server Size
|-|-
|##|##

- Aperiodic task file

![](https://i.imgur.com/f9vkHN4.png)

format
|Jobs No.|Arrive Time|Execution Time|Absolute Deadline
|-|-|-|-
|##|##|##|##

- Scheduling diagram

![](https://i.imgur.com/G16KS4f.png)

- Final result

![](https://i.imgur.com/fnWIGlQ.png)