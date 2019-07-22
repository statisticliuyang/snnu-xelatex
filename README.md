# Snnu-XeLaTex
XeLaTex for Snnu.

![image](https://github.com/statisticliuyang/box/blob/master/fm1.jpg)
<!--  __  __    _         _____           -->
<!--  \ \/ /___| |    __ |_   _|____  __  -->
<!--   \  // _ \ |   / _` || |/ _ \ \/ /  -->
<!--   /  \  __/ |__| (_| || |  __/>  <   -->
<!--  /_/\_\___|_____\__,_||_|\___/_/\_\  -->
 
<!--   __               -->
<!--  / _|  ___  _ __   -->
<!--  | |_ / _ \| '__|  -->
<!--  |  _| (_) | |     -->
<!--  |_|  \___/|_|     -->
                
<!--   ____  _   _ _   _ _   _   -->
<!--  / ___|| \ | | \ | | | | |  -->
<!--  \___ \|  \| |  \| | | | |  -->
<!--   ___) | |\  | |\  | |_| |  -->
<!--  |____/|_| \_|_| \_|\___/   -->

## Main Files Introduct

|file name|introduct|
|:--------:|:--------:|
|**snnu.tex**|*the main tex file which you need edit with UTF-8*|
|**snnu.bib**|*the bib file saving the list of your reference cites*|
|**snnu.bst**|*the bst file setting a type of reference format*|
|**snnu.jpg**|*the mark of snnu in cover*|
|**dt.jpg**|*some example in the article*|
|**slashbox.stl**|*a configuration file you may need*|
|**.gitigonre**|*igonre the file created in translate and edit when upload to GitHub*|

##  Compatibility
you can edit and tanslate in Ctex,TexLive eta by your PC,pad or smart phone
[![here is an example in pad](https://raw.githubusercontent.com/statisticliuyang/box/master/QUIK_20190721_140819.mp4)].

<!--![image](https://github.com/statisticliuyang/box/blob/master/Video_20190721_044317_880.gif)-->

## Reference

we have two differenct types of reference format

### Self-Set Reference Format
you an use the first type of reference format by these 
``` tex
\vskip 0.15cm
{\parindent=5pt
\def\toto#1#2{\centerline{\hbox  to 0.7cm{[#1]\hss}
\parbox[t]{15cm}{#2}\vspace{0.05cm}}}
\toto{1}{李子奈, 潘文卿. 计量经济学[M]. 北京：高等教育出版社, 2007.}
\toto{2}{Li Y, Chen Y Q, Podlubny I. Residual analysis of  linear systems[J]. Automatica, 2009, 45(8):1965-1969.}
}
```
![image](https://github.com/statisticliuyang/box/blob/master/re1.png)

### Use natbib package

to use another type of reference format you should make sure **snnu.bib** and **snnu.bst** in your root file 
and then
use natbib package
```tex
\usepackage[square,numbers,sort&compress]{natbib} %参考文献设置
\setlength{\bibsep}{0ex}
\bibliographystyle{snnu}
```
you can add or change the reference information by editing **snnu.bib** ,just like this
```tex
@article{xiao2013predicting,
	title={Predicting the HIV/AIDS epidemic and measuring the effect of mobility in mainland China},
	author={Xiao, Yanni and Tang, Sanyi and Zhou, Yicang and Smith, Robert J and Wu, Jianhong and Wang, Ning},
	journal={Journal of Theoretical Biology},
	volume={317},
	pages={271--285},
	year={2013}}
```
use these in **snnu.tex** can cite this reference
```tex
\cite{xiao2013predicting}
```
in the end of article you can create a list of reference cite by these
```tex
\bibliography{snnu}
```
![image](https://github.com/statisticliuyang/box/blob/master/re2.png)

more information of setting in [![here](https://raw.githubusercontent.com/statisticliuyang/box/master/natbib-zh.pdf)]

## Header and Footer

### First type

![image](https://github.com/statisticliuyang/box/blob/master/hya.png)

### Second type

![image](https://github.com/statisticliuyang/box/blob/master/hyb.png)

## Proof and Othor Environment 

![image](https://github.com/statisticliuyang/box/blob/master/penv.png)

## Figure

![image](https://github.com/statisticliuyang/box/blob/master/t1.png)

![image](https://github.com/statisticliuyang/box/blob/master/t2.png)

## Table

![image](https://github.com/statisticliuyang/box/blob/master/bg.png)

## Code

![image](https://github.com/statisticliuyang/box/blob/master/code.png)

## Contents

![image](https://github.com/statisticliuyang/box/blob/master/ttl.png)

## Abstract

![image](https://github.com/statisticliuyang/box/blob/master/ttc1.png)

![image](https://github.com/statisticliuyang/box/blob/master/tte1.png)

![image](https://github.com/statisticliuyang/box/blob/master/ttc2.png)

![image](https://github.com/statisticliuyang/box/blob/master/tte2.png)
