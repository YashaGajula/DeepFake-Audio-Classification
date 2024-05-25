# DeepFake-Audio-Classification
Deepfake technology, encompassing the manipulation of audio and video content, poses a significant threat to the integrity of media content. This paper presents a deepfake audio classification system utilizing a Convolutional Neural Network (CNN) architecture trained and evaluated on the ASVspoof2019 LA dataset and FoR(Fake or real) dataset. The dataset comprises a diverse collection of audio recordings categorized into bonafide (genuine) and spoofed (synthesized) instances, enabling the development and assessment of deepfake detection techniques. We demonstrate the effectiveness of our method through comprehensive evaluations, including confusion matrix analysis, ROC curve, precision-recall curve, and calibration curve. Additionally, we visualize the Mel spectrograms of test audio files, providing insights into the detection process. The proposed CNN-based approach achieves robust performance in accurately distinguishing between authentic and manipulated audio content, as evidenced by high ROC curve area (AUC) of 0.90 and an average precision of 0.87 on the test dataset. An accuracy of 0.98 on training the FoR data over a CNN. These results demonstrate the efficacy of the model in combatting the proliferation of audio deepfakes, contributing to advancements in audio spoofing detection technologies. Overall, our study presents a promising framework for automated detection of audio deepfakes, contributing to the ongoing efforts in combating synthetic media manipulation.
# Dataset: 
ASVspoof 2019 dataset containing genuine and spoof audio recordings. [https://www.kaggle.com/datasets/awsaf49/asvpoof-2019-dataset]

FakeorReal - for-2sec containing real or fake audio recordings.

Preprocessing: Convert audio files to Mel spectrograms, augment training data.

Model Architecture: Convolutional Neural Network (CNN) with classification layers.

Training: Binary cross-entropy loss, Adam optimizer

Evaluation: Accuracy, ROC curve, Calibration curve, EER.
![image](https://github.com/YashaGajula/DeepFake-Audio-Classification/assets/170789442/fcd8d155-6454-404e-a28c-af2cc29670d1)

# ASVspoof 2019 dataset:
![image](https://github.com/YashaGajula/DeepFake-Audio-Classification/assets/170789442/fa2ad466-25af-4af6-9dc4-47ed8d749a5f)
![image](https://github.com/YashaGajula/DeepFake-Audio-Classification/assets/170789442/c78ab50a-aab8-4637-a18b-a781ac726970)
![image](https://github.com/YashaGajula/DeepFake-Audio-Classification/assets/170789442/79908df3-8939-4e26-8151-7a64c7e34413)
# FakeorReal:
![image](https://github.com/YashaGajula/DeepFake-Audio-Classification/assets/170789442/f1d6984f-4a39-416e-9df4-d139157d82f4)
![image](https://github.com/YashaGajula/DeepFake-Audio-Classification/assets/170789442/81810efb-a285-4878-8108-3e2a60ff5700)
![image](https://github.com/YashaGajula/DeepFake-Audio-Classification/assets/170789442/5efc2b03-09bb-40b0-92ba-e66ab394e8f4)
![image](https://github.com/YashaGajula/DeepFake-Audio-Classification/assets/170789442/11b9dc81-ed67-4b99-8e13-74a9226e67b1)



