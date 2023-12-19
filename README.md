물류 주문서 자동 인식기 개발 및 XAI 적용

### Main ipynb files

TableDetectionOCR.ipynb for Text Detection & Text Recognition
SER.ipynb for Semantic Entity Recognition

### Labeling Dataset
train_data/training_Label_no_blank.json
train_data/testing_Label_no_blank.json
train_data/validation_Label_no_blank.json

you need appropriate jpg file to train/infer KIE model


### Required Dependency
paddlepaddle-gpu == 2.5.2
paddleocr
paddlenlp
...


### inference model
det model (Text Detection)
https://drive.google.com/file/d/1OgKa0EYQw7b0YKqLoCsUq-g6BLV7Spi-/view?usp=drive_link

rec model (Text Recognition)
https://drive.google.com/file/d/1VlTxgMTbV2aU4bFvbIzXTOmxr0tWihFX/view?usp=drive_link

https://github.com/YunSungJu/OderformKIE

![image](https://github.com/YunSungJu/OderformKIE/assets/48467841/931295c6-0e0d-4862-b435-16ff64d503b3)
