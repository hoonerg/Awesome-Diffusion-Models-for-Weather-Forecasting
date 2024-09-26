# Awesome Diffusion Models for Weather Forecasting 
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hoonerg/Awesome-Diffusion-Models-for-Weather-Forecasting) ![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) 

A collection of research papers on Diffusion Models for Weather Forecasting.  
The papers are ordered by date.

I check Arxiv weekly and add any diffusion-related papers on topics in atmospheric science.  
I might miss the publication of a paper if it is published after its initial upload to Arxiv.

## Diffusion Models
| Model              | Paper                      | Topic                      | Publication    | Date (&darr;) | Links                                         |
| ------------------ | -------------------------- | -------------------------- | -------------- | -------- | --------------------------------------------- |
| -            | Diffusion Models for High-Resolution Solar Forecasts | Cloud Cover Forecasting | - | 2023.02  | [[paper]](https://arxiv.org/pdf/2302.00170v1.pdf)   |
| LDCast            | Latent diffusion models for generative precipitation nowcasting with accurate uncertainty quantification | Precipitation Nowcasting | - | 2023.04  | [[paper]](https://arxiv.org/pdf/2304.12891.pdf) [[code]](https://github.com/MeteoSwiss/ldcast)  |
| DiffESM | Conditional Emulation of Earth System Models with Diffusion Models | Emulation | ICLR 2023 Workshop | 2023.04  | [[paper]](https://arxiv.org/pdf/2304.11699.pdf) [[code]](https://github.com/JGCRI/diffesm)  |
| SEEDS            | Emulation of Weather Forecast Ensembles with Diffusion Models | Ensemble Forecast Emulation | Science Advances | 2023.06  | [[paper]](https://arxiv.org/pdf/2306.14066.pdf)  |
| DYffusion | A Dynamics-informed Diffusion Model for Spatiotemporal Forecasting | Spatiotemporal Forecasting | NeurIPS 2024 | 2023.06  | [[paper]](https://arxiv.org/pdf/2306.01984.pdf) [[code]](https://github.com/Rose-STL-Lab/dyffusion)  |
| SwinRDM            |  Integrate SwinRNN with Diffusion Model towards High-Resolution and High-Quality Weather Forecasting | Global Weather Forecasting | AAAI 2023 | 2023.06  | [[paper]](https://arxiv.org/pdf/2306.03110.pdf)  |
| PreDiff            |  Precipitation Nowcasting with Latent Diffusion Models | Precipitation Nowcasting | NeurIPS 2023 | 2023.07  | [[paper]](https://arxiv.org/pdf/2307.10422.pdf) [[code]](https://github.com/gaozhihan/PreDiff)  |
| GDE            | Precipitation nowcasting with generative diffusion models | Precipitation Nowcasting | - | 2023.08  | [[paper]](https://arxiv.org/pdf/2308.06733.pdf) [[code]](https://github.com/fmerizzi/Precipitation-nowcasting-with-generative-diffusion-models)  |
| CorrDiff            | Residual Diffusion Modeling for Km-scale Atmospheric Downscaling | Downscaling | - | 2023.10  | [[paper]](https://arxiv.org/pdf/2309.15214.pdf) |
| FuXi-Extreme | Improving extreme rainfall and wind forecasts with diffusion model | Global (Extreme) Weather Forecasting | - | 2023.10  | [[paper]](https://arxiv.org/pdf/2310.19822.pdf) |
| OF-Diff            | Probabilistic Precipitation Downscaling with Optical Flow-Guided Diffusion | Downscaling | - | 2023.11  | [[paper]](https://arxiv.org/pdf/2312.06071.pdf) |
| GenCast            | GenCast: Diffusion-based ensemble forecasting for medium-range weather | Global Weather Forecasting | - | 2023.12  | [[paper]](https://arxiv.org/pdf/2312.15796)   |
| DiffCast            | A Unified Framework via Residual Diffusion for Precipitation Nowcasting | Precipitation Nowcasting | CVPR 2024 | 2023.12  | [[paper]](https://arxiv.org/pdf/2312.06734.pdf) [[code]](https://github.com/DeminYu98/DiffCast) |
| DGDM            | Deterministic Guidance Diffusion Model for Probabilistic Weather Forecasting | Weather Forecasting using Satellite | ECCV 2024 | 2023.12  | [[paper]](https://arxiv.org/pdf/2312.02819.pdf) [[code]](https://github.com/DongGeun-Yoon/DGDM?tab=readme-ov-file)  |
| - | Advancing Realistic Precipitation Nowcasting With a Spatiotemporal Transformer-Based Denoising Diffusion Model | Precipitation Nowcasting | IEEE TGRS | 2024.01  | [[paper]](https://ieeexplore.ieee.org/abstract/document/10403855)  |
| DiffDA            | A diffusion model for weather-scale data assimilation | Data Assimilation | - | 2024.01  | [[paper]](https://arxiv.org/pdf/2401.05932.pdf) [[code]](https://github.com/spcl/DiffDA) |
| LT3P            | Long-Term Typhoon Trajectory Prediction: A Physics-Conditioned Approach Without Reanalysis Data | Tropical Cyclone Trajectory Forecasting | ICLR 2024 | 2024.01  | [[paper]](https://arxiv.org/pdf/2401.15726.pdf) [[code]](https://github.com/iclr2024submit/LT3P) |
| -            | Wind speed super-resolution and validation: from ERA5 to CERRA via diffusion models | Super resolution | - | 2024.01  | [[paper]](https://arxiv.org/pdf/2401.15469.pdf) [[code]](https://github.com/fmerizzi/ERA5-to-CERRA-via-Diffusion-Models/) |
| ExtremeCast | Boosting Extreme Value Prediction for Global Weather Forecast | Global (Extreme) Weather Forecasting | - | 2024.02  | [[paper]](https://arxiv.org/pdf/2402.01295.pdf)  |
| CasCast            | Skillful High-resolution Precipitation Nowcasting via Cascaded Modelling | Precipitation Nowcasting | - | 2024.02  | [[paper]](https://arxiv.org/pdf/2402.04290.pdf)  |
| SDEdit-Weather            | Weather Prediction with Diffusion Guided by Realistic Forecast Processes | Global Weather Forecasting | - | 2024.02  | [[paper]](https://arxiv.org/pdf/2402.06666.pdf)  |
| - | Physics-Informed Diffusion Model and Sampling for Global Weather Forecasting | Global Weather Forecasting | - | 2024.03  | [[paper]](https://doi.org/10.5194/egusphere-egu24-13882)  |
| DiffObs | Generative Diffusion for Global Forecasting of Satellite Observations | Global Preciptation Forecasting | ICLR 2024 Workshop | 2024.04  | [[paper]](https://arxiv.org/pdf/2404.06517.pdf)  |
| - | Diffusion-Based Joint Temperature and Precipitation Emulation of Earth System Models | Emulation | ICLR 2024 Workshop | 2024.04  | [[paper]](https://arxiv.org/pdf/2404.08797.pdf)  |
| SLAMS | Deep Generative Data Assimilation in Multimodal Setting | Data Assimilation | - | 2024.04  | [[paper]](https://arxiv.org/pdf/2404.06665) [[code]](https://github.com/yongquan-qu/SLAMS)  |
| ClimateDiffuse | Generative Diffusion-based Downscaling for Climate | Downscaling | - | 2024.04  | [[paper]](https://arxiv.org/pdf/2404.17752) [[code]](https://github.com/robbiewatt1/ClimateDiffuse)  |
| CloudDiff | Super-resolution ensemble retrieval of cloud properties for all day using the generative diffusion model | Super-resolution | - | 2024.05  | [[paper]](https://arxiv.org/pdf/2405.04483)  |
| Spherical DYffusion | Probabilistic Emulation of a Global Climate Model with Spherical DYffusion | Global Climate Modelling | - | 2024.06  | [[paper]](https://arxiv.org/pdf/2406.14798)  |
| - | Towards diffusion models for large-scale sea-ice modelling | Sea-Ice modelling | - | 2024.06  | [[paper]](https://arxiv.org/pdf/2406.18417)  |
| AIFS | ECMWF's data-driven forecasting system | Global Weather Forecasting | - | 2024.06  | [[paper]](https://arxiv.org/pdf/2406.01465) |
| - | Generative Data Assimilation of Sparse Weather Station Observations at Kilometer Scales | Data Assimilation | - | 2024.06  | [[paper]](https://arxiv.org/pdf/2406.16947)  |
| - | Latent Diffusion Model for Generating Ensembles of Climate Simulations | Ensemble Forecasting | - | 2024.07  | [[paper]](https://arxiv.org/pdf/2407.02070)  |
| CPMGEM | Machine learning emulation of precipitation from km-scale regional climate simulations using a diffusion model | Precipitation Forecasting | - | 2024.07  | [[paper]](https://arxiv.org/pdf/2407.14158) [[code]](https://github.com/henryaddison/mlde)  |
| - | Forecasting Tropical Cyclones with Cascaded Diffusion Models | TC/Precipitation Forecasting | ICLR 2024 Workshop | 2024.07  | [[paper]](https://arxiv.org/pdf/2310.01690) [[code]](https://github.com/p3jitnath/forecast-diffmodels)  |
| KESHDiff | Generative Diffusion Model-based Downscaling of Observed Sea Surface Height over Kuroshio Extension since 2000 | Downscaling | - | 2024.08  | [[paper]](https://arxiv.org/pdf/2408.12632) |
| StormCast | Kilometer-Scale Convection Allowing Model Emulation using Generative Diffusion Modeling | Emulation | - | 2024.08  | [[paper]](https://arxiv.org/pdf/2408.10958)  |
| DifERS | A Generative Diffusion Model for Probabilistic Ensembles of Precipitation Maps Conditioned on Multisensor Satellite Observations | Precipitation Forecasting | - | 2024.09  | [[paper]](https://arxiv.org/pdf/2409.16319) [[code]]()  |
| CoDiCast | Conditional Diffusion Model for Weather Prediction with Uncertainty Quantification | Global Weather Forecasting | - | 2024.09  | [[paper]](https://arxiv.org/pdf/2409.05975) [[code]](https://github.com/JimengShi/CoDiCast)  |
| - | - | - | - | 2024.00  | [[paper]]() [[code]]()  |
