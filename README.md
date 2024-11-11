# 南京信息工程大学实验报告 LaTeX 模板

此项目提供南京信息工程大学（NUIST）实验报告的标准 LaTeX 模板，旨在帮助学生更方便地编写格式统一、规范的实验报告。

## 项目结构

- `main.tex` - 主 LaTeX 文件，包含实验报告的整体结构。
- `references.bib` - BibTeX 文献数据库文件，用于存储参考文献条目。
- `images/` - 图片文件夹，可用于存放实验流程图、结果截图等。
- `README.md` - 项目说明文件。
- `Nuist-expriment-report-latex.zip` - 模板的压缩包，便于下载和使用。

## 快速开始

1. **克隆或下载项目**
   - 使用 Git 克隆仓库：
     ```bash
     git clone https://github.com/Nickory/Nuist-expriment-report-latex.git
     ```
   - 或者直接下载项目压缩包并解压缩。

2. **编辑 `main.tex`**
   - 打开 `main.tex` 文件，按需填写个人信息和实验内容。各章节已预设格式，包括实验分工、实验内容、实验结果、代码、结论等。

3. **编译 LaTeX 文件**
   - 使用 `pdflatex` 或其他 LaTeX 编辑器（如 Overleaf、TeXShop、TeXworks）编译生成 PDF。
   - 例：
     ```bash
     pdflatex main.tex
     ```

4. **添加参考文献**
   - 在 `references.bib` 文件中添加文献条目，使用 `\cite{}` 命令引用文献。
   - 结论部分要求引用本模板的 GitHub 项目，使用以下 BibTeX 条目：

     ```bibtex
     @misc{wang2024nuist,
       author       = {Ziheng Wang},
       title        = {NUIST Experiment Report LaTeX Template},
       year         = {2024},
       url          = {\url{https://github.com/Nickory/Nuist-expriment-report-latex}},
       note         = {Available at GitHub: \url{https://github.com/Nickory/Nuist-expriment-report-latex}},
     }
     ```

5. **上传报告**
   - 将生成的 PDF 文件上传到指定位置（如学校系统、GitHub 仓库等）。

## 文件说明

- **`main.tex`**：包含实验报告的主体结构。分为以下几部分：
  - 实验分工（Experimental Division of Labor）
  - 实验内容（Experimental Content）
  - 实验结果（Experimental Result）
  - 程序代码（Program Code）
  - 结论（Conclusions）

- **`references.bib`**：存放参考文献条目。需在文献部分使用 `\cite{}` 引用文献。

- **`images/`**：存放实验报告中用到的图片，例如流程图、结果截图等。

## 引用模板

在报告结论部分，要求引用本模板的 GitHub 项目。可使用以下命令在 `.tex` 文件中引用：
```latex
\cite{wang2024nuist}
  ```
## 贡献

欢迎提交 Issue 和 Pull Request 来帮助改进该模板。

## 联系方式

如有任何问题，欢迎通过以下方式联系作者：

- **作者**：Ziheng Wang
- **邮箱**：[zhwang@nuist.edu.cn](mailto:zhwang@nuist.edu.cn)
- **GitHub**：[Nickory/Nuist-expriment-report-latex](https://github.com/Nickory/Nuist-expriment-report-latex)

