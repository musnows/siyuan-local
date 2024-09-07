## 思源笔记纯本地魔改版本

本项目 fork 自 [github.com/siyuan-note/siyuan](https://github.com/siyuan-note/siyuan) (v3.15.0, commit 260a47761ac09487eae4f00e3dbf66b45027d011)

魔改的目标是**剔除**思源笔记中的链滴账户登录、云端同步、谷歌统计、SDK自动上传这些涉及到**外网访问**的功能，让思源能完全本地使用，且不会有给任何外网URL发送请求的处理逻辑。使思源更加符合商业环境的信息安全要求。

关于思源笔记的介绍，详见项目原始README文件：[README_ORIGIN_zh_CN](./README_ORIGIN_zh_CN.md)。

欢迎各位有相同需求且感兴趣的开发者加入本项目，一起研究如何剔除思源的这些外网访问功能。即便您不是开发者，也可下载使用本项目魔改后的思源笔记，反馈是否有影响到思源原有功能的BUG。感激不尽！

----

This is a fork of the siyuan-note project (v3.15.0, commit 260a47761ac09487eae4f00e3dbf66b45027d011) from [github.com/siyuan-note/siyuan](https://github.com/siyuan-note/siyuan) with modifications targeting a fully offline version of Siyuan Note that eliminates external service dependencies like third-party account login, cloud sync, Google Analytics, and SDK auto-upload. This aims to enhance the local data security by preventing any Internet requests.

The original README file can be found in [README_ORIGIN](./README_ORIGIN.md). The project is intended for developers who wish to contribute to making Siyuan Note work offline and for users seeking a secure alternative without internet connectivity requirements.

If you are not a developer but interested in using the modified version, feel free to download and try it out. Your feedback on any potential issues with the functionality would be greatly appreciated. Thank you!
