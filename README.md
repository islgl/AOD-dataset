<div align="center">
    <h1>
        AOD Dataset
    </h1>
</div>

## Introduction
The AOD (Animal Object Detection) dataset is a large-scale animal image dataset specifically designed for object detection tasks. It integrates animal images and bounding box annotations from five publicly available datasets. These datasets encompass both animal-focused datasets and general datasets covering a wide range of scenes.

<div align="center">
    <img src="./assets/dataset.png">
</div>



Our dataset encompasses data from 18 different animal species, including livestock and wildlife. You can find a complete list of categories in [categories.yaml](https://github.com/islgl/AOD-dataset/blob/main/categories.yaml). It comprises a total of 35,054 images and 81,078 annotated bounding boxes, capturing scenes ranging from everyday life to zoos and wildlife environments.

<div align="center">
    <img src="assets/images_distribution.svg" width="400">
    <img src="assets/instances_distribution.svg" width="400">
    <img src="assets/bboxes_distribution.svg" width="800" height="500">
</div>

The dataset is organized in the YOLO data format, with each image having a corresponding `.txt` file containing bounding box annotations. For detailed information on YOLO data format, please refer to the [Ultralytics YOLOv5 documentation](https://docs.ultralytics.com/yolov5/tutorials/train_custom_data/#:~:text=download%20your%20dataset.-,Option%202%3A%20Create%20a%20Manual%20Dataset,-2.1%20Create%20dataset).

## Download
You can download the whole dataset from [Google Drive](https://drive.google.com/drive/folders/10qifTMvSSYeQLRCS9b650fMlthQCy9Mu?usp=sharing) or [OneDrive](https://yqsyw-my.sharepoint.com/:f:/g/personal/hi_lglgl_cc/EjEh8D0AuBVEsBVwe6fkbdcBKRCSZ7H65rtjhWZl1RK8SQ?e=T35lOi).

| Set        | Images | Instances |
| ---------- | ------ | --------- |
| train      | 28,051 | 64,834    |
| validation | 7,003  | 16,244    |

### AOD-Rare
In addition, we also provide the **AODR (AOD-Rare)** dataset, which includes the complete AOD dataset and incorporates an additional 10 rare animal data categories. AODR comprises over 55,000 images and more than 110,000 instances. You can download the AODR dataset from [OneDrive](https://yqsyw-my.sharepoint.com/:u:/g/personal/hi_lglgl_cc/EeWrFUDf2LpBq2reLArjWA0BUs261zwHyxdNm8_PSIo-pQ?e=MTEVOs).

## Acknowledgement
All data in the AOD dataset is sourced from five public datasets, including well-known and widely used datasets such as [Pascal VOC 2012](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/)[^1] and [MS COCO 2017](https://cocodataset.org/#home)[^2]. Additionally, the AOD dataset includes data from three animal-focused public datasets, namely [Animal Pose](https://sites.google.com/view/animal-pose/)[^3] by Jinkun Cao and others, [LoTE-Animal](https://lote-animal.github.io/)[^4] by Dan Liu and others, as well as [ATRW (Amur Tiger Re-identification in the Wild)](https://cvwc2019.github.io/challenge.html)[^5] from CVWC 2019. **We express sincere gratitude to the contributors of these datasets.**

## Copyright
This dataset is licensed under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Refer to the [LICENSE](https://github.com/islgl/AOD-dataset/blob/main/LICENSE) file for details.<a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a>

## References
[^1]: Everingham, M., et al, "The PASCAL Visual Object Classes Challenge 2012 (VOC2012) Results,"
[^2]: T.-Y. Lin *et al.*, “Microsoft COCO: Common Objects in Context.” arXiv, Feb. 20, 2015. doi: [10.48550/arXiv.1405.0312](https://doi.org/10.48550/arXiv.1405.0312).
[^3]: Cao, J., et al, "Cross-Domain Adaptation for Animal Pose Estimation," in *The IEEE International Conference on Computer Vision (ICCV)*, 2019.
[^4]: Liu, D., et al, "LoTE-Animal: A Long Time-span Dataset for Endangered Animal Behavior Understanding," in *Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)*, 2023, pp. 20064-20075.
[^5]: S. Li, J. Li, H. Tang, R. Qian, and W. Lin, “ATRW: A Benchmark for Amur Tiger Re-identification in the Wild,” in *Proceedings of the 28th ACM International Conference on Multimedia*, Oct. 2020, pp. 2590–2598. doi: [10.1145/3394171.3413569](https://doi.org/10.1145/3394171.3413569).

