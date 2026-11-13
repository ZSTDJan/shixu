# 事序 SHIXU

[打开事序介绍网站](https://zstdjan.github.io/shixu/)

花了半年，手搓了一款叫「事序」的 Windows 待办软件。

平时可以贴便签、列待办、写图文日记，也能在日历里看安排。

遇到工程协调、问题排查、材料申报这类要反复跟进的事，可以单独建一个「事项」，把每次进展、下一步待办、截图和附件都放进去。隔几周再打开，也能看清上次跟到哪一步、当时是怎么定的、还有什么待确认。

需要汇报或交接时，可以按模板把事项和过程记录导出成 PDF 或 Word，也可以连同原始附件一起打包发给接手的人。

事序的资料保存在独立的本地文件夹里，可以整库备份、用网盘同步，也可以复制到另一台电脑接着用。

[![事序功能总览](assets/00-cover.png)](assets/00-cover.png)

[下载与环境](#下载与环境) · [功能](#功能) · [功能配图](#功能配图) · [首次使用](#首次使用) · [反馈与支持](#反馈与支持)

## 下载与环境

个人开发，免费使用。当前公开测试安装包面向 **Windows 11 x64**。

**Win10 兼容进度：** Windows 10 专业版 22H2 x64（19045.6456）已通过本地实测；完整安装包尚待整合复验，当前公开包未包含修复。其它 Win10 版本未验证。

[下载事序 0.3.6 测试版](https://github.com/ZSTDJan/shixu/releases/tag/v0.3.6)（Windows 11 x64）。

## 功能

- **总览工作台** — 把日历、待办、关注事项和常用工具放在一起，按需调整组件。
- **待办与四象限** — 用列表查看详情，用四象限安排优先级。两个视图共用同一份待办。
- **日历** — 按年、月、周查看排期，设置重复待办和提醒。
- **快速收集** — 用快捷键把其他软件里的文字、图片和文件存成收集卡。
- **收集板** — 分区整理卡片，从卡片内容创建待办或事项。
- **随记** — 按日期写图文记录，可以回看、导出和打印。
- **事项与过程** — 在同一个事项里记录进展、经过、待办和相关材料。
- **资料包交接** — 把所选事项、过程记录和原始附件打包交接。
- **导出模板** — 保存常用版式和字段，换一组内容继续生成 PDF 或 Word。
- **主题与配色** — 自选主色、背景和明暗模式。
- **独立事项库** — 备份或换机时，可以把记录、材料和库内布局一起带走。
- **AI 连接** — 通过 MCP 连接兼容的 AI 客户端读取当前事项库。授权写入后，可创建或修改记录。

## 功能配图

点击图片查看原图。

<table class="gallery">
<tr>
<td width="50%"><a href="assets/01-workbench.png"><img src="assets/01-workbench.png" alt="总览工作台" width="480" loading="lazy"></a><br>总览工作台</td>
<td width="50%"><a href="assets/02-tasks.png"><img src="assets/02-tasks.png" alt="待办列表与四象限" width="480" loading="lazy"></a><br>待办列表与四象限</td>
</tr>
<tr>
<td width="50%"><a href="assets/03-calendar.png"><img src="assets/03-calendar.png" alt="年、月、周日历" width="480" loading="lazy"></a><br>年、月、周日历</td>
<td width="50%"><a href="assets/04-quick-capture.png"><img src="assets/04-quick-capture.png" alt="快速收集" width="480" loading="lazy"></a><br>快速收集</td>
</tr>
<tr>
<td width="50%"><a href="assets/05-collection-board.png"><img src="assets/05-collection-board.png" alt="收集板" width="480" loading="lazy"></a><br>收集板</td>
<td width="50%"><a href="assets/06-journal.png"><img src="assets/06-journal.png" alt="图文随记" width="480" loading="lazy"></a><br>图文随记</td>
</tr>
<tr>
<td width="50%"><a href="assets/07-issues.png"><img src="assets/07-issues.png" alt="事项与过程" width="480" loading="lazy"></a><br>事项与过程</td>
<td width="50%"><a href="assets/08-handover.png"><img src="assets/08-handover.png" alt="资料包交接" width="480" loading="lazy"></a><br>资料包交接</td>
</tr>
<tr>
<td width="50%"><a href="assets/09-export-template.png"><img src="assets/09-export-template.png" alt="导出模板" width="480" loading="lazy"></a><br>导出模板</td>
<td width="50%"><a href="assets/10-themes.png"><img src="assets/10-themes.png" alt="主题与配色" width="480" loading="lazy"></a><br>主题与配色</td>
</tr>
<tr>
<td width="50%"><a href="assets/11-library.png"><img src="assets/11-library.png" alt="独立事项库" width="480" loading="lazy"></a><br>独立事项库</td>
<td width="50%"><a href="assets/12-mcp.png"><img src="assets/12-mcp.png" alt="通过 MCP 连接 AI" width="480" loading="lazy"></a><br>通过 MCP 连接 AI</td>
</tr>
</table>

## 首次使用

1. 第一次打开时，新建事项库。如果已有资料，选择「打开已有事项资料库」，选中整个库文件夹。
2. 新建后进入总览，点击「快速上手」，打开第一张示例卡。
3. 跟着卡片做一次操作，例如把一段文字收成卡片，或安排一条待办。

[查看使用手册](https://zstdjan.github.io/shixu/manual.html#首次使用)

## 反馈与支持

### 交流与反馈

- QQ 群「事序-交流」 · **89641678**
- 反馈邮箱 · [w.jan@FOXmail.com](mailto:w.jan@FOXmail.com)

反馈问题时，可以附上事序版本和复现步骤。

<img class="qr" src="assets/feedback-qq.png" alt="事序交流 QQ 群二维码" width="160" height="160" loading="lazy">

### 支持事序

如果事序对你有帮助，欢迎在 GitHub 点亮 Star，也可以扫码赞助。

<table class="support-codes">
<tr>
<td align="center"><img class="qr" src="assets/sponsor-wechat.png" alt="微信赞助二维码" width="160" height="160" loading="lazy"><br>微信</td>
<td align="center"><img class="qr" src="assets/sponsor-alipay.png" alt="支付宝赞助二维码" width="160" height="160" loading="lazy"><br>支付宝</td>
</tr>
</table>
