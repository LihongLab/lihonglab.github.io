---
title: "Tools"
permalink: /TOOLS/
# layout: splash
# toc: true
# toc_sticky: true
# toc_label: " "
# toc_icon: "bars"
# header:
#   overlay_color: "#000"
#   overlay_filter: "0"
#   overlay_image: /assets/img/photos/header8.jpg
feature_row1:
  - image_path: /assets/img/tools/disyn.png
    title: "DiSyn"
    excerpt: "This is a python implementation of Disentangled Synthesis Transfer Network (DiSyn) which enhances generalizability of drug response prediction by extracting features related and unrelated to drug responses to synthesize new training samples and improve prediction accuracy of label-scarce target domains."
    url: "https://github.com/LiHongCSBLab/DiSyn"
    btn_class: "btn--primary"
    btn_label: "Learn more"
feature_row2:
  - image_path: /assets/img/tools/jointsyn.png
    title: "JointSyn"
    excerpt: "We have proposed JointSyn that utilizes dual-view jointly learning to predict sample-specific effects of drug combination from drug and cell features. JointSyn capture the drug synergy related features from two views. One view is the embedding of drug combination on cancer cell lines, and the other view is the combination of two drugs' embeddings on cancer cell lines. Finally, the prediction net uses the features learned from the two views to predict the drug synergy of the drug combination on the cell line."
    url: "https://github.com/LiHongCSBLab/JointSyn"
    btn_class: "btn--primary"
    btn_label: "Learn more"
feature_row3:
  - image_path: /assets/img/tools/soapy.png
    title: "SOAPy"
    excerpt: "SOAPy is an integrated toolkit that focuses on addressing spatial heterogeneity. SOAPy contains four data preprocessing modules (“Data Import”, “spatial network”, and “Spatial Domain”), three modules for analyzing spatial expression patterns of genes (“Spatial Variation”, “Spatial Tendency”, and “Spatiotemporal Pattern”), two modules for analyzing the spatial architecture of cells (“Spatial Proximity”, “Spatial Composition”), and two module for analyzing Spatial Communication."
    url: "https://github.com/LiHongCSBLab/SOAPy"
    btn_class: "btn--primary"
    btn_label: "Learn more"      
feature_row4:
  - image_path: /assets/img/tools/Raman.jpg
    title: "Raman Analysis"
    excerpt: "Cell therapy using proliferating human hepatocytes (ProliHHs) is an effective treatment approach for advanced liver diseases. However, rapid and accurate identification of high-quality ProliHHs from different donors is challenging due to individual heterogeneity. Here, we developed a machine learning framework to integrate single-cell Raman spectroscopy from multiple donors and identify different stages of ProliHHs. A repository of more than 14,000 Raman spectra, consisting of primary human hepatocytes (PHHs) and different passages of ProliHHs from six donors, was generated. Using a sliding window algorithm, potential biomarkers distinguishing the different cell stages were identified through differential analysis. Leveraging machine learning models, accurate classification of cell stages was achieved in both within-donor and cross-donor prediction tasks."
    url: "https://github.com/LiHongCSBLab/Raman_ProliHH"
    btn_class: "btn--primary"
    btn_label: "Learn more"
---
# Spatial Omics Analysis

{% include feature_row id="feature_row3" type="left" %}

# Cancer Precision Medicine

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="left" %}

# Single Cell Analysis

{% include feature_row id="feature_row4" type="left" %}