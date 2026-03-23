# Harvesting AlphaEarth

![alt text](https://github.com/yuchima8/Harvest_AlphaEarth/blob/main/HarvestAlphaEarth.png)

This is the homepage for the project __Harvesting AlphaEarth: Benchmarking the Geospatial Foundation Model for Agricultural Downstream Tasks__. 

# Motivation
In 2025, Google DeepMind introduced AlphaEarth Foundation (AEF), a GFM pre-trained using multi-source EOs across continuous time. An annual, global embedding dataset is produced using AEF, ready for analysis and modeling. The internal experiments show that AEF embeddings have outperformed operational models in 15 EO tasks without re-training. 

However, those experiments are mostly about land cover and land use classification. Applying AEF and other GFMs to agricultural monitoring requires an in-depth evaluation in critical agricultural downstream tasks. There is also a lack of comprehensive comparison between the AEF-based models and traditional remote sensing (RS)-based models under different scenarios, which could offer valuable guidance for researchers and practitioners. This study addresses some of these gaps by evaluating AEF embeddings in three agricultural downstream tasks: crop yield prediction, tillage type classification, and cover crop detection.

# Contribution
__Scope__: We systematically evaluate AEF embeddings across tasks at different scales and locations in US, and RS-based models are trained as comparison models.

__Findings__: We identify several limitations in current AEF embeddings, such as limited spatial transferability compared to RS-based models, low interpretability, and limited time sensitivity.

__Workflow__: We propose a benchmarking workflow and datasets that can be readily applied to evaluate future GFMs and facilitate their use in agricultural downstream applications


# Method

This evaluation scheme is built on four pillars: 

__Region-Year Cross-Validation__: assessing local performance using standard spatial-temporal cross-validation

__Yearly Cross-Validation__:testing temporal generalizability with a yearly CV scheme 

__Space-Transfer__: testing spatial transferability across distinct ecoregions

__Scale-Transfer__: evaluating scale transferability from coarse to fine resolutions. 

This holistic approach allows us to diagnose not just how well the embeddings perform, but under what conditions they succeed or fail, providing generalizable insights for the broader GFM field.

<img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/f975e233-d937-4c07-8ed5-1811d77e4a05" />

# Code and Data

The codes and data for county-level corn yield prediction are provided.

# Publication
