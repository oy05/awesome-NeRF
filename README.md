# Awesome Neural Radiance Fields [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome neural radiance fields papers, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).


#### [How to submit a pull request?](https://github.com/yenchenlin/awesome-NeRF/blob/main/how-to-PR.md)
#### [Want to help maintain the list?](https://github.com/awesome-NeRF/awesome-NeRF/issues/108#issuecomment-1350732470)


## Table of Contents

- [Survey](#survey)
- [Papers](#papers)
- [Talks](#talks)
- [Implementations](#implementations)

## Papers
- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf), Mildenhall et al., ECCV 2020 | [github](https://github.com/bmild/nerf)  | [bibtex](./NeRF-and-Beyond.bib#L168-L173) <!---Mildenhall20eccv_nerf-->


<details open>
<summary>Faster Inference</summary>
  
- [RT-NeRF: Real-Time On-Device Neural Radiance Fields Towards Immersive AR/VR Rendering](https://arxiv.org/abs/2212.01120), Li et al., ICCAD 2022 | [bibtex](./citations/rt-nerf.txt)
- [ENeRF: Efficient Neural Radiance Fields for Interactive Free-viewpoint Video](https://zju3dv.github.io/enerf/), Lin et al., SIGGRAPH 2022 | [github](https://github.com/zju3dv/ENeRF) | [bibtex](./citations/enerf.txt)
- [R2L: Distilling Neural Radiance Field to Neural Light Field for Efficient Novel View Synthesis](https://arxiv.org/abs/2203.17261), Wang et al., ECCV 2022 | [github](https://github.com/snap-research/R2L) | [bibtex](./citations/r2l.txt) <!---wang2022r2l-->
- [Real-Time Neural Light Field on Mobile Devices](https://arxiv.org/abs/2212.08057), Cao et al., Arxiv 2022 | [github](https://github.com/snap-research/MobileR2L) | [bibtext](./citations/r2l-mobile.txt) <!---cao2022mobiler2l-->
- [Hardware Acceleration of Neural Graphics](https://arxiv.org/pdf/2303.05735.pdf), Mubarik et al., ISCA 2023 | [bibtext](./citations/hw_accelaration.txt) <!---mubarik2023hardware-->
- [DyLiN: Making Light Field Networks Dynamic](https://dylin2023.github.io/), Yu et al., CVPR 2023 | [github](https://github.com/Heng14/DyLiN) | [bibtext](./citations/dylin.txt) <!---yu2023dylin-->
</details>


<details open>
<summary>Faster Training</summary>

- [Direct Voxel Grid Optimization: Super-fast Convergence for Radiance Fields Reconstruction](https://arxiv.org/abs/2111.11215.pdf), Sun et al., CVPR 2022 | [github](https://github.com/sunset1995/DirectVoxGO) | [bibtex](./citations/DirectVoxGO.txt) <!---sun2021direct-->
- [Instant Neural Graphics Primitives with a Multiresolution Hash Encoding](https://nvlabs.github.io/instant-ngp/), Müller et al., SIGGRAPH 2022 | [github](https://github.com/NVlabs/instant-ngp) | [bibtex](./citations/instant-ngp.txt)
- [Plenoxels Radiance Fields without Neural Networks](https://alexyu.net/plenoxels/), Yu et al., CVPR 2022 | [github](https://github.com/sxyu/svox2) | [bibtex](./citations/plenoxels.txt)
- [TensoRF: Tensorial Radiance Fields](https://apchenstu.github.io/TensoRF/), Chen et al., ECCV 2022 | [github](https://github.com/apchenstu/TensoRF) | [bibtex](./citations/tensorf.txt)
- [BakedSDF: Meshing Neural SDFs for Real-Time View Synthesis](https://bakedsdf.github.io/), Yariv et al., Arxiv 2023 | [bibtex](./citations/bakedsdf.txt)
- [Lightning NeRF: Efficient Hybrid Scene Representation for Autonomous Driving](https://arxiv.org/pdf/2403.05907v1.pdf), Cao et al. ICRA 2024 | [github](https://github.com/VISION-SJTU/Lightning-NeRF) | [bibtex](./citations/lightning-nerf.txt)
</details>

<details open>
<summary>Compression</summary>

- [Variable Bitrate Neural Fields](https://nv-tlabs.github.io/vqad/), Takikawa et al., SIGGRAPH 2022 | [github](https://github.com/nv-tlabs/vqad) | [bibtex](./citations/Variable-bitrate-neural-fields.txt)
</details>

<details open>
<summary>Unconstrained Images</summary>
- [Ha-NeRF:laughing:: Hallucinated Neural Radiance Fields in the Wild](https://rover-xingyu.github.io/Ha-NeRF/), Chen et al., CVPR 2022 | [github](https://github.com/rover-xingyu/Ha-NeRF) | [bibtex](./citations/Ha-NeRF.txt) <!---chen2021hallucinated-->
- [HDR-Plenoxels: Self-Calibrating High Dynamic Range Radiance Fields](https://hdr-plenoxels.github.io/), Jun-seong et al., ECCV 2022 | [github](https://github.com/postech-ami/HDR-Plenoxels) | [bibtex](./citations/hdr-plenoxels.txt) <!---Jun-seong2022hdr-plenoxels-->
- [UP-NeRF: Unconstrained Pose-Prior-Free Neural Radiance Fields](https://mlvlab.github.io/upnerf/), In-jae et al., NeurIPS 2023 | [github](https://github.com/mlvlab/UP-NeRF) | [bibtex](./citations/upnerf.txt) <!---kim2023upnerf-->
</details>


<details open>
<summary>Deformable</summary>

- [CLA-NeRF: Category-Level Articulated Neural Radiance Field](https://arxiv.org/abs/2202.00181), Tseng et al., ICRA 2022 | [bibtex](./citations/cla-nerf.txt)
- [TiNeuVox: Fast Dynamic Radiance Fields with Time-Aware Neural Voxels](https://jaminfong.cn/tineuvox/), Fang et al., SIGGRAPH Asia 2022 | [github](https://github.com/hustvl/TiNeuVox) | [bibtex](./citations/TiNeuVox.txt)
- [HumanNeRF: Free-viewpoint Rendering of Moving People from Monocular Video](https://grail.cs.washington.edu/projects/humannerf/), Weng et al., CVPR 2022 | [github](https://github.com/chungyiweng/humannerf) | [bibtex](./citations/humannerf.txt)
- [AligNeRF: High-Fidelity Neural Radiance Fields via Alignment-Aware Training](https://yifanjiang19.github.io/alignerf), Jiang et al., CVPR 2023 | [bibtex](./citations/AligNeRF.txt)
- [DynIBaR: Neural Dynamic Image-Based Rendering](https://dynibar.github.io/), Li et al., CVPR 2023 | [bibtex](./citations/DynIBaR.txt)

</details>


<details open>
<summary>Video</summary>

- [UV Volumes for Real-time Rendering of Editable Free-view Human Performance](https://fanegg.github.io/UV-Volumes/), Chen et al., CVPR 2023 | [github](https://github.com/fanegg/UV-Volumes) | [bibtex](citations/UV-Volumes.txt) <!---Chen22arxiv_uvvolumes-->
- [Neural 3D Video Synthesis from Multi-view Video](https://neural-3d-video.github.io/), Li et al., CVPR 2022 | [bibtex](./citations/3d-video.txt)
- [Streaming Radiance Fields for 3D Video Synthesis](https://arxiv.org/abs/2210.14831) Li et al. NeurIPS 2022 | [github](https://github.com/AlgoHunt/StreamRF) | [bibtex](./citations/StreamRF.txt)
</details>


<details open>
<summary>Generalization</summary>

- [Point-NeRF: Point-based Neural Radiance Fields](https://xharlie.github.io/projects/project_sites/pointnerf/index.html), Xu et al., CVPR 2022 | [github](https://github.com/Xharlie/pointnerf) | [bibtex](./citations/Point-NeRF.txt)
- [SinNeRF: Training Neural Radiance Fields on Complex Scenes from a Single Image](https://vita-group.github.io/SinNeRF/), Xu et al., ECCV 2022 | [github](https://github.com/VITA-Group/SinNeRF) | [bibtex](./citations/SinNeRF.txt)
- [Rodin: A Generative Model for Sculpting 3D Digital Avatars Using Diffusion](https://3d-avatar-diffusion.microsoft.com/), Wang et al., CVPR 2023 | [github](https://3d-avatar-diffusion.microsoft.com/) | [bibtex](./citations/rodin.txt)
- [SurfelNeRF: Neural Surfel Radiance Fields for Online Photorealistic Reconstruction of Indoor Scenes](https://arxiv.org/abs/2304.08971), Gao et al., CVPR 2023 | [github](https://gymat.github.io/SurfelNeRF-web/) | [bibtex](./citations/SurfelNeRF.txt)
- [NeO 360: Neural Fields for Sparse View Synthesis of Outdoor Scenes](https://arxiv.org/abs/2308.12967), Irshad et al., ICCV 2023 | [github](https://github.com/zubair-irshad/NeO-360) | [bibtex](./citations/SurfelNeRF.txt)
- [X-NeRF: Explicit Neural Radiance Field for Multi-Scene 360° Insufficient RGB-D Views](https://arxiv.org/abs/2210.05135), Zhu et al., WACV 2023 | [github](https://github.com/HaoyiZhu/XNeRF) | [bibtex](./citations/x-nerf.txt)
- [UFORecon: Generalizable Sparse-View Surface Reconstruction from Arbitrary and Unfavorable Sets](https://arxiv.org/abs/2403.05086), Na et al., CVPR 2024 | [github](https://github.com/Youngju-Na/UFORecon) | [bibtex](./citations/uforecon.txt)
- [🏡Know Your Neighbors: Improving Single-View Reconstruction via Spatial Vision-Language Reasoning](https://arxiv.org/abs/2404.03658), Li et al., CVPR 2024 | [github](https://github.com/ruili3/Know-Your-Neighbors) | [bibtex](./citations/KYN.txt)

</details>

<details open>
<summary>Pose Estimation</summary>

- [DFNet: Enhance Absolute Pose Regression with Direct Feature Matching](https://dfnet.active.vision/), Chen et al., ECCV 2022 | [github](https://github.com/ActiveVisionLab/DFNet) | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/dfnet.txt)
- [GARF: Gaussian Activated Radiance Fields for High Fidelity Reconstruction and Pose Estimation](https://arxiv.org/abs/2204.05735), Chng et al., ECCV 2022 | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/garf.txt)
- [L2G-NeRF: Local-to-Global Registration for Bundle-Adjusting Neural Radiance Fields](https://rover-xingyu.github.io/L2G-NeRF/), Chen et al., CVPR 2023 | [github](https://github.com/rover-xingyu/L2G-NeRF) | [bibtex](./citations/L2G-NeRF.txt)
- [NoPe-NeRF: Optimising Neural Radiance Field with No Pose Prior](https://nope-nerf.active.vision/), Bian et al., CVPR 2023 | [github](https://github.com/ActiveVisionLab/nope-nerf) | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/nope-nerf.txt)
- [Loc-NeRF: Monte Carlo Localization using Neural Radiance Fields](https://arxiv.org/abs/2209.09050), Maggio et al., ICRA 2023 | [github](https://github.com/MIT-SPARK/Loc-NeRF) | [bibtex](./citations/locnerf.txt)
- [Robust Camera Pose Refinement for Multi-Resolution Hash Encoding](http://arxiv.org/abs/2302.01571), Heo et al., ICML 2023 | [bibtex](.citations/instantpose.txt)
- [CROSSFIRE: Camera Relocalization On Self-Supervised Features from an Implicit Representation](https://arxiv.org/abs/2303.04869), Moreau et al., ICCV 2023 | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/crossfire.txt)
- [PoRF: Pose Residual Field for Accurate Neural Surface Reconstruction](https://porf.active.vision/), Bian et al., ICLR 2024 | [github](https://github.com/ActiveVisionLab/porf) | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/porf.txt)
- [Neural Refinement for Absolute Pose Regression with Feature Synthesis](https://nefes.active.vision/), Chen et al., CVPR 2024 | [github](https://github.com/ActiveVisionLab/NeFeS) | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/nefes.txt)
</details>

<details open>
<summary>Lighting</summary>
  
- [KiloNeuS: Implicit Neural Representations with Real-Time Global Illumination](https://arxiv.org/abs/2206.10885), Esposito et al., Arxiv 2022 | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/kiloneus.txt)
</details>


<details open>
<summary>Compositionality</summary>

- [Unsupervised Discovery of Object Radiance Fields](https://kovenyu.com/uorf/), Yu et al., ICLR 2022 | [github](https://github.com/KovenYu/uORF) | [bibtex](./citations/uorf.txt)
- [Unsupervised Discovery and Composition of Object Light Fields](https://cameronosmith.github.io/colf/), Smith et al., TMLR 2023 | [github](https://github.com/cameronosmith/COLF) | [bibtex](./citations/colf.txt)
- [Learning Object-centric Neural Scattering Functions for Free-viewpoint Relighting and Scene Composition](https://kovenyu.com/osf/), Yu et al., TMLR 2023 | [github](https://github.com/michguo/osf) | [bibtex](./citations/osf.txt)
</details>


<details open>
<summary>Scene Labelling and Understanding</summary>

- [NeRF-SOS: Any-view Self-supervised Object Segmentation on Complex Real-world Scenes](https://zhiwenfan.github.io/NeRF-SOS/), Fan et al., ICLR 2023 | [bibtex](./citations/NeRF-SOS.txt)
- [Contrastive Lift: 3D Object Instance Segmentation by Slow-Fast Contrastive Fusion](https://www.robots.ox.ac.uk/~vgg/research/contrastive-lift/), Bhalgat et al., NeurIPS 2023 (**Spotlight**) | [bibtex](./citations/contrastive-lift.txt)
</details>


<details open>
<summary>Multi-scale</summary>
  
- [Mip-NeRF 360: Unbounded Anti-Aliased Neural Radiance Fields](https://jonbarron.info/mipnerf360/), Barron et al., Arxiv 2022 | [bibtex](./citations/mip-nerf-360.txt)
</details>


<details open>
<summary>Model Reconstruction</summary>

- [NeAT: Learning Neural Implicit Surfaces with Arbitrary Topologies from Multi-view Images](https://arxiv.org/abs/2303.12012), Meng et al., CVPR 2023 | [github](https://github.com/xmeng525/NeAT) | [bibtex](./citations/neat.txt)
</details>


<details open>
<summary>Robotics</summary>

- [Vision-Only Robot Navigation in a Neural Radiance World](https://arxiv.org/abs/2110.00168), Adamkiewicz et al., RA-L 2022 Vol.7 No.2 | [bibtex](./citations/vision-only.txt)
- [Differentiable Physics Simulation of Dynamics-Augmented Neural Objects](https://arxiv.org/abs/2210.09420), Le Cleac'h et al., RA-L 2023 | [bibtex](./citations/dano.txt)
- [Customizable Perturbation Synthesis for Robust SLAM Benchmarking](https://arxiv.org/abs/2402.08125), Xu et al., ArXiv 2024 | [bibtex](./citations/customizable-SLAM.txt)
</details>

<details open>
<summary>Large-scale scene</summary>

- [Switch-NeRF: Learning Scene Decomposition with Mixture of Experts for Large-scale Neural Radiance Fields](https://mizhenxing.github.io/switchnerf), Mi et al., ICLR 2023 | [github](https://github.com/MiZhenxing/Switch-NeRF) | [bibtex](./citations/Switch-NeRF.txt)
- [Block-NeRF: Scalable Large Scene Neural View Synthesis](https://waymo.com/research/block-nerf/), Tancik et al., Arxiv 2022 | [bibtex](./citations/Block-NeRF.txt)
</details>

<details open>
<summary>Pre-training</summary>

- [Ponder: Point Cloud Pre-training via Neural Rendering](https://openaccess.thecvf.com/content/ICCV2023/html/Huang_Ponder_Point_Cloud_Pre-training_via_Neural_Rendering_ICCV_2023_paper.html), Huang et al., ICCV 2023 | [bibtex](./citations/ponder.txt)
- [PonderV2: Pave the Way for 3D Foundation Model with A Universal Pre-training Paradigm](https://arxiv.org/abs/2310.08586), Zhu et al., Arxiv 2023 | [github](https://github.com/OpenGVLab/PonderV2) | [bibtex](./citations/ponderv2.txt)
- [UniPAD: A Universal Pre-training Paradigm for Autonomous Driving](https://arxiv.org/abs/2310.08370), Yang et al., Arxiv 2023 | [github](https://github.com/Nightmare-n/UniPAD) | [bibtex](./citations/unipad.txt)
</details>

## Implementations
#### Tensorflow
- [NeRF](https://github.com/bmild/nerf), Mildenhall et al., 2020 | [bibtex](./NeRF-and-Beyond.bib#L168-L173)
- [Nerual-Radiance-Fields](https://www.kaggle.com/code/ritzraha/nerual-radiance-fields), [@ariG23498](https://twitter.com/ariG23498), [@ritwik_raha](https://twitter.com/ritwik_raha), 2022

#### PyTorch
- [NeRF-PyTorch](https://github.com/yenchenlin/nerf-pytorch), Yen-Chen Lin, 2020 | [bibtex](./citations/pytorch-nerf.txt)
- [NeRF-PyTorch-Lighting](https://github.com/kwea123/nerf_pl), [@kwea123](https://github.com/kwea123), 2020
- [NeRF-W](https://github.com/kwea123/nerf_pl/tree/nerfw), [@kwea123](https://github.com/kwea123), 2021
- [NeRF-PyTorch3D](https://github.com/facebookresearch/pytorch3d/tree/master/projects/nerf), [@facebookresearch](https://github.com/facebookresearch), 2020

#### Jax
- [JaxNeRF](https://github.com/google-research/google-research/tree/master/jaxnerf), Deng et al., 2020 | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/NeRF-and-Beyond.bib#L55-L60)
- [Mip-NeRF](https://github.com/google/mipnerf), [@google](https://github.com/google), 2021 | [bibtex](./citations/mipnerf.txt)
- [[Jax + Flax] Minimal Implementation of NeRF](https://www.kaggle.com/code/sauravmaheshkar/jax-flax-minimal-implementation-of-nerf), [@soumikrakshit](https://www.kaggle.com/soumikrakshit), [@sauravmaheshkar](https://www.kaggle.com/sauravmaheshkar), 2022

#### Libraries
- [Visu3d](https://github.com/google-research/visu3d), [@google](https://github.com/google-research), 2022

## License
MIT
