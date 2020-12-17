# My-Modify-Verision-Bayesian-Crowd-Counting
This is a more convenient version that I modified on BL and provided dataset,The previous [official version](https://github.com/ZhihengCV/Bayesian-Crowd-Counting) of the dataset path is not friendly and only for UCF_QNRF dataset,Therefore, we have made some modifications on the basis above. The modified code can directly correspond to the folder path of the Shanghai_ParA and PatB dataset.

We provide our generated dataset (currently only ParB)[Baiduyun_link](https://pan.baidu.com/s/1LnBT0gm8bX9JjTee9JaM3A)  Extraction code：tp7i

## Tips:

1. If you need Preprocessing data of Shanghai_ParA ,you can run preprocess_dataset.py .Just change its PartB path to PartA.Other datasets are the same way!

2. You only need to modify its --data_dir (directory of processed data>) and --save_dir (directory of log and model) in train.py,The method of training model is consistent with the [official version](https://github.com/ZhihengCV/Bayesian-Crowd-Counting)
