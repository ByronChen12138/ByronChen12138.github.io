---
title: "[ICSME 2024] Demystifying Device-Specific Compatibility Issues in Android Apps"
collection: publications
category: conferences
permalink: /publication/2024-10-6-Compatibility-Issues-in-Android-Apps-number-2
excerpt: ''
date: 2024-10-6
venue: '2024 IEEE International Conference on Software Maintenance and Evolution (ICSME)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10795002'
authors: [Junfeng Chen, Kevin Li, Yifei Chen, Lili Wei, Yepang Liu]
---

Authors: Junfeng Chen, Kevin Li, **Yifei Chen**, Lili Wei, and Yepang Liu

The Android ecosystem is profoundly fragmented due to the frequent updates of the Android system and the prevalent customizations by mobile device manufacturers. Previous research primarily focused on identifying and repairing evolution-induced API compatibility issues, with limited consideration of device-specific compatibillty issues (DSC issues). To fill this gap, we conduct an empirical study of 197 DSC issues collected from 94 open-source repositories on GitHub. We introduce a new perspective for comprehending these issues by categorizing them into two principal groups, Functionality Breaks, and OEM Features, based on their manifestations and root causes. The functionality break issues disrupt standard Android system behaviors, lead to crashes or unexpected behaviors on specific devices, and require developers to implement workarounds to preserve the original functionality. The OEM feature issues involve the introduction of device-specific functionalities or features beyond the basic Android system. The different nature of functionality break issues and OEM feature issues lead to unique challenges in addressing them. For example, our examination of issue fixing practices highlights significant differences in addressing the two categories of DSC issues. Common solutions for functionality break issues involve calling additional APIs, substituting problematic ones, or using specific parameters, while resolving OEM feature issues often relies on Android inter-component communication methods and reflection, with additional unconventional strategies. Such observations highlight the distinctive challenges in addressing DSC issues in Android apps and will facilitate the future development of testing and analysis tools targeting these issues. Our study demonstrates that Functionality break and OEM feature issues have different characteristics, and future research may need to investigate them separately.

[Paper](https://ieeexplore.ieee.org/abstract/document/10795002)