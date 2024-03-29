<!---
  README.md for NutriAI project
--->

<div align="center">
  <img width="30%" alt="NutriAI_logo" src="https://github.com/Nutri-AI/.github/blob/main/profile/images/NutriAI_logo.png" title="NutriAI logo">
  <br/>
  <h3 align="center">이미지 탐지를 통한 식단 분석 및 영양제 추천</h3>
  <h3 align="center">Personal Diet Assessment and Supplement Recommendation Application</h3>
  <p align="center">
    <a href="https://github.com/hyeniii">황혜원 (Hye Won Hwang)</a>
    ·
    <a href="https://github.com/Angwoo-the-Fuego">지영우</a>
    ·
    <a href="https://github.com/kymjaehong">김재홍</a>
    ·
    <a href="https://github.com/ziyoon">김지윤</a>
  </p>
  <p align="center">
    2022.02 ~ 2022.03 | SK planet T-academy
    <br/>
    🥇 1st Place in T-academy and Medici Education Program
    <br/>
    <a href="https://www.youtube.com/watch?v=jiwFvVVISpo" target="_blank">
      <img width="40%" alt="youtube" src="https://img.youtube.com/vi/jiwFvVVISpo/maxresdefault.jpg" title="NutriAI Presentation">
    </a>
  </p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ul>
    <li>
      <a href="#overview">Overview</a>
      <ul>
        <li><a href="#service-component">Service Component</a></li>
        <li><a href="#short-video">Short Video</a></li>
      </ul>
    </li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#data">Data</a></li>
    <li><a href="#erd">ERD</a></li>
    <li><a href="#development">Development</a></li>
  </ul>
</details>

## Overview
### Service Component
- 이미지를 통한 식단 기록 (Detects and logs food image)
- 사용자 영양상태 확인 (Summarize user nutritional status)
- 사용자 맞춤 영양제 추천 (Recommend supplement based on user diet)

### Short Video
<div align="center">
  <video src="https://user-images.githubusercontent.com/33509018/163580554-2daf92a4-33e3-4818-9278-31258f6444be.mp4" data-canonical-src="https://user-images.githubusercontent.com/33509018/163580554-2daf92a4-33e3-4818-9278-31258f6444be.mp4" controls="controls" muted="muted" style="max-height:640px;">
  </video>
</div>



## Built With
- [Amazon DynamoDB](https://aws.amazon.com/dynamodb/)
- [Amazon EC2](https://aws.amazon.com/ec2/)
- [YOLOv3](https://github.com/ultralytics/yolov3)
- [FastAPI](https://fastapi.tiangolo.com/)
- [Flutter](https://flutter.dev/)

## Data
- [한국음식이미지 AIhub](https://aihub.or.kr/aidata/13594)
- [Imageye](https://chrome.google.com/webstore/detail/image-downloader-imageye/agionbommeaifngbhincahgmoflcikhm) - Image Downloader
- [AutoCrawler](https://github.com/YoongiKim/AutoCrawler)
- [식품의약품안전처](https://www.foodsafetykorea.go.kr/fcdb/)
- [IHerb Scrapping](https://github.com/Nutri-AI/Iherb_Scraping)

## ERD
<div align="center">
  <img width="55%" alt="NutriAI_database_ERD" src="https://github.com/Nutri-AI/.github/blob/main/profile/images/ERD_key.drawio.png">
</div>

## Development
- [Data Preprocessing](https://github.com/Nutri-AI/Iherb_Preprocessing)
- [Database](https://github.com/Nutri-AI/Database)
- [Model](https://github.com/Nutri-AI/yolov3_onnx_inf)
- [API](https://github.com/Nutri-AI/api-fastapi)
- [APP](https://github.com/Nutri-AI/Application)

