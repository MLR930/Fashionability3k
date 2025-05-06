# Fashionability3k

 [[DOWNLOAD]](https://drive.google.com/file/d/1_VPkPoPNM7n0X53IlIB3wvL5IlCNy63S/view?usp=drive_link)

Dataset provided by us for ACADEMIC USAGE ONLY. If you want to use them in commercial products, please kindly send an email to lynn.ma.930@gmail.com for further inquiry.

:bulb: **Brief Intro**

We introduce a new Fashionability3k dataset (each outfit including clothes and shoe but without accessories) specifically targeting the global attribute (fashionability) comparison task based upon the online fashion-oriented community website SHOPLOOK.

:bulb: **Key Notes**
- Labels in this dataset are all manually annotated;
- Label=2: outfit<sub> i </sub> is more fashionable than outfit<sub> j </sub>;
- Label=1: outfit<sub> i </sub> and outfit<sub> j </sub> are equally fashionable;
- Label=0: outfit<sub> i </sub> is less fashionable than outfit<sub> j </sub>;
- 10bins.txt: We adopt the ten‑bin method (Altwaijry & Belongie, 2013) to group samples by fashionability and sharply cut down the number of required comparisons. 10 bins are being used to emulate fashion levels 1 to 10, where bin10 ≻ bin9 ≻ ...... ≻ bin2 ≻ bin1.


:bulb: **Reference**

Please cite the following reference paper when this dataset is used in any academic and research reports.

**Ordinal focal loss: A relative fashionability ranking learning method** [[pdf]](https://www.sciencedirect.com/science/article/pii/S0306457325001463)

```bib
@article{MA2025104205,
title = {Ordinal focal loss: A relative fashionability ranking learning method},
journal = {Information Processing & Management},
volume = {62},
number = {5},
pages = {104205},
year = {2025},
issn = {0306-4573},
doi = {https://doi.org/10.1016/j.ipm.2025.104205},
url = {https://www.sciencedirect.com/science/article/pii/S0306457325001463},
author = {Ling Ma and Chuhang Zou and Ziyi Guo and Tao Li and Zheng Liu and Fengyuan Zou}
}
```
