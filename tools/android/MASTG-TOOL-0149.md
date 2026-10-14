---
title: LSPosed
platform: android
source: https://github.com/JingMatrix/Vector
---

LSPosed is a Zygisk module that allows modifying the system or application aspect and behavior at runtime, without modifying any Android application package (APK) or re-flashing. Technically, it is an extended version of Zygote that exports APIs for running Java code when a new process is started. Running Java code in the context of the newly instantiated app makes it possible to resolve, hook, and override Java methods belonging to the app.

!!! note
    The upstream project has been renamed. The JingMatrix fork of LSPosed is now called **Vector Framework** and lives at <https://github.com/JingMatrix/Vector>. It is still widely referred to as LSPosed and existing LSPosed modules keep working. The original `LSPosed/LSPosed` repository documents support for Android 8.1 to 14 only, while Vector supports Android 8.1 through Android 17 Beta and requires Magisk or KernelSU with Zygisk enabled.
