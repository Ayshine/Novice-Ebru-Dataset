# Style Transfer: Novice Ebru Dataset


![display](imgs/display.jpg  "display")
## Introduction
This repository provides style transfer example on  **Novice Ebru Dataset (NED)** from paper Turkish-Ottoman Style Transfer Research: Novice Ebru Dataset (Ayşin Taşdelen, Eren Bozarık, Can Umay, Yavuz Kömeçoğlu ve Şebnem Özdemir)

**NED** contains 250 different Ebru art samples based on five well-known styles with their distinct attributes.



## Getting Started

- install [anaconda](https://www.anaconda.com/download/) or [miniconda](https://conda.io/miniconda.html) 
- clone project repository `git clone https://github.com/Ayshine/Novice-Ebru-Dataset.git`
- create conda environment using [Ebru Dataset Yaml](/ebru-dataset.yaml)   file. ```conda env create --file=ebru-dataset.yaml```
- activate conda environment `source activate ebru`(linux)`activate ebru`(windows)

Note: This project created using NVDIA 1080 GPU and Anaconda 3.6 environment. Thus, yaml file provided contains GPU version of Pytorch. In order to use CPU only version of pytorch please refer to  [Pytorch](https://pytorch.org/)  website to setup your environment CPU only version.

## Downloading Novice Ebru Dateset
Our dataset can be downloaded from [GoogleDrive](#)
After Downloading data create a folder named EBRU under the project folder.

## Citing  Deep Novice Ebru Dateset
```
@inproceedings{Turkish-Ottoman Style Transfer Research: Deep Novice Ebru Dataset,
    Author = {Ayşin Taşdelen, Eren Bozarık, Can Umay, Yavuz Kömeçoğlu, Şebnem Özdemir},
    Title = {Triggering Diversity of Artificial Intelligence Based Art Research by 
    using Turkish-Ottoman Art Genre},
    Conference = {DATASCI},
    Year = {2018}
}
```
## License
...
