

### Beijing Jiaotong University Graduate Thesis Template

The school's official template is too outdated and has significant discrepancies with the Word version.

This template is revised based on the [BJTU Official Template](https://gs.bjtu.edu.cn/cms/item/477.html), compiles without errors, and is ready to use upon download. Compared to the original, this template optimizes support for different graduate categories and improves the resolution of the school logo (using the LaTeX template files officially provided by the school).


This template supports the following features:
- Supported template types:
1. Academic Master's Student (AcMaster)
2. Professional Master's Student (EnMaster)
3. Doctoral Student (Doctor)
- Single-sided and double-sided thesis templates

#### Before Use
##### Required Modifications
Please modify the following parameters in `main.tex`:

```latex
\documentclass[AcMaster]{BJTU-thesis}      %%%    选择模板为学硕
```

##### Single-sided and Double-sided Thesis
1. Add the `twoside` parameter in `main.tex` to enable the double-sided thesis template:

```latex
\documentclass[AcMaster,twoside]{BJTU-thesis} 
```

2. Change the single-sided printing setting to double-sided printing in the `BJTU-thesis.cls` file.

##### Chinese Font Bold Issue
Overleaf and TeXstudio load different packages. When bolding Chinese text in TeXstudio, you need to include `\songti`. (Using `\textbf` alone will not work for bolding Chinese characters.)
```latex
\songti\textbf{粗体}
```

#### Before Compilation
Please select `XeLaTeX` as the compiler. It is compatible with both Overleaf and TeX Live.

#### Acknowledgments
Special thanks to [bigworldsmall](https://github.com/bigworldsmall)
