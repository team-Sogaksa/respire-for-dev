hihi

참고: https://github.com/microsoft/RespireNet/

### Dependencies:

* Python3 (3.9.2)
* Pandas (2.2.2)
* Librosa (0.10.2.post1)
<!--
* Pytorch (torch, torchvision and other dependencies for Pytorch)
* Numpy
* nlpaug (0.0.14)
* scikit-learn (0.23.1)
* tqdm (4.48.0)
* cudnn (CUDA for training on GPU)
-->
<br>...

### Directory
.<br>
├── data/<br>
│   ├── ICBHI_final_database/<br>
│   │       ├── 101_1b1_Al_sc_Meditron.txt<br>
│   │       ├── 101_1b1_Al_sc_Meditron.wav<br>
│   │       ...<br>
│   ├── metadata<br>
│   ...<br>
├── images/<br>
├── models/<br>
├── nets/<br>
├── scripts/<br>
├── train.py<br>
├── eval.py<br>
├── image_dataloader.py<br>
├── utils.py<br>
└── README.md

- data/: raw data. 모은 데이터는 허깅페이스에 업로드 예정
- images/: description
- models/: training 결과저장. ckpt_best.pkl
- nets/: model
- scripts/: train/eval등 run.sh 

