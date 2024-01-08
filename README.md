# Unmasking Deepfake Faces from Videos An Explainable Cost-Sensitive Deep Learning Approach

### 📌 Abstract
<h4 align="justify" >
Deepfake technology is widely used, which has led to serious worries about the authenticity of digital media, making the need for trustworthy deepfake face recognition techniques more urgent than ever. This study employs a resource-effective and transparent cost-sensitive deep learning method to effectively detect deepfake faces in videos. To create a reliable deepfake detection system, four pre-trained Convolutional Neural Network (CNN) models: XceptionNet, InceptionResNetV2, EfficientNetV2S, and EfficientNetV2M were used. FaceForensics++ and CelebDf-V2 as benchmark datasets were used to assess the performance of our method. To efficiently process video data, key frame extraction was used as a feature extraction technique. Our main contribution is to show the models adaptability and effectiveness in correctly identifying deepfake faces in videos. Furthermore, a cost-sensitive neural network method was applied to solve the dataset imbalance issue that arises frequently in deepfake detection. The XceptionNet model on the CelebDf-V2 dataset gave the proposed methodology a 98% accuracy, which was the highest possible whereas, the InceptionResNetV2 model, achieves an accuracy of 94% on the FaceForensics++ dataset.
</h4>


## Results

| Models        | Accuracy   | Precision  |  Recall | #  F1 Score   |
| ------------- |:-------------:| :-------------:| :-------------:| :-------------:| 
|  InceptionResNetV2  | 94%  |  0.94  | 0.94  | 0.94 |
|  XceptionNet  | 93%  | 0.93  | 0.93  | 0.93 |
|  EfficientNetV2S  | 92%  | 0.92  | 0.92  | 0.92 |
|  EfficientNetV2M  | 88%  | 0.89  | 0.88  | 0.88 |
|  Fine-tuned DenseNet 201 (from the last dense block) | **85.8%** | **83.9%**  |  711 layers | 19,309,127 |
|  Fine-tuned Inception V3 (all layers) | 86.92% | 86.826% | _ | _ |
|  Fine-tuned DenseNet 201 (all layers)  | **86.696%** | **87.725%** | _ | _ |
|  Ensemble of fully-fine-tuned Inception V3 and DenseNet 201 | **88.8%** | **88.52%** | _ | _ |


### 📝 Citation
If you found this code helpful please consider citing,
```
@article{mahmud2023unmasking,
  title={Unmasking Deepfake Faces from Videos Using An Explainable Cost-Sensitive Deep Learning Approach},
  author={Mahmud, Faysal and Abdullah, Yusha and Islam, Minhajul and Aziz, Tahsin},
  journal={arXiv preprint arXiv:2312.10740},
  year={2023}
}
```

### ⚖️ License
Copyright © 2023 Faysal Mahmud
