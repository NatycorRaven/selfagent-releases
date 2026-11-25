# SelfAgent Releases

SelfAgent 的公开下载页与安装包。源码仓库保持私有，这里只放发布物。

- 下载页：<https://natycorraven.github.io/selfagent-releases/>
- 最新版本：<https://github.com/NatycorRaven/selfagent-releases/releases/latest>

## 版本

| 版本 | 日期 | 大小 | 说明 |
|---|---|---|---|
| v0.1.0 | 2026-11-25 | 20.9 MB | 首个可安装版：DeepSeek 对话、日程/任务/本地记忆、系统日历、精确提醒、内外屏布局 |

## 安装

```bash
adb install -r selfagent-0.1.0.apk
```

或手机打开下载页，点「下载 APK」。

APK 使用 debug 签名，用于自用侧载；不要上架应用商店。

## 注意

- 需要自备 DeepSeek API Key（<https://platform.deepseek.com/api_keys>）。
- 小米/Redmi：开启自启动、省电策略设为「无限制」，否则提醒可能被后台清理。
- SHA-256（v0.1.0）：`38b654c2af7702df4042ce6513e7f2e729173c1e3c0687b22df72acf82f095f5`
