---
title: Pipelines Overview
menu:
  docs:
    parent: Monitoring Pipelines
    weight: 1
---

{{% tip %}}
Note all information in the dashboard is updated in realtime.
{{% /tip %}}


Once Jobs have been submitted Tower enables you to easily monitor progress and results. **The left side bar** contains all previous jobs executions, each new or resumed job will be given a random name starting with an adjective and followed by a noun e.g(grave_williams).

{{% pretty_screenshot img="/uploads/2020/10/monitoring_overview.png" %}}

In the left bar:

  - jobs in **Blue** are running Jobs
  - jobs in **Green** are successfully executed Jobs
  - jobs in **yellow** are successfully executed Jobs where some process partially failed
  - jobs in **red** are jobs where where at least one process fully failed
  - jobs in **gray** are jobs that where forced to stop during execution

  Selecting a job on the left panel will display the job execution details.