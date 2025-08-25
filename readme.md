## COMPATIBILITY

ALL my main libraries have been updated to support following KMP targets:

* `jvm`
* `android`
* `ios`
* `macos`
* `wasm`

### Binary Compatibility

I do try to keep versions binary compatible as long as possible now - non major versions will be binary compatible!

### Libraries

Here are the minimum versions that do work with each other without problems.

**UTILITIES**

| Library  | Version | Link | Latest Version |
| - | - | - | - |
| CacheFileProvider | `1.0.0`  | https://mflisar.github.io/CacheFileProvider/ | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.cachefileprovider/library?color=blue) |
| FeedbackManager | `3.0.0`  | https://mflisar.github.io/FeedbackManager/ | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.feedbackmanager/library?color=blue) |

**Libraries**

| Library  | Minimum Version | Link | Latest Version |
| - | - | - | - |
| KotBilling | `2.0.0`  | https://mflisar.github.io/KotBilling/ | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.kotbilling/library?color=blue) |
| KotPreferences | `2.0.0`  | https://mflisar.github.io/KotPreferences/ | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.kotpreferences/core?color=blue) |
| Lumberjack | `8.0.0`  | https://mflisar.github.io/Lumberjack/ | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.lumberjack/core?color=blue) |

**Compose**

| Library  | Version | Link | Latest Version |
| - | - | - | - |
| ComposeColors | `1.0.0`  | https://mflisar.github.io/ComposeColors/ | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.composecolors/core?color=blue) |
| ComposeDebugDrawer | `2.0.0`  | https://mflisar.github.io/ComposeDebugDrawer/ | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.composedebugdrawer/core?color=blue) |
| ComposeChangelog | `2.0.0` | https://mflisar.github.io/ComposeChangelog/ | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.composechangelog/core?color=blue) |
| ComposeThemer | `1.0.0` | https://mflisar.github.io/ComposeThemer/ | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.composethemer/core?color=blue) |
| ComposeDialogs | `3.0.0` | https://mflisar.github.io/ComposeDialogs/ | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.composedialogs/core?color=blue) |
| ComposePreferences | `2.0.0` | https://mflisar.github.io/ComposePreferences/ | ![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.composepreferences/core?color=blue) |

> [!IMPORTANT]  
> Above mentioned versions are the **minimum versions** that are compatible with each other. From there on I try to make new versions **binary compatible** - so any newer versions will work with each other without problems.

## NOTES

### Experimental

**Why do some libraries use experimental functions?**

Mostly I do use the compose `BackHandler` and the the `kotlinx.datetime.Clock` class. Both are currently still marked as experimental. I need both to support all the platforms so I do use those...
