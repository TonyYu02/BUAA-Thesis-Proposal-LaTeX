# BUAA-Thesis-Proposal-LaTeX
## 文献综述&开题报告二合一LaTeX模板 V1.2

目前是按2025年的Word模板文件复刻。

## 使用方法

### 文档使用
1. 在`main.tex`开头选择学硕or专硕、综述or报告，以及在待编辑信息中填写信息。`\professionalfalse`为学术型硕士；改为`\professionaltrue`切换为专业硕士。`\reviewfalse`为开题报告；改为`\reviewtrue`切换为文献综述。题目不超过25个汉字；必要时可在题目宏中使用`\\`指定两行断行。第二导师可留空。其他信息按照实际情况填写。
2. 按照开题报告(kaiti)或文献综述(zongshu)，在对应`chap`文件夹中，填写正文的内容，具体安排见下文文件夹结构。同时图片可以保存在`pic`对应的文件夹中，文献可以保存在`ref`对应的文件夹中。
3. 使用 XeLaTeX 连续编译两次，以更新交叉引用。

### 示例pdf
| 文件名 | 超链接 |
| --- | --- |
| 专业硕士学位开题报告 | [查看](template_pdf/专业硕士学位开题报告.pdf) |
| 专业硕士学位文献综述 | [查看](template_pdf/专业硕士学位文献综述.pdf) |
| 硕士开题报告 | [查看](template_pdf/硕士开题报告.pdf) |
| 硕士文献综述 | [查看](template_pdf/硕士文献综述.pdf) |

### 文件夹结构
``` text
│  main.tex #主文件
│
├─chap
│  ├─kaiti #开题报告文件夹
│  │      ch1.tex #论文选题依据
│  │      ch2.tex #论文研究方案
│  │      ch3.tex #预期达到的目标及考核指标
│  │      ch4.tex #论文工作计划
│  │
│  └─zongshu #文献综述文件夹
│          abs.tex #摘要与关键词（中英文）
│          ch2.tex #文献概述
│          ch3.tex #基本研究现状与发展趋势
│          ch4.tex #结论
│
├─def
│      GBT7714-2015-NoWarning.bst #参考文献样式文件
│
├─fonts
│      FangSong_GB2312.ttf #仿宋_GB2312字体
│
├─pic
│  │  buaa-mark.jpg #校徽
│  │  logo-buaa.eps #校名
│  │
│  ├─kaiti #开题报告文件夹
│  │      flowchart.png #示例用流程图
│  │
│  └─zongshu #文献综述文件夹
│          example.png #例图
│
├─ref
│  ├─kaiti #开题报告文件夹
│  │      reference.bib
│  │
│  └─zongshu #文献综述文件夹
│          reference.bib
│
└─template_pdf #示例pdf
        专业硕士学位开题报告.pdf
        专业硕士学位文献综述.pdf
        硕士开题报告.pdf
        硕士文献综述.pdf
```
