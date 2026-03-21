# 《美国经济评臆》(American Economic Rubbish) 官方论文库

欢迎来到全球首个致力于“用经济学解释人类迷惑的行为”的整活期刊——**《美国经济评臆》（American Economic Rubbish）** 的官方 LaTeX 代码仓库！



## 📖 关于本刊 (About Us)
本刊由 Academic Waste Association 出版，是学术界公认的经济学 bottom 5 期刊，亦是著名的 UTD 26 （Union of Trash Dump 26）和 FT50（Full of Trash 50）期刊，是久负盛名的经管类权威底刊。

为了捍卫本刊的学术尊严，我们为所有作者提供**宇宙级顶刊排版规范**。本仓库包含了本刊中英双语的底层模板与已经排版发布的文章源码。

---

## 🛠️ 排版指南 (Formatting Guidelines)

本刊实行极其严苛的“双轨制”排版。我们不要求您从零开始学习 LaTeX 的底层黑科技，**最稳妥的排版方式是：直接复制本仓库中已发布文章的 `.tex` 和 `.bib` 源码，用您的内容进行替换套用。**

### 🇺🇸 英文模板 (English Submissions)
英文稿件采用纯正的美国经济学会（AEA）顶级期刊《American Economic Review》官方排版格式。
* **依赖模板**：`AEA.cls`, `aea.bst`
* **编译引擎**：必须使用 `pdflatex` $\to$ `bibtex` $\to$ `pdflatex` $\to$ `pdflatex`。严禁使用 `biber`！
* **套用范例**：请直接参考并复制本仓库中的 `AERub_win_graph.tex` 与 `AERub_win_graph.bib`（《陈平不等式的图论证明》）。该文件已完美内置了原版 AER 的标题脚注黑科技与悬浮蓝三角超链接，照着改准没错。

### 🇨🇳 中文模板 (Chinese Submissions)
中文稿件采用《经济研究》（Economic Research Journal）的底层逻辑，自带国内顶刊的绝对威压。
* **依赖模板**：`chinese-erj.cls`
* **编译引擎**：必须使用 `xelatex` $\to$ `biber` $\to$ `xelatex` $\to$ `xelatex`。
* **套用范例**：请直接参考并复制本仓库中的中文稿件（如 `AERub_tiangou.tex` 或 `AERub_lemon.tex`）。这些源码已为您配置好了所有格式。

---

## 💡 投稿方式 (How to Submit)

在您的本地电脑成功编译出没有任何排版瑕疵的 PDF 后，请将您的 **PDF 成品**、**`.tex` 主文件**、**`.bib` 参考文献库**及**图片资源**打包。本刊提供以下三种投稿渠道：

1. 🌐 **官方直连 (Web of Nothing 平台 - 推荐！)**：
   直接登录本刊专属的学术提交系统 [Web of Nothing 投稿中心](https://webofnothing.top/paper-submit) 完成在线传稿，享受丝滑的投稿体验。

2. 📧 **传统学术 (编辑部邮箱)**：
   将压缩包作为附件发送至本刊编辑部：`aerubbish.editorial@outlook.com`。
   *邮件标题请遵循格式：`[AERub投稿] + 您的文章标题`。*

3. 💻 **极客专属 (GitHub PR - 慎用！)**：
   您也可以直接 Fork 本仓库，将您的文件夹 Push 后向我们提交 Merge Request。
   *(⚠️ 严正警告：此通道将默认您自愿放弃“盲审”权利，您的“迷惑行为源码”将在合并前接受全网开源极客的无情审视！)*

## 📱 关注本刊 (Follow Us)

立刻扫码关注 **《美国经济评臆》官方微信公众号**！我们将定期推送本刊录用的文章的硬核拆解、学术圈整活前沿。

**祝你早日发顶刊，赢麻你的人生！**

![《美国经济评臆》微信公众号](image/qrcode.jpeg)
