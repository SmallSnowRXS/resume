# Resume 中文简历模板

做简历的时候找了很多模板，https://github.com/fky2015/resume-ng 是最满意的，简约大气。原项目还有其他版本也很不错。

在原项目的基础上，我增加了支持 bib 的论文成果展示，可以方便地导入参考文献。此外，还支持作者名字加粗显示。如果是英文论文也是 OK 的。如果你使用原作者提供的 Overleaf 链接 https://www.overleaf.com/read/ygxtzycvwyqm 来创建自己的简历，只需要创建 publications.bib 文件把自己的 bib 文献条目放进去，然后在简历中添加如下部分：

```
\section{论文成果}
\renewcommand\refname{\vskip -0.305cm}
\bibliographystyle{unsrt}
\bibliography{publications}
\nocite{*}
```
