> 🌍 **Language / 语言 / 語言**: [🇺🇸 English](./readme-en.md) | [🇨🇳 简体中文](./readme-cn.md) | [🇹🇼 繁体中文](./readme.md)

# 8 分钟学会 n8n 错误处理工作流 Error Workflow！3大通知方法 LINE、Email、Google Sheet 即时掌握 99% 的错误｜🧠 省力知识库

[![YouTube](https://img.shields.io/badge/Watch%20on-YouTube-red?logo=youtube)](https://youtu.be/Yt0gVZX_OGQ)

![n8n 错误处理工作流](https://github.com/qwedsazxc78/ai-automation-n8n/blob/main/n8n/18-n8n-error-workflow/cover.png?raw=true)

## 作者信息

* **作者：** Alexhsieh
* **平台：** n8n（您可以将 `.json` 档导入自己的 n8n 环境，查看完整流程与设定）
* **注意事项：** 范例档案已移除所有 API 密钥与个资，使用时请自行填写

---

## 📌 功能介绍

此 n8n 错误处理工作流（Error Workflow）适用于任何 n8n 自动化脚本与流程中，帮助您即时监控并掌握 99% 工作流异常！

* ✅ **Email（HTML邮件）即时通知**：自动发送包含错误类型与详细信息的 HTML 邮件，快速锁定问题来源。
* ✅ **Google Sheet 完整记录**：将每一次错误发生的所有执行细节记录于 Google Sheet，便于长期追踪、报表统计与问题归档。
* ✅ **LINE Messenger 即时推播**：当重大错误发生时，马上推播至 LINE，让你随时随地掌握系统状态，迅速反应！

---

## 🔧 运作方式

1. **工作流设定错误处理**：工作流必须切换为 Active，并设定 Error Workflow 工作流。只有在正式启用下，错误通知才能自动触发。
2. **模拟错误产生**：藉由 Schedule Trigger 每 30 秒发送一个故意设成无效网址的 HTTP Request，模拟真实错误情境。
3. **多元通知流程**：
   - **Email 通知**：错误发生，自动寄出 HTML 邮件，主旨自定、内容清楚标示所有错误细节。
   - **Google Sheet 记录**：利用 Google Sheet 同步记录错误出现的时间、Workflow 名称、URL、执行 ID与错误内容。
   - **LINE 即时推播**：整合 LINE Messaging API，推送包含错误简述与追踪连结的信息，错误不漏接！
4. **灵活选择搭配**：根据通知急迫性与用途，配合不同管道单独或组合运用。

---

## 🚀 通知方式选择建议

* 需即时反应 ➔ 选 LINE！
* 减少干扰、例行记录 ➔ 用 Email。
* 想长期统计、维运管理 ➔ Google Sheet。

> ⏰ **小提醒：** 测试时请记得必须「启用 workflow」而非仅按测试按钮，否则 Error Workflow 不会启动！如需串接 LINE 请参考上一集完整教学。[![YouTube](https://img.shields.io/badge/Watch%20on-YouTube-red?logo=youtube)](https://youtu.be/HJKDHJ5x1F0)

---

## 延伸学习资源

* [n8n 官方说明](https://docs.n8n.io/)
* [上一集：8分钟学会 n8n 串接 LINE Messenger API](https://youtu.be/HJKDHJ5x1F0)
* [Google Sheet API 教学](https://developers.google.com/sheets/api)

---

## 🚀 快速上手 n8n 自動化資源懶人包

### 🎓 學習與社群

* 🔗 [加入 AI 學習社群 (Skool)](https://www.skool.com/ai-brain-alex/about?ref=5dde9b20e8e7432aa9a01df6e89685f4)
  建立學習 AI 與 n8n 的學習路徑，無痛上手！
* 🔗 [加入 Line 社群一起搞懂 AI](https://line.me/ti/g2/ZypIgLSzVPweRBgBqKvaRU10WEmnotuZOr7Lpg)
  互相幫助前進！打造自己的 AI 自動化場景！

### 📚 教學資源

* 🎥 [n8n AI 自動化工作流：從基礎到進階實戰](https://youtube.com/playlist?list=PLUf88uk7T54I83MBdbuXgUuA8rVklF4FA&si=wHsQw8YJu-erSdLd)
  YouTube 系列教學，邊看邊做快速上手！
* ⏱️ [碎片化時間學習 n8n](https://youtube.com/playlist?list=PLUf88uk7T54Iv6LV2NFgdTghaX2cPhtgH&si=G3gj2qn179ZFUqAZ)
  每天5分鐘學習，自動化養成沒負擔。

### 🛠️ 部署與工具

* 🧩 [zeabur n8n 部署模板 (隨時更新)](https://zeabur.com/zh-TW/templates/0TUVZ7?referralDesktop=qwedsazxc78)
  零架設壓力，點擊部署即可使用，適合初學者與進階用戶。
* 🌐 [n8n 官方網站](https://n8n.io/)
  了解更多功能與文件，掌握最新更新。
