# my_childrens_voice_AI

## 실행 순서

### 환경 세팅
```
pip install -r requirement.txt
```
### Pretrained Model 다운로드
https://drive.google.com/drive/folders/1j8GGrlrfNsXrIE-BYqFxSC1i8mSO2vWX?usp=drive_link
+ hubert_base.pt
+ ./pretrained_v2
+ ./male_tacotron
+ ./male_waveglow
+ ./female_tacotron
+ ./female_waveglow

### Train
```
python main_train.py
```
### Inference
```
python inference.py
```
