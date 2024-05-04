# Unmasking Deepfake Faces from Videos An Explainable Cost-Sensitive Deep Learning Approach

This repository contains the code and datasets used in the paper titled **"Unmasking Deepfake Faces from Videos An Explainable Cost-Sensitive Deep Learning Approach"** accepted and presented at the 26th International Conference on Computer and Information Technology (ICCIT) 2023.

**Paper Link:** [PDF](https://www.researchgate.net/publication/378533983_Unmasking_Deepfake_Faces_from_Videos_Using_An_Explainable_Cost-Sensitive_Deep_Learning_Approach)

## Table of Contents
  - [Dataset](#dataset)
  - [Result](#result)
  - [Citation](#citation)

## Dataset
We used publicly available datasets they are [CelbDF-V2](https://github.com/yuezunli/celeb-deepfakeforensics) and [FaceForensics++](https://github.com/ondyari/FaceForensics)

## Result

####  Performance Metrics of Weighted Average on CelebDf-V2 Dataset

| Model         | Accuracy   | Precision  |  Recall | F1 Score   |
| ------------- |:-------------:| :-------------:| :-------------:| :-------------:| 
|  XceptionNet  | **98%**  | **0.98**  | **0.98**  | **0.98** |
|  InceptionResNetV2  | 0.97  |  0.97  | 0.97  | 0.97 |
|  EfficientNetV2S  | 0.97  | 0.97  | 0.97  | 0.97 |
|  EfficientNetV2M  | 0.97  | 0.97  | 0.97  | 0.97 |

####  Performance Metrics of Weighted Average on FaceForensics++ Dataset

| Models        | Accuracy   | Precision  |  Recall | F1 Score   |
| ------------- |:-------------:| :-------------:| :-------------:| :-------------:| 
|  InceptionResNetV2  | **94%**  |  **0.94**  | **0.94**  | **0.94** |
|  XceptionNet  | 93%  | 0.93  | 0.93  | 0.93 |
|  EfficientNetV2S  | 92%  | 0.92  | 0.92  | 0.92 |
|  EfficientNetV2M  | 88%  | 0.89  | 0.88  | 0.88 |



## Citation
If you found this code helpful please consider citing,
```
@INPROCEEDINGS{10441026,
            author={Mahmud, Faysal and Abdullah, Yusha and Islam, Minhajul and Aziz, Tahsin},
            booktitle={2023 26th International Conference on Computer and Information Technology (ICCIT)}, 
            title={Unmasking Deepfake Faces from Videos Using An Explainable Cost-Sensitive Deep Learning Approach}, 
            year={2023},
            volume={},
            number={},
            pages={1-6},
            keywords={Deep learning;Deepfakes;Adaptation models;Face recognition;Computational modeling;Feature extraction;Convolutional neural networks;Deepfake               
            video;Keyframe;Explainable AI (XAI);Cost-sensitive;Face Detection;CelebDf;FaceForensics++;CNN},
            doi={10.1109/ICCIT60459.2023.10441026}
}
```
