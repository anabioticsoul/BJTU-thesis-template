### 北京交通大学研究生论文模板

学校的官方模板过于陈旧，且与word版本有较大差距。

本模板基于 [北交官方模板](https://gs.bjtu.edu.cn/cms/item/477.html) 修订，编译无报错，下载即用。相较于原版，本模板优化了对研究生类别的支持，优化了学校log的分辨率（使用的是学校官方提供的latex模板文件）


本模板支持以下选项：
- 学术型硕士研究生 (AcMaster)
- 专业型硕士研究生 (EnMaster)
- 学术型博士研究生 (Doctor)

#### 使用前
##### 必须修改
请在main.tex中修改如下参数

e.g.
```latex
\documentclass[AcMaster]{BJTU-thesis}      %%%    选择模板为学硕
```

##### 单面论文和双面论文
1. 请在main.tex中加入`twoside`参数来启用双面论文模板

```latex
\documentclass[AcMaster,twoside]{BJTU-thesis} 
```

2. 在`BJTU-thesis.cls`文件中将单面打印换成双面打印

#### 编译前
请选择`XeLaTeX`作为编译器进行编译，Overleaf和TeX live都可以使用

论文模板由[bigworldsmall](https://github.com/bigworldsmall) 提供
