# Snnu-XeLaTex
XeLaTex for Snnu.

<!--![image](https://github.com/statisticliuyang/box/blob/master/fm1.jpg)-->
![image](http://img02.sogoucdn.com/app/a/100520146/ab2ff67088f4546bf2293fbf9410c050)
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

(Compile with in Android)
![image](http://img02.sogoucdn.com/app/a/100520146/bb31d298a440adf4fc84096035d32f6f)

<!--![image](http://img03.sogoucdn.com/app/a/100520146/70a370786389b2c7bd443c1548b882db)-->






## Reference

we have two differenct types of reference format

### Self-Set Reference Format
you can use the first type of reference format by these 
``` tex
\vskip 0.15cm
{\parindent=5pt
\def\toto#1#2{\centerline{\hbox  to 0.7cm{[#1]\hss}
\parbox[t]{15cm}{#2}\vspace{0.05cm}}}
\toto{1}{李子奈, 潘文卿. 计量经济学[M]. 北京：高等教育出版社, 2007.}
\toto{2}{Li Y, Chen Y Q, Podlubny I. Residual analysis of  linear systems[J]. Automatica, 2009, 45(8):1965-1969.}
}
```
![image](http://img01.sogoucdn.com/app/a/100520146/644b9f6b51770408f7b07331407b4cba)
<!--![image](https://github.com/statisticliuyang/box/blob/master/re1.png)-->
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
![image](http://img01.sogoucdn.com/app/a/100520146/f674ed23dbd7e4747e44c001bb64cdf5)
<!--![image](https://github.com/statisticliuyang/box/blob/master/re2.png)-->

more information of setting in [![here](https://github.com/statisticliuyang/box/blob/master/natbib-zh.pdf)]

## Header and Footer

### First type

![image](http://img02.sogoucdn.com/app/a/100520146/7f6394e18e81f93d19443834b9856925)

### Second type

![image](http://img02.sogoucdn.com/app/a/100520146/9da2484ff9e23703c55dadc0b40cc4b4)

## Proof and Other Environment 

![image](http://img03.sogoucdn.com/app/a/100520146/06dbc4d96cf8a3ec76735632a2ad925c)

## Figure

![image](http://img02.sogoucdn.com/app/a/100520146/ec28dfd1316bd3de664b4b011b2337af)

![image](http://img04.sogoucdn.com/app/a/100520146/f6e859cc2ceb841090c2fab3f4bf3c6f)

## Table

![image](http://img02.sogoucdn.com/app/a/100520146/53fa6f53187cc0733c63ce4b543a1978)

## Code

![image](http://img02.sogoucdn.com/app/a/100520146/9587ad45903a134c646584d225a81827)

## Contents

![image](http://img04.sogoucdn.com/app/a/100520146/53ccf3cf3b4d3d322b3ad00559f21632)

## Abstract

![image](http://img03.sogoucdn.com/app/a/100520146/64851a1eca49a8bb3f9d8f021f9ef94c)

![image](http://img02.sogoucdn.com/app/a/100520146/c489f7fa34f62575d4d1c329eab1bbeb)

![image](http://img02.sogoucdn.com/app/a/100520146/70d398bdac55a40548d5178d438c6bf2)

![image](http://img01.sogoucdn.com/app/a/100520146/41343cb3c194a9feac4ac185a8a11575)
