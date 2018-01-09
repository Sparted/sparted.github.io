---
layout    : post
title     : "Spectre & Meltdown"
date      : 2018-01-08 11:57:27 +0100
categories: security bulletins
---

## Information Leak via speculative execution side channel attacks (CVE-2017-5715, CVE-2017-5753, CVE-2017-5754 aka Spectre and Meltdown)

### Regarding:

- [Spectre - CVE-2017-5715](https://people.canonical.com/~ubuntu-security/cve/2017/CVE-2017-5715.html)
- [Spectre - CVE-2017-5753](https://people.canonical.com/~ubuntu-security/cve/2017/CVE-2017-5753.html)
- [Meltdown - CVE-2017-5754](https://people.canonical.com/~ubuntu-security/cve/2017/CVE-2017-5754.html)

### Note

SPARTED's server machines runs on AWS EC2. We are waiting for Canonical to publish their new update. As per their [latest security bulletin](https://wiki.ubuntu.com/SecurityTeam/KnowledgeBase/SpectreAndMeltdown):

> The original coordinated disclosure date was planned for January 9 and we have been driving toward that date to release fixes. Due to the early disclosure, we are trying to accelerate the release, but we don't yet have an earlier ETA when the updates will be released. We will release Ubuntu Security Notices when the updates are available.

To mitigate any delay, SPARTED will be able to guarantee that the patch will be installed at most by the end of the 12th of January.

Charles-Antoine de Salaberry
Information Security Officer
