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
1. TE_landscape (Fig. 1): [Jupyter Notebook](https://github.com/ventson/hscTE/blob/main/TE_landscape/TE_landscape.ipynb) | [Source data](https://bis.zju.edu.cn/hscTE/download/TE_landscape.tar.gz)
- Human data processing
1. EHT_RNA_Preprocessing (Fig. 2): [Jupyter Notebook](https://github.com/ventson/hscTE/blob/main/human_data_processing/1_EHT_RNA_Preprocessing/sample_human_agm.ipynb) | [Source data](https://bis.zju.edu.cn/hscTE/download/human_data_processing/1_EHT_RNA_Preprocessing.tar.gz)
2. EHT_Trajectory_Reconstruction
3. EHT_TE_Expression
4. EHT_TE_hdWGCNA
5. EHT_TE_Silencing_Relaxation
6. EHT_TE_Sensing
7. EHT_Spatial_Transcriptome
8. EHT_TE_Hypoxia
9. HUVEC_Hypoxia_Bulk
