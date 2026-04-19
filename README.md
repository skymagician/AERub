# 《美国经济评臆》(American Economic Rubbish) 官方文库

欢迎来到致力于“用经济学解释人类迷惑的行为”的整活期刊——**《美国经济评臆》（American Economic Rubbish）**!

本仓库包含了本刊的排版模板和所有已经发布的文章的 LaTeX 代码。

## 📖 关于本刊 (About Us)
本刊由 Academic Waste Association 出版，是学术界公认的经济学 bottom 5 期刊之一，亦属于 UTD 26 （Union of Trash Dump 26）和 FT50（Full of Trash 50），是久负盛名的经管类权威底刊。

---

## 🛠️ 排版指南 (Formatting Guidelines)

本刊实行极其严苛的中英文稿件“双轨制”排版。

### 🇨🇳 中文模板 (Chinese Template)
中文稿件采用《经济研究》排版格式：
* **依赖模板**：`chinese-erj.cls`
* **编译引擎**：必须使用 `xelatex` $\to$ `biber` $\to$ `xelatex` $\to$ `xelatex`。
* **套用范例**：请参考本仓库的中文稿件代码（如`AERub_tiangou.tex` + `AERub_tiangou.bib`）。

### 🇺🇸 英文模板 (English Template)
英文稿件采用美国经济学会（AEA）排版格式：
* **依赖模板**：`AEA.cls`, `aea.bst`
* **编译引擎**：必须使用 `pdflatex` $\to$ `bibtex` $\to$ `pdflatex` $\to$ `pdflatex`。严禁使用 `biber`！
* **套用范例**：请参考本仓库的英文稿件代码（ 如`AERub_Simp.tex` + `AERub_Simp.bib`）。

---

## 💡 投稿方式 (How to Submit)

在您的本地电脑成功编译出 PDF 后，请将您的 **PDF 成品**、**`.tex` 主文件**、**`.bib` 参考文献库**及**图片资源**打包。本刊提供以下三种投稿渠道：

1. 🌐 **Web of Nothing 平台 (推荐)**：
   直接使用 WoN 平台 [Web of Nothing 投稿中心](https://webofnothing.top/paper-submit)，享受丝滑的投稿体验。

2. 📧 **Email**：
   将稿件发送至本刊编辑部邮箱：`aerubbish.editorial@outlook.com`。

3. 💻 **GitHub PR (慎用)**：
   您也可以 Fork 本仓库，将您的稿件 Push 后向我们提交 Merge Request。
   
   *(⚠️ 严正警告：此通道将默认您自愿放弃“盲审”权利，您的“迷惑行为源码”将在合并前接受全网开源极客的无情审视！)*

---

## ⚖️ 开源协议与版权声明 (License & Acknowledgements)

本仓库的主体代码（包括所有 `.tex` 示例文档、`.bib` 参考文献库）均采用 **[MIT License]** 开源。您可以随意取用、修改、甚至用于水论文，但本刊编辑部不对您因此造成的任何学术声誉破产负责。

**【特别致谢与第三方协议】**
本仓库中用于中文排版的模板 `chinese-erj.cls` 基于开源项目 [EthanDeng/Chinese-ERJ](https://github.com/EthanDeng/Chinese-ERJ) 进行了修改与定制。该文件及其衍生代码遵循 **[LaTeX Project Public License (LPPL) Version 1.3c](http://www.latex-project.org/lppl.txt)**。
我们向原作者表示崇高的敬意。

## 📱 关注本刊 (Follow Us)

立刻扫码关注 **《美国经济评臆》官方微信公众号**！我们将定期推送本刊录用的文章的硬核拆解、学术圈整活前沿。

**祝你早日发顶刊，赢麻你的人生！**

![《美国经济评臆》微信公众号](image/qrcode.jpeg)
