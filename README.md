# Bilingual Simple ATS-Friendly Resume Template 中英双语简历标准模板
一份中英双语简历样本模板，同时编辑中英文双语信息，一键导出中英文简历。信息密度高，易于浏览和电子扫描。适用于有双语简历需求的社招校招小伙伴。
## 中文简历样本
![中文简历](https://github.com/mimicji/Bilingual-Resume-Template/releases/download/1.0/Resume_Template_CN.jpg)

## 英文简历样本
![英文简历](https://github.com/mimicji/Bilingual-Resume-Template/releases/download/1.0/Resume_Template_EN.jpg)

## 使用方法
- 使用XeLaTeX编译
- 仅需修改main.tex文件
- 自main.tex文件的第50行起，开始你的简历撰写。`\CN{}`中填写中文信息，`\EN{}`中填写英文信息。
- 导出中文简历时，确保第11行未被注释
```
\usepackage[Chinese]{languageSelection} % 导出中文版
```
且第12行为已被注释的状态
```
%\usepackage[English]{languageSelection} % 导出英文版
```
- 导出英文简历时反之，确保第12行已被注释
```
%\usepackage[Chinese]{languageSelection} % 导出中文版
```
且第12行为未被注释的状态
```
\usepackage[English]{languageSelection} % 导出英文版
```
