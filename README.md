## Systematic single-cell analysis reveals dynamic control of transposable element activity orchestrating the endothelial-to-hematopoietic transition
![image](https://bis.zju.edu.cn/hscTE/img/hscTE.jpg)  
Here we provide the entire processing pipeline for reproducing the results in the manuscript. This pipeline may facilitate the study of transposable elements (TEs) in the context of stem cell development and other cell type transition systems.
### Execution requirements
- [R (recommend >=4.2)](https://cran.r-project.org/)
- [Python (recommend >=3.9)](https://www.python.org/)
- [(Optional but recommend) Jupyter Notebook](https://jupyter.org/)
- Other packages (see session info at the end of each notebook)
### Pipelines and data
- TE landscape analysis
1. TE_landscape (Fig. 1): [Jupyter](https://github.com/ventson/hscTE/blob/main/TE_landscape/TE_landscape.ipynb) | [Source data](https://bis.zju.edu.cn/hscTE/download/TE_landscape.tar.gz)
- Human data processing
1. EHT_RNA_Preprocessing (Fig. 2): [Jupyter](https://github.com/ventson/hscTE/blob/main/human_data_processing/1_EHT_RNA_Preprocessing/sample_human_agm.ipynb) | [Source data](https://bis.zju.edu.cn/hscTE/download/human_data_processing/1_EHT_RNA_Preprocessing.tar.gz)
2. EHT_Trajectory_Reconstruction (Fig. 2, Fig. 8): [Jupyter](https://github.com/ventson/hscTE/blob/main/human_data_processing/2_EHT_Trajectory_Reconstruction/sample_human_velocity.ipynb) | [Source data](https://bis.zju.edu.cn/hscTE/download/human_data_processing/2_EHT_Trajectory_Reconstruction.tar.gz)
3. EHT_TE_Expression (Fig. 2, Fig. 3, Fig. 4, Fig. 8): [Jupyter 1](https://github.com/ventson/hscTE/blob/main/human_data_processing/3_EHT_TE_Expression/sample_human_TE_EHT.ipynb), [Jupyter 2](https://github.com/ventson/hscTE/blob/main/human_data_processing/3_EHT_TE_Expression/sample_human_TE_AGM.ipynb) | [Source data](https://bis.zju.edu.cn/hscTE/download/human_data_processing/3_EHT_TE_Expression.tar.gz)
4. EHT_TE_hdWGCNA (Fig. 3): [Jupyter](https://github.com/ventson/hscTE/blob/main/human_data_processing/4_EHT_TE_hdWGCNA/sample_human_TE_hdWGCNA.ipynb) | [Source data](https://bis.zju.edu.cn/hscTE/download/human_data_processing/4_EHT_TE_hdWGCNA.tar.gz)
5. EHT_TE_Silencing_Relaxation (Fig. 4): [Jupyter](https://github.com/ventson/hscTE/blob/main/human_data_processing/5_EHT_TE_Silencing_Relaxation/sample_human_TE_silencing_relaxation.ipynb) | [Source data](https://bis.zju.edu.cn/hscTE/download/human_data_processing/5_EHT_TE_Silencing_Relaxation.tar.gz)
6. EHT_TE_Sensing (Fig. 5): [Jupyter](https://github.com/ventson/hscTE/blob/main/human_data_processing/6_EHT_TE_Sensing/sample_human_TE_sensing.ipynb) | [Source data](https://bis.zju.edu.cn/hscTE/download/human_data_processing/6_EHT_TE_Sensing.tar.gz)
7. EHT_Spatial_Transcriptome (Fig. 8): [Jupyter](https://github.com/ventson/hscTE/blob/main/human_data_processing/7_EHT_Spatial_Transcriptome/sample_human_spatial.ipynb) | [Source data](https://bis.zju.edu.cn/hscTE/download/human_data_processing/7_EHT_Spatial_Transcriptome.tar.gz)
8. EHT_TE_Hypoxia (Fig. 8): [Jupyter](https://github.com/ventson/hscTE/blob/main/human_data_processing/8_EHT_TE_Hypoxia/sample_human_TE_hypoxia.ipynb) | [Source data](https://bis.zju.edu.cn/hscTE/download/human_data_processing/8_EHT_TE_Hypoxia.tar.gz)
9. HUVEC_Hypoxia_Bulk (Fig. 8): [Jupyter](https://github.com/ventson/hscTE/blob/main/human_data_processing/9_HUVEC_Hypoxia_Bulk/sample_huvec_hypoxia.ipynb) | [Source data](https://bis.zju.edu.cn/hscTE/download/human_data_processing/9_HUVEC_Hypoxia_Bulk.tar.gz)
