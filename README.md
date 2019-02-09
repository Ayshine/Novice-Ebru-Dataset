#  Novice Ebru Dataset: Style Transfer Example


![display](imgs/display.jpg  "display")
## Introduction
This repository provides style transfer example on  **Novice Ebru Dataset (NED)** from paper Turkish-Ottoman Style Transfer Research: Novice Ebru Dataset (Ayşin Taşdelen, Eren Bozarık, Can Umay, Yavuz Kömeçoğlu ve Şebnem Özdemir)

**NED** contains 250 different Ebru art samples based on five well-known styles with their distinct attributes.



## Getting Started

- install [anaconda](https://www.anaconda.com/download/) or [miniconda](https://conda.io/miniconda.html) 
- clone project repository `git clone https://github.com/Ayshine/Novice-Ebru-Dataset.git`
- create conda environment using [Ebru Dataset Yaml](/ebru-dataset.yaml)   file. ```conda env create --file=ebru-dataset.yaml```
- activate conda environment `source activate ebru`(linux)`activate ebru`(windows)

Note: This project created using NVDIA 1080 GPU and Anaconda 3.6 environment. Thus, yaml file provided contains GPU version of Pytorch. In order to use CPU only version of pytorch please refer to  [Pytorch](https://pytorch.org/)  website to setup your environment CPU only version. The code in this repository is a version of Udacity's [Intro to Deep Learning with Pytorch](https://www.udacity.com/course/deep-learning-pytorch--ud188) program's style transfer section repository.

## Downloading Novice Ebru Dateset
Our dataset can be downloaded from [GoogleDrive](#)
After Downloading data create a folder named EBRU under the project folder.

## Citing Relevant Paper - Triggering Diversity of Artificial Intelligence Based Art Research by using Turkish-Ottoman Art Genre
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

MIT License

Copyright (c) 2019 Ayşin Taşdelen

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
