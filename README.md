# Awesome Digital and Computational Pathology with stars

## Contents

* [Software](#software)
  * [Assistant](#assistant)
  * [Image Analysis](#image-analysis)
  * [Image IO](#image-io)
  * [Machine Learning](#machine-learning)
  * [Model](#model)
  * [Foundation Model](#foundation-model)
  * [Platform](#platform)
  * [Viewer](#viewer)
  * [Viewer (Free)](#viewer-free)
* [Data](#data)
  * [Challenges](#challenges)
  * [Datasets](#datasets)
  * [References](#references)
* [Publications](#publications)
  * [Papers](#papers)
  * [Repositories](#repositories)

## Software

### Assistant

* [Digital Pathology Assistant](https://chatgpt.com/g/g-L1IbnIIVt-digital-pathology-assistant-v3-0) - Specify your requirements in plain english and I'll provide PathML and Python code for your use-case.

### Image Analysis

* [TIA Toolbox](https://github.com/TissueImageAnalytics/tiatoolbox/) ⭐ 545 | 🐛 16 | 🌐 Python | 📅 2026-08-21 - Computational pathology toolbox that provides an end-to-end API for pathology image analysis.
* [HistomicsTK](https://github.com/DigitalSlideArchive/HistomicsTK/) ⭐ 485 | 🐛 28 | 🌐 Python | 📅 2026-08-13 - Toolkit for the analysis of digital pathology images.
* [HistoQC](https://github.com/choosehappy/HistoQC/) ⭐ 329 | 🐛 70 | 🌐 JavaScript | 📅 2026-08-03 - Quality control tools for digital pathology.
* [InstanSeg](https://github.com/instanseg/instanseg/) ⭐ 235 | 🐛 14 | 🌐 Python | 📅 2026-07-30 - Cell and nucleus segmentation pipeline for fluorescence and brightfield microscopy images.
* [GrandQC](https://github.com/cpath-ukk/grandqc/) ⭐ 117 | 🐛 27 | 🌐 Python | 📅 2025-12-27 - A comprehensive solution to quality control problem in digital pathology.
* [PyHIST](https://github.com/manuel-munoz-aguirre/PyHIST/) ⭐ 72 | 🐛 8 | 🌐 Python | 📅 2023-04-02 - Histological image segmentation tool.
* [pyslide](https://github.com/PingjunChen/pyslide/) ⭐ 54 | 🐛 0 | 🌐 Python | 📅 2023-04-02 - Digital pathology WSI analysis toolbox.
* [PathProfiler](https://github.com/MaryamHaghighat/PathProfiler/) ⭐ 45 | 🐛 2 | 🌐 Python | 📅 2024-01-04 - Quality assessment of histopathology WSI cohorts.
* [PatchSorter](https://github.com/choosehappy/PatchSorter/) ⭐ 36 | 🐛 18 | 🌐 JavaScript | 📅 2026-08-21 - A tool for rapidly labeling objects using deep learning feature embedding.
* [CellPilot](https://github.com/philippendres/CellPilot/) ⭐ 6 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-05-03 - A unified approach to automatic and interactive segmentation in histopathology.

### Image IO

* [tifffile](https://github.com/cgohlke/tifffile/) ⭐ 663 | 🐛 0 | 🌐 Python | 📅 2026-08-15 - Read and write TIFF-like files using in bioimaging.
* [cuCIM](https://github.com/rapidsai/cucim/) ⭐ 468 | 🐛 157 | 🌐 Jupyter Notebook | 📅 2026-08-20 - NVIDIA's accelerated computer vision and image processing software library for multidimensional images.
* [Bio-Formats](https://github.com/ome/bioformats/) ⭐ 426 | 🐛 174 | 🌐 Java | 📅 2026-08-13 - Java software tool for reading and writing microscopy image using standardized, open formats.
* [WholeSlideData](https://github.com/DIAGNijmegen/pathology-whole-slide-data/) ⭐ 119 | 🐛 6 | 🌐 Python | 📅 2025-11-08 - Batch iterator that enables fast, efficient and easy patch sampling.
* [compay-syntax](https://github.com/jgamper/compay-syntax/) ⭐ 55 | 🐛 6 | 🌐 Python | 📅 2022-11-22 - Tissue mask and tiling pipeline.
* [NGFF-Converter](https://github.com/glencoesoftware/NGFF-Converter/) ⭐ 38 | 🐛 8 | 🌐 Java | 📅 2026-08-19 - GUI application for conversion of bioimage formats into OME-NGFF or OME-TIFF.
* [svg2svs](https://github.com/Ellogon/svg2svs/) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2021-05-07 - Generate checkerboard and build multi-layer pyramidal SVS files from SVG images.
* [libvips](https://www.libvips.org/) - A fast image processing library with low memory needs.
* [OpenSlide](https://openslide.org/) - Provides a simple C interface with Python bindings to read WSIs in multiple formats.

### Machine Learning

* [Trident](https://github.com/mahmoodlab/TRIDENT/) ⭐ 621 | 🐛 41 | 🌐 Python | 📅 2026-08-16 - Toolkit for large-scale WSI processing.
* [PathML](https://github.com/Dana-Farber-AIOS/pathml/) ⭐ 461 | 🐛 52 | 🌐 Python | 📅 2026-08-14 - Tools for computational pathology.
* [histocartography](https://github.com/BiomedSciAI/histocartography/) ⭐ 273 | 🐛 23 | 🌐 Python | 📅 2023-12-23 - Library designed to facilitate the development of graph-based computational pathology pipelines.
* [eva](https://github.com/kaiko-ai/eva/) ⭐ 170 | 🐛 31 | 🌐 Python | 📅 2026-08-05 - Evaluation framework for oncology foundation models.
* [MHIM-MIL](https://github.com/DearCaat/MHIM-MIL/) ⭐ 96 | 🐛 1 | 🌐 Python | 📅 2026-01-07 - Multiple instance learning framework with masked hard instance mining for WSI classification.
* [nuclei.io](https://github.com/huangzhii/nuclei.io/) ⭐ 89 | 🐛 10 | 🌐 Python | 📅 2025-05-18 - Human-in-the-loop active learning framework for pathology image analysis.
* [ENACT](https://github.com/Sanofi-Public/enact-pipeline/) ⭐ 82 | 🐛 10 | 🌐 Python | 📅 2026-02-10 - End-to-end analysis and cell type annotation for Visium HD slides.
* [DLUP](https://github.com/nki-ai/dlup/) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2026-08-09 - Deep learning utilities for pathology.
* [FlashDeconv](https://github.com/cafferychen777/flashdeconv/) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2026-06-30 - High-performance spatial transcriptomics deconvolution for cell type mapping using structure-preserving randomized sketching.
* [Slideflow](https://slideflow.dev/) - Python package that provides a unified API for building and testing deep learning models for histopathology.

### Model

* [LongViT](https://github.com/microsoft/torchscale/blob/main/examples/longvit/) ⭐ 3,137 | 🐛 39 | 🌐 Python | 📅 2024-04-11 - Vision Transformer that can process gigapixel images in an end-to-end manner.
* [CLAM](https://github.com/mahmoodlab/CLAM/) ⭐ 1,726 | 🐛 49 | 🌐 Python | 📅 2025-04-14 - Data-efficient and weakly supervised computational pathology on WSI.
* [StarDist](https://github.com/stardist/stardist/) ⭐ 1,253 | 🐛 70 | 🌐 Python | 📅 2026-02-14 - Object detection with star-convex shapes.
* [HoVer-Net](https://github.com/vqdang/hover_net/) ⭐ 738 | 🐛 68 | 🌐 Python | 📅 2023-10-27 - Simultaneous segmentation and classification of nuclei in multi-tissue histology images.
* [TransMIL](https://github.com/szc19990412/TransMIL/) ⭐ 494 | 🐛 26 | 🌐 Python | 📅 2024-05-03 - Transformer based correlated multiple instance learning for WSI classification.
* [CellViT](https://github.com/TIO-IKIM/CellViT/) ⭐ 393 | 🐛 21 | 🌐 Python | 📅 2025-07-23 - Vision transformers for precise cell segmentation and classification.
* [StainTools](https://github.com/Peter554/StainTools/) ⚠️ Archived - Tools for tissue image stain normalisation and augmentation.
* [DeepLIIF](https://github.com/nadeemlab/DeepLIIF/) ⭐ 259 | 🐛 0 | 🌐 Python | 📅 2026-07-17 - Deep-learning inferred multiplex immunofluorescence for immunohistochemical image quantification.
* [MCAT](https://github.com/mahmoodlab/MCAT/) ⭐ 256 | 🐛 13 | 🌐 Jupyter Notebook | 📅 2022-03-11 - Multimodal co-attention transformer for survival prediction in gigapixel WSIs.
* [torchstain](https://github.com/EIDOSLAB/torchstain/) ⭐ 190 | 🐛 14 | 🌐 Python | 📅 2025-11-13 - Stain normalization transformations.
* [Patch-GCN](https://github.com/mahmoodlab/Patch-GCN/) ⭐ 172 | 🐛 7 | 🌐 Python | 📅 2024-05-14 - WSI are 2D point clouds: Context-aware survival prediction using patch-based graph convolutional networks.
* [PANTHER](https://github.com/mahmoodlab/Panther/) ⭐ 150 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-02-22 - Morphological prototyping for unsupervised slide representation learning in computational pathology.
* [TCGA segmentation](https://github.com/MarvinLer/tcga_segmentation/) ⭐ 142 | 🐛 5 | 🌐 Python | 📅 2021-08-05 - Weakly supervised multiple instance learning histopathological tumor segmentation.
* [ACMIL](https://github.com/dazhangyu123/ACMIL/) ⭐ 137 | 🐛 2 | 🌐 Python | 📅 2025-04-28 - WSI classification.
* [MMP](https://github.com/mahmoodlab/MMP/) ⭐ 120 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-02-22 - Multimodal prototyping for cancer survival prediction.
* [TANGLE](https://github.com/mahmoodlab/TANGLE/) ⭐ 116 | 🐛 6 | 🌐 Python | 📅 2024-10-15 - Transcriptomics-guided slide representation learning in computational pathology.
* [Cell-DETR](https://github.com/ChristophReich1996/Cell-DETR/) ⭐ 107 | 🐛 4 | 🌐 Python | 📅 2022-03-28 - Attention-based transformers for instance segmentation of cells in microstructures.
* [Cerberus](https://github.com/TissueImageAnalytics/cerberus/) ⭐ 103 | 🐛 6 | 🌐 Python | 📅 2024-11-27 - Multi-task learning enables simultaneous histology image segmentation and classification.
* [HistoGPT](https://github.com/marrlab/HistoGPT/) ⭐ 100 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2025-09-04 - Generating highly accurate histopathology reports from whole slide images.
* [HistoSegNet](https://github.com/lyndonchan/hsn_v1/) ⭐ 94 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2020-01-15 - Semantic segmentation of histological tissue type in WSIs.
* [BEPH](https://github.com/Zhcyoung/BEPH/) ⭐ 78 | 🐛 7 | 🌐 Python | 📅 2025-03-24 - BEiT-based model pre-training on WSIs.
* [StainGAN](https://github.com/xtarx/StainGAN/) ⭐ 72 | 🐛 6 | 🌐 Python | 📅 2021-02-04 - Stain style transfer for digital histological images.
* [stainlib](https://github.com/sebastianffx/stainlib/) ⭐ 66 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2022-09-12 - Augmentation & normalization of H\&E images.
* [RSP](https://github.com/srinidhiPY/SSL_CR_Histo/) ⭐ 61 | 🐛 0 | 🌐 Python | 📅 2022-03-05 - Self-supervised driven consistency training for annotation efficient histopathology image analysis.
* [Snuffy](https://github.com/jafarinia/snuffy/) ⭐ 57 | 🐛 0 | 🌐 Python | 📅 2024-09-24 - Efficient WSI classifier.
* [DT-MIL](https://github.com/yfzon/DT-MIL/) ⭐ 38 | 🐛 4 | 🌐 Python | 📅 2021-10-26 - Deformable transformer for multi-instance learning on histopathological image.
* [DiffInfinite](https://github.com/marcoaversa/diffinfinite/) ⭐ 36 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2024-10-30 - Large mask-image synthesis via parallel random patch diffusion in histopathology.
* [MSINet](https://github.com/rikiyay/MSINet/) ⭐ 31 | 🐛 2 | 🌐 Python | 📅 2021-02-11 - Deep learning model for the prediction of microsatellite instability in colorectal cancer.
* [FrOoDo](https://github.com/MECLabTUDA/FrOoDo/) ⭐ 28 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2023-05-15 - Framework for out of distribution detection.
* [DMMN](https://github.com/MSKCC-Computational-Pathology/DMMN/) ⭐ 27 | 🐛 1 | 🌐 Python | 📅 2025-10-15 - Deep Multi-Magnification Network for multi-class tissue segmentation of WSI.
* [SparseConvMIL](https://github.com/MarvinLer/SparseConvMIL/) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2021-10-11 - Sparse convolutional context-aware multiple instance learning for WSI classification.
* [HMIL](https://github.com/ChengJin-git/HMIL/) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2025-12-18 - Hierarchical multi-instance learning for fine-grained WSI classification.
* [fseg](https://github.com/deepathology/fseg/) ⭐ 17 | 🐛 2 | 🌐 Python | 📅 2024-11-21 - Unsupervised semantic segmentation for pathology by factorizing foundation model features.

### Foundation Model

* [UNI](https://github.com/mahmoodlab/UNI/) ⭐ 767 | 🐛 32 | 🌐 Jupyter Notebook | 📅 2025-03-26 - General-purpose foundation model for computational pathology.
* [Prov-GigaPath](https://github.com/prov-gigapath/prov-gigapath/) ⭐ 630 | 🐛 74 | 🌐 Python | 📅 2026-08-07 - A whole-slide foundation model for digital pathology from real-world data.
* [HIPT](https://github.com/mahmoodlab/HIPT/) ⭐ 620 | 🐛 26 | 🌐 Jupyter Notebook | 📅 2024-03-19 - Scaling vision transformers to gigapixel images via hierarchical self-supervised learning.
* [CONCH](https://github.com/mahmoodlab/CONCH/) ⭐ 523 | 🐛 16 | 🌐 Python | 📅 2025-03-26 - Vision-language foundation model for computational pathology.
* [TITAN](https://github.com/mahmoodlab/TITAN/) ⭐ 363 | 🐛 3 | 🌐 Python | 📅 2025-12-13 - Multimodal whole slide foundation model for pathology.
* [TransPath](https://github.com/Xiyue-Wang/TransPath/) ⭐ 360 | 🐛 40 | 🌐 Python | 📅 2025-03-29 - Transformer-based unsupervised contrastive learning for histopathological image classification.
* [MUSK](https://github.com/lilab-stanford/MUSK/) ⭐ 241 | 🐛 4 | 🌐 Python | 📅 2025-10-26 - A vision-language foundation model for precision oncology.
* [PathoDuet](https://github.com/openmedlab/PathoDuet/) ⭐ 225 | 🐛 8 | 🌐 Python | 📅 2024-06-24 - Foundation models for pathological slide analysis of H\&E and IHC stains.
* [Phikon](https://github.com/owkin/HistoSSLscaling/) ⭐ 171 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2024-01-29 - Scaling self-supervised learning for histopathology with masked image modeling.
* [H-optimus](https://github.com/bioptimus/releases/tree/main/models/h-optimus/v0/) ⭐ 109 | 🐛 5 | 📅 2024-11-21 - Foundation model for histology.
* [Hibou](https://github.com/HistAI/hibou/) ⭐ 79 | 🐛 1 | 🌐 Python | 📅 2024-10-23 - A family of foundational vision transformers for pathology.
* [KEEP](https://github.com/MAGIC-AI4Med/KEEP/) ⭐ 69 | 🐛 0 | 🌐 Python | 📅 2026-04-17 - A Knowledge-enhanced pathology vision-language foundation model for cancer diagnosis.
* [VIM4Path](https://github.com/AtlasAnalyticsLab/Vim4Path/) ⭐ 60 | 🐛 0 | 🌐 Python | 📅 2025-07-23 - Self-supervised vision mamba for WSIs.
* [ROAM](https://github.com/whiteyunjie/ROAM/) ⭐ 39 | 🐛 0 | 🌐 Python | 📅 2024-12-11 - A transformer-based weakly supervised computational pathology method for clinical-grade diagnosis and molecular state revelation of gliomas.
* [BiomedCLIP](https://huggingface.co/microsoft/BiomedCLIP-PubMedBERT_256-vit_base_patch16_224/) - Multimodal biomedical foundation model pretrained from fifteen million scientific image-text pairs.
* [PathDino](https://kimialabmayo.github.io/PathDino-Page/) - Rotation-agnostic image representation learning for digital pathology.
* [Path Foundation](https://huggingface.co/google/path-foundation/) - Embedding model for efficiently building AI for histopathology applications.
* [UNI2-h](https://huggingface.co/MahmoodLab/UNI2-h/) - General-purpose foundation model for computational pathology.
* [Virchow](https://huggingface.co/paige-ai/Virchow/) - Self-supervised vision transformer pretrained using 1.5M WSIs.

### Platform

* [Digital Slide Archive](https://digitalslidearchive.github.io/digital_slide_archive/) - Provides the ability to store, manage, visualize and annotate large imaging datasets.

### Viewer

* [slim](https://github.com/ImagingDataCommons/slim/) ⭐ 166 | 🐛 67 | 🌐 TypeScript | 📅 2026-08-20 - Interoperable web-based slide microscopy viewer and annotation tool.
* [QuickAnnotator](https://github.com/choosehappy/QuickAnnotator/) ⭐ 92 | 🐛 30 | 🌐 JavaScript | 📅 2026-08-21 - Model assisted tool for rapid annotation of WSIs.
* [HistomicsUI](https://github.com/DigitalSlideArchive/HistomicsUI/) ⭐ 81 | 🐛 51 | 🌐 JavaScript | 📅 2026-08-11 - Web interface to visualize WSI and manage annotations.
* [DigiPathAI](https://github.com/haranrk/DigiPathAI/) ⭐ 76 | 🐛 10 | 🌐 JavaScript | 📅 2026-02-20 - Tool to visualize gigantic pathology images and use AI to segment cancer cells and present as an overlay.
* [ASAP](https://computationalpathologygroup.github.io/ASAP/) - Desktop application for visualizing, annotating and automatically analyzing WSIs.
* [Cytomine](https://doc.cytomine.org/) - Collaborative analysis of WSIs.
* [QuPath](https://qupath.github.io/) - Java application that enables researchers and pathologists to visualize, analyze and annotate WSIs.

### Viewer (Free)

* [Aperio ImageScope](https://www.leicabiosystems.com/en-ca/digital-pathology/manage/aperio-imagescope/) - Freely downloadable software for viewing WSIs. Windows only.
* [PathPresenter](https://www.pathpresenter.com/) - A complete enterprise workflow platform built by pathologists.

## Data

### Challenges

* [ACDC](https://acdc-lunghp.grand-challenge.org/) - Automatic Cancer Detection and Classification of lung histopathology.
* [ACROBAT](https://acrobat.grand-challenge.org/) - AutomatiC Registration Of Breast cAncer Tissue.
* [ANHIR](https://anhir.grand-challenge.org/) - Automatic Non-rigid Histological Image Registration.
* [BACH](https://iciar2018-challenge.grand-challenge.org/) - BreAst Cancer Histology images.
* [BCI](https://bci.grand-challenge.org/) - Breast Cancer Immunohistochemical image generation.
* [BreastPathQ](https://breastpathq.grand-challenge.org/) - Quantitative biomarkers for the determination of cancer cellularity.
* [CAMELYON16](https://camelyon16.grand-challenge.org/) - Cancer metastasis detection in lymph node.
* [CAMELYON17](https://camelyon17.grand-challenge.org/) - Building on CAMELYON16 by moving from slide level analysis to patient level analysis.
* [CellSeg](https://neurips22-cellseg.grand-challenge.org/) - Cell segmentation in multi-modality high-resolution microscopy images.
* [CoNIC](https://conic-challenge.grand-challenge.org/) - Colon Nuclei Identification and Counting.
* [DigestPath 2019](https://digestpath2019.grand-challenge.org/) - Digestive-system pathological detection and segmentation.
* [ENDO-AID](https://endo-aid.grand-challenge.org/) - Endometrial carcinoma detection in pipelle biopsies.
* [Gleason 2019](https://gleason2019.grand-challenge.org/) - Automatic Gleason grading of prostate cancer in digital histopathology.
* [HER2 Scoring Contest](https://warwick.ac.uk/fac/cross_fac/tia/data/her2contest/) - Automated HER2 scoring algorithms in WSI of breast cancer tissues.
* [HEROHE](https://ecdp2020.grand-challenge.org/) - Predicting HER2 status in breast cancer from H\&E.
* [KPIs](https://sites.google.com/view/kpis2024/) - Kidney Pathology Image segmentation.
* [LEOPARD](https://leopard.grand-challenge.org/leopard/) - LEarning biOchemical Prostate cAncer Recurrence from histopathology sliDes.
* [LYSTO](https://lysto.grand-challenge.org/) - LYmphocytes aSsessment hackathOn in immunohistochemically stained tissue sections.
* [LYON19](https://lyon19.grand-challenge.org/) - LYmphocyte detectiON in IHC stained specimens.
* [MIDOG 2021](https://imig.science/midog2021/) - MItosis DOmain Generalization on tissue preparation and image acquisition.
* [MIDOG 2022](https://imig.science/midog/) - MItosis DOmain Generalization on tissue types.
* [MITOS-ATYPIA-14](https://mitos-atypia-14.grand-challenge.org/) - Detection of mitosis and evaluation of nuclear atypia score.
* [MONKEY](https://monkey.grand-challenge.org/) - Machine-learning for Optimal detection of iNflammatory cells in the KidnEY.
* [MoNuSAC](https://monusac-2020.grand-challenge.org/) - Multi-Organ NUclei Segmentation And Classification.
* [MoNuSeg](https://monuseg.grand-challenge.org/) - Multi-Organ NUclei Segmentation.
* [PAIP2019](https://paip2019.grand-challenge.org/) - Liver cancer segmentation.
* [PAIP2020](https://paip2020.grand-challenge.org/) - Classification and segmentation of microsatellite instability (MSI) in colorectal cancer.
* [PAIP2021](https://paip2021.grand-challenge.org/) - Perineural invasion in multiple organ cancer.
* [PAIP2023](https://2023paip.grand-challenge.org/) - Tumor cellularity prediction in pancreatic cancer and colon cancer.
* [PANDA](https://www.kaggle.com/competitions/prostate-cancer-grade-assessment/) - Prostate cANcer graDe Assessment.
* [SegPC](https://segpc-2021.grand-challenge.org/) - Segmentation of multiple myeloma in Plasma Cells.
* [TIGER](https://tiger.grand-challenge.org/) - Fully automated assessment of tumor-infiltrating lymphocytes (TILs) in H\&E breast cancer slides.
* [TUPAC16](https://tupac.grand-challenge.org/) - TUmor Proliferation Assessment.
* [WSSS4LUAD](https://wsss4luad.grand-challenge.org/) - Weakly-supervised tissue semantic segmentation for lung adenocarcinoma.

### Datasets

* [PCAM](https://github.com/basveeling/pcam/) ⭐ 529 | 🐛 7 | 🌐 Python | 📅 2024-01-31 - PatchCamelyon provides a new benchmark for machine learning models akin to CIFAR-10 and MNIST.
* [HEST](https://github.com/mahmoodlab/hest/) ⭐ 428 | 🐛 24 | 🌐 Jupyter Notebook | 📅 2026-04-16 - Bringing spatial transcriptomics and histopathology together.
* [LC25000](https://github.com/tampapath/lung_colon_image_set/) ⭐ 66 | 🐛 9 | 📅 2020-09-04 - Lung and colon cancer histopathological image dataset.
* [CryoNuSeg](https://github.com/masih4/CryoNuSeg/) ⭐ 45 | 🐛 1 | 🌐 MATLAB | 📅 2023-02-08 - Nuclei segmentation of cryosectioned H\&E-stained histological images.
* [H2T](https://github.com/vqdang/H2T/) ⭐ 37 | 🐛 1 | 🌐 Python | 📅 2023-02-16 - Handcrafted Histological Transformer for unsupervised representation of WSIs.
* [UNITOPATHO](https://github.com/EIDOSLAB/UNITOPATHO/) ⭐ 36 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2023-05-18 - A labeled histopathological dataset for colorectal polyps classification and adenoma dysplasia grading.
* [UNMaSk](https://github.com/pathdata/UNMaSk/) ⭐ 11 | 🐛 9 | 🌐 HTML | 📅 2022-11-22 - Unmasking the immune microecology of ductal carcinoma in situ.
* [MS-SCC](https://github.com/DeepMicroscopy/MultiScanner_SCC/) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2023-08-22 - Multi-scanner squamous cell carcinoma dataset.
* [ARCH](https://warwick.ac.uk/fac/cross_fac/tia/data/arch/) - Multiple instance captioning.
* [BCNB](https://bcnb.grand-challenge.org/) - Early Breast Cancer Core-Needle Biopsy WSI dataset.
* [BCSS](https://bcsegmentation.grand-challenge.org/) - Breast Cancer Semantic Segmentation.
* [BRACS](https://www.bracs.icar.cnr.it/) - BReAst Carcinoma Subtyping.
* [CATCH](https://www.cancerimagingarchive.net/collection/catch/) - CAnine cuTaneous Cancer Histology dataset.
* [CRC](https://zenodo.org/record/1214456/) - 100,000 histological images of human colorectal cancer and healthy tissue.
* [LyNSeC](https://zenodo.org/records/8065174/) - Lymphoma nuclear segmentation and classification dataset.
* [MHIST](https://bmirds.github.io/MHIST/) - Minimalist histopathology image analysis dataset.
* [NuInsSeg](https://www.kaggle.com/datasets/ipateam/nuinsseg/) - A fully annotated dataset for nuclei instance segmentation in H\&E-stained histological images.
* [NuCLS](https://sites.google.com/view/nucls/home/) - A scalable crowdsourcing approach & dataset for nucleus classification, localization and segmentation in breast cancer.
* [OCELOT](https://lunit-io.github.io/research/publications/ocelot/) - Overlapped cell on tissue dataset for histopathology.
* [OBR](https://www.cancerimagingarchive.net/collection/ovarian-bevacizumab-response/) - Ovarian Bevacizumab Response: a dataset of histopathological WSIs for classification of treatment effectiveness to ovarian cancer.
* [PanNuke](https://warwick.ac.uk/fac/cross_fac/tia/data/pannuke/) - Dataset for nuclei instance segmentation and classification.
* [TCGA](https://www.cancer.gov/ccg/research/genome-sequencing/tcga/) - The Cancer Genome Atlas is a landmark cancer genomics program that molecularly characterized over 20,000 primary cancer and matched normal samples spanning 33 cancer types.

### References

* [ADP](https://github.com/mahdihosseini/ADP/) ⭐ 25 | 🐛 1 | 🌐 Python | 📅 2020-06-22 - Atlas of digital pathology for deep learning.
* [Cytomine Collection](https://cytomine.com/collection/) - Open access to high quality WSI in several formats.
* [DICOM WSI Standard](https://dicom.nema.org/dicom/dicomwsi/) - DICOM WSI document.
* [Jerad Gardner, MD](https://www.youtube.com/@JMGardnerMD/) - Popular YouTube channel for educational videos by a pathologist.
* [WebPathology](https://www.webpathology.com/) - Visual survey of surgical pathology.

## Publications

### Papers

* [chen2022self](https://github.com/Richarizardd/Self-Supervised-ViT-Path/) ⭐ 144 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2022-06-09 - Self-Supervised Vision Transformers Learn Visual Concepts in Histopathology.
* [wolflein2023good](https://github.com/georg-wolflein/good-features/) ⭐ 18 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-08-17 - A Good Feature Extractor Is All You Need for Weakly Supervised Pathology Slide Classification.
* [breen2024ovarian](https://github.com/scjjb/Ovarian_Features/) ⭐ 16 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-01-31 - Histopathology foundation models enable accurate ovarian cancer subtype classification.
* [vaidya2024demographic](https://github.com/mahmoodlab/CPATH_demographics/) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2024-04-29 - Demographic bias in misdiagnosis by computational pathology models.
* [matous2024latent](https://github.com/MatousE/rot-invariance-analysis/) ⭐ 1 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-12-17 - Are the latent representations of foundation models for pathology invarient to rotation?
* [kang2022benchmarking](https://lunit-io.github.io/research/publications/pathology_ssl/) - Benchmarking Self-Supervised Learning on Diverse Pathology Datasets.

### Repositories

* [stettler2022datasets](https://github.com/maduc7/Histopathology-Datasets/) ⭐ 570 | 🐛 7 | 📅 2026-03-06 - Resources of histopathology datasets.
* [jahanifar2023domain](https://github.com/mostafajahanifar/awesome-dg-cpath/) ⭐ 25 | 🐛 0 | 📅 2024-11-07 - Awesome domain generalization for computational pathology.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-22._
