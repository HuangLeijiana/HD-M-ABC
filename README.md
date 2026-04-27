# 第一阶段技术报告草稿

这个目录是第一阶段的 v1 成果：一份可继续提交 arXiv 或导入 Overleaf 编译的英文 LaTeX 技术报告。

## 文件

- `main.tex`：英文技术报告主体，已包含六个核心部分、四层架构图、关键机制、数据对象、操作循环、参数表、两个科学猜想和后续实验协议。
- `references.bib`：参考文献库，覆盖 ABC、PSO、ACO、动态优化记忆机制和认知记忆系统。

## 当前判断

三个阶段整体合理，但需要收紧表述：

1. 第一阶段适合作为“概念技术报告 + 时间戳”，不要把 arXiv 描述成正式优先权或同行评审证明。
2. 报告中已经避免强说“首个”，改成了“a conceptual architecture / to be empirically tested”一类表述。
3. 第二阶段的实验指标应从“到达全局最优”改为“达到预设误差阈值”，否则连续优化里很难严格判定。
4. CEC 测试函数不要直接复制未确认许可证的网上代码，后续应优先使用可复现、许可清晰的实现。
5. 第三阶段投稿窗口要按当年 CFP 重新确认；不要依赖文档里的通常月份。

## 下一步待办

- 核对 `main.tex` 里的作者信息：`Lei Huang`，`Independent Researcher`，`Chongqing, China`，`2644901977@qq.com`。
- 用 Overleaf 或本机 TeX 编译正式 PDF。
- 逐页检查 PDF 的标题、作者、图、表和参考文献。
- 用 `pdflatex -> bibtex -> pdflatex -> pdflatex` 或 `latexmk -pdf main.tex` 编译 PDF。
- 编译通过后再准备 arXiv 上传压缩包。
