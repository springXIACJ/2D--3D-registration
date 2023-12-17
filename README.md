# Awesome-Medical-Image-Registration [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A  curated list of 2D/3D medical image rigid registration algorithms, articles, software, and resources.

## Table of Contents

- [Reviews](#reviews)
- [Point-Based Methods](#point-based-methods)
- [Regression Methods](#regression-methods)
- [Optimization Methods](#optimization-methods)

## Reviews

- `2021/08` | **The Impact of Machine Learning on 2D/3D Registration for Image-Guided Interventions: A Systematic Review and Perspective**  
Mathias Unberath, Cong Gao, Yicheng Hu, Max Judish, Russell H Taylor, Mehran Armand, and Robert Grupp  
Frontiers in Robotics and AI, 2021  
[[arxiv](https://arxiv.org/abs/2108.02238)]
[[paper](https://www.frontiersin.org/articles/10.3389/frobt.2021.716007/full)]

- `2010/04` | **A review of 3D/2D registration methods for image-guided interventions**  
P. Markelj, D. Tomazˇevicˇ, B. Likar, F. Pernuš  
Medical Image Analysis (MIA), 2012  
[[paper](https://www.sciencedirect.com/science/article/pii/S1361841510000368)]

## Point-Based Methods

- `2023/09` | **Fully automatic tracking of native glenohumeral kinematics from stereo-radiography**  
William Burton, Ignacio Rivero Crespo, Thor Andreassen, Moira Pryhoda, Andrew Jensen, Casey Myers, Kevin Shelburne, Scott Banks, and Paul Rullkoetter  
Computers in Biology and Medicine, 2023  
[[paper](https://www.sciencedirect.com/science/article/pii/S0010482523006546)]

- `2021/08` | **Transfer Learning from an Artificial Radiograph-landmark Dataset for Registration of the Anatomic Skull Model to Dual Fluoroscopic X-ray Images**  
Chaochao Zhou, Thomas Cha, Yun Peng, and Guoan Li  
Computers in Biology and Medicine, 2021  
[[arXiv](https://arxiv.org/abs/2108.06466)]
[[paper](https://www.sciencedirect.com/science/article/pii/S0010482521007174)]

- `2019/11` **Automatic Annotation of Hip Anatomy in Fluoroscopy for Robust and Efficient 2D/3D Registration**  
Robert Grupp, Mathias Unberath, Cong Gao, Rachel Hegeman, Ryan Murphy, Clayton Alexander, Yoshito Otake, Benjamin McArthur, Mehran Armand, and Russell Taylor  
International Journal of Computer Assisted Radiology and Surgery (IJCARS), 2020  
[[arXiv](https://arxiv.org/abs/1911.07042)]
[[paper](https://link.springer.com/article/10.1007/s11548-020-02162-7)]

- `2019/10` | **Towards Fully Automatic X-Ray to CT Registration**  
Javier Esteban, Matthias Grimm, Mathias Unberath, Guillaume Zahnd, and Nassir Navab  
Medical Image Computing and Computer-Assisted Intervention (MICCAI), 2019  
[[paper](https://link.springer.com/chapter/10.1007/978-3-030-32226-7_70)]

- `2019/03` | `Point2` | **Multiview 2D/3D Rigid Registration via a Point-Of-Interest Network for Tracking and Triangulation**  
Haofu Liao, Wei-An Lin, Jiarui Zhang, Jingdan Zhang, Jiebo Luo, and S. Kevin Zhou  
Computer Vision and Pattern Recognitio (CVPR), 2019  
[[arXiv](https://arxiv.org/abs/1903.03896)]
[[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Liao_Multiview_2D3D_Rigid_Registration_via_a_Point-Of-Interest_Network_for_Tracking_CVPR_2019_paper.pdf)]

## Regression Methods

- `2023/10` | **A Patient-Specific Self-supervised Model for Automatic X-Ray/CT Registration**  
Baochang Zhang, Shahrooz Faghihroohi, Mohammad Farid Azampour, Shuting Liu, Reza Ghotbi, Heribert Schunkert, and Nassir Navab  
Medical Image Computing and Computer Assisted Intervention (MICCAI), 2023  
[[paper](https://link.springer.com/chapter/10.1007/978-3-031-43996-4_49)]
[[code](https://github.com/BaochangZhang/PSSS_registration)]
[[reviews](https://conferences.miccai.org/2023/papers/021-Paper2349.html)]

- `2023/10` | **X-Ray to CT Rigid Registration Using Scene Coordinate Regression**  
Pragyan Shrestha, Chun Xie, Hidehiko Shishido, Yuichi Yoshii, and Itaru Kitahara  
Medical Image Computing and Computer Assisted Intervention (MICCAI), 2023  
[[paper](https://link.springer.com/chapter/10.1007/978-3-031-43999-5_74)]
[[code](https://github.com/Pragyanstha/SCR-Registration)]
[[reviews](https://conferences.miccai.org/2023/papers/726-Paper3129.html)]

- `2023/08` | **A Fully Differentiable Framework for 2D/3D Registration and the Projective Spatial Transformers**  
Cong Gao, Anqi Feng, Xingtong Liu, Russell H. Taylor, Mehran Armand, and Mathias Unberath  
IEEE Transactions on Medical Imaging (TMI), 2023  
[[paper](https://ieeexplore.ieee.org/document/10210439)]

- `2021/07` | **Deep Iterative 2D/3D Registration**  
Srikrishna Jaganathan, Jian Wang, Anja Borsdorf, Karthik Shetty, and Andreas Maier  
Medical Image Computing and Computer Assisted Intervention (MICCAI), 2021  
[[arXiv](https://arxiv.org/abs/2107.10004)]
[[paper](https://link.springer.com/chapter/10.1007/978-3-030-87202-1_37)]
[[reviews](https://miccai2021.org/openaccess/paperlinks/2021/09/01/130-Paper2357.html)]

- `2020/03` | **Generalizing Spatial Transformers to Projective Geometry with Applications to 2D/3D Registration**  
Cong Gao, Xingtong Liu, Wenhao Gu, Benjamin Killeen, Mehran Armand, Russell Taylor, and Mathias Unberath  
Medical Image Computing and Computer Assisted Intervention (MICCAI), 2020  
[[arXiv](https://arxiv.org/abs/2003.10987)]
[[paper](https://link.springer.com/chapter/10.1007/978-3-030-59716-0_32)]
[[Code](https://github.com/gaocong13/Projective-Spatial-Transformers)]

- `2016/01` | **A CNN Regression Approach for Real-Time 2D/3D Registration**  
Shun Miao, Z. Jane Wang, and Rui Liao  
IEEE Transactions on Medical Imaging (TMI), 2016  
[[arXiv version](https://arxiv.org/abs/1507.07505)]
[[paper](https://ieeexplore.ieee.org/document/7393571)]

## Optimization Methods

- `2021/01` | **A novel approach to 2D/3D registration of X-ray images using Grangeat’s relation**  
Robert Frysch, Tim Pfeiffer, and Georg Rose  
Medical Image Analysis (MIA), 2021  
[[paper](https://www.sciencedirect.com/science/article/pii/S1361841520301791)]

- `2008/03` | **2D/3D registration with the CMA-ES method**  
Ren Hui Gong, and Purang Abolmaesumi  
Society of Photo-Optical Instrumentation Engineers (SPIE), 2008    
[[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/6918/1/2D3D-registration-with-the-CMA-ES-method/10.1117/12.770331.short?SSO=1)]

## Others

- `2022/10` | **Self-Supervised 2D/3D Registration for X-Ray to CT Image Fusion**  
Srikrishna Jaganathan, Maximilian Kukla, Jian Wang, Karthik Shetty, and Andreas Maier  
Winter Conference on Applications of Computer Vision (WACV), 2023  
[[arXiv](https://arxiv.org/abs/2210.07611)]
[[paper](https://openaccess.thecvf.com/content/WACV2023/papers/Jaganathan_Self-Supervised_2D3D_Registration_for_X-Ray_to_CT_Image_Fusion_WACV_2023_paper.pdf)]
