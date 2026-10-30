# 素材清单 / Asset Inventory

**免费内测 v0.1.1 · Free beta**

在本地浏览器检查游戏项目的重复素材、文件夹体积与疑似未引用资源。面向整理 Godot / Unity 项目素材的独立开发者。

## 直接下载 / Download

- [下载免费测试包 / Download free beta](https://github.com/Zopha-c/asset-inventory-beta/releases/download/v0.1.1-beta.1/Asset-Inventory-Free-Beta-v0.1.1.zip)
- [版本说明 / Release notes](https://github.com/Zopha-c/asset-inventory-beta/releases/tag/v0.1.1-beta.1)
- [报告故障或反馈体验 / Report a bug or share feedback](https://github.com/Zopha-c/asset-inventory-beta/issues/new/choose)

## 下载和开始

打开本仓库的 **Releases**，选择 **v0.1.1-beta.1**，在附件中下载 **Asset-Inventory-Free-Beta-v0.1.1.zip**。请下载这个附件，不是 GitHub 自动生成的 Source code 压缩包。

完整解压后，使用近期桌面 Chrome 或 Edge 打开 index.html，先点“体验示例”或扫描包内 demo-project，再尝试自己的小型项目。扫描中可查看阶段进度或停止扫描。右上角支持简体中文 / English。

## 能解决什么问题

- 查找精确重复文件，并人工复核相似图片和同名冲突。
- 按文件夹查看哪些源文件占用空间最多。
- 查看 Godot / Unity 文本引用线索和疑似未引用资源。
- 检查图片尺寸、命名问题，标记需要保留的文件或目录。
- 导出 CSV / JSON / Markdown，重新打开报告，比较两次扫描中的文件和问题变化。

分析在本地浏览器进行；页面不包含上传、移动或删除项目文件的功能。无需注册或付款。导出报告含文件名及路径，分享前请检查内容。

## 本轮改进

- 新增本地一键示例和扫描阶段进度；哈希阶段按 4 MiB 分块更新。
- 新增独立停止按钮；停止后清空未完成结果。
- 修复意外异常后按钮锁住、旧引用任务污染新扫描说明的问题。
- 相似度比较更稳定地让出执行时间，便于响应停止操作。

## 测试版限制

完整浏览器交互、大型真实项目与不同引擎版本的准确率仍待验证。疑似未引用可能误报，动态加载和引擎二进制资源可能漏报，需在引擎中复核。源文件大小不等于构建包大小，纹理内存为计算参考。相似图片结果也需要人工复核。

工具不会自动删除文件。历史报告不含原图，也不能代表当前磁盘状态。

## 希望得到的反馈

请在 **Issues → New issue** 中选择“使用故障 / Bug report”或“试用体验 / Beta feedback”。首先关心：是否能完成扫描、哪条结果不准确、是否发现了一个值得处理的真实问题。

无需提交完整游戏项目、客户素材或个人联系方式。可以提供去除敏感内容后的截图或最小复现样本。

本仓库用于分发免费内测包与收集反馈。免费试用并未附带开源许可证，也不承诺将来正式版本的价格或功能。

## English

Asset Inventory is an early free beta for reviewing local game assets: exact duplicates, similar images, folder sizes, Godot / Unity reference hints, naming checks and report comparisons.

Open Releases, choose v0.1.1-beta.1 and download Asset-Inventory-Free-Beta-v0.1.1.zip from its assets. Extract it, open index.html in a recent desktop Chrome or Edge, and try demo-project first. Select English at the top right.

Files are analyzed locally. The page does not upload, move or delete project files. No signup or payment is required. Review exported filenames and paths before sharing reports.

Full browser and large real-project validation remain incomplete. Unused-file and similarity results require manual review. Source-file sizes are not build sizes; texture memory is an estimate. Submit feedback through Issues without uploading your complete project or private assets.
