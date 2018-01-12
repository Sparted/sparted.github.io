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

#### Update:

- 2018 Jan 11: The current update [might fail](http://www.zdnet.com/article/linux-vs-meltdown-ubuntu-gets-second-update-after-first-one-fails-to-boot/). we decided to move the server updates to the 17th of January.


### Timeline

- 2018 Jan 03: [issue becomes public](https://googleprojectzero.blogspot.com/2018/01/reading-privileged-memory-with-side.html) a few days before the CRD
- 2018 Jan 09: Ubuntu kernel updates are made available in USN 3522-1 (Ubuntu 16.04 LTS), USN 3523-1 (Ubuntu 17.10), USN 3522-2 (Ubuntu 14.04 LTS (HWE)), and USN-3524-1 (Ubuntu 14.04 LTS)
- 2018 Jan 11: [some 16.04 LTS Xenial users couldn't boot their machines once the update was installed](http://www.zdnet.com/article/linux-vs-meltdown-ubuntu-gets-second-update-after-first-one-fails-to-boot/)
- 2018 Jan 11: The update has been moved to 17th of January


Charles-Antoine de Salaberry
Information Security Officer
