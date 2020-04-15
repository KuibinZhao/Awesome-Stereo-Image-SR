### <img src="https://raw.github.com/YingqianWang/Awesome-Stereo-Image-SR/master/Fig/Thumbnail.jpg" width="1000">
#### **We present a collection of papers, datasets, and repositories for *Stereo Image Super-Resolution*. This repository will be updated on a regular basis, so stay tuned~~🎉🎉🎉**

## Datasets

|     Name     |   links |  Comments |
| :----------: |  :-----: | :-------: |
|     ***Flickr1024***     | [***website***](https://yingqianwang.github.io/Flickr1024/) & [***paper***](http://openaccess.thecvf.com/content_ICCVW_2019/papers/LCI/Wang_Flickr1024_A_Large-Scale_Dataset_for_Stereo_Image_Super-Resolution_ICCVW_2019_paper.pdf) | **large-scale; 1024 high-quality images pairs; diverse senarios** |
|     ***Middlebury***     | [***website***](http://vision.middlebury.edu/stereo/) | ***several sub-datasets; indoor scenarios; groundtruth disparity*** |
|     ***KITTI2012***     | [***website***](http://www.cvlibs.net/datasets/kitti/index.php) | **driving perspectives; multi-role; groundtruth disparity** |
|     ***KITTI2015***     | [***website***](http://www.cvlibs.net/datasets/kitti/index.php) | **driving perspectives; multi-role; groundtruth disparity** |
|     ***Holopix50k***     | [***website***](http://github.com/leiainc/holopix50k) & [***paper***](https://arxiv.org/pdf/2003.11172.pdf) | **large-scale; 50K images; diverse senarios** |


## Methods
|     Model     |   Published |  Codes | Keywords | Outperforms |
| :----------: |  :-----: | :-------: | :-------: | :-------: |
| ***StereoSR*** | [***CVPR2018***](http://openaccess.thecvf.com/content_cvpr_2018/papers/Jeon_Enhancing_the_Spatial_CVPR_2018_paper.pdf) | N/A | **pioneering work** | ***SRCNN, VDSR***
| ***PASSRnet*** | [***CVPR2019***](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Learning_Parallax_Attention_for_Stereo_Image_Super-Resolution_CVPR_2019_paper.pdf) | [***PyTorch***](https://github.com/LongguangWang/PASSRnet) | **parallax attention** | ***StereoSR, DRCN, DRRN, LapSRN, SRResNet***
| ***SAM*** | [***SPL2020***](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8998204) | [***PyTorch***](https://github.com/XinyiYing/SAM) | **extend SISR networks for stereo image SR** | ***SRResNet+SAM > PASSRnet***
| ***SPAMnet*** | [***AAAI2020***](https://www.aaai.org/Papers/AAAI/2020GB/AAAI-SongW.10348.pdf) | N/A | **stereo consistency, self-and-parallax attention** | ***PASSRnet***|
| ***NNRANet*** | [***ICASSP2020***](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9054687) | N/A | **non-local, nested residual group** | ***PASSRnet***
