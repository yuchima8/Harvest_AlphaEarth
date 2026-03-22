# Harvesting AlphaEarth

This is the homepage for the project Harvesting AlphaEarth: Benchmarking the geospatial Foundation model for agricultural downstream tasks. 

# Motivation
In 2025, Google DeepMind introduced AlphaEarth Foundation (AEF), a GFM pre-trained using multi-source EOs across continuous time. An annual, global embedding dataset is produced using AEF, ready for analysis and modeling. The internal experiments show that AEF embeddings have outperformed operational models in 15 EO tasks without re-training. 

However, those experiments are mostly about land cover and land use classification. Applying AEF and other GFMs to agricultural monitoring requires an in-depth evaluation in critical agricultural downstream tasks. There is also a lack of comprehensive comparison between the AEF-based models and traditional remote sensing (RS)-based models under different scenarios, which could offer valuable guidance for researchers and practitioners. This study addresses some of these gaps by evaluating AEF embeddings in three agricultural downstream tasks in the U.S., including crop yield prediction, tillage type classification, and cover crop detection.

# Contribution
(1) We systematically evaluate AEF embeddings across tasks at different scales and locations, and RS-based models are trained as comparison models.

(2) We identify several limitations in current AEF embeddings, such as limited spatial transferability compared to RS-based models, low interpretability, and limited time sensitivity.

(3) We propose a benchmarking workflow and datasets that can be readily applied to evaluate future GFMs and facilitate their use in agricultural downstream applications



# Method

This evaluation scheme is built on four pillars: (1) assessing local performance using standard spatial-temporal cross-validation; (2) testing temporal generalizability with a yearly CV scheme; (3) testing spatial transferability across distinct ecoregions; and (4) evaluating scale transferability from coarse to fine resolutions. This holistic approach allows us to diagnose not just how well the embeddings perform, but under what conditions they succeed or fail, providing generalizable insights for the broader GFM field.<img width="468" height="106" alt="image" src="https://github.com/user-attachments/assets/693845ff-964d-4a4c-bff9-1329e3624ac8" />

<img width="468" height="142" alt="image" src="https://github.com/user-attachments/assets/f975e233-d937-4c07-8ed5-1811d77e4a05" />

