# Paper
<img align="left" src="https://github.com/PhoebusSi/VQA-VS-homepage/raw/main/VS.jpg" width = "155" height = "85"/>
&emsp;**Language Prior Is Not the Only Shortcut: A Benchmark for Shortcut Learning in VQA**    
&emsp;[<font size=2>Qingyi Si</font>](https://phoebussi.github.io/siqingyi/)<font size=2>, Fandong Meng, Mingyu Zheng, Zheng Lin</font> 
&emsp;<font size=2>Yuanxin Liu，Peng Fu, Yanan Cao, Weiping Wang, Jie Zhou</font> 
<!-- &emsp;<font size=2>Institute of Information Engineering, Chinese Academy of Sciences</font>  -->
<font size=2>Conference on Empirical Methods in Natural Language Processing</font> <font size=2>(EMNLP’2022, Findings)</font> 

[ [Arxiv](https://arxiv.org/abs/2210.04692) \| [github](https://github.com/PhoebusSi/VQA-VS) \| [paperwithcode](https://paperswithcode.com/dataset/vqa-vs) \]

# Data
The current OOD benchmark VQA-CP v2 only considers one type of shortcut (from question type to answer) and thus still cannot guarantee that the modelrelies on the intended solution rather than a solution specific to this shortcut. To overcome this limitation, VQA-VS proposes a new dataset that considers varying types of shortcuts by constructing different distribution shifts in multiple OOD test sets. In addition, VQA-VS overcomes three troubling practices in the use of VQA-CP v2, e.g., selecting models using OOD test sets, and further standardize OOD evaluation procedure. VQA-VS provides a more rigorous and comprehensive testbed for shortcut learning in VQA. 

## The VQA-VS dataset is provided below.
<!-- <font face="黑体" color=green size=2>VQA-VS Annotations</font>｜ <font face="黑体" color=green size=2>VQA-VS Questions</font> -->
VQA-VS Annotations | VQA-VS Questions
-|-
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
```

## Input Questions Format
```
{"image_id": 458752, "question": "What color is the players shirt?", "question_id": 458752002}
```
## Annotations Format
```
{"question_type": "what color is the", "multiple_choice_answer": "red", 
"answers": [
  {"answer": "red", "answer_confidence": "yes", "answer_id": 1}, 
  {"answer": "red", "answer_confidence": "yes", "answer_id": 2}, 
  {"answer": "red & white", "answer_confidence": "yes", "answer_id": 3}, 
  {"answer": "black", "answer_confidence": "no", "answer_id": 4}, 
  {"answer": "red", "answer_confidence": "yes", "answer_id": 5}, 
  {"answer": "red", "answer_confidence": "yes", "answer_id": 6}, 
  {"answer": "red", "answer_confidence": "yes", "answer_id": 7}, 
  {"answer": "red", "answer_confidence": "maybe", "answer_id": 8}, 
  {"answer": "red", "answer_confidence": "yes", "answer_id": 9}, 
  {"answer": "red and white", "answer_confidence": "yes", "answer_id": 10}], 
  "image_id": 262146, "answer_type": "other", "question_id": 262146002}
```
<font color=red>question_type</font>: <font size=2>type of the question determined by the first few words of the question. For details, please see </font>[<font size=2>README.</font>](https://github.com/VT-vision-lab/VQA/raw/master/README.md)

<font color=red>answer_type</font>: <font size=2>type of the answer -- "yes/no", "number", and "other".</font>

<font color=red>multiple_choice_answer</font>: <font size=2>correct multiple choice answer.</font>

<font color=red>answer_confidence</font>: <font size=2>subject's confidence in answering the question. For details, please see the </font>[<font size=2>VQA paper.</font>](http://arxiv.org/pdf/1505.00468v6.pdf)

# Dataset Analysis
## Motivation of our benchmark.
![image](https://github.com/PhoebusSi/VQA-VS/raw/main/figures/motivations.jpg)
Figure 1: (a) The acc improvement of LMH over its backbone model UpDn on nine OOD test sets. (The acronyms, like QT, are defined in Sec. 3.2 of paper) (b) Solutions possibly learnd by models.

As shown in Fig. 1(a), despite performing well on VQA-CP v2, the debi- asing method LMH (Clark et al., 2019), can only boost its backbone model UpDn on few certain OOD test sets while fails to generalize to other OOD sets. This shows VQA-CP v2 cannot identify whether the models rely on other types of short- cuts (e.g., correlations between visual objects and answers). Therefore, as shown in Fig. 1(b), more OOD test sets are needed to measure the reliance of the model on different types of shortcuts. As the performance on more OOD test sets is improved simultaneously, the more confidently can the model be deemed to have learned the intended solution.

## Data statistics.
![image](https://github.com/PhoebusSi/VQA-VS/raw/main/figures/data-statistics.jpg)
Table 1: Data statistics of VQA-VS (bold) and nine shortcuts.

Tab. 1 shows the data statistics of VQA-VS, and the group and sample statistics for each shortcut. The total numbers of groups vary significantly among different shortcuts (65 ~183683).


## Relevance of Shortcuts & Overlaps Between OOD Test Sets.
![image](https://github.com/PhoebusSi/VQA-VS/raw/main/figures/relevance-overlaps.jpg)
Figure 3: (a) The Jaccard Similarity Coefficients be- tween all head splits of the training set. The higher the value, the closer the two types of shortcuts. (b) The co-incidence ratios between all OOD test sets. The square with coordinate (KO, QT) denotes that the proportion of the duplicate samples between KO and QT in the QT OOD test set.

Relevance of Shortcuts. The samples of head splits, which are frequent and dominating the model training (Goyal et al., 2017), are the main cause of the shortcuts in training data. Therefore, we use the relevance of two shortcuts’ head splits in training set to analyze the relevance of two short- cuts. As shown in Fig. 3(a), the Jaccard Simliarity Coefficient between QT and KO shortcuts is obvi- ously higher. A possible explanation is that there is a strong correlation between question types and key-object types. For example, the question type "who is" and key-object type "person" co-occurfrequently. Moreover, the KOP shortcut is closely relevant with KO because the shortcut concepts of KOP are involved with KO concepts. Consequently, QT is highly relevant with KOP. The relevance ex- tends to some of the other shortcuts in the same way, which can explain the light pink squares of Fig. 5(a). Differently, the coarse-grained QT and the fine-grained QT+KW have a low relevance even though the concepts of QT+KW include the QT concepts. This shows the necessity of introducing more fine-grained shortcuts which focus on a large number of concepts. 

Overlaps Between OOD Test Sets. Intuitively, if two OOD test sets share too many samples, there is no need to separately evaluate the model on the two OOD test sets. To rule out this possibility and valid the necessity of nine OOD test sets, we count the numbers of duplicate samples between all OOD test sets and compute corresponding coincidence rates. From Fig. 3(b), we find that the coincidence ratios between most OOD test sets are low. Al- though (KO, QT) has a high coincidence rate 0.79, the coincidence rate of (QT, KO) is much lower, 0.49, which shows the KO has a different emphasis compared with QT.

## Comparison of our benchmark and VQA-CP v2.
![image](https://github.com/PhoebusSi/VQA-VS/raw/main/figures/comparison.jpg)
Table 2: Comparison of our benchmark and VQA-CP v2. The results are computed over four seeds.


## Performance of SoTA debiasing methods.
![image](https://github.com/PhoebusSi/VQA-VS/raw/main/figures/sotas.jpg)
Table 3: Performance of SoTA debiasing methods.


## Reference
Coming Soon!


