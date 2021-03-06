                                 IIAU (2017) Saliency Detection Models
Introduction
------------------------------------------------------------------------------------------------------------------
This file contains saliency detection models using the Caffe framework. We dive into the convolutional features in pre-trained FCN models and propose the following methods.

1) Amulet

Title: Amulet: Aggregating Multi-level Convolutional Features for Salient Object Detection

Authors: Pingping Zhang, Dong Wang, Huchuan Lu*, Hongyu Wang and Xiang Ruan

Paper Links: 

Google Drive Link: https://drive.google.com/file/d/0B5t8yubOMmTKUnZUYTY5NDdWcTg/view?usp=sharing

One Drive    Link: https://1drv.ms/u/s!AnzjJimFPB2Ibqy-4-sxZOHnb2s

Baidu Pan    Link: https://pan.baidu.com/s/1gfKkIwN

2) UCF

Title: Learning Uncertain Convolutional Features for Accurate Saliency Detection

Authors: Pingping Zhang, Dong Wang, Huchuan Lu*, Hongyu Wang and Baocai Yin

Paper Links: 

Google Drive Link: https://drive.google.com/file/d/0B5t8yubOMmTKbUFUQ1gtekVnNEE/view?usp=sharing

One Drive    Link: https://1drv.ms/u/s!AnzjJimFPB2IbY_bYGa-d5HemFw

Baidu Pan    Link: https://pan.baidu.com/s/1skCi4Dv

How to use
--------------------------------------------------------------------------------------------------------------

Prerequisites:

Download source code from  

Google Drive Link: https://drive.google.com/file/d/0B5t8yubOMmTKelBZQlE3Y3JzOWs/view?usp=sharing 

One Drive    Link: https://1drv.ms/u/s!AnzjJimFPB2Ib_zU3E15C6AxkXQ 

Baidu Pan    Link: https://pan.baidu.com/s/1boX9Pkr


Follow the official websites of the Caffe framework and install the whole toolbox (necessary Matlab wrappers)

1) Training

The training code is in ./models/Amulet and ./models/UCF. For saving memory, we use the BN method implemented by Alex Kendall etal http://mi.eng.cam.ac.uk/projects/segnet/. The training is followed as examples in Caffe. The only need is changing the path of data files.

2) Testing

The testing code is in ./matlab/Amulet_test and ./models/UCF_test.

For dataset testing,

(1) Get prediction : test_saliency_dataset.m

(2) Get PR value : PR.m

(3) Plot PR curves: code_pr.m

(4) Plot Bar figures: code_bar.m

(5) Get MAE for each method : getmae.m

Note that we have provided the PR curves in ./PR_curves

Citation
---------------------------------------------------------------------------------------------------------------------
Please cite the following papers if our models help your research:

@article{zhang2017amulet,

  title={Amulet: Aggregating Multi-level Convolutional Features for Salient Object Detection},
  
  author={Zhang, Pingping and Wang, Dong and Lu, Huchuan and Wang, Hongyu and Ruan, Xiang},
  
  journal={arXiv preprint arXiv:1708.02001},
  
  year={2017}
  
}

@InProceedings{Zhang_2017_ICCV,

author = {Zhang, Pingping and Wang, Dong and Lu, Huchuan and Wang, Hongyu and Ruan, Xiang},

title = {Amulet: Aggregating Multi-Level Convolutional Features for Salient Object Detection},

booktitle = {The IEEE International Conference on Computer Vision (ICCV)},

month = {Oct},

year = {2017}

}

@article{zhang2017learning,

  title={Learning Uncertain Convolutional Features for Accurate Saliency Detection},
  
  author={Zhang, Pingping and Wang, Dong and Lu, Huchuan and Wang, Hongyu and Yin, Baocai},
  
  journal={arXiv preprint arXiv:1708.02031},
  
  year={2017}
  
}

@InProceedings{Zhang_2017_ICCV,

author = {Zhang, Pingping and Wang, Dong and Lu, Huchuan and Wang, Hongyu and Yin, Baocai},

title = {Learning Uncertain Convolutional Features for Accurate Saliency Detection},

booktitle = {The IEEE International Conference on Computer Vision (ICCV)},

month = {Oct},

year = {2017}

}

Question and connection
------------------------------------------------------------------------------------------------------------------
If any question, please connect

jssxzhpp@gmail.com;  jssxzhpp@mail.dlut.edu.cn
