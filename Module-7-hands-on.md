---
layout: default
title: Hands-on Activity
description: In this hands-on activity, we describe the process of mining a GitHub repository for SaltStack scripts and example of security weakness in SaltStack scripts. 
---

## GitHub Repository Mining

In order to identify the presence of security weaknesses in SaltStack scripts, the students need to mine repository from GitHub as most IT organizations hosts their Open Source Software (OSS) projects in GitHub. The GitHub repositories need to be curated with filteration criteria. The following figure shows the GitHub repository curation process. GitHub API allows user to mine repositories based on criterias.

![](/assets/GH.png)

In the following code snippet, the highlighted red box denotes a security weakness,presence hard-coded secrets/keys in SaltStack scripts mined from GitHub.

![](/assets/key.png)



[**Go M7 Pre-Lab**](./Module-7-Prelab.html)

[**Go M7 Post-Lab**](./Module-7-Postlab.html)

[**GO M7 Home**](./Module-7.html)

[**Return Home**](./)
