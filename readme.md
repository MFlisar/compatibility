## COMPATIBILITY

Recently ALL my main libraries have been updated to support KMP targets like `jvm`, `android`, `ios`, `macos` and `wasm`. The side effect is, that it was nearly impossible to keep the libraries binary compatible.

Beginning from 08/2025 I will update all libraries step by step and mark them initially as pre releases. As soon as all are updated I will remove the `pre release` mark. From then on I will try my best to keep everything binary compatible. The list below contains all libraries that are done and published:

### Libraries

**Core Libraries**

| Library  | Version |
| - | - |
| Lumberjack | `8.0.0`  |
| KotPreferences | `1.0.3`  |

**Compose**

| Library  | Version |
| - | - |
| ComposeColors | `1.0.1`  |

### TODO

* ComposeChangelog
* ComposePreferences
* ComposeDebugDrawer
* ComposeDialogs
* ComposeThemer

It is save to use my compose libraries together with newer the ones above if they do not depend on them or if you do not use the modules that do depend on them!

### FINISH DATE

My goal is to get this done in the next 2 weeks at most!
