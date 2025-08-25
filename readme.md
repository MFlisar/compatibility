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

| Library  | Version | Link |
| - | - | - |
| CacheFileProvider | `1.0.0`  | https://mflisar.github.io/CacheFileProvider/ |
| FeedbackManager | `3.0.0`  | https://mflisar.github.io/FeedbackManager/ |

**Libraries**

| Library  | Minimum Version | Link | Latest Version |
| - | - | - | - |
| KotBilling | `2.0.0`  | https://mflisar.github.io/KotBilling/ | [![Maven Central Version](https://img.shields.io/maven-central/v/io.github.mflisar.cachefileprovider/library?color=blue)]() |
| KotPreferences | `2.0.0`  | https://mflisar.github.io/KotPreferences/ | https://img.shields.io/maven-central/v/io.github.mflisar.kotpreferences/core?color=blue |
| Lumberjack | `8.0.0`  | https://mflisar.github.io/Lumberjack/ | https://img.shields.io/maven-central/v/io.github.mflisar.lumberjack/core?color=blue |

**Compose**

| Library  | Version | Link |
| - | - | - |
| ComposeColors | `1.0.0`  | https://mflisar.github.io/ComposeColors/ |
| ComposeDebugDrawer | `2.0.0`  | https://mflisar.github.io/ComposeDebugDrawer/ |
| ComposeChangelog | `2.0.0` | https://mflisar.github.io/ComposeChangelog/ |
| ComposeThemer | `1.0.0` | https://mflisar.github.io/ComposeThemer/ |
| ComposeDialogs | `3.0.0` | https://mflisar.github.io/ComposeDialogs/ |
| ComposePreferences | `2.0.0` | https://mflisar.github.io/ComposePreferences/ |

> [!IMPORTANT]  
> Above mentioned versions are the **minimum versions** that are compatible with each other. From there on I try to make new versions **binary compatible** - so any newer versions will work with each other without problems.

## NOTES

### Experimental

**Why do some libraries use experimental functions?**

Mostly I do use the compose `BackHandler` and the the `kotlinx.datetime.Clock` class. Both are currently still marked as experimental. I need both to support all the platforms so I do use those...
