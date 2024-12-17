# Class Label Conditioning Diffusion Model for Robust Brain Tumor MRI Synthesis

This repository contains the code for the project "Class Label Conditioning Diffusion Model for Robust Brain Tumor MRI Synthesis".

## Dataset
https://usf.box.com/s/cssdhtgudaphhibsf8989mrhzhpn2oj2

## Paper abstract

**<p align="center">Figure: Proposed Class Label Conditioning Diffusion Model Framework.</p>**
<p align="center">
<img src="https://github.com/quocnh/DF_MRI/blob/main/fig_framework_df.png"/>
</p>

Generating realistic and contextually relevant brain tumor images is a challenging task in medical image synthesis. The scarcity of labeled tumor images, coupled with the intricate similarities and variations between tumor and non-tumor regions, as well as the diverse spectrum of brain tumor types, present formidable barriers to achieving accurate image synthesis. While existing research has explored various techniques for medical image synthesis, there is a gap in investigating the use of label conditional diffusion models for tumor image synthesis, particularly for brain tumors. In this study, we propose a novel approach for robust and trustworthy brain tumor MRI image synthesis using a label conditional diffusion model. By incorporating label conditioning, our approach effectively captures the specific features associated with tumor tissue, resulting in high-quality tumor images. We introduce a trustworthiness control mechanism using evaluation metrics such as Fréchet Inception Distance (FID) and Inception Score (IS) to ensure the generated MRI brain tumor images meet stringent quality, accuracy, and clinical relevance criteria. Our framework demonstrates its efficacy in generating accurate tumor representations, even with a limited and imbalanced dataset. Furthermore, our approach addresses challenges related to image similarities and variations in brain tumor images, surpassing the performance of conditional generative adversarial networks (GANs) by producing realistic details and textures. While sharpness may be limited due to resolution constraints, our conditional diffusion model-based framework fills a critical research gap in brain tumor image synthesis and significantly contributes to the field.
## Output
**<p align="center">Figure: Comparison between with/without class condition.</p>**
<p align="center">
<img src="https://github.com/quocnh/DFMRI/blob/main/project4_output.png"/>
</p>

**<p align="center">Figure: Output Quality Control.</p>**
<p align="center">
<img src="https://github.com/quocnh/DFMRI/blob/main/project4_output1.png"/>
</p>

## Project Structure
```
|---- Dataset
|---- Source
|---- README.md
```

## Reproduce 1,2,3:
```
|---- Ver3_DiffusionModel_with_DataPre.ipynb
|---- Ver3_Diffusion Mode_without_PreProcessingl.ipynb
|---- ver2_diffusion_model_no_condition.ipynb
```
## Reproduce Exp4:
```
|----GAN
     |----Conditional_WGAN.ipynb
     |----WGAN.ipynb

```


## Citation
If you find this repository useful in your research, please cite the following articles as: 

```
Cite as: Quoc Nguyen , Trung Le , Thang Nguyen , et al. Class Label Conditioning Diffusion Model for Robust Brain Tumor MRI Synthesis. TechRxiv. October 11, 2023.
DOI: 10.36227/techrxiv.24243829.v1

```

