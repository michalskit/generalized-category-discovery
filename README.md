# Generalized Category Discovery - Fork

This is a fork of the original [Generalized Category Discovery](https://github.com/sgvaze/generalized-category-discovery) repository.

![image](https://github.com/sgvaze/generalized-category-discovery/blob/main/assets/main_img.png)

## Contents
- [:boom: 1. Updates from Original Repo](#updates)
- [:running: 2. Usage](#running)
- [:1234: 3. Results](#results)
- [:clipboard: 4. Citation of Original Work](#cite)

## <a name="updates"/> :boom: Updates from Original Repo

This section contains updates from the original repository. Please check the original repository for the most recent changes and improvements.

## <a name="running"/> :running: Usage

### Dependencies

Install the dependencies from the requirements.txt file:
pip install -r requirements.txt


### Configuration

Set paths to datasets, pre-trained models, and desired log directories in `config.py`. Set `SAVE_DIR` (logfile destination) and `PYTHON` (path to python interpreter) in `bash_scripts` scripts.

### Datasets

Datasets used in the original work include:

- [The Semantic Shift Benchmark (SSB)](https://github.com/sgvaze/osr_closed_set_all_you_need#ssb)
- [Herbarium19](https://www.kaggle.com/c/herbarium-2019-fgvc6)
- [CIFAR-10/100](https://pytorch.org/vision/stable/datasets.html)
- [ImageNet](https://image-net.org/download.php)

### Scripts

**Train representation**:
bash bash_scripts/contrastive_train.sh


**Extract features**:
bash bash_scripts/extract_features.sh


**Fit semi-supervised k-means**:
bash bash_scripts/k_means.sh


## <a name="results"/> :1234: Results

Results of re-running models with this fork compared to reported numbers in the original work:

| **Dataset**       | **All** | **Old** | **New** |
|-------------------|---------|---------|---------|
| TBD | TBD | TBD | TBD |

## <a name="cite"/> :clipboard: Citation of Original Work

If you use this fork in your research, please consider citing the original paper:
@InProceedings{vaze2022gcd,
title={Generalized Category Discovery},
author={Sagar Vaze and Kai Han and Andrea Vedaldi and Andrew Zisserman},
booktitle={IEEE Conference on Computer Vision and Pattern Recognition},
year={2022}}
