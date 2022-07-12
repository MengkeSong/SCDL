# SCDL
## Description 
This is the source code for ''A Comprehensive Survey on Video Saliency Detection with Auditory Information: the Audio-visual Consistency Perceptual is the Key!''

![alt](https://github.com/MengkeSong/SCDL/blob/main/img/review%20architecture.png)
<p align="center">Figure 1: The structure of our review.</p>

![alt](https://github.com/MengkeSong/SCDL/blob/main/img/pipeline.png)
<p align="center">Figure 2: Demonstrations of the differences between the conventional audio-visual saliency detection model training/testing pipeline (a) and the newly modified training/testing pipeline (b).</p>

![alt](https://github.com/MengkeSong/SCDL/blob/main/img/visual.png)
<p align="center">Figure 3: Demonstration of the differences regarding the scene contents of six wide-usedly datasets of AVAD, Coutrot1, Coutrot1, DIEM, ETMD and SumMe.</p>

## Getting Started
### Requirements
* Python 3.7
* Pytorch 1.6.0
* CUDA v10.1, cudnn v.7.5.0
* torchvision

### Usage
1.Clone
git clone https://github.com/MengkeSong/SCDL.git
cd SCDL/

2.Download the datasets
Download the following datasets and unzip them into your_data folder. All datasets and labeled Audio-visual Consistency Degree can be downloaded at this [data link](https://www.iqiyi.com/v_ubdb92qzbk.html?vfm=2008_aldbd&fv=p_02_01 "data link"). Then put them under the following directory:
```
-video_frame/
  -AVAD/
  -Coutrot1/
  -Coutrot2/
  -DIEM/
  -ETMD/
  -SumMe/

-annotation/
  -AVAD/
  -Coutrot1/
  -Coutrot2/
  -DIEM/
  -ETMD/
  -SumMe/

-audio/
  -AVAD/
  -Coutrot1/
  -Coutrot2/
  -DIEM/
  -ETMD/
  -SumMe/

-fold_list/
  -AVAD/
  -Coutrot1/
  -Coutrot2/
  -DIEM/
  -ETMD/
  -SumMe/
```

3.Training & Testing
Unzip the zip files and run training files & testing files.

### Results
![alt](https://github.com/MengkeSong/SCDL/blob/main/img/quantititive%20results.png)
<p align="center">Figure 3: Quantitative comparisons between our method with other fully-/weakly-/un-supervised methods on all 6 datasets.</p>

## Citation
Please cite the following article when referring to this method.
```
@ARTICLE{Chen2022SCDL,
      title={A Comprehensive Survey on Video Saliency Detection with Auditory Information: the Audio-visual Consistency Perceptual is the Key!}, 
      author={Chenglizhao Chen and Mengke Song and Wenfeng Song and Li Guo and Muwei Jian},
      year={2022},
}
```

## Acknowledgement 
Thanks to [STANet](https://github.com/guotaowang/STANet), [STAViS](https://github.com/atsiami/STAViS) and [AViNet](https://github.com/samyak0210/ViNet).
