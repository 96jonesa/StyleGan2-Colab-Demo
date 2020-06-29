# StyleGan2-Colab-Demo
Notebook for training and generating samples with Colab and Google Drive, using lucidrains' StyleGAN2 PyTorch implementation.

output_small_set_demo.ipynb is a notebook comparing results across various training configurations (with and without attention,
and with varying differentiable augmentation probabilities) on various small datasets (... and CelebA).

small_set_demo.ipynb is a notebook used for training models with lucidrains' StyleGAN2 PyTorch implementation, using Colab
and Google Drive (because free compute is nice).

Here is a link to the public directory on my Google Drive containing the generated sample images used in the
output_small_set_demo.ipynb notebook:
https://drive.google.com/drive/folders/1gpZKmuvOnsuRmCo3MEcpST_WC1Laaz3W?usp=sharing

Here is a link to the public directory on my Google Drive containing all of the models and results from training using the
small_set_demo.ipynb notebook:
https://drive.google.com/drive/folders/1lBe6A5oTX6SuIg_iEoTcOdeC6-Quk9Ez?usp=sharing

So far, this is an afternoon's work. Expect frequent updates in the near future.

# Citations
@inproceedings{choi2020starganv2,
  title={StarGAN v2: Diverse Image Synthesis for Multiple Domains},
  author={Yunjey Choi and Youngjung Uh and Jaejun Yoo and Jung-Woo Ha},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  year={2020}
}

@inproceedings{liu2015faceattributes,
 title = {Deep Learning Face Attributes in the Wild},
 author = {Liu, Ziwei and Luo, Ping and Wang, Xiaogang and Tang, Xiaoou},
 booktitle = {Proceedings of International Conference on Computer Vision (ICCV)},
 month = {December},
 year = {2015} 
}

@article{Karras2019stylegan2,
  title   = {Analyzing and Improving the Image Quality of {StyleGAN}},
  author  = {Tero Karras and Samuli Laine and Miika Aittala and Janne Hellsten and Jaakko Lehtinen and Timo Aila},
  journal = {CoRR},
  volume  = {abs/1912.04958},
  year    = {2019},
}

@misc{zhao2020feature,
    title   = {Feature Quantization Improves GAN Training},
    author  = {Yang Zhao and Chunyuan Li and Ping Yu and Jianfeng Gao and Changyou Chen},
    year    = {2020}
}

@misc{chen2020simple,
    title   = {A Simple Framework for Contrastive Learning of Visual Representations},
    author  = {Ting Chen and Simon Kornblith and Mohammad Norouzi and Geoffrey Hinton},
    year    = {2020}
}

@article{,
  title     = {Oxford 102 Flowers},
  author    = {Nilsback, M-E. and Zisserman, A., 2008},
  abstract  = {A 102 category dataset consisting of 102 flower categories, commonly occuring in the United Kingdom. Each class consists of 40 to 258 images. The images have large scale, pose and light variations.}
}

@article{afifi201911k,
  title   = {11K Hands: gender recognition and biometric identification using a large dataset of hand images},
  author  = {Afifi, Mahmoud},
  journal = {Multimedia Tools and Applications}
}

@misc{zhang2018selfattention,
    title   = {Self-Attention Generative Adversarial Networks},
    author  = {Han Zhang and Ian Goodfellow and Dimitris Metaxas and Augustus Odena},
    year    = {2018},
    eprint  = {1805.08318},
    archivePrefix = {arXiv}
}

@article{shen2019efficient,
  author    = {Zhuoran Shen and
               Mingyuan Zhang and
               Haiyu Zhao and
               Shuai Yi and
               Hongsheng Li},
  title     = {Efficient Attention: Attention with Linear Complexities},
  journal   = {CoRR},  
  year      = {2018},
  url       = {http://arxiv.org/abs/1812.01243},
}

@misc{zhao2020image,
    title  = {Image Augmentations for GAN Training},
    author = {Zhengli Zhao and Zizhao Zhang and Ting Chen and Sameer Singh and Han Zhang},
    year   = {2020},
    eprint = {2006.02595},
    archivePrefix = {arXiv}
}

@misc{karras2020training,
    title   = {Training Generative Adversarial Networks with Limited Data},
    author  = {Tero Karras and Miika Aittala and Janne Hellsten and Samuli Laine and Jaakko Lehtinen and Timo Aila},
    year    = {2020},
    eprint  = {2006.06676},
    archivePrefix = {arXiv},
    primaryClass = {cs.CV}
}

@article{article,
author = {Krizhevsky, Alex},
year = {2012},
month = {05},
pages = {},
title = {Learning Multiple Layers of Features from Tiny Images},
journal = {University of Toronto}
}

@misc{karras2020training,
    title={Training Generative Adversarial Networks with Limited Data},
    author={Tero Karras and Miika Aittala and Janne Hellsten and Samuli Laine and Jaakko Lehtinen and Timo Aila},
    year={2020},
    eprint={2006.06676},
    archivePrefix={arXiv},
    primaryClass={cs.CV}
}

@article{article,
author = {Aksac, Alper and Demetrick, Douglas and Ozyer, Tansel},
year = {2019},
month = {12},
pages = {},
title = {BreCaHAD: a dataset for breast cancer histopathological annotation and diagnosis},
volume = {12},
journal = {BMC Research Notes},
doi = {10.1186/s13104-019-4121-7}
}
