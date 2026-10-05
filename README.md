# BUAA-Thesis-Proposal-LaTeX
## 文献综述&开题报告LaTeX模板 V1.0

目前是按2025年的Word模板文件复刻。

## 使用方法

1. 在`main.tex`开头待编辑信息中填写信息。`\professionalfalse`对应学术型硕士；改为`\professionaltrue`切换为专业硕士。题目不超过25个汉字；必要时可在题目宏中使用`\\`指定两行断行。第二导师可留空；如需填写，在 `\SecondSupervisor` 和 `\SecondSupervisorTitle` 中写入姓名和职称。其他信息按照实际情况填写。
2. 在`chap`文件夹中，按正文结构填写内容。
3. 使用 XeLaTeX 连续编译两次，以更新交叉引用。
