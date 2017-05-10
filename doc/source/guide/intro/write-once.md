---
title: Write once, Run Everywhere
type: guide
order: 4.4
version: 2.1
---

# Write Once, Run Everywhere

Weex is a "Write Once, Run Everywhere" solution.

* Weex leverages web dev experience, including syntax and project structure.
* Each component & module in Weex is discussed by iOS, Android, and web developers together to ensure it's common enough to satisfy every platform.
* The same Weex code works for all platforms.

## Consider this

Today for most mobile apps, one app must solve the same problem over again, for each platform. Weex hopes to supply a lightweight way to describe business logic which works well on all mobile platforms.

For the differences between mobile platforms, we follow these guidlines to fill the gap:
    1. Design the same APIs for all platforms to ensure different platforms the same business logic description.
    2. Implement the APIs with any differences in styles or behaviors to ensure the implementation and user experience matches the respective platform.
Still, different platforms have different features. We also have some environment variables to help developers in specific situations.

We trust web standards to be the best for all features on all platforms.
