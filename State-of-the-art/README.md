## State-of-the-art
If you notice any result that have not been included in this table, please connect [Zhedong Zheng](mailto:zdzheng12@gmail.com) without hesitation to add the method. You are welcomed!
 
|Methods | Rank@1 | mAP| Reference|
| -------- | ----- | ---- | ---- |
|BoW+kissme | 25.13% | 12.17% | "[Scalable person re-identification: a benchmark](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7410490)", Liang Zheng, Liyue Shen, Lu Tian, Shengjin Wang, Jingdong Wang and Qi Tian, ICCV 2015 [[project]](http://www.liangzheng.org/Project/project_reid.html)|
|LOMO+XQDA | 30.75% | 17.04% | "[Person Re-identification by Local Maximal Occurrence Representation and Metric Learning](https://arxiv.org/abs/1406.4216)", Shengcai Liao, Yang Hu, Xiangyu Zhu and Stan Z Li, CVPR 2015 [[project]](http://www.cbsr.ia.ac.cn/users/scliao/projects/lomo_xqda/index.html)|
|Basel.  | 65.22% | 44.99%| "[Person Re-identification: Past, Present and Future](https://arxiv.org/abs/1610.02984)", Liang Zheng, Yi Yang, and Alexander G. Hauptmann, arXiv:1610.02984 [[code]](https://github.com/zhunzhong07/IDE-baseline-Market-1501)|
|Basel. + LSRO   | 67.68% | 47.13%| "[Unlabeled Samples Generated by GAN Improve the Person Re-identification Baseline in vitro](https://arxiv.org/abs/1701.07717)", Zhedong Zheng, Liang Zheng and Yi Yang, ICCV 2017 [[code]](https://github.com/layumi/Person-reID_GAN)|
|Basel. + OIM | 68.1% | - | "[Joint Detection and Identification Feature Learning for Person Search](https://arxiv.org/abs/1604.01850)", Tong Xiao, Shuang Li, Bochao Wang, Liang Lin, Xiaogang Wang, CVPR 2017
|Verif + Identif | 68.9% | 49.3% | "[A Discriminatively Learned Cnn Embedding for Person Re-identification](https://arxiv.org/abs/1611.05666)",  Zhedong Zheng, Liang Zheng, and Yi Yang, TOMM 2017. [[code]](https://github.com/layumi/2016_person_re-ID)| 
|APR | 70.69% | 51.88% | "[Improving person re-identification by attribute and identity learning](https://arxiv.org/abs/1703.07220)", Yutian Lin, Liang Zheng, Zhedong Zheng, Yu Wu, Yi Yang, arXiv:1703.07220 [[Attribute Dataset]](https://github.com/vana77/DukeMTMC-attribute) |
|ACRN | 72.58% | 51.96% | "[Person Re-Identification by Deep Learning Attribute-Complementary Information](http://openaccess.thecvf.com/content_cvpr_2017_workshops/w17/papers/Schumann_Person_Re-Identification_by_CVPR_2017_paper.pdf)", Arne Schumann and Rainer Stiefelhagen, CVPR 2017 Workshop|
|PAN | 71.59% | 51.51% |"[Pedestrian Alignment Network for Large-scale Person Re-identification](https://arxiv.org/abs/1707.00408)", Zhedong Zheng, Liang Zheng, Yi Yang, arXiv:1707.00408 [[code]](https://github.com/layumi/Pedestrian_Alignment)|
|PAN+rerank | 75.94% | 66.74% | | 
|FMN | 74.51% | 56.88% |"[Let Features Decide for Themselves: Feature Mask Network for Person Re-identification](https://arxiv.org/abs/1711.07155)", Guodong Ding, Salman Khan, Zhenmin Tang, Fatih Porikli, arXiv:1711.07155 | 
|FMN+rerank | 79.52% | 72.79% | | 
|SVDNet | 76.7% | 56.8% | "[SVDNet for Pedestrian Retrieval](https://arxiv.org/abs/1703.05693)", Yifan Sun, Liang Zheng, Weijian Deng, Shengjin Wang, ICCV 2017 [[code]](https://github.com/syfafterzy/SVDNet-for-Pedestrian-Retrieval)|
|dMpRL | 76.81% | 58.56% | "[Multi-pseudo Regularized Label for Generated Samples in Person Re-Identification](https://arxiv.org/abs/1801.06742)", Huang Yan, Jinsong Xu, Qiang Wu, Zhedong Zheng, Zhaoxiang Zhang, and Jian Zhang, arXiv:1801.06742 |
|DPFL | 79.2% | 60.6% | "[Person Re-Identification by Deep Learning Multi-Scale Representations](http://www.eecs.qmul.ac.uk/~sgg/papers/ChenEtAl_ICCV2017WK_CHI.pdf)", Yanbei Chen, Xiatian Zhu and Shaogang Gong, ICCV2017 workshop|
|SVDNet + REDA| 79.31% | 62.44% | "[Random Erasing Data Augmentation](https://arxiv.org/abs/1708.04896)", Zhun Zhong, Liang Zheng, Guoliang Kang, Shaozi Li, Yi Yang, arXiv:1708.04896 [[code]](https://github.com/layumi/Pedestrian_Alignment)|
|SVDNet + REDA + ReRank | 84.02% | 78.28% | |
|ATWL(2-stream)| 79.80% | 63.40% | "[Features for Multi-Target Multi-Camera Tracking and Re-Identification](https://arxiv.org/abs/1803.10859)", Ergys Ristani and Carlo Tomasi, CVPR2018|
|Mid-level Representation| 80.43% | 63.88% | "[The Devil is in the Middle: Exploiting Mid-level Representations for Cross-Domain Instance Matching](https://arxiv.org/abs/1711.08106)", Qian Yu, Xiaobin Chang, Yi-Zhe Song, Tao Xiang, Timothy M. Hospedales, arXiv:1711.08106|  
|HA-CNN| 80.5% | 63.8% |"[Harmonious Attention Network for Person Re-Identification](https://arxiv.org/abs/1802.08122)", Li Wei, Xiatian Zhu, and Shaogang Gong, arXiv:1802.08122|
|Deep-Person | 80.90% | 64.80% | "[Deep-Person: Learning Discriminative Deep Features for Person Re-Identification](https://arxiv.org/abs/1711.10658)", Xiang Bai, Mingkun Yang, Tengteng Huang, Zhiyong Dou, Rui Yu, Yongchao Xu, arXiv:1711.10658|  
|PSE| 79.8% | 62.0% | "[A Pose-Sensitive Embedding for Person Re-Identification with Expanded Cross Neighborhood Re-Ranking](https://arxiv.org/abs/1711.10378)", M. Saquib Sarfraz, Arne Schumann, Andreas Eberle, Rainer Stiefelhagen, arXiv:1711.10378 [[code]](https://github.com/pse-ecn/pose-sensitive-embedding)|
|PSE + ECN + ReRank | 85.2% | 79.8% | |
|PCB| 83.3% | 69.2% | "[Beyond Part Models: Person Retrieval with Refined Part Pooling](https://arxiv.org/abs/1711.09349)", Yifan Sun, Liang Zheng, Yi Yang, Qi Tian, Shengjin Wang, arXiv:1711.09349|
|GP-reID | 85.2% | 72.8% | "[Re-ID done right: towards good practices for person re-identification](https://arxiv.org/abs/1801.05339)", Jon Almazan, Bojana Gajic, Naila Murray, Diane Larlus, arXiv:1801.05339 |