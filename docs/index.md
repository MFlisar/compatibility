---
icon: material/information-variant
title: Compatibility
---

ALL my main libraries have been updated to support following KMP targets:

* `jvm`
* `android`
* `ios`
* `macos`
* `wasm`

## Binary Compatibility

I do try to keep versions binary compatible as long as possible now - non major versions will be binary compatible!

## Libraries

Here are the minimum versions that do work with each other without problems.

**UTILITIES**

| Library  | Minimum Version | Latest Version | Info |
| - | - | - | - |
| [CacheFileProvider](https://mflisar.github.io/CacheFileProvider/) | `1.0.0` | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.cachefileprovider/library) | |
| [FeedbackManager](https://mflisar.github.io/FeedbackManager/) | `3.0.0` | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.feedbackmanager/library) | - depends on `CacheFileProvider` |

**Libraries**

| Library  | Minimum Version | Latest Version | Info |
| - | - | - | - |
| [KotBilling](https://mflisar.github.io/KotBilling/) | `2.0.0` | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.kotbilling/library) | |
| [KotPreferences](https://mflisar.github.io/KotPreferences/) | `2.0.0` | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.kotpreferences/core) | |
| [Lumberjack](https://mflisar.github.io/Lumberjack/) | `9.0.0`| ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.lumberjack/core) | - `extension-feedback` artifact depends on `FeedbackManager` |

**Compose**

| Library  | Minimum Version  | Latest Version | Info |
| - | - | - | - |
| [ComposeColors](https://mflisar.github.io/ComposeColors/) | `1.0.0` | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.composecolors/core) | |
| [ComposeDebugDrawer](https://mflisar.github.io/ComposeDebugDrawer/) | `2.0.0` | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.composedebugdrawer/core) | - `plugin-kotpreferences` artifact depends on `KotPreferences`<br/>- `plugin-lumberjack` artifact depends on `Lumberjack` |
| [ComposeChangelog](https://mflisar.github.io/ComposeChangelog/) | `3.0.0` | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.composechangelog/core) | - `statesaver-kotpreferences` artifact depends on `KotPreferences` |
| [ComposeThemer](https://mflisar.github.io/ComposeThemer/) | `1.0.0` | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.composethemer/core) | |
| [ComposeDialogs](https://mflisar.github.io/ComposeDialogs/) | `3.0.0` | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.composedialogs/core) | - `dialog-billing` artifact depends on `KotBilling` |
| [ComposePreferences](https://mflisar.github.io/ComposePreferences/) | `2.0.0` | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.composepreferences/core) | - depends on `ComposeDialogs`<br/>- `kotpreferences` artifact depends on `KotPreferences` |

!!! note

	Above mentioned versions are the **minimum versions** that are compatible with each other. From there on I try to make new versions **binary compatible** - so any newer versions will work with each other without problems.

# Notes

## Experimental

**Why do some libraries use experimental functions?**

Mostly I do use the compose `BackHandler` and the the `kotlinx.datetime.Clock` class. Both are currently still marked as experimental. I need both to support all the platforms so I do use those...
