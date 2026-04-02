<div align="center">
  
# CARLA-Haze: A Synthetic Benchmark for Outdoor Image Dehazing
[Henry Velesaca](https://ec.linkedin.com/in/henry-velesaca-lara/)\, [Leo Thomas Ramos](https://www.linkedin.com/in/leo-thomas-ramos/)\, [Ángel D. Sappa](https://es.linkedin.com/in/angel-sappa-61532b17)
</div>

<!-- This repository is the official Pytorch implementation for [SkyScenes](). -->

<!-- [![Website](https://img.shields.io/badge/Project-Website-orange)](https://hoffman-group.github.io/SkyScenes/) [![arXiv](https://img.shields.io/badge/arXiv-SkyScenes-b31b1b.svg)](#)  -->


<!-- [![Watch the Demo](./assets/robust_aerial_videos.mp4)](./assets/robust_aerial_videos.mp4) -->

<img src="./assets/teaser.png" width="100%"/>

## Announcements

- CARLA-Haze has been accepted at the 5th IEEE/CVF Workshop on Image/Video/Audio Quality Assessment in Computer Vision, VLM and Diffusion Model (WVAQ) @ WACV 2026 📣📣📣
- CARLA-Haze is under review

## About the project

We present CARLA-Haze, a synthetic dataset designed for outdoor image dehazing. CARLA-Haze contains 10,000 high-resolution paired images (clean and hazy), distributed across 10 different scenarios and 10 incremental haze intensity levels. The dataset includes diverse scenarios and visual elements, distance-based haze distribution consistent with realistic atmospheric conditions, and multiple viewpoints enhancing visual variability. Additionally, two preprocessed versions with standardized resolutions of 640x480 and 512x512 pixels are provided, each containing 40,000 images. CARLA-Haze also offers predefined splits for training, validation, and testing to facilitate its use. 

### Paper

CARLA-Haze paper is available at WACV proceedings [here](https://openaccess.thecvf.com/content/WACV2026W/WVAQ/html/Velesaca_CARLA-Haze_A_Synthetic_Benchmark_for_Outdoor_Image_Dehazing_WACVW_2026_paper.html)


## Dataset download

The dataset is available for download via Kaggle [here](https://www.kaggle.com/datasets/angeldsappa/carla-haze).

## Training and test on all haze leves

In order to train and/or evaluate your models using all haze levels together (or a specific combination), we provide a straight forward script where you can specify the paths of the different levels or scenes of interest and generate the combined train, val, and test splits. See [combine.py](https://github.com/Leo-Thomas/CARLA-Haze/blob/main/combine.py)

## License

Distributed under MIT license. See `LICENSE` for more information.

## BibTex

If you find this dataset useful, please star ⭐️⭐️⭐️ our repo and cite our paper.

```
@InProceedings{carla_haze_2026_WACV,
    author    = {Velesaca, Henry O. and Ramos, Leo Thomas and Sappa, Angel D.},
    title     = {CARLA-Haze: A Synthetic Benchmark for Outdoor Image Dehazing},
    booktitle = {Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) Workshops},
    year      = {2026},
    pages     = {1-10}
}
```

