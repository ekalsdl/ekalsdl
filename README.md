# 👩‍💻 Portfolio


### a collection of **major class assignments**

- Multi class Image Classification *https://github.com/ekalsdl/Multi-class-Image-Classification*

  포켓몬 이름 맞추기(다중분류)

- Deep Learning  *https://github.com/ekalsdl/Deep-Learning*

  건포도 이름 예측(이진분류), 과일 이름 예측(다중분류), 식당 월 매출 예측(회귀문제)
- Explainable Artificial Intelligence *https://github.com/ekalsdl/Explainable-Artificial-Intelligence*

  지진해일 발생 여부 예측(이진분류), 흉부 X-Ray 이미지로부터 폐렴 여부 검출(이진분류)

- Machine Learning *https://github.com/ekalsdl/Machine-Learning*

  주가 지수로부터 금값 예측(회귀문제), 주가 지수, 은, 석유, 백금, 팔라듐 가격으로부터 금값 예측(다중 회귀 문제), 강수 여부 예측(이진분류)

## 📫 Contact Me
- GitHub: @ekalsdl
- Email: ldm3479@gmail.com

<!--
**ekalsdl/ekalsdl** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<div align="center">

# 🚗 침착 (沈着)

### 데이터로 확인하는 내 주변의 침수 위험 주차장

<p align="center">
  <sub>
    침착은 강수량, 지형 정보, 과거 침수 이력 데이터를 활용하여
    주차장별 상대적인 침수 위험도를 분석하고,
    사용자 주변의 주차장 정보를 제공하는 서비스입니다.
  </sub>
</p>

</div>

## 🎯 Project Purpose

- 침수로 인한 차량 피해 예방
- 공공데이터 기반 주차장별 침수 위험도 분석
- 상대적으로 위험도가 낮은 주차장 선택 지원

## ⚙️ Main Features

- 사용자 위치 기반 주변 주차장 조회
- 주차장별 침수 위험도 분석 및 순위 제공
- 과거 침수구역과 주차장 간 거리 분석
- 상대적으로 위험도가 낮은 주차장 추천

## 🛠 Tech Stack

| Category | Technology |
|:---|:---|
| Language | <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/> |
| Framework | <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white"/> |
| Data Analysis | <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white"/> |
| Database | <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white"/> |
| Version Control | <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/> |

<br>
API: 침수흔적도 REST API

## 📂 Data Sources

| 데이터 | 제공 기관 | 활용 목적 |
|:---|:---|:---|
| [전국주차장표준데이터](https://www.data.go.kr/data/15012896/standard.do) | 지방자치단체 | 서울시 내 주차장 데이터 수집 |
| [침수흔적도](https://www.safemap.go.kr/opna/data/dataViewRenew.do?objtId=212) | 행정안전부 재난보험과 | 과거 침수 이력 및 침수심 분석 |
| [방재기상관측(AWS)](https://data.kma.go.kr/data/grnd/selectAwsRltmList.do?pgmNo=56) | 기상청 | 주차장 주변 강수 위험도 산출 |
| [서울시 경사도](https://data.seoul.go.kr/dataList/OA-22241/F/1/datasetView.do) | 도시공간본부 도시계획상임기획과 | 지형 특성을 활용한 저지대 위험도 분석 |

## ⚠️ Limitations

- 2025년도 데이터를 기준으로 분석하여 이후 발생한 침수 이력 및 환경 변화는 반영하지 못합니다.
- 실시간 강수 및 배수 시설 상태를 완벽하게 반영하지 못합니다.
- 산출된 위험도는 주차장 간 상대적 비교 지표이며, 실제 침수 확률이나 안전성을 보장하지 않습니다.
