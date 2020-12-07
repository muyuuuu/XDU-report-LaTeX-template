# 介绍

这里是西安电子科技大学实验报告 `LaTeX` 模板，注：此模板是我自己写的，只是按照老师要求添加了基本元素，非官方，非官方，非官方。来这上学一个月了，我也没找到官方的，老师也没发过任何模板，也不要求格式，所以我决定开 `LaTeX` 放飞自我了。**如果老师有明确要求，请勿使用此模板。**

我写的代码首要目的是简洁、易用和容易扩展，所以：

- 图片大小、文字大小不合适你都可以调，cls代码简洁明了。
- 想添加内容也很简单，比如在封面添加「指导教师」这一项，你看看其他选项如何声明并传参的就可以了。

更多样式请点击这里：https://muyuuuu.github.io/2020/10/20/XDU-report-LaTeX-template/

# 文档目录与编译方式

`windows` 和 `Arch Linux` 都跑通了，`TexLive 2020`，编译方式为 `xelatex` 配 `bibtex`。

```bash
XDU-exp
├─ chapter                                  # 各个章节
│    ├─ abstract.tex                            # 摘要页
│    ├─ appendix.tex                            # 附录
│    ├─ conclusion.tex                          # 实验结果分析
│    ├─ experiment.tex                          # 实验步骤
│    └─ reference.tex                           # 参考文献
├─ figure                                   # 图片文件
│    ├─ 1.jpg                                   # 西电logo
│    ├─ 2.jpg                                   # 西电logo和文字并排
│    ├─ 3.jpg                                   # 西电logo和文字竖排
│    └─ 4.jpg                                   # 西电文字
├─ code                                     # 代码文件
│    └─ demo.c                                  # 一个C语言样例代码
├─ books.bib                                # 参考文献的 bib 文件
├─ main.bbl                                 # 编译生成的 bbl 文件，不用管
├─ main.pdf                                 # 结果 pdf 文件
├─ main.tex                                 # 要编译的主文件
└─ xdureport.cls                            # 要导入的文档类
```

如果实在看不懂代码，等作业结束后，我会在[release](https://github.com/muyuuuu/XDU-report-LaTeX-template/releases/tag/1.0)里放一个样例。

# 其他

- 代码字体为 `IBM Plex Mono`，没有的话换一个或下载安装；
- 图片logo来自这里：https://xcb.xidian.edu.cn/info/1008/1094.htm
- 我是计算机学院的，对其他学院的了解很少，如果有其他建议，欢迎补充～
- 也可以来这里下载，下载一次我能挣一毛钱，顺便帮这个网站引流：https://latexstudio.net/index/details/index/mid/870.html