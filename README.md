README
======

[License](./LICENSE)

<details>
  <summary>
    Some Details
  </summary>
  Here is some hidden text

  ```
  A code block
  ```
</details>

```mermaid
gantt

title ROS 2 Release Process
axisFormat %b %y

section My section
Completed    : done,      des1, 2021-01-06, 3d
Active       : active,    des2, after des1, 90d
Parallel 1   :            des3, after des1, 100d
Parallel 2   : crit,      des4, after des1, 52w
Parallel 3   :            des5, after des3, 1d
Parallel 4   :            des6, after des4, 1d
Test         :            t1, 2021-01-20, 3d
Milestone    : milestone, ms, 2022-01-20, 4d

section Section 2
New tasks : done, 2022-02-1, 2w
This month : active, 2022-06-01, 6w
```