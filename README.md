# ReID_extra_testdata
## Sample Input
This repository stores the example input of the ReID sample in https://github.com/ReID-Team/opencv/tree/sample_person_reid

## Baseline Model
Following link store several state-of-the-art baseline models from Tencent Youtu Lab.

### Download Link
[models](https://drive.google.com/drive/folders/1wFGcuolSzX3_PqNKb4BAV3DNac7tYpc2?usp=sharing)

### Model Performance
|Model | Market1501(mAP/rank-1) | DukeMTMC(mAP/rank-1) | MSMT17(mAP/rank-1)|
| :--- | :--- | :--- | :--- |
|youtu_reid_baseline_lite   |88.16/95.43|79.75/89.05 |58.82/80.81| 
|youtu_reid_baseline_medium |90.95/96.47|83.38/91.56 |65.30/85.08| 

### Reference
Following datasets are used for the baseline training:

#### Market1501
```
@inproceedings{zheng2015scalable,
  title={Scalable person re-identification: A benchmark},
  author={Zheng, Liang and Shen, Liyue and Tian, Lu and Wang, Shengjin and Wang, Jingdong and Tian, Qi},
  booktitle={Proceedings of the IEEE international conference on computer vision},
  pages={1116--1124},
  year={2015}
}
```
#### DukeMTMC
```
@inproceedings{ristani2016performance,
  title={Performance measures and a data set for multi-target, multi-camera tracking},
  author={Ristani, Ergys and Solera, Francesco and Zou, Roger and Cucchiara, Rita and Tomasi, Carlo},
  booktitle={European Conference on Computer Vision},
  pages={17--35},
  year={2016},
  organization={Springer}
}
```

#### CHUK03
```
@inproceedings{li2014deepreid,
  title={DeepReID: Deep Filter Pairing Neural Network for Person Re-identification},
  author={Li, Wei and Zhao, Rui and Xiao, Tong and Wang, Xiaogang},
  booktitle={CVPR},
  year={2014}
}
```
#### MSMT17
```
@inproceedings{wei2018person,
  title={Person transfer gan to bridge domain gap for person re-identification},
  author={Wei, Longhui and Zhang, Shiliang and Gao, Wen and Tian, Qi},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  pages={79--88},
  year={2018}
}
```
