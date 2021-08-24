### The annotation for MAsked FAce

The global spread of the COVID-19 coronavirus pandemic has led to numerous consequences in our everyday life, including the emergency of a social distance and a ``mask`` culture. This repository are proposed the annotation for ``MAsked FAce`` (MAFA (Ge et al., 2017)) suitable for the implementation of methods for tracking the presence/absence of a protective mask on people's faces.

MAFA contains 30,811 images, 35,806 detected faces belong to the ``masked face`` class.  MAFA was divided into train and test sets. Train set contains 25876 images files, test set - 4935 images files. 
Despite the fact that to date the MAFA database is the largest among counterparts, it has a serious drawback: presented labels are incorrect since any overlap of the face is considered as the ``masked face`` class, it is also worth noting that there are no  clear labels, for example, ``protective mask``, ``microphone`` or  ``clown nose``, which means that for more correct use of it, repeated manual annotation is necessary. The annotation of the train and test sets were performed according to the following rules:

− ``Unmasked face``, i.e. mouth and nose are opened (0 class);

− ``Masked face``, i.e. mouth and nose are closed with a ``protective mask`` (1 class);

− ``Incorrectly masked face``, i.e. mouth or nose is closed with a ``protective mask`` (2 class);

− ``Overlap with another object``, i.e. it can be a phone, a fruit, a book, a hand, etc. (3 class).

The ``protective mask`` class includes various medical masks, respirators, colorful masks, scarves, etc. This rules are proposed in paper (Ruymina al., 2021).

### Table. Number of samples in train and test sets

| Set | 0 class | 1 class | 2 class | 3 class |
| - | ---- | ---- | ---- | ---- |
| Train| 1644| 23889 | 715 | 3204| 
| Test| 2470 | 5140 | 192 | 2203|

### Links to papers

- [Ge, S., Li, J., Ye, Q., Luo, Z., 2017: Detecting masked faces in the wild with lle-cnns. IEEE Conference on Computer Vision and Pattern Recognition, CVPR-2017, Honolulu, HI, 2682-2690.](https://openaccess.thecvf.com/content_cvpr_2017/html/Ge_Detecting_Masked_Faces_CVPR_2017_paper.html)
- [Ryumina, E., Ryumin, D., Ivanko, D., Karpov, A. 2021: A Novel Method for Protective Face Mask Detection Using Con-volutional Neural Networks and Image Histograms. International Archives of the Photogrammetry Remote Sensing and Spatial Information Sciences, ISPRS Archives, XLIV-2/W1-2021, 177-182. doi.org/10.5194/isprs-archives-XLIV-2-W1-2021-177-2021.](https://doi.org/10.5194/isprs-archives-XLIV-2-W1-2021-177-2021)