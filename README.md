# awesome video object/instance segmentation
A curated list of awesome video object/instance segmentation resources.

*Last updated: 2020/12/17*

## What is video object segmentation and video instance segmentation?

Video object segmentation is a binary labeling problem aiming to separate foreground object(s) from the background region of a video.

Video instance segmentation not only need to segment foreground object(s)/instance(s), but also have to identify the category of each object and keep tracking objects across frames.


## Dataset
- DAVIS [`[Download]`](https://davischallenge.org/davis2017/code.html#semisupervised)
- YouTube-VOS and -VIS [`[Download]`](https://youtube-vos.org/dataset/vis/)


## Table of Contents
- [Video object segmentation](#video-object-segmentation)
- [Video instance segmentation](#video-instance-segmentation)


## Video object segmentation
- A Benchmark Dataset and Evaluation Methodology for Video Object Segmentation | **[CVPR' 16]** |[`[pdf]`](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Perazzi_A_Benchmark_Dataset_CVPR_2016_paper.pdf)
- (**OSVOS**) One-Shot Video Object Segmentation | **[CVPR' 17]** |[`[pdf]`](https://openaccess.thecvf.com/content_cvpr_2017/papers/Caelles_One-Shot_Video_Object_CVPR_2017_paper.pdf) | [`[code]`](https://github.com/kmaninis/OSVOS-PyTorch)
- (**MaskTrack**) Learning Video Object Segmentation from Static Images | **[CVPR' 17]** |[`[pdf]`](https://openaccess.thecvf.com/content_cvpr_2017/papers/Perazzi_Learning_Video_Object_CVPR_2017_paper.pdf) | [`[code]`](https://github.com/omkar13/masktrack)
- (**OSVOS-S**) Video object segmentation without temporal information | **[TPAMI' 18]** |[`[pdf]`](https://arxiv.org/pdf/1709.06031.pdf)
- (**Lucid**) Lucid Data Dreaming for Video Object Segmentation | **[IJCV' 19]** |[`[pdf]`](https://link.springer.com/article/10.1007/s11263-019-01164-6) | [`[code]`](https://github.com/yelantf/pyLucid)
- (**PTSNet**) Proposal, Tracking and Segmentation (PTS): A Cascaded Network for Video Object Segmentation | **[arxiv' 19]** |[`[pdf]`](https://arxiv.org/pdf/1907.01203v2.pdf) | [`[code]`](https://github.com/sydney0zq/PTSNet)
- (**SiamMask**) Fast Online Object Tracking and Segmentation: A Unifying Approach | **[CVPR' 19]** |[`[pdf]`](https://arxiv.org/pdf/1812.05050.pdf) | [`[code]`](https://github.com/foolwood/SiamMask)
- (**RANet**) RANet: Ranking Attention Network for Fast Video Object Segmentation | **[ICCV' 19]** |[`[pdf]`](https://arxiv.org/pdf/1908.06647.pdf) | [`[code]`](https://github.com/Storife/RANet)
- (**FEELVOS**) Feelvos: Fast end-to-end embedding learning for video object segmentation | **[CVPR' 19]** |[`[pdf]`](https://arxiv.org/pdf/1902.09513v2.pdf) | [`[code]`](https://github.com/kim-younghan/FEELVOS)
- (**STCNN**) Spatiotemporal CNN for Video Object Segmentation | **[CVPR' 19]** |[`[pdf]`](https://arxiv.org/pdf/1904.02363v1.pdf) | [`[code]`](https://github.com/longyin880815/STCNN)
- (**MHP-VOS**) MHP-VOS: Multiple Hypotheses Propagation for Video Object Segmentation | **[CVPR' 19]** |[`[pdf]`](https://arxiv.org/pdf/1904.08141v1.pdf) | [`[code]`](https://github.com/shuangjiexu/MHP-VOS)
- (**A-GAME**) A Generative Appearance Model for End-to-end Video Object Segmentation | **[CVPR' 19]** |[`[pdf]`](https://arxiv.org/pdf/1811.11611v2.pdf) | [`[code]`](https://github.com/joakimjohnander/agame-vos)
- (**RVOS**) RVOS: End-to-End Recurrent Network for Video Object Segmentation | **[CVPR' 19]** |[`[pdf]`](https://arxiv.org/pdf/1903.05612v2.pdf) | [`[code]`](https://github.com/imatge-upc/rvos)
- (**CapsuleVOS**) CapsuleVOS: Semi-Supervised Video Object Segmentation Using Capsule Routing | **[ICCV' 19]** |[`[pdf]`](https://arxiv.org/pdf/1910.00132v1.pdf) | [`[code]`](https://github.com/KevinDuarte/CapsuleVOS)
- (**STM**) Video Object Segmentation using Space-Time Memory Networks | **[ICCV' 19]** |[`[pdf]`](https://openaccess.thecvf.com/content_ICCV_2019/papers/Oh_Video_Object_Segmentation_Using_Space-Time_Memory_Networks_ICCV_2019_paper.pdf) | [`[code]`](https://github.com/seoungwugoh/STM)
- (**e-OSVOS**) Make One-Shot Video Object Segmentation Efficient Again | **[NIPS' 20]** |[`[pdf]`](https://proceedings.neurips.cc//paper/2020/file/781397bc0630d47ab531ea850bddcf63-Paper.pdf) | [`[code]`](https://github.com/dvl-tum/e-osvos)
- (**GC**) Fast Video Object Segmentation using the Global Context Module | **[CVPR' 20]** |[`[pdf]`](https://arxiv.org/pdf/2001.11243v2.pdf)
- (**FRTM-VOS**) Learning Fast and Robust Target Models for Video Object Segmentation | **[CVPR' 20]** |[`[pdf]`](https://arxiv.org/pdf/2003.00908v2.pdf) | [`[code]`](https://github.com/andr345/frtm-vos)
- (**PMVOS**) PMVOS: Pixel-Level Matching-Based Video Object Segmentation | **[Arxiv' 20]** |[`[pdf]`](https://arxiv.org/pdf/2009.08855v1.pdf)
- (**CFBI**) Collaborative Video Object Segmentation by Foreground-Background Integration | **[ECCV' 20]** |[`[pdf]`](https://arxiv.org/pdf/2003.08333v2.pdf) | [`[code]`](https://github.com/z-x-yang/CFBI)
- (**TVOS**) A Transductive Approach for Video Object Segmentation | **[CVPR' 20]** |[`[pdf]`](https://arxiv.org/pdf/2004.07193v2.pdf) | [`[code]`](https://github.com/microsoft/transductive-vos.pytorch)
- (**Siam R-CNN**) Siam R-CNN: Visual Tracking by Re-Detection | **[CVPR' 20]** |[`[pdf]`](https://arxiv.org/pdf/1911.12836v2.pdf) | [`[code]`](https://github.com/VisualComputingInstitute/SiamR-CNN)
- (**MuG-W**) Learning Video Object Segmentation from Unlabeled Videos | **[CVPR' 20]** |[`[pdf]`](https://arxiv.org/pdf/2003.05020v1.pdf) | [`[code]`](https://github.com/carrierlxk/MuG)
- (**TTVOS**) TTVOS: Lightweight Video Object Segmentation with Adaptive Template Attention Module and Temporal Consistency Loss | **[arxiv' 20]** |[`[pdf]`](https://arxiv.org/pdf/2011.04445v1.pdf)




## Video instance segmentation


## Performance

**FT==Online Fine-tuning/Learning**
**OF==Optical FLow**


### DAVIS16 VAL
| Method                |year  |Technique| J      | F     | J&F   |  FPS   |
| :----:                |:----:|  :----: | :----: | :----:| :----:| :----: |
| OSVOS                 |2017  | FT      |79.8    |80.6   |80.2   | 0.1    |
| MaskTrack             |2017  | FT+OF   |79.7    |75.4   |77.6   | 0.08   |
| OSVOS-S               |2018  | FT      |85.6    |87.5   |86.6   | 0.22   |
| Lucid                 |2019  | FT+OF   |83.9    |82.0   |83.0   |        |
| SiamMask              |2019  |         |71.7    |67.8   |69.8   | 55     |
| RANet                 |2019  |         |85.5    |85.4   |85.5   | 30     |
| RANet                 |2019  | FT      |86.6    |87.6   |87.1   | 0.25   |
| FEELVOS               |2019  |         |81.1    |82.2   |81.7   | 2.2    |
| STCNN                 |2019  |         |83.8    |83.8   |83.8   |        |
| MHP-VOS               |2019  |         |87.6    |89.5   |88.6   |        |
| A-GAME                |2019  |         |81.5    |82.2   |81.9   | 15     |
| STM                   |2019  |         |88.7    |90.1   |89.4   | 6.25   |
| e-OSVOS               |2020  | FT      |86.6    |87.0   |86.8   | 0.29   |
| GC                    |2020  |         |87.6    |85.7   |86.6   | 25     |
| FRTM-VOS              |2020  |         |        |       |83.5   | 21.9   |
| PMVOS                 |2020  |         |86.1    |85.1   |85.6   | 54     |
| CFBI                  |2020  |         |88.3    |90.5   |89.4   | 5      |
| Siam R-CNN            |2020  |         |76.8    |80.4   |78.6   | 4.2    |
| MuG-W                 |2020  |         |65.7    |63.6   |64.7   |        |
| TTVOS                 |2020  |         |        |       |83.8   | 39.6   |



### DAVIS17 VAL
| Method                |year  |Technique| J      | F     | J&F   |  FPS   |
| :----:                |:----:|  :----: | :----: | :----:| :----:| :----: |
| OSVOS                 |2017  | FT      |56.6    |63.9   |60.3   | 0.1    |
| OSVOS-S               |2018  | FT      |64.7    |71.3   |68.0   | 0.22   |
| SiamMask              |2019  |         |54.3    |58.5   |56.4   | 55     |
| RANet                 |2019  |         |63.2    |68.2   |65.7   | 30     |
| FEELVOS               |2019  |         |69.1    |74.0   |71.6   | 2.2    |
| STCNN                 |2019  |         |58.7    |64.6   |61.7   |        |
| MHP-VOS               |2019  |         |73.4    |78.9   |76.2   |        |
| A-GAME                |2019  |         |68.5    |73.6   |71.1   | 15     |
| RVOS                  |2019  |         |57.5    |63.6   |60.6   |        |
| STM                   |2019  |         |79.2    |84.3   |81.8   | 6.25   |
| e-OSVOS               |2020  | FT      |74.4    |80.0   |77.2   | 0.29   |
| GC                    |2020  |         |69.3    |73.5   |71.4   | 25     |
| FRTM-VOS              |2020  |         |        |       |76.7   | 21.9   |
| PMVOS                 |2020  |         |71.2    |76.7   |74.0   | 54     |
| CFBI                  |2020  |         |79.1    |84.6   |81.9   | 5      |
| TVOS                  |2020  |         |69.9    |74.7   |72.3   | 37     |
| Siam R-CNN            |2020  |         |66.1    |75.0   |70.6   | 3.1    |
| MuG-W                 |2020  |         |54.1    |58.0   |56.1   |        |
| TTVOS                 |2020  |         |        |       |67.8   | 39.6   |



### DAVIS17 TEST
| Method                |year  |Technique| J      | F     | J&F   |  FPS   |
| :----:                |:----:|  :----: | :----: | :----:| :----:| :----: |
| OSVOS                 |2017  | FT      |47.0    |54.8   |50.9   | 0.1    |
| OSVOS-S               |2018  | FT      |52.9    |62.1   |57.5   | 0.22   |
| Lucid                 |2019  | FT+OF   |63.4    |69.9   |66.6   |        |
| SiamMask              |2019  |         |40.6    |45.8   |43.2   | 55     |
| RANet                 |2019  |         |53.4    |57.3   |55.4   | 30     |
| FEELVOS               |2019  |         |55.1    |60.4   |57.8   | 2.2    |
| MHP-VOS               |2019  |         |66.4    |72.7   |69.5   |        |
| A-GAME                |2019  |         |49.2    |55.3   |52.3   | 15     |
| CapsuleVOS            |2019  |         |47.4    |55.2   |51.3   | 13.5   |
| RVOS                  |2019  |         |47.9    |52.6   |50.3   |        |
| STM                   |2019  |         |69.3    |75.2   |72.2   | 6.25   |
| e-OSVOS               |2020  | FT      |60.9    |68.6   |64.8   | 0.29   |
| PMVOS                 |2020  |         |59.5    |65.3   |62.4   | 54     |
| CFBI                  |2020  |         |71.1    |78.5   |74.8   | 5      |
| TVOS                  |2020  |         |58.8    |67.4   |63.1   | 37     |
| Siam R-CNN            |2020  |         |48.0    |58.6   |53.3   | 3.1    |



### YouTube-VOS VAL
| Method                |year  |Technique| Overall|  FPS   |
| :----:                |:----:|  :----: | :----: | :----: |
| OSVOS                 |2017  | FT      | 58.8   | 0.1    |
| SiamMask              |2019  |         | 52.8   | 55     |
| CapsuleVOS            |2019  |         | 62.3   | 13.5   |
| e-OSVOS               |2020  | FT      | 71.4   | 0.29   |
| GC                    |2020  |         | 73.2   | 25     |
| FRTM-VOS              |2020  |         | 72.1   | 21.9   |
| PMVOS                 |2020  |         | 68.6   | 54     |
| CFBI                  |2020  |         | 81.4   | 5      |
| TVOS                  |2020  |         | 67.8   | 37     |




### YouTube-VIS
| Method                | Optical Flow | VAL AP |TEST AP|  FPS        |
| :----:                |      :----:  | :----: |:----: | :----:      |
| MaskTrack R-CNN       |      ✘       | 30.3   |32.3   |20 (1080Ti)  |




## Contact & Feedback
If you have any suggestions about papers, feel free to mail me :)
- [e-mail](mailto:bomiaobbb@gmail.com)
- [pull request](https://github.com/bo-miao/awsome-video-object-instance-segmentation/pulls)