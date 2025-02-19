# Awesome Diffusion Models for Weather Forecasting 
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hoonerg/Awesome-Diffusion-Models-for-Weather-Forecasting) ![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) 

A collection of research papers on Diffusion Models for Weather Forecasting.  
The papers are ordered by date.

I check Arxiv weekly and add any diffusion-related papers on topics in atmospheric science.  
I might miss the publication of a paper if it is published after its initial upload to Arxiv.

## Diffusion Models
| Model Name         | Paper Title                | Topic                      | Publication    | Date (&darr;) | Links                                         |
| ------------------ | -------------------------- | -------------------------- | -------------- | -------- | --------------------------------------------- |
| -            | Diffusion Models for High-Resolution Solar Forecasts | Cloud Cover Forecasting | - | 2023.02  | [[paper]](https://arxiv.org/pdf/2302.00170v1.pdf)   |
| LDCast            | Latent diffusion models for generative precipitation nowcasting with accurate uncertainty quantification | Precipitation Nowcasting | - | 2023.04  | [[paper]](https://arxiv.org/pdf/2304.12891.pdf) [[code]](https://github.com/MeteoSwiss/ldcast)  |
| DiffESM | Conditional Emulation of Earth System Models with Diffusion Models | Emulation | ICLR 2023 Workshop | 2023.04  | [[paper]](https://arxiv.org/pdf/2304.11699.pdf) [[code]](https://github.com/JGCRI/diffesm)  |
| SEEDS            | Emulation of Weather Forecast Ensembles with Diffusion Models | Ensemble Forecast Emulation | Science Advances | 2023.06  | [[paper]](https://arxiv.org/pdf/2306.14066.pdf)  |
| DYffusion | A Dynamics-informed Diffusion Model for Spatiotemporal Forecasting | Spatiotemporal Forecasting | NeurIPS 2023 | 2023.06  | [[paper]](https://arxiv.org/pdf/2306.01984.pdf) [[code]](https://github.com/Rose-STL-Lab/dyffusion)  |
| SwinRDM            |  Integrate SwinRNN with Diffusion Model towards High-Resolution and High-Quality Weather Forecasting | Global Weather Forecasting | AAAI 2023 | 2023.06  | [[paper]](https://arxiv.org/pdf/2306.03110.pdf)  |
| PreDiff            |  Precipitation Nowcasting with Latent Diffusion Models | Precipitation Nowcasting | NeurIPS 2023 | 2023.07  | [[paper]](https://arxiv.org/pdf/2307.10422.pdf) [[code]](https://github.com/gaozhihan/PreDiff)  |
| GDE            | Precipitation nowcasting with generative diffusion models | Precipitation Nowcasting | - | 2023.08  | [[paper]](https://arxiv.org/pdf/2308.06733.pdf) [[code]](https://github.com/fmerizzi/Precipitation-nowcasting-with-generative-diffusion-models)  |
| CorrDiff            | Residual Diffusion Modeling for Km-scale Atmospheric Downscaling | Downscaling | - | 2023.10  | [[paper]](https://arxiv.org/pdf/2309.15214.pdf) |
| FuXi-Extreme | Improving extreme rainfall and wind forecasts with diffusion model | Global (Extreme) Weather Forecasting | - | 2023.10  | [[paper]](https://arxiv.org/pdf/2310.19822.pdf) |
| OF-Diff            | Probabilistic Precipitation Downscaling with Optical Flow-Guided Diffusion | Downscaling | - | 2023.11  | [[paper]](https://arxiv.org/pdf/2312.06071.pdf) |
| GenCast            | Diffusion-based ensemble forecasting for medium-range weather | Global Weather Forecasting | Nature | 2023.12  | [[paper]](https://arxiv.org/pdf/2312.15796)  [[code]](https://github.com/google-deepmind/graphcast) |
| DiffCast            | A Unified Framework via Residual Diffusion for Precipitation Nowcasting | Precipitation Nowcasting | CVPR 2024 | 2023.12  | [[paper]](https://arxiv.org/pdf/2312.06734.pdf) [[code]](https://github.com/DeminYu98/DiffCast) |
| DGDM            | Deterministic Guidance Diffusion Model for Probabilistic Weather Forecasting | Weather Forecasting using Satellite | ECCV 2024 | 2023.12  | [[paper]](https://arxiv.org/pdf/2312.02819.pdf) [[code]](https://github.com/DongGeun-Yoon/DGDM?tab=readme-ov-file)  |
| - | Advancing Realistic Precipitation Nowcasting With a Spatiotemporal Transformer-Based Denoising Diffusion Model | Precipitation Nowcasting | IEEE TGRS | 2024.01  | [[paper]](https://ieeexplore.ieee.org/abstract/document/10403855)  |
| DiffDA            | A diffusion model for weather-scale data assimilation | Data Assimilation | ICML 2024 | 2024.01  | [[paper]](https://arxiv.org/pdf/2401.05932.pdf) [[code]](https://github.com/spcl/DiffDA) |
| LT3P            | Long-Term Typhoon Trajectory Prediction: A Physics-Conditioned Approach Without Reanalysis Data | Tropical Cyclone Trajectory Forecasting | ICLR 2024 | 2024.01  | [[paper]](https://arxiv.org/pdf/2401.15726.pdf) [[code]](https://github.com/iclr2024submit/LT3P) |
| -            | Wind speed super-resolution and validation: from ERA5 to CERRA via diffusion models | Super resolution | - | 2024.01  | [[paper]](https://arxiv.org/pdf/2401.15469.pdf) [[code]](https://github.com/fmerizzi/ERA5-to-CERRA-via-Diffusion-Models/) |
| ExtremeCast | Boosting Extreme Value Prediction for Global Weather Forecast | Global (Extreme) Weather Forecasting | - | 2024.02  | [[paper]](https://arxiv.org/pdf/2402.01295.pdf) [[code]](https://github.com/black-yt/ExtremeCast) |
| CasCast            | Skillful High-resolution Precipitation Nowcasting via Cascaded Modelling | Precipitation Nowcasting | ICML 2024 | 2024.02  | [[paper]](https://arxiv.org/pdf/2402.04290.pdf) [[code]](https://github.com/OpenEarthLab/CasCast) |
| SDEdit-Weather            | Weather Prediction with Diffusion Guided by Realistic Forecast Processes | Global Weather Forecasting | - | 2024.02  | [[paper]](https://arxiv.org/pdf/2402.06666.pdf)  |
| - | Physics-Informed Diffusion Model and Sampling for Global Weather Forecasting | Global Weather Forecasting | - | 2024.03  | [[paper]](https://doi.org/10.5194/egusphere-egu24-13882)  |
| DiffObs | Generative Diffusion for Global Forecasting of Satellite Observations | Global Preciptation Forecasting | ICLR 2024 Workshop | 2024.04  | [[paper]](https://arxiv.org/pdf/2404.06517.pdf)  |
| - | Diffusion-Based Joint Temperature and Precipitation Emulation of Earth System Models | Emulation | ICLR 2024 Workshop | 2024.04  | [[paper]](https://arxiv.org/pdf/2404.08797.pdf)  |
| SLAMS | Deep Generative Data Assimilation in Multimodal Setting | Data Assimilation | CVPR 2024 Workshop | 2024.04  | [[paper]](https://arxiv.org/pdf/2404.06665) [[code]](https://github.com/yongquan-qu/SLAMS)  |
| ClimateDiffuse | Generative Diffusion-based Downscaling for Climate | Downscaling | - | 2024.04  | [[paper]](https://arxiv.org/pdf/2404.17752) [[code]](https://github.com/robbiewatt1/ClimateDiffuse)  |
| CloudDiff | Super-resolution ensemble retrieval of cloud properties for all day using the generative diffusion model | Super-resolution | - | 2024.05  | [[paper]](https://arxiv.org/pdf/2405.04483)  |
| Spherical DYffusion | Probabilistic Emulation of a Global Climate Model with Spherical DYffusion | Global Climate Modelling | NeurIPS 2024 | 2024.06  | [[paper]](https://arxiv.org/pdf/2406.14798)  [[code]](https://github.com/Rose-STL-Lab/spherical-dyffusion) |
| - | Towards diffusion models for large-scale sea-ice modelling | Sea-Ice modelling | - | 2024.06  | [[paper]](https://arxiv.org/pdf/2406.18417)  |
| AIFS | ECMWF's data-driven forecasting system | Global Weather Forecasting | - | 2024.06  | [[paper]](https://arxiv.org/pdf/2406.01465) [[code]](https://huggingface.co/ecmwf/aifs-single) |
| - | Generative Data Assimilation of Sparse Weather Station Observations at Kilometer Scales | Data Assimilation | - | 2024.06  | [[paper]](https://arxiv.org/pdf/2406.16947)  |
| LDM_res | Can AI be enabled to dynamical downscaling? A Latent Diffusion Model to mimic km-scale COSMO5.0_CLM9 simulations | Downscaling | - | 2024.06  | [[paper]](https://arxiv.org/pdf/2406.13627) [[code]](https://github.com/DSIP-FBK/DiffScaler)  |
| - | Latent Diffusion Model for Generating Ensembles of Climate Simulations | Ensemble Forecasting | - | 2024.07  | [[paper]](https://arxiv.org/pdf/2407.02070)  |
| CPMGEM | Machine learning emulation of precipitation from km-scale regional climate simulations using a diffusion model | Precipitation Forecasting | - | 2024.07  | [[paper]](https://arxiv.org/pdf/2407.14158) [[code]](https://github.com/henryaddison/mlde)  |
| - | Forecasting Tropical Cyclones with Cascaded Diffusion Models | TC/Precipitation Forecasting | ICLR 2024 Workshop | 2024.07  | [[paper]](https://arxiv.org/pdf/2310.01690) [[code]](https://github.com/p3jitnath/forecast-diffmodels)  |
| KESHDiff | Generative Diffusion Model-based Downscaling of Observed Sea Surface Height over Kuroshio Extension since 2000 | Downscaling | - | 2024.08  | [[paper]](https://arxiv.org/pdf/2408.12632) |
| StormCast | Kilometer-Scale Convection Allowing Model Emulation using Generative Diffusion Modeling | Emulation | - | 2024.08  | [[paper]](https://arxiv.org/pdf/2408.10958)  |
| DifERS | A Generative Diffusion Model for Probabilistic Ensembles of Precipitation Maps Conditioned on Multisensor Satellite Observations | Precipitation Forecasting | - | 2024.09  | [[paper]](https://arxiv.org/pdf/2409.16319) |
| CoDiCast | Conditional Diffusion Model for Weather Prediction with Uncertainty Quantification | Global Weather Forecasting | - | 2024.09  | [[paper]](https://arxiv.org/pdf/2409.05975) [[code]](https://github.com/JimengShi/CoDiCast)  |
| R2-D2 | Dynamical-generative downscaling of climate model ensembles | Downscaling | - | 2024.10  | [[paper]](https://arxiv.org/pdf/2410.01776) |
| Yantian | An Application Platform for AI Global Weather Forecasting Models | Global Weather Forecasting | - | 2024.10  | [[paper]](https://arxiv.org/pdf/2410.04539)  |
| ARCI | Continuous Ensemble Weather Forecasting with Diffusion models | Ensemble Forecasting | - | 2024.10  | [[paper]](https://arxiv.org/pdf/2410.05431) [[code]](https://github.com/martinandrae/Continuous-Ensemble-Forecasting)  |
| IceDiff | High Resolution and High-Quality Sea Ice Forecasting with Generative Diffusion Prior | Sea Ice Forecasting | - | 2024.10  | [[paper]](https://arxiv.org/pdf/2410.09111)  |
| - | Ensemble-based, large-eddy reconstruction of wind turbine inflow in a near-stationary atmospheric boundary layer through generative artificial intelligence | Data Reconstruction | - | 2024.10  | [[paper]](https://arxiv.org/pdf/2410.14024)  |
| TCP-Diffusion | A Multi-modal Diffusion Model for Global Tropical Cyclone Precipitation Forecasting with Change Awareness | TC/Precipitation Forecasting | - | 2024.10  | [[paper]](https://arxiv.org/pdf/2410.13175) |
| GenBCSR | Statistical Downscaling via High-Dimensional Distribution Matching with Generative Models | Downscaling | - | 2024.12  | [[paper]](https://arxiv.org/pdf/2412.08079) |
| - | Downscaling Precipitation with Bias-informed Conditional Diffusion Model | Downscaling | - | 2024.12  | [[paper]](https://arxiv.org/pdf/2412.14539) [[code]](https://github.com/RoseLV/research_super-resolution)  |
| - | Spatiotemporally Coherent Probabilistic Generation of Weather from Climate | Downscaling | - | 2024.12  | [[paper]](https://arxiv.org/pdf/2412.15361) [[code]](https://github.com/schmidtjonathan/Climate2Weather)  |
| - | A Generative Framework for Probabilistic, Spatiotemporally Coherent Downscaling of Climate Simulation | Downscaling | - | 2024.12  | [[paper]](https://arxiv.org/pdf/2412.15361) [[code]](https://github.com/schmidtjonathan/Climate2Weather)  |
| - | Using Generative Models to Produce Realistic Populations of UK Windstorms | Windstorm Simulation | - | 2025.01  | [[paper]](https://arxiv.org/pdf/2501.16110) |
| - | Improving Tropical Cyclone Forecasting With Video Diffusion Models | Tropical Cyclone Forecasting | - | 2025.01  | [[paper]](https://arxiv.org/pdf/2501.16003) [[code]](https://github.com/Ren-creater/forecast-video-diffmodels)  |
| - | Ensemble score filter with image inpainting for data assimilation in tracking surface quasi-geostrophic dynamics with partial observations | Data Assimilation | - | 2025.01  | [[paper]](https://arxiv.org/pdf/2501.12419) [[code]](https://github.com/Siming-Liang/EnSFInpainting)  |
| SGD | Satellite Observations Guided Diffusion Model for Accurate Meteorological States at Arbitrary Resolution | Downscaling | - | 2025.02  | [[paper]](https://arxiv.org/pdf/2502.07814)  |
| SATcast | Skillful Nowcasting of Convective Clouds With a Cascade Diffusion Model | Convective Clouds Nowcasting | - | 2025.02  | [[paper]](https://arxiv.org/pdf/2502.10957) [[code]](https://github.com/cd4tpcell/SATcast/tree/main)  |
| - | - | - | - | 2025.00  | [[paper]]() [[code]]()  |
