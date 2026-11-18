# 每日 Routine

手机浏览器打开即用的每日习惯打卡 App，不需要登录任何账号。

- 按早晨 / 白天 / 晚上分组打卡，显示今日进度、近 7 天和连续全勤天数
- 习惯库（单独页面）：好习惯先收藏，想坚持时一键加入 Routine
- 可切换日期（年月日选择、前一天/后一天），回看过去并补打卡
- 年度日历：一年 12 个月的完成度热力图，可按单个事项查看，点日期跳转
- 数据存在本机浏览器（localStorage）；可选「手机电脑同步」，用 GitHub 令牌把数据同步到自己的私密 Gist
- 「备份与恢复」可导出 / 导入 JSON 备份，换手机时用
- 支持「添加到主屏幕」，离线也能打开

## 文件

- `index.html`：App 本体（单文件，无外部依赖）
- `manifest.webmanifest`、`sw.js`、`icons/`：添加到主屏幕与离线缓存
- `_artifact_version/`：旧的 Claude Artifact 版本（依赖 Claude 账号，仅存档）

## 本地预览

```
python -m http.server 8765
```
然后打开 http://localhost:8765
