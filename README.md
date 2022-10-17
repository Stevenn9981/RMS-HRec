# RMS-HRec
This is the source code of RMS-HRec. 

__Paper__: Automatic Meta-Path Discovery for Effective Graph-Based Recommendation (CIKM'22)

### Environment
```
pytorch == 1.5.0
dgl == 0.6.0
```
Note that `dgl` should be installed according to the instructions on [DGL official website](https://www.dgl.ai/pages/start.html). __DO NOT__ use `pip install dgl`

### To run the code
```shell
python train_fm.py --data_name yelp_data
```


If you use our datasets or codes, please cite our paper.
```
@inproceedings{RMS-HRec,
author = {Ning, Wentao and Cheng, Reynold and Shen, Jiajun and Haldar, Nur Al Hasan and Kao, Ben and Yan, Xiao and Huo, Nan and Lam, Wai Kit and Li, Tian and Tang, Bo},
title = {Automatic Meta-Path Discovery for Effective Graph-Based Recommendation},
year = {2022},
publisher = {ACM},
booktitle = {CIKM},
pages = {1563–1572}
}
```
