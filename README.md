# Awesome-VFI
This is a summary of recent video frame interpolation (VFI) methods.
| Title                  | Model                  | Published                                                    | Repo                                                         | Keywords                                                     |
| ---------------------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Video Frame Interpolation via Adaptive Convolution | -- | [CVPR2017](https://arxiv.org/pdf/1703.07514.pdf) | -- | Kernel-based |
| Video Frame Interpolation via Adaptive Separable Convolution | SepConv | [ICCV2017](https://arxiv.org/pdf/1708.01692.pdf) | [Pytorch&Cupy](https://github.com/sniklaus/sepconv-slomo) ![Github stars](https://img.shields.io/github/stars/sniklaus/sepconv-slomo) | Kernel-based |
| Video Frame Synthesis using Deep Voxel Flow | DVF | [ICCV2017](https://arxiv.org/pdf/1702.02463.pdf) | [TensorFlow](https://github.com/liuziwei7/voxel-flow) ![Github stars](https://img.shields.io/github/stars/liuziwei7/voxel-flow) | Voxel flow | 
| Context-aware Synthesis for Video Frame Interpolation | CtxSyn | [CVPR2018](https://arxiv.org/pdf/1803.10967.pdf) | -- | Flow-based, Content |
| Super SloMo: High Quality Estimation of Multiple Intermediate Frames for Video Interpolation | Super SloMo | [CVPR2018](https://arxiv.org/pdf/1712.00080.pdf) | [Pytorch](https://github.com/avinashpaliwal/Super-SloMo) ![Github stars](https://img.shields.io/github/stars/avinashpaliwal/Super-SloMo) | Flow-based, Arbitrary time | 
| Video Enhancement with Task-Oriented Flow | ToFlow | [IJCV2019](https://arxiv.org/pdf/1711.09078.pdf) | [Torch&Lua](https://github.com/anchen1011/toflow) ![Github stars](https://img.shields.io/github/stars/anchen1011/toflow) | Flow-based, [Vimeo-90K](http://toflow.csail.mit.edu/) |
| Depth-Aware Video Frame Interpolation | DAIN | [CVPR2019](https://arxiv.org/pdf/1904.00830.pdf) | [Pytorch](https://github.com/baowenbo/DAIN) ![Github stars](https://img.shields.io/github/stars/baowenbo/DAIN) | Flow-based, Depth-guided | 
| PhaseNet for Video Frame Interpolation | PhaseNet | [CVPR2019](https://arxiv.org/pdf/1804.00884.pdf) | -- | Phase-based |
| IM-Net for High Resolution Video Frame Interpolation | IM-Net | [CVPR2019](https://openaccess.thecvf.com/content_CVPR_2019/papers/Peleg_IM-Net_for_High_Resolution_Video_Frame_Interpolation_CVPR_2019_paper.pdf) | -- | Kernel-based |
| Unsupervised Video Interpolation Using Cycle Consistency | -- | [ICCV2019](https://arxiv.org/pdf/1906.05928.pdf) | [Pytorch](https://github.com/NVIDIA/unsupervised-video-interpolation) ![Github stars](https://img.shields.io/github/stars/NVIDIA/unsupervised-video-interpolation) | Unsupervised, Cycle consistency |
| Deep Video Frame Interpolation Using Cyclic Frame Generation | CyclicGen | [AAAI2019](https://ojs.aaai.org/index.php/AAAI/article/view/4905/4778) | [TensorFlow](https://github.com/alex04072000/CyclicGen) ![Github stars](https://img.shields.io/github/stars/alex04072000/CyclicGen) | Cycle consistency |
| Quadratic Video Interpolation | QVI | [NIPS2019](https://arxiv.org/pdf/1911.00627.pdf) | [Pytorch&Cupy](https://github.com/xuxy09/QVI) ![Github stars](https://img.shields.io/github/stars/xuxy09/QVI)  | Multiple frames | 
| AdaCoF: Adaptive Collaboration of Flows for Video Frame Interpolation | AdaCoF | [CVPR2020](https://arxiv.org/pdf/1907.10244.pdf) | [Pytorch](https://github.com/HyeongminLEE/AdaCoF-pytorch) ![Github stars](https://img.shields.io/github/stars/HyeongminLEE/AdaCoF-pytorch) | Kernel-based, Deformable convolution | 
| Softmax Splatting for Video Frame Interpolation | SoftSplat | [CVPR2020](https://arxiv.org/pdf/2003.05534.pdf) | [Pytorch&Cupy](https://github.com/sniklaus/softmax-splatting) ![Github stars](https://img.shields.io/github/stars/sniklaus/softmax-splatting) | Flow-based, Forward warping | 
| FeatureFlow: Robust Video Interpolation via Structure-to-texture Generation | FeFlow | [CVPR2020](https://openaccess.thecvf.com/content_CVPR_2020/papers/Gui_FeatureFlow_Robust_Video_Interpolation_via_Structure-to-Texture_Generation_CVPR_2020_paper.pdf) | [Pytorch](https://github.com/CM-BF/FeatureFlow) ![Github stars](https://img.shields.io/github/stars/CM-BF/FeatureFlow) | Flow-based, Kernel-based, Deformable convolution |
| BMBC: Bilateral Motion Estimation with Bilateral Cost Volume for Video Interpolation | BMBC | [ECCV2020](https://arxiv.org/pdf/2007.12622.pdf) | [Pytorch](https://github.com/JunHeum/BMBC) ![Github stars](https://img.shields.io/github/stars/JunHeum/BMBC) | Flow-based, Cost volume | 
| Channel Attention Is All You Need for Video Frame Interpolation | CAIN | [AAAI2020](https://ojs.aaai.org/index.php/AAAI/article/download/6693/6547) | [Pytorch](https://github.com/myungsub/CAIN) ![Github stars](https://img.shields.io/github/stars/myungsub/CAIN) | Channel attention |
| FLAVR: Flow-Agnostic Video Representations for Fast Frame Interpolation | FLAVR | [Arxiv.2012](https://arxiv.org/pdf/2012.08512.pdf) | [Pytorch](https://github.com/tarun005/FLAVR) ![Github stars](https://img.shields.io/github/stars/tarun005/FLAVR) | 3d convolution |
| CDFI: Compression-Driven Network Design for Frame Interpolation | CDFI | [CVPR2021](https://arxiv.org/pdf/2103.10559.pdf) | [Pytorch](https://github.com/tding1/CDFI) ![Github stars](https://img.shields.io/github/stars/tding1/CDFI) | Model compression | 
| Deep Animation Video Interpolation in the Wild | AnimeInterp | [CVPR2021](https://arxiv.org/pdf/2104.02495.pdf) | [Pytorch](https://github.com/lisiyao21/AnimeInterp) ![Github stars](https://img.shields.io/github/stars/lisiyao21/AnimeInterp) | Amine interpolation, [ATD-12K](https://drive.google.com/file/d/1XBDuiEgdd6c0S4OXLF4QvgSn_XNPwc-g/view) |
| XVFI: eXtreme Video Frame Interpolation | XVFI | [ICCV2021](https://arxiv.org/pdf/2103.16206.pdf) | [Pytorch](https://github.com/JihyongOh/XVFI) ![Github stars](https://img.shields.io/github/stars/JihyongOh/XVFI) | Flow-based, [X4K1000FPS](https://www.dropbox.com/sh/duisote638etlv2/AABJw5Vygk94AWjGM4Se0Goza?dl=0) |
| Asymmetric Bilateral Motion Estimation for Video Frame Interpolation | ABME | [ICCV2021](https://arxiv.org/pdf/2108.06815.pdf) | [Pytorch](https://github.com/JunHeum/ABME) ![Github stars](https://img.shields.io/github/stars/JunHeum/ABME) | Flow-based, Multiple flows, Cost volume |
| Revisiting Adaptive Convolutions for Video Frame Interpolation | -- | [WACV2021](https://arxiv.org/pdf/2011.01280.pdf) | [Pytorch&Cupy](https://github.com/sniklaus/revisiting-sepconv) ![Github stars](https://img.shields.io/github/stars/sniklaus/revisiting-sepconv) | Kernel-based |
| IFRNet: Intermediate Feature Refine Network for Efficient Frame Interpolation | IFRNet | [CVPR2022](https://arxiv.org/pdf/2205.14620.pdf) | [Pytorch](https://github.com/ltkong218/IFRNet) ![Github stars](https://img.shields.io/github/stars/ltkong218/IFRNet) | Flow-based, Efficiency |
| FILM: Frame Interpolation for Large Motion | FILM | [CVPR2022](https://arxiv.org/pdf/2202.04901.pdf) | [Pytorch](https://github.com/google-research/frame-interpolation) ![Github stars](https://img.shields.io/github/stars/google-research/frame-interpolation) | Flow-based, Large motion |
| Video Frame Interpolation Transformer | VFIT | [CVPR2022](https://arxiv.org/pdf/2111.13817.pdf) |[Pytorch](https://github.com/zhshi0816/Video-Frame-Interpolation-Transformer) ![Github stars](https://img.shields.io/github/stars/zhshi0816/Video-Frame-Interpolation-Transformer) | Window-based Attention, Multiple Frames |
| Video Frame Interpolation with Transformer | VFIFormer | [CVPR2022](https://arxiv.org/pdf/2205.07230.pdf) | [Pytorch](https://github.com/dvlab-research/VFIformer) ![Github stars](https://img.shields.io/github/stars/dvlab-research/VFIformer) | Flow-based, Window-attention | 
| Long-term Video Frame Interpolation via Feature Propagation | P-INet | [CVPR2022](https://arxiv.org/pdf/2203.15427.pdf) | -- | Flow-based | 
| ST-MFNet: A Spatio-Temporal Multi-Flow Network for Frame Interpolation | ST-MFNet | [CVPR2022](https://arxiv.org/pdf/2111.15483.pdf) | [Pytorch](https://github.com/danielism97/ST-MFNet) ![Github stars](https://img.shields.io/github/stars/danielism97/ST-MFNet) | Flow-based, Multiple frames |
| Many-to-many Splatting for Efficient Video Frame Interpolation | M2M-VFI | [CVPR2022](https://arxiv.org/pdf/2204.03513.pdf) | [Pytorch&Cupy](https://github.com/feinanshan/M2M_VFI) ![Github stars](https://img.shields.io/github/stars/feinanshan/M2M_VFI) | Flow-based, Forward warping, Multiple flows |
| Real-Time Intermediate Flow Estimation for Video Frame Interpolation | RIFE | [ECCV2022](https://arxiv.org/pdf/2011.06294.pdf) | [Pytorch](https://github.com/megvii-research/ECCV2022-RIFE) ![Github stars](https://img.shields.io/github/stars/megvii-research/ECCV2022-RIFE) | Flow-based, Distillation |
| Improving the Perceptual Quality of 2D Animation Interpolation | -- | [ECCV2022](https://arxiv.org/abs/2111.12792) | [Pytorch](https://github.com/ShuhongChen/eisai-anime-interpolator) ![Github stars](https://img.shields.io/github/stars/ShuhongChen/eisai-anime-interpolator) | Animation Interpolation, New metrics |
| Cross-Attention Transformer for Video Interpolation | TAIN |[Arxiv.2207](https://arxiv.org/pdf/2207.04132.pdf) | -- | Cross-Attention, Transformer |
| Error-Aware Spatial Ensembles for Video Frame Interpolation | -- | [Arxiv.2207](https://arxiv.org/pdf/2207.12305.pdf) | -- | Flow-based, Divide-and-conquer |
| TTVFI: Learning Trajectory-Aware Transformer for Video Frame Interpolation | -- | [Arxiv.2207](https://arxiv.org/abs/2207.09048) | -- | Flow-based,  Transformer | 
| Splatting-based Synthesis for Video Frame Interpolation | -- | [WACV2023](https://openaccess.thecvf.com/content/WACV2023/papers/Niklaus_Splatting-Based_Synthesis_for_Video_Frame_Interpolation_WACV_2023_paper.pdf) | -- | Flow-based, Forward warp |
| A Unified Pyramid Recurrent Network for Video Frame Interpolation | -- | [CVPR2023](https://arxiv.org/pdf/2211.03456.pdf) | -- | Flow-based, Forward warping, Cost volume |
| Exploring Motion Ambiguity and Alignment for High-Quality Video Frame Interpolation | -- | [CVPR2023](https://arxiv.org/pdf/2203.10291.pdf) | -- | -- |
| Frame Interpolation Transformer and Uncertainty Guidance | -- | [CVPR2023]() | -- | -- |
| Exploring Discontinuity for Video Frame Interpolation | -- | [CVPR2023](https://arxiv.org/pdf/2202.07291.pdf) | -- | Discontinuious motion |
| BiFormer: Learning Bilateral Motion Estimation via Bilateral Transformer for 4K Video Frame Interpolation | BiFormer | [CVPR2023](https://arxiv.org/pdf/2202.07291.pdf) | [TBD](https://github.com/JunHeum/BiFormer) ![Github stars](https://img.shields.io/github/stars/JunHeum/BiFormer) | Flow-based, Transformer, Cost Volume |
| Extracting Motion and Appearance via Inter-Frame Attention for Efficient Video Frame Interpolation | EMA-VFI | [CVPR2023](https://arxiv.org/pdf/2303.00440.pdf) | [Pytorch](https://github.com/MCG-NJU/EMA-VFI) ![Github stars](https://img.shields.io/github/stars/MCG-NJU/EMA-VFI) | Flow-based, Transformer |
| Range-nullspace Video Frame Interpolation with Focalized Motion Estimation | -- | [CVPR2023]() | -- | -- |
| AMT: All-Pairs Multi-Field Transforms for Efficient Frame Interpolation | AMT | [CVPR2023]() | [Pytorch]() | Flow-based, All-pair Cost volume, Multiple flows |

*The keywords `Multiple Frames` means the number of input frames is more than two.

*Above methods exclude Spatial-Temporal Super Resolution, Event-based Frame Interpolation and other joint tasks (*e.g.* deblur+VFI). Coming soon! (Perhaps not soon)
