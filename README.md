# 相册日报 · 技术支持 / Album Digest Support

相册日报每天在 iPhone 本地分析新增的照片和截图，和前几天对比，把值得注意的事整理成一份简短的日报，在你设定的时间提醒你。照片和分析结果都不会离开你的设备。

- [隐私政策 / Privacy Policy](PRIVACY.md)
- 问题反馈 / Contact：[GitHub Issues](https://github.com/kuangre123/xiangce-ribao-support/issues)

## 常见问题

**日报是谁写的？**
支持 Apple 智能并已开启的设备（iPhone 15 Pro 及之后的机型），由 Apple 端侧大模型写成；其他设备由规则模板生成，日报详情页会注明“规则模板生成”。

**为什么推送时间不准？**
iOS 不允许 App 在精确的时间点后台运行。相册日报会在夜里充电时整理照片，第二天按设定时间推送；如果夜里没来得及整理，会先发一条提醒。想要准点，可以在“快捷指令 → 自动化 → 特定时间”里添加“生成相册日报”操作，并设为“立即运行”。

**为什么有的日子没有推送？**
只有重要程度达到你设置的推送门槛（设置里的“推送门槛”）时才会推送，平淡的日子不打扰你。

**照片会上传吗？数据保存在哪里？**
不会。分析全部在手机上完成；分析结果和日报只保存在 App 里，不进入 iCloud 或电脑备份。

**怎么删除全部数据？**
删除 App 即可，它保存的数据会一起删除。

**界面支持哪些语言？**
目前只有简体中文。

## FAQ (English)

**Who writes the digest?**
On devices with Apple Intelligence turned on (iPhone 15 Pro or later), Apple's on-device model writes it. Other devices use a rule-based template, and the digest says so.

**Why isn't the notification on time?**
iOS does not let apps run in the background at an exact time. The app analyzes your photos overnight while charging and notifies you at your chosen time the next day. For an exact time, add the "生成相册日报" action to a time-based automation in Shortcuts and set it to run immediately.

**Are my photos uploaded? Where is the data stored?**
No. All analysis happens on your iPhone. Results and digests stay inside the app and are excluded from iCloud and computer backups.

**How do I delete all data?**
Delete the app; everything it stored is removed with it.

**Which languages does the app support?**
The interface and digests are currently in Simplified Chinese only.
