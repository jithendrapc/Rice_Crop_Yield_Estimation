# Rice_Crop_Yield_Estimation
The goal is to predict the yield of rice crop at a given location using satellite data. By the time, we would have developed a rice crop yield forecasting model, which can predict the yield of rice crop.
In this notebook, we will demonstrate a basic model workflow that can serve as a starting point for the challenge. The basic model has been built to predict the yield of rice crop in Vietnam using features from Sentinel-1 Radiometrically Terrain Corrected (RTC) dataset as predictor variables. In this demonstration, we have used statistical features generated from the bands (VV and VH) of the Sentinel-1 RTC dataset and mathematical combinations of these bands (VV/VH). We have trained an extra tree regressor model with these features. We have extracted the VV and VH band data from the Sentinel-1 dataset for summer autumn (SA) /winter spring (WS) season for the year 2022 based on the data provided.

Most of the functions presented in this notebook were adapted from the Sentinel-1-RTC notebook found in the Planetary Computer portal.

