# Human Activity Retrieval Using Siamese Network

This project implements a Siamese Network for human activity retrieval from images. The model is trained to distinguish between different activities and retrieve similar activity images based on learned feature embeddings.

## Table of Contents

- [Dependencies](#dependencies)
- [Dataset](#dataset)
- [Setup](#setup)
- [Training the Model](#training-the-model)
- [Evaluating the Model](#evaluating-the-model)
- [Results](#results)

## Dependencies

- Python 3.x
- torch
- torchvision
- numpy
- scikit-learn
- Pillow
- tqdm

You can install the necessary dependencies using `pip`:

```sh
pip install torch torchvision numpy scikit-learn pillow tqdm


human_activity_retrieval_dataset/
    ├── train/
    │   ├── img1.jpg
    │   ├── img2.jpg
    │   └── ...
    ├── query_images/
    │   ├── query_img1.jpg
    │   ├── query_img2.jpg
    │   └── ...
    ├── gallery/
    │   ├── gallery_img1.jpg
    │   ├── gallery_img2.jpg
    │   └── ...
    ├── train_image_info.json
    └── test_image_info.json


mAP@1: 0.1234
mAP@10: 0.5678
mAP@50: 0.7890
Mean Rank: 21.1234

