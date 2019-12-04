# 中南大学毕业论文 $\LaTeX$ 模板（非本科生院制）

本$\LaTeX$模板完全参考原Word模板“附件7：中南大学毕业设计（论文）模板.docx”，是由作者（本科学生）自己编写的$\LaTeX$模板，不是本科生院书写的模板。

本项目主要包括四个`.tex`源文件、一个`.pdf`论文模板、一个`.docx`论文Word模板、一个`.sty`宏包和两个`.bst`格式文件，经测试，完全适用于本科生毕业论文的格式要求。

文件`THSIS_csu.pdf`对论文中常见的各类格式（列表、脚注、程序代码、目录、交叉引用、文献格式及引用、公式、多种表格和多种图片格式）进行了详细说明，适用于对$\LaTeX$具有一定程度了解的读者。

- Maintainer : Chai Xingtao
- Email : xtChai1126@gmail.com

## 使用指南

1.  文件`附件7：中南大学毕业设计（论文）模板.docx`为原Word模板；
2.  文件`THSIS_csu.tex`为主源文件，主要包括导言区及各副源文件的引用。在使用时，请**编译**此文件；
3.  请在文件`BasicInformation.tex`中更改编辑论文扉页上论文标题等基本信息；
4.  请在文件`abstract.tex`中更改编辑论文标题和中、英文摘要；
5. 请在文件`body.tex`中更改编辑文章正文；
6. 请在文件`appendix.tex`中更改编辑论文附录；
7.  文件`THSIS_csu.pdf`为本论文模板的更为具体详细的使用说明，当然，该文件本身就是根据论文模板编译得来的；
8.  文件`gbt7714.sty`、`gbt7714-plain.bst`和`gbt7714-unsrt.bst`是符合国家标准GB/T 7714-2015的文献格式引用宏包和格式文件，在使用过程中请保持该三个文件与所有`.tex`文件在同一文件夹下；
9.  文件夹`literature`存放文献数据库`.bib`文件；
10.  文件夹`picture`存放论文中引用的图片。

# 引用参考

文件`gbt7714.sty`、`gbt7714-plain.bst`和`gbt7714-unsrt.bst`来源于GitHub项目：GB/T 7714-2015 BibTeX Style，https://github.com/CTeX-org/gbt7714-bibtex-style