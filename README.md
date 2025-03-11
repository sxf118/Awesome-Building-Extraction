# Awesome-Building-Extraction
📚 A collection of datasets / free productions / codes about Building Extraction with Deep Learning. 


### Datasets

#### Single-Source

| Dataset Name                   | Annotation Type  | Download Link                                                |
|:------------------------------ |:--------------- |:------------------------------------------------------------ |
| Massachusetts Building Dataset | Raster          | [Download](https://www.kaggle.com/datasets/balraj98/massachusetts-buildings-dataset) |
| INRIA Aerial Image Labeling    | Raster          | [Download](https://project.inria.fr/aerialimagelabeling/)    |
| Bing Huts                      | Raster          | [Download](https://github.com/dmarcosg/DSAC)                 |
| AiCrowd Mapping Challenge      | Polygon         | [Download](https://www.aicrowd.com/challenges/mapping-challenge) |
| OpenAI Dataset                 | Polygon         | [Download](https://aistudio.baidu.com/aistudio/datasetdetail/76145) |
| Vaihingen Buildings            | Raster         | [Download](https://github.com/dmarcosg/DSAC)                 |
| WHU Aerial Imagery Dataset     | Raster         | [Download](https://gpcv.whu.edu.cn/data/building_dataset.html) |
| WHU Satellite Dataset I        | Raster         | [Download](https://gpcv.whu.edu.cn/data/building_dataset.html) |
| WHU Satellite Dataset II       | Raster/Polygon | [Download](https://gpcv.whu.edu.cn/data/building_dataset.html) |
| SpaceNet7                      | Polygon         | [Download](https://spacenet.ai/datasets/)                    |
| SDLED                          | Raster         | [Download](https://www.kaggle.com/datasets/balraj98/massachusetts-buildings-dataset) |
| Sentinel-2                     | Raster         | [Download](https://drive.google.com/drive/folders/1rIVCRvSl1eU0Ee9sSF1GV0WzG2rH2e9R%3fusp%3dsharing) |
| SpaceNet8                      | Polygon         | [Download](https://spacenet.ai/datasets/)                    |
| UBCv1                          | Polygon        | [Download](https://github.com/AICyberTeam/UBC-dataset)       |
| BONAI                          | Polygon        | [Download](https://github.com/jwwangchn/BONAI.git)           |
| OmniCity                       | Polygon/Raster (Height) | [Download](https://opendatalab.com/OpenDataLab/OmniCity)     |
| WHU-Mix                        | Raster/Polygon | [Download (raster)](https://gpcv.whu.edu.cn/data/whu-mix(raster)/whu_mix%20(raster).html), [Download (vector)](https://gpcv.whu.edu.cn/data/whu-mix%20(vector)/whu_mix(vector).html) |
| SMAB                           | Polygon         | [Download](https://github.com/AngCV/SMAB_DATASET)            |
| BFE-Set                        | Raster         | [Download](https://github.com/WangZhenqing-RS/BFE-Set)       |

#### Multi-source

| Dataset Name       | Annotation Type  | Download Link                                                |
|:------------------ |:--------------- |:------------------------------------------------------------ |
| ISPRS 2D Vaihingen | Raster          | [Download](https://www.isprs.org/education/benchmarks/UrbanSemLab/2d-sem-label-vaihingen.aspx) |
| ISPRS 2D Postdam   | Raster          | [Download](https://www.isprs.org/education/benchmarks/UrbanSemLab/2d-sem-label-potsdam.aspx) |
| USGS               | Polygon         | [Download](https://figshare.com/articles/dataset/San_Francisco_California_-_Aerial_imagery_object_identification_dataset_for_building_and_road_detection_and_building_height_estimation/3504350) |
| SpaceNet1          | Polygon         | [Download](https://spacenet.ai/datasets/)                    |
| SpaceNet2          | Polygon         | [Download](https://spacenet.ai/datasets/)                    |
| SpaceNet4          | Polygon         | [Download](https://spacenet.ai/datasets/)                    |
| SpaceNet6          | Polygon         | [Download](https://spacenet.ai/datasets/)                    |
| BISM               | Raster/Polygon  | [Download](https://github.com/yuanqinglie/Building-instance-segmentation-combining-anchor-free-detectors-and-multi-modal-feature-fusion.git) |
| DFC23              | Polygon         | [Download](https://ieee-dataport.org/competitions/2023-ieee-grss-data-fusion-contest-large-scale-fine-grained-building-classification) |
| UBCv2              | Polygon         | [Download](https://github.com/AICyberTeam/UBC-dataset/tree/UBCv2) |


### Productions

| Production Name                      | Access Link                                                  |
|:------------------------------------ |:------------------------------------------------------------ |
| Google Open Buildings                | [Link](https://sites.research.google/gr/open-buildings/)     |
| Google Open Buildings Temporal       | [Link](https://sites.research.google/gr/open-buildings/temporal/) |
| Microsoft GlobalMLBuildingFootprints | [Link](https://github.com/microsoft/GlobalMLBuildingFootprints) |
| EUBUCCO                              | [Link](https://eubucco.com/)                                 |
| 90-cities                            | [Link](https://www.cnopendata.com/en/data/m/meteorological/Vectorized-rooftop-area-data-for-90-cities-in-China.html) |
| CBRA                                 | [Link](https://zenodo.org/records/7500612)                   |
| GABLE                                | [Link](https://github.com/AICyberTeam/GABLE)                 |
| East Asian Buildings                 | [Link](https://doi.org/10.5281/zenodo.8174931)               |
| CBF                                  | [Link](http://dx.doi.org/10.5281/zenodo.10043351)|


### Open-Source Codes

| Methods     | Input Type    | Output Type | Paper                                                        | Access Link                                                  |
|:----------- |:------------- |:----------- |:------------------------------------------------------------ |:------------------------------------------------------------ |
| STT         | Single-Source | Raster      | [RS 2021](https://www.mdpi.com/2072-4292/13/21/4441)         | [Link](https://github.com/KyanChen/STT)                      |
| FFL         | Single-Source | Polygon     | [CVPR 2021](https://openaccess.thecvf.com/content/CVPR2021/papers/Girard_Polygonal_Building_Extraction_by_Frame_Field_Learning_CVPR_2021_paper.pdf) | [Link](https://github.com/Lydorn/Polygonization-by-Frame-Field-Learning) |
| ASLNet      | Single-Source | Raster      | [TIP 2021](https://ieeexplore.ieee.org/document/9653801)     | [Link](https://github.com/ggsDing/ASLNet)                    |
| CBRNet      | Single-Source | Raster      | [ISPRS JPRS 2022](https://www.sciencedirect.com/science/article/pii/S0924271621002975) | [Link](https://github.com/HaonanGuo/CBRNet)                  |
| BuildFormer | Single-Source | Raster      | [TRGS 2022](https://ieeexplore.ieee.org/document/9808187/)   | [Link](https://github.com/WangLibo1995/BuildFormer)          |
| CVNet       | Single-Source | Polygon     | [CVPR 2022](https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_CVNet_Contour_Vibration_Network_for_Building_Extraction_CVPR_2022_paper.pdf) | [Link](https://github.com/xzq-njust/CVNet)                   |
| CGSANet     | Single-Source | Raster      | [JSTARS 2022](https://ieeexplore.ieee.org/document/9664368/) | [Link](https://github.com/MrChen18/CGSANet)                  |
| U-Net-AFM   | Single-Source | Raster      | [TRGS 2022](https://ieeexplore.ieee.org/document/9808187/)   | [Link](https://github.com/lqycrystal/AFM_building)           |
| C3Net       | Single-Source | Raster      | [KBS 2023](https://www.sciencedirect.com/science/article/pii/S0950705123000333) | [Link](https://github.com/TongfeiLiu/C3Net-for-building-extraction) |
| SDSC-UNet   | Single-Source | Raster      | [GRSL 2023](https://ieeexplore.ieee.org/document/10108049)   | [Link](https://github.com/stdcoutzrh/BuildingExtraction)     |
| UANet       | Single-Source | Raster      | [TGRS 2024](https://ieeexplore.ieee.org/document/10418227)   | [Link](https://github.com/Henryjiepanli/Uncertainty-aware-Network) |
| CMGFNet     | Multi-Source  | Raster      | [ISPRS JPRS 2022](https://www.sciencedirect.com/science/article/abs/pii/S0924271621003294) | [Link](https://github.com/hamidreza2015/CMGFNet-Building_Extraction) |


### Citation

```

@article{YUAN2025104253,
author = {Yuan Yuan and Xiaofeng Shi and Junyu Gao},
title = {Building extraction from remote sensing images with deep learning: A survey on vision techniques},
journal = {Computer Vision and Image Understanding},
volume = {251},
pages = {104253},
year = {2025},
doi = {https://doi.org/10.1016/j.cviu.2024.104253}
}

@ARTICLE{10507075,
  author={Shi, Xiaofeng and Gao, Junyu and Yuan, Yuan},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={Enhancing Unimodal Features Matters: A Multimodal Framework for Building Extraction}, 
  year={2024},
  volume={62},
  pages={1-13},
  doi={10.1109/TGRS.2024.3392631}
}

```

