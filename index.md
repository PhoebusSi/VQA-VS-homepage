# Paper
<img align="left" src="https://github.com/PhoebusSi/VQA-VS-homepage/blob/main/VS.jpg" width = "155" height = "85"/>
&emsp;**Language Prior Is Not the Only Shortcut: A Benchmark for Shortcut Learning in VQA**    
&emsp;[<font size=2>Qingyi Si</font>](https://phoebussi.github.io/siqingyi/)<font size=2>, Fandong Meng, Mingyu Zheng, Zheng Lin</font> 
&emsp;<font size=2>Yuanxin Liu，Peng Fu, Yanan Cao, Weiping Wang, Jie Zhou</font> 
<!-- &emsp;<font size=2>Institute of Information Engineering, Chinese Academy of Sciences</font>  -->
<font size=2>Conference on Empirical Methods in Natural Language Processing</font> <font size=2>(EMNLP’2022, Findings)</font> 

[ [Arxiv](https://arxiv.org/abs/2210.04692) \| [github](https://github.com/PhoebusSi/VQA-VS) \| [paperwithcode](https://paperswithcode.com/dataset/vqa-vs) \]

# Data
The current OOD benchmark VQA-CP v2 only considers one type of shortcut (from question type to answer) and thus still cannot guarantee that the modelrelies on the intended solution rather than a solution specific to this shortcut. To overcome this limitation, VQA-VS proposes a new dataset that considers varying types of shortcuts by constructing different distribution shifts in multiple OOD test sets. In addition, VQA-VS overcomes three troubling practices in the use of VQA-CP v2, e.g., selecting models using OOD test sets, and further standardize OOD evaluation procedure. VQA-VS provides a more rigorous and comprehensive testbed for shortcut learning in VQA. 

## The VQA-VS dataset is provided below.
<font face="黑体" color=green size=2>VQA-VS Annotations</font> | <font face="黑体" color=green size=2>VQA-VS Questions</font>
:-: | :-: 
[Training Annotations](https://drive.google.com/file/d/1gDIUlSFHUKDpP5rYrIL3y8ER-RFmawbv/view?usp=sharing) | [Training Questions](https://drive.google.com/file/d/1VtPYUq7bSpozAvEYFiBewppQSiBDcSu2/view?usp=sharing)
[Validation Annotations](https://drive.google.com/file/d/1_1fPVpdwdCzYjcQNhj9Cln9btTXI-mov/view?usp=sharing) | [Validation Questions](https://drive.google.com/file/d/17sxbQFow3I-cSiwyVcmQ9AdlUDBKp1uM/view?usp=sharing)
[IID-Test Annotations](https://drive.google.com/file/d/1aNlIQBQ5mIF9M8dQ55UOxbw46sAiwYo4/view?usp=sharing) | [IID-Test Questions](https://drive.google.com/file/d/1Bn1jkyBWONGHFrAM8rh6L8NDdIVe7j5v/view?usp=sharing)
[OOD-QT-Test Annotations](https://drive.google.com/file/d/1q928zVC0M14rWkuk9hLymW9RddD58bV4/view?usp=sharing) | [OOD-QT-Test Questions](https://drive.google.com/file/d/1ONNpoYpqbqXS1kyGkS09Hq8m1OVCKfqt/view?usp=sharing)
[OOD-KW-Test Annotations](https://drive.google.com/file/d/19AzV4Q4X8_zITbAkFUBSOzbGIrA3Pxo3/view?usp=sharing) | [OOD-KW-Test Questions](https://drive.google.com/file/d/1wbrj7NfXugQqgvI03XFm_cm325Bn0k0H/view?usp=sharing)
[OOD-KWP-Test Annotations](https://drive.google.com/file/d/1Z0Ga2SXkIwkWibpX12MBOFo5SGvr1Yu4/view?usp=sharing) | [OOD-KWP-Test Questions](https://drive.google.com/file/d/1bhVr54lqHO9rQM8vKh3Z2F3G9d98M5hr/view?usp=sharing)
[OOD-KO-Test Annotations](https://drive.google.com/file/d/1gbJJhAoCGlbK3lPeaPgTGwvDFLgEO-1q/view?usp=sharing) | [OOD-KO-Test Questions](https://drive.google.com/file/d/1d-M4qBAwSpDaLnh2gjO61B_gspmzCNO7/view?usp=sharing)
[OOD-KOP-Test Annotations](https://drive.google.com/file/d/1PGsvmGLO5kyn-pqqPtsKPcK2vlaFwW_Y/view?usp=sharing) | [OOD-KOP-Test Questions](https://drive.google.com/file/d/14Cj03Xkpa0J8DcN_UShQW8ZMZuLvlOSC/view?usp=sharing)
[OOD-QT+KO-Test Annotations](https://drive.google.com/file/d/1J_YoK-miWtxGQs-lrR85WiSFzcneUTKN/view?usp=sharing) | [OOD-QT+KO-Test Questions](https://drive.google.com/file/d/1RW-7ZsE50zN83OJnMs5SrPIxIagkfew-/view?usp=sharing)
[OOD-KW+KO-Test Annotations](https://drive.google.com/file/d/1jK35yUPVNhSKIHJgOVRzO-96QPgcQORA/view?usp=sharing) | [OOD-KW+KO-Test Questions](https://drive.google.com/file/d/13N0_sow6xOLzmz_OEgAiqgAKBbwo0y-d/view?usp=sharing)
[OOD-QT+KW+KO-Test Annotations](https://drive.google.com/file/d/1V1IgxbQsJ17c5gcy5K0gW-hOFdPgr6-H/view?usp=sharing) | [OOD-QT+KW+KO-Test Questions](https://drive.google.com/file/d/1dwrG9apK64TfY3L9zNHfkYYu0RZC_kBY/view?usp=sharing)

For simplicity, the whole dataset can be download [here](https://drive.google.com/drive/folders/1i6xqke5X5GoQ8YGoNcs3rtMsDtgs4OLG?usp=sharing).

## Other approaches to download our dataset.
The above links for downloading are based on Google Drive. If Google Drive is not avaliable for you, there are two approaches to downlownd our dataset:
### Zip Compressed File
You can download the compressed files from our github [repository](https://github.com/PhoebusSi/VQA-VS/tree/main/data) according to the dir structure of **data** folder, and extract them separately.
### Contact me
You can contact me by email **siqingyi@iie.ac.cn**, and I will send the complete dataset to you.

## Matters needing attention.
### 1. Inference and Test
Note that all OOD test sets are the subsets of the IID test set. Therefore, you can choose to predict the answers for the questions of each OOD test set seperately to get their test accuracy, or you can choose to predict the answers for the questions of the IID test set directly, and then collect the corresponding prediction results according to the question-id of each OOD test set to get their test accuracy.
### 2. Images of VQA-VS
Note that our proposed benchmark is re-organized from VQA v2, therefore, the images in the VQA-CP v1 and v2 datasets (both train and test) are from [training](http://images.cocodataset.org/zips/train2014.zip) and [validation](http://images.cocodataset.org/zips/val2014.zip) sets of the COCO dataset.

For simplicity, same as the practice for VQA v2 or VQA-CP v2, you can also download the image features (extracted by FasterRCNN) by:
```
wget -P https://imagecaption.blob.core.windows.net/imagecaption/trainval_36.zip
unzip coco/trainval_36.zip -d image_features/
'''





