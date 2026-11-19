# OHOS fork

- Package: `cupertino_ui` 1.1.7
- Upstream: https://github.com/flutter/packages/tree/main/packages/cupertino_ui
- Purpose: Adds `TargetPlatform.ohos` cases to platform switches so the package compiles with the OpenHarmony Flutter fork.
- Changes: only `TargetPlatform.ohos` handling; no API/behavior changes for other platforms.

Usage in an OHOS Flutter build:

```yaml
dependency_overrides:
  cupertino_ui:
    git:
      url: https://github.com/deretame/cupertino_ui_ohos.git
      ref: ohos-1.1.7
```
