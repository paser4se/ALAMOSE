---
layout: default
title: Post-Lab
description: In the Post-Lab activity, we demonstrated an instance of security weakness in a Saltstack script, and showed the steps on how to identify it.
---

## Security Weakness in SaltStack scripts
In the following SaltStack code snippet we have highlighted an example of security weakness, suspicious comment. Suspicious comments often reveal edge cases, missing functionality of the source code that can make source code vulnerable to attack.


![](/assets/comment.png)

## Steps of identifying the suspicious comment in SaltStack scripts
According to CWE database, use of specific key-words such as `hack` , `fixme`, `todo`, `bug`, `later`, `bug` in comments can reveal missing security functionality, presence of bugs (CWE-546). In the following figure, we demonstrated steps for automatically identifying suspicious comment in SaltStack scripts.

![](/assets/steps.png)

[**Go M7 Home**](./Module-7.html)

[Go M7 Pre-Lab](./Module-7-Prelab.html)

[Go M7 Hands-on](./Module-7-hands-on.html)

[**Return Home**](./)
