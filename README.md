# awesome video object/instance segmentation
A curated list of awesome video object/instance segmentation resources.

*Last updated: 2020/12/17*

## What is video object segmentation and video instance segmentation?

Video object segmentation is a binary labeling problem aiming to separate foreground object(s) from the background region of a video.

Video instance segmentation not only need to segment foreground object(s)/instance(s), but also have to identify the category of each object and keep tracking objects across frames.


## Dataset
- DAVIS [`[link]`](https://davischallenge.org/davis2017/code.html#semisupervised)
- YouTube-VOS and -VIS [`[link]`](https://youtube-vos.org/dataset/vis/)


## Table of Contents
- [Video object segmentation](#video-object-segmentation)
- [Video instance segmentation](#video-instance-segmentation)


## Video object segmentation
- A Benchmark Dataset and Evaluation Methodology for Video Object Segmentation | **[CVPR' 16]** |[`[pdf]`](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Perazzi_A_Benchmark_Dataset_CVPR_2016_paper.pdf)
- One-Shot Video Object Segmentation | **[CVPR' 17]** |[`[pdf]`](https://openaccess.thecvf.com/content_cvpr_2017/papers/Caelles_One-Shot_Video_Object_CVPR_2017_paper.pdf) | [`[code]`](https://github.com/kmaninis/OSVOS-PyTorch)


1.2. Performance

|                                     DAVIS VAL                             |
| Paper             |    Supervise    | J      | F      | mIoU    |   FPS   |
| :----:            |      :----:     | :----: | :----: | :----:  | :----:  |
| OSVOS             | Semi-supervised | 79.8   | 80.6   | 单元格   | 单元格   |
| 单元格             | Semi-supervised | 单元格  | 单元格  | 单元格   | 单元格   |


|                                    YouTube-VOS                            |
| Paper             |    Supervise    | mIoU   | F      | mIoU    |   FPS   |
| :----:            |      :----:     | :----: | :----: | :----:  | :----:  |
| OSVOS             | Semi-supervised | 78.3   |        | 单元格   | 单元格   |
| 单元格             | Semi-supervised | 单元格  | 单元格  | 单元格   | 单元格   |


|                                YouTube-V                        |
| Paper             |    Supervise    | AP     |  AR    |   FPS   |
| :----:            |      :----:     | :----: | :----: | :----:  |
| Benchmark         | Semi-supervised |        |        | 单元格   |
| 单元格             | Semi-supervised | 单元格  | 单元格  | 单元格   |




## Contact & Feedback
If you have any suggestions about papers, feel free to mail me :)
- [e-mail](mailto:bomiaobbb@gmail.com)
- [pull request](https://github.com/bo-miao/awsome-video-object-instance-segmentation/pulls)