# Awesome Parameter-Efficient Fine-Tuning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
% A curated list of awesome parameter-efficient fine-tuning resources focusing on computer vision. Your contributions are always welcome!

This is a curated list of awesome parameter-efficient fine-tuning resources in `Parameter-Efficient Fine-tuning` (**PEFT**), which also goes by other names, such as `Parameter-Efficient Transfer Learning` (**PETL**). 

The repository is actively maintained. Pull requests or direct messages are welcome.

## Content
- [Background & Problem]()

- [Keywords Convention](#keywords-convention)
  
- [Addition-Based Fine-Tuning]()
  - [Adapter Tuning]()

  - [Prompt Tuning]()

  - [Prefix Tuning]()

  - [Side Tuning]()

- [Partial-Based Fine-Tuning]()
  - [Specification Tuning]()
  
  - [Repatameter Tuning]()

- [Unified Fine-Tuning]()

## Overeview
![avatar](.png)




## Problem

## Code Library
Coming soon....


## Papers
### Survey
- **Visual Tuning,** Arxiv 2023.
  
  *Yu, Bruce XB and Chang, Jianlong and Wang, Haixin and Liu, Lingbo and Wang, Shijie and Wang, Zhiyu and Lin, Junfan and Xie, Lingxi and Li, Haojie and Lin, Zhouchen and others.*

  [[Paper](https://arxiv.org/abs/2305.06061)][Code]



### Prompt Tuning
- **Learning to Prompt for Vision-Language Models,** IJCV 2022.
  
  *Kaiyang Zhou, Jingkang Yang, Chen Change Loy, Ziwei Liu.*

  [[Paper](https://arxiv.org/abs/2109.01134)][[Code](https://github.com/KaiyangZhou/CoOp)]

- **Visual Prompt Tuning,** ECCV 2022.
  
  *Menglin Jia, Luming Tang, Bor-Chun Chen, Claire Cardie, Serge Belongie, Bharath Hariharan, Ser-Nam Lim.*

  [[Paper](https://arxiv.org/abs/2203.12119)][[Code](https://github.com/kmnp/vpt)]

- **Hyperprompt: Prompt-based task-conditioning of transformers,** ICML 2022.
  
  *He, Yun and Zheng, Steven and Tay, Yi and Gupta, Jai and Du, Yu and Aribandi, Vamsi and Zhao, Zhe and Li, YaGuang and Chen, Zhao and Metzler, Donald and others.*

  [[Paper](https://proceedings.mlr.press/v162/he22f.html)][Code]

- **MaPLe: Multi-modal Prompt Learning,** CVPR 2023.
  
  *Khattak, Muhammad Uzair and Rasheed, Hanoona and Maaz, Muhammad and Khan, Salman and Khan, Fahad Shahbaz.*

  [[Paper](https://arxiv.org/abs/2210.03117)][[Code](https://github.com/muzairkhattak/multimodal-prompt-learning)]

- **Hierarchical Prompt Learning for Multi-Task Learning,** CVPR 2023.
  
  *Liu, Yajing and Lu, Yuning and Liu, Hao and An, Yaozu and Xu, Zhuoran and Yao, Zhuokun and Zhang, Baofeng and Xiong, Zhiwei and Gui, Chenguang.*

  [[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Liu_Hierarchical_Prompt_Learning_for_Multi-Task_Learning_CVPR_2023_paper.html)][Code]


- **Visual Exemplar Driven Task-Prompting for Unified Perception in Autonomous Driving,** CVPR 2023.
  
  *Liang, Xiwen and Niu, Minzhe and Han, Jianhua and Xu, Hang and Xu, Chunjing and Liang, Xiaodan.*

  [[Paper](https://arxiv.org/abs/2303.01788)][Code]

- **Dual Modality Prompt Tuning for Vision-Language Pre-Trained Model,** TMM 2023.
  
  *Xing, Yinghui and Wu, Qirui and Cheng, De and Zhang, Shizhou and Liang, Guoqiang and Wang, Peng and Zhang, Yanning.*

  [[Paper](https://ieeexplore.ieee.org/abstract/document/10171397/)][[Code](https://github.com/fanrena/DPT)]


- **Tokenize Anything via Prompting,** Arxiv 2023.
  
  *Pan, Ting and Tang, Lulu and Wang, Xinlong and Shan, Shiguang.*

  [[Paper](https://arxiv.org/pdf/2312.09128.pdf)][[Code](https://github.com/baaivision/tokenize-anything)]

- **MmAP : Multi-modal Alignment Prompt for Cross-domain Multi-task Learning,** AAAI 2024.
  
  *Yi Xin, Junlong Du, Qiang Wang, Ke Yan, Shouhong Ding.*

  [[Paper](https://arxiv.org/abs/2312.08636)][[Code]()]




  

### Adapter Tuning
- **Parameter-efficient multi-task fine-tuning for transformers via shared hypernetworks,** ACL 2021.
  
  *Mahabadi, Rabeeh Karimi and Ruder, Sebastian and Dehghani, Mostafa and Henderson, James.*

  [[Paper](https://arxiv.org/abs/2106.04489)][[Code](https://github.com/rabeehk/hyperformer)]
  
- **Compacter: Efficient Low-Rank Hypercomplex Adapter Layer,** NeurIPS 2021.
  
  *Karimi Mahabadi, Rabeeh and Henderson, James and Ruder, Sebastian.*

  [[Paper](https://arxiv.org/abs/2106.04647)][[Code](https://github.com/rabeehk/compacter)]

- **AdaptFormer: Adapting Vision Transformers for Scalable Visual Recognition,** NeurIPS 2022.
  
  *Shoufa Chen, Chongjian Ge, Zhan Tong, Jiangliu Wang, Yibing Song, Jue Wang, Ping Luo.*

  [[Paper](https://arxiv.org/abs/2205.13535)][[Code](https://github.com/ShoufaChen/AdaptFormer)]

- **Polyhistor: Parameter-Efficient Multi-Task Adaptation for Dense Vision Tasks,** NeurIPS 2022.
  
  *Yen-Cheng Liu, Chih-Yao Ma, Junjiao Tian, Zijian He, Zsolt Kira.*

  [[Paper](https://arxiv.org/abs/2210.03265)][Code]

- **Parameter-efficient and student-friendly knowledge distillation,** NeurIPS 2022.
  
  *Rao, Jun and Meng, Xv and Ding, Liang and Qi, Shuhan and Tao, Dacheng.*

  [[Paper](https://arxiv.org/abs/2205.15308)][Code]

- **Vl-adapter: Parameter-efficient transfer learning for vision-and-language tasks,** CVPR 2022.
  
  *Sung, Yi-Lin and Cho, Jaemin and Bansal, Mohit.*

  [[Paper](https://arxiv.org/abs/2112.06825)][[Code](https://github.com/ylsung/VL_adapter)]
  
- **1% VS 100%: Parameter-Efficient Low Rank Adapter for Dense Predictions,** CVPR 2023.
  
  *Yin, Dongshuo and Yang, Yiran and Wang, Zhechao and Yu, Hongfeng and Wei, Kaiwen and Sun, Xian.*

  [[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Yin_1_VS_100_Parameter-Efficient_Low_Rank_Adapter_for_Dense_Predictions_CVPR_2023_paper.html)][Code]

- **Vision transformer adapter for dense predictions.** ICLR 2023.

  *Chen, Zhe and Duan, Yuchen and Wang, Wenhai and He, Junjun and Lu, Tong and Dai, Jifeng and Qiao, Yu.*

  [[Paper](https://arxiv.org/abs/2205.08534)][[Code](https://github.com/czczup/ViT-Adapter)]
  

- **UniAdapter: Unified Parameter-Efficient Transfer Learning for Cross-modal Modeling,** ArXiv2023.
  
  *Haoyu Lu, Mingyu Ding, Yuqi Huo, Guoxing Yang, Zhiwu Lu, Masayoshi Tomizuka, Wei Zhan.*

  [[Paper](https://arxiv.org/abs/2302.06605)][[Code](https://github.com/RERV/UniAdapter)]

- **Important Channel Tuning,** Openreview 2023.

  *Hengyuan Zhao, Pichao WANG, Yuyang Zhao, Fan Wang, Mike Zheng Shou.*

  [[Paper](https://openreview.net/forum?id=TTMyoOdB9hZ)][Code]

- **Revisit Parameter-Efficient Transfer Learning: A Two-Stage Paradigm,** Arxiv 2023.

  *Zhao, Hengyuan and Luo, Hao and Zhao, Yuyang and Wang, Pichao and Wang, Fan and Shou, Mike Zheng.*

  [[Paper](https://arxiv.org/abs/2303.07910)][Code]

- **SCT: A Simple Baseline for Parameter-Efficient Fine-Tuning via Salient Channels,** IJCV 2023.

  *Henry Hengyuan Zhao, Pichao Wang, Yuyang Zhao, Hao Luo, Fan Wang, Mike Zheng Shou.*

  [[Paper](https://arxiv.org/abs/2303.07910)][[Code](https://github.com/showlab/SCT)]

- **VMT-Adapter: Parameter-Efficient Transfer Learning for Multi-Task Dense Scene Understanding,** AAAI 2024.

  *Yi Xin, Junlong Du, Qiang Wang, Zhiwen Lin, Ke Yan.*

  [[Paper](https://arxiv.org/abs/2312.08733)][[Code]()]

- **VMT-Adapter: Parameter-Efficient Transfer Learning for Multi-Task Dense Scene Understanding,** AAAI 2024.

  *Yi Xin, Junlong Du, Qiang Wang, Zhiwen Lin, Ke Yan.*

  [[Paper](https://arxiv.org/abs/2312.08733)][[Code]()]

- **Parameter Efficient Fine-tuning via Cross Block Orchestration for Segment Anything Model,** Arxiv 2023.

  *Zelin Peng, Zhengqin Xu, Zhilin Zeng, Lingxi Xie, Qi Tian, and Wei Shen.*
  
  [[Paper](https://arxiv.org/pdf/2311.17112.pdf)][Code]

- **Hydra: Multi-head Low-rank Adaptation for Parameter Efficient Fine-tuning,** Arxiv 2023.

  *Sanghyeon Kim, Hyunmo Yang, Younghyun Kim, Youngjoon Hong, Eunbyung Park.*
  
  [[Paper](https://arxiv.org/abs/2309.06922)][[Code](https://github.com/extremebird/Hydra/tree/main)]

- **A Closer Look at Parameter-Efficient Tuning in Diffusion Models,** Arxiv 2023.

  *Chendong Xiang, Fan Bao, Chongxuan Li, Hang Su, Jun Zhu.*
  
  [[Paper](https://arxiv.org/abs/2303.18181)][[Code](https://github.com/Xiang-cd/unet-finetune)]

- **MixPHM: Redundancy-Aware Parameter-Efficient Tuning for Low-Resource Visual Question Answering,** Arxiv 2023.

  *Jingjing Jiang, Nanning Zheng.*
  
  [[Paper](https://web3.arxiv.org/abs/2303.01239)][Code]

- **Vision Transformers are Parameter-Efficient Audio-Visual Learners,** CVPR 2023.

  *Yan-Bo Lin, Yi-Lin Sung, Jie Lei, Mohit Bansal, Gedas Bertasius.*
  
  [[Paper](https://ieeexplore.ieee.org/document/10203390/authors#authors)][Code]


  

  
### Parameter Tuning
- **LoRA: Low-Rank Adaptation of Large Language Models.** NeurIPS 2021.

  *Hu, Edward J and Shen, Yelong and Wallis, Phillip and Allen-Zhu, Zeyuan and Li, Yuanzhi and Wang, Shean and Wang, Lu and Chen, Weizhu.*

  [[Paper](https://arxiv.org/pdf/2106.09685.pdf)][[Code](https://github.com/microsoft/LoRA)]

- **Scaling & Shifting Your Features: A New Baseline for Efficient Model Tuning,** NeurIPS 2022.
  
  *Dongze Lian, Daquan Zhou, Jiashi Feng, Xinchao Wang.*

  [[Paper](https://arxiv.org/abs/2210.08823)][[Code](https://github.com/dongzelian/SSF)]

- **BitFit: Simple Parameter-efficient Fine-tuning for Transformer-based Masked Language-models.** ACL 2022.

  *Zaken, Elad Ben and Ravfogel, Shauli and Goldberg, Yoav.*

  [[Paper](https://arxiv.org/pdf/2106.10199.pdf)][[Code](https://github.com/benzakenelad/BitFit)]

- **Parameter-efficient Model Adaptation for Vision Transformers.** AAAI 2023.

  *He, Xuehai and Li, Chunyuan and Zhang, Pengchuan and Yang, Jianwei and Wang, Xin Eric.*

  [[Paper](https://arxiv.org/abs/2203.16329)][[Code](https://github.com/eric-ai-lab/PEViT)]

- **Gradient-based Parameter Selection for Efficient Fine-Tuning,** Arxiv 2023.
  
  *Zhi Zhang, Qizhe Zhang, Zijun Gao, Renrui Zhang, Ekaterina Shutova, Shiji Zhou, Shanghang Zhang.*

  [[Paper](https://arxiv.org/abs/2312.10136)][[Code]()]

- **Three things everyone should know about Vision Transformers,** ECCV 2022.
  
  *Hugo Touvron, Matthieu Cord, Alaaeldin El-Nouby, Jakob Verbeek, Hervé Jégou.*

  [[Paper](https://arxiv.org/abs/2203.09795)][[Code]()]

- **Sensitivity-Aware Visual Parameter-Efficient Fine-Tuning,** ICCV 2023.
  
  *Haoyu He, Jianfei Cai, Jing Zhang, Dacheng Tao, Bohan Zhuang.*

  [[Paper](https://arxiv.org/abs/2303.08566)][[Code](https://github.com/ziplab/SPT)]

- **DiffFit: Unlocking Transferability of Large Diffusion Models via Simple Parameter-Efficient Fine-Tuning,** ICCV 2023.
  
  *Enze Xie, Lewei Yao, Han Shi, Zhili Liu, Daquan Zhou, Zhaoqiang Liu, Jiawei Li, Zhenguo Li.*

  [[Paper](https://arxiv.org/abs/2304.06648)][[Code]()]






### Re-Parameter Tuning

- **SAM-PARSER: Fine-tuning SAM Efficiently by Parameter Space Reconstruction,** AAAI 2024.
  
  *Zelin Peng, Zhengqin Xu, Zhilin Zeng, Xiaokang Yang, Wei Shen.*

  [[Paper](https://arxiv.org/abs/2308.14604)][[Code]()]

- **Strong Baselines for Parameter Efficient Few-Shot Fine-tuning,** AAAI 2024.
  
  *Samyadeep Basu, Daniela Massiceti, Shell Xu Hu, Soheil Feizi.*

  [[Paper]([https://arxiv.org/abs/2308.14604](https://arxiv.org/abs/2304.01917))][[Code]()]

- **KronA: Parameter Efficient Tuning with Kronecker Adapter,** Arxiv 2023.
  
  *Ali Edalati, Marzieh Tahaei, Ivan Kobyzev, Vahid Partovi Nia, James J. Clark, Mehdi Rezagholizadeh.*

  [[Paper](https://arxiv.org/abs/2212.10650))][Code]

### Unified
- **Towards a Unified View of Parameter-Efficient Transfer Learning,** ICLR 2022.

  *Junxian He, Chunting Zhou, Xuezhe Ma, Taylor Berg-Kirkpatrick, Graham Neubig.*

  [[Paper](https://arxiv.org/abs/2110.04366)][[Code](https://github.com/jxhe/unify-parameter-efficient-tuning)]

- **Towards a Unified View on Visual Parameter-Efficient Transfer Learning,** Arxiv 2023.

  *Yu, Bruce XB and Chang, Jianlong and Liu, Lingbo and Tian, Qi and Chen, Chang Wen.*

  [[Paper](https://arxiv.org/abs/2210.00788)][[Code](https://github.com/bruceyo/V-PETL)]

### Others
- **LST: Ladder Side-Tuning for Parameter and Memory Efficient Transfer Learning,** NeurIPS 2022.

  *Sung, Yi-Lin and Cho, Jaemin and Bansal, Mohit.*

  [[Paper](https://arxiv.org/abs/2206.06522)][[Code](https://github.com/ylsung/Ladder-Side-Tuning)]

- **GIST: Improving Parameter Efficient Fine Tuning via Knowledge Interaction,** Arxiv 2023.

  *Jiacheng Ruan, Jingsheng Gao, Mingye Xie, Suncheng Xiang, Zefang Yu, Ting Liu, Yuzhuo Fu.*

  [[Paper](https://arxiv.org/pdf/2312.07255.pdf)][Code]()

- **Point-PEFT: Parameter-Efficient Fine-Tuning for 3D Pre-trained Models,** AAAI 2024.

  *Yiwen Tang, Ray Zhang, Zoey Guo, Xianzheng Ma, Dong Wang, Zhigang Wang, Bin Zhao, Xuelong Li.*

  [[Paper](https://arxiv.org/abs/2310.03059)][Code]()

- **AdaptIR: Parameter Efficient Multi-task Adaptation for Pre-trained Image Restoration Models,** Arxiv 2023.

  *Hang Guo, Tao Dai, Yuanchao Bai, Bin Chen, Shu-Tao Xia, Zexuan Zhu.*

  [[Paper](https://arxiv.org/pdf/2312.08881.pdf)][Code](https://github.com/csguoh/AdaptIR)]


