# Multimodal Fusion Transformer for Remote Sensing Image Classification

[Swalpa Kumar Roy](https://swalpa.github.io), [Ankur Deria](), [Danfeng Hong](https://sites.google.com/view/danfeng-hong), [Behnood Rasti](https://scholar.google.com/citations?user=hA_Xi6MAAAAJ&hl=en), [Antonio Plaza](https://scholar.google.com/citations?user=F1UAj8oAAAAJ&hl=en), and [Jocelyn Chanussot](http://jocelyn-chanussot.net/)


<sup><font color="red"><strong>New!!</strong></font></sup> Code will be available here soon.
___________

The repository contains the implementations for [Multimodal Fusion Transformer for Remote Sensing Image Classification](https://www.researchgate.net/publication/359647022_Multimodal_Fusion_Transformer_for_Remote_Sensing_Image_Classification).

<img src="./model.png" width="700" height="500"/>

---------------------
### Dataset

* **Trento** AISA Eagle sensors were used to collect HSI data over rural regions in the south of Trento, Italy, where the Optech ALTM 3100EA sensors collected LiDAR data. There are 63 bands in each HSI with wavelength ranging from 0.42-0.99 μm, and 1 raster in the LiDAR data that provides elevation information. The spectral resolution is 9.2 nm, and the spatial resolution is 1 meters per pixel. The scene comprises 6 vegetation land-cover classes that are mutually exclusive and a pixel count of 600 × 166.

* **Muffle** The MUUFL Gulfport scene was collected over the campus of the University of Southern Mississippi in November 2010 using the Reflective Optics System Imaging Spectrometer (ROSIS) sensor. There are 325 × 220 pixels with 72 spectral bands in the HSI of this dataset. The LiDAR image of this dataset contains elevation data of 2 rasters. The 8 initial and final bands were removed due to noise, giving a total of 64 bands. The data depicts 11 urban land-cover classes containing 53687 ground truth pixels.

* **Houston** was acquired by the ITRES CASI-1500 sensor over the University of Houston campus, TX, USA, in June 2012. This data set was originally released by the 2013 IEEE GRSS data fusion contest2, and it has been widely applied for evaluating the performance of land cover classification. The original image is 349 × 1905 pixels recorded in 144 bands ranging from 0.364 to 1.046 μm.

* **Augsburg scene** There are three types of data in Augsburg scene which include an HSI, a dual-Pol SAR image, and a DSM image. SAR data are collected from Sentinel-1 platform, while HS and DSM data are captured by DAS-EOC, DLR over the city of Augsburg, Germany. The collection is done by the HySpex sensor, the Sentinel-1 sensor, and the DLR-3 K system, respectively. The spatial resolutions of all images are down-sampled to a unified spatial resolution of 30 m ground sampling distance (GSD) for adequately managing the multimodal fusion. For the HSI, there are 332 × 485 pixels and 180 spectral bands ranging between 0.4-2.5 μm. The DSM image has a single band, whereas the SAR image has 4 bands. The four bands indicate VV intensity, VH intensity, the real component, and the imaginary component of the PolSAR covariance matrix’s off-diagonal element.


## Models

The following traditional machine learning methods will be available:

- [x] [RF](https://ieeexplore.ieee.org/document/1396322) 
- [x] [SVM](https://ieeexplore.ieee.org/document/1323134) 
- [x] [RNN](https://ieeexplore.ieee.org/document/8662780)
- [x] [KNN](https://ieeexplore.ieee.org/document/9065747) 

The following deep learning methods will be available:

- [x] [CNN-1D](https://www.sciencedirect.com/science/article/pii/S0924271619302187)
- [x] [CNN-2D](https://ieeexplore.ieee.org/document/7326945)
- [x] [CNN-3D](https://ieeexplore.ieee.org/document/8344565)

The following transformer based deep learning methods will be available:

- [x] [ViT](https://paperswithcode.com/paper/an-image-is-worth-16x16-words-transformers-1)
- [x] [SpectralFormer](https://ieeexplore.ieee.org/document/9627165)
- [x] [MFT](https://www.researchgate.net/publication/359647022_Multimodal_Fusion_Transformer_for_Remote_Sensing_Image_Classification)

Citation
---------------------

**Please kindly cite the papers if this code is useful and helpful for your research.**

    @article{roy2022multimodal,
      title={Multimodal Fusion Transformer for Remote Sensing Image Classification},
      author={Roy, Swalpa Kumar and Deria, Ankur and Hong, Danfeng and Rasti, Behnood and Plazza, Antonio and Chanussot, Jocelyn},
      journal={arxiv.org/abs/2203.16952},
      year={2022}  
    }
