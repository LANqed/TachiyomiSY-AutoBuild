# TachiyomiSY-AutoBuild

自动跟踪 `syncyomi/TachiyomiSY` 的 `feat/syncyomi-v2` 分支并自动构建、签名和发布。

频道：
- Dev：每周构建一次
- Nightly：每天构建一次

APP 内可以选择更新频道。

每次 Release 会自动包含上游 commit Changelog、APP 内 Changelog、多架构 APK 和 SHA-256。
