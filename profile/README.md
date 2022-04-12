<div align="center">
  <img width="30%" alt="NutriAI_logo" src="https://user-images.githubusercontent.com/33509018/162863401-8f624292-3c11-4038-8b3a-b15b8803e000.png" title="NutriAI">
</div>

# Nutri-AI
이미지 분석을 통한 식단 추적 및 영양제 추천 서비스 구현


## 개요
### Service component
- 이미지를 통한 식단 기록
- 사용자 영양상태 확인
- 사용자 맞춤 영양제 추천
<!--
![main](https://user-images.githubusercontent.com/100662106/161993806-71dcb943-c3f7-4fbd-9e44-83834fcb6082.PNG)

![summary](https://user-images.githubusercontent.com/100662106/161993701-aa0011a5-78b6-4c17-83ab-4452b1f2f425.PNG)
-->
### Short Video


## Project Summary

### Contributors
* 황혜원 : [HyeWon's Github](https://github.com/hyeniii)
* 지영우 : [YoungWoo's Github](https://github.com/Angwoo-the-Fuego)
* 김지윤 : [Jiyoon's Github](https://github.com/ziyoon)
* 김재홍 : [JaeHong's Github](https://github.com/kymjaehong)
### Period
2022.02 ~ 2022.03
### Institution
SK planet T-academy
### Award
:trophy: 1st Place in T-academy and Medici Education Program
### Presentation
:link: https://www.youtube.com/watch?v=jiwFvVVISpo


## Data & Data Preprocessing

### image data
- [한국음식이미지 AIhub](https://aihub.or.kr/aidata/13594)
- Image Downloader - Imageye(https://chrome.google.com/webstore/detail/image-downloader-imageye/agionbommeaifngbhincahgmoflcikhm)
- AutoCrawler(https://github.com/YoongiKim/AutoCrawler)
### Food nutrient info
- [식품의약품안전처](https://www.foodsafetykorea.go.kr/fcdb/)
### Nutritional supplement data
- IHerb Scrapping: :link:https://github.com/Nutri-AI/Iherb_Scrapping

### Preprocessing
- Annotation tool : [CVAT](https://cvat.org/)
- nutrients notation
- nutrients unit

## Database
:link:https://github.com/Nutri-AI/Database

AWS DynamoDB
<div>
    <img src="https://xpertlab.com/wp-content/uploads/2021/08/edit_dynamodb.png" width="50%" alt="dynamodb-logo">
</div>

### ERD
<div align="center">
  <img width="50%" alt="NutriAI_database_ERD" src="https://user-images.githubusercontent.com/33509018/162860867-4b17044b-33c2-4d68-9ac9-6b5285d5e40e.png">
</div>


## Model
:link:https://github.com/Nutri-AI/yolov3_onnx_inf

### Models used
[Ultralytics: YOLOv3](https://github.com/ultralytics/yolov3)

<!--
[zylo117: Yet-Another-EfficientDet-Pytorch](https://github.com/zylo117/Yet-Another-EfficientDet-Pytorch)
-->


## API
:link:https://github.com/Nutri-AI/api-fastapi

FastAPI

<div>
    <img src="https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png" width="50%" alt="fastapi-logo">
</div>



## APP
:link:https://github.com/Nutri-AI/Application

Flutter

<div>
    <img src="https://storage.googleapis.com/cms-storage-bucket/c823e53b3a1a7b0d36a9.png" width="50%" alt="flutter-logo">
</div>
