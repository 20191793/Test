# 한밭대학교 한민우 이창민팀
**팀구성**
+ 20191793 한민우
+ 20182658 이창민
# Project Background
+ **배경 분석**
  + 컨슈머인사이트에서 조사한 2021년, 2022년 국내여행 여부를 살펴보면 2021년 1분기에 51.4%, 2분기에 57.8%, 3분기에 63.5%, 4분기에 67.7%이고, 2022년 1분기에 64.3%, 2분기에 64.9%, 3분기에 74.1%, 4분기에 73.5%로 코로나 펜데믹이 끝난 이후로 국내여행을 하는 사람들이 늘어나고 있음을 알 수 있다. 이러한 전망에 따라, 앞으로도 많은 사람들이 여행을 다닐 것으로 예측되고, 여행 어플에 대한 수요도 증가할 것으로 예상된다.

+ **문제점**
  + 일반적인 여행 어플들은 추천 여행지를 글과 사진만으로 표현하거나, 지도에 위치만 보여주거나 하는 식으로 간단한 구성을 하고 있다. 그렇기에 소개글이 잘못 써져있거나 설명이 부족하다면 해당 여행지에 대해 판단할 정보가 없다.
  + 소개글이나 리뷰를 직접 1개씩 읽어보지 않는 이상 여행지가 어떤 느낌이고 어떤 환경인지를 알 수 없다.
 
+ **필요성**
  + 여행지의 위치 표시와 자동차 이동 경로 표시, 이동 시간 표시, 자동 일정 추천 등의 기능들을 통해 여행 계획을 세우는데 시간을 효율적으로 사용할 수 있게 될 것이다.
  + 글을 일일이 읽어야만 하는 점에 대해서 여행지 정보를 점수로 매겨 지표화를 통해 그래픽적인 평가를 한 눈에 보게 한다. 이를 통해 사람들이 여행지에 대해 조사할 때 정보를 빠르게 파악할 수 있게 될 것이다.
  + 여행지에 대해 모르는 채로 검색하게될 상황에 대해 개발 어플리케이션에서 AI 챗봇 기능을 제공한다. 이를 통해 AI에게 간단히 질문한 후 해당 답변을 키워드로 추가적인 정보를 조사할 수 있게되어 조사 시간을 절약할 수 있게 될 것이다.

+ **프로젝트 목표**
  + 여행지 일정 관리를 도와주며, 각 여행지 간의 이동 경로를 보여주어 이동 계획에도 도움을 줄 수 있다. 무료 입장 여행지를 추천해주며 해당 여행지들 리뷰의 지표화를 통한 효과적인 정보 전달로, 여행 계획을 세우는 것에 도움을 주는 어플을 개발하는 것이다.
# System Design
+ **시스템 구성도**
<img src = "https://private-user-images.githubusercontent.com/128362238/270861262-1b16179f-5697-49c4-99c7-e919c6ce6ab6.PNG?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE2OTU3ODg3NjAsIm5iZiI6MTY5NTc4ODQ2MCwicGF0aCI6Ii8xMjgzNjIyMzgvMjcwODYxMjYyLTFiMTYxNzlmLTU2OTctNDljNC05OWM3LWU5MTljNmNlNmFiNi5QTkc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBSVdOSllBWDRDU1ZFSDUzQSUyRjIwMjMwOTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDIzMDkyN1QwNDIxMDBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT02NGIyMTMyMTllMmMxYjFiMTBjOTM4ZmM3OWUzNDFjMDEzZWRhMzE4NTEwN2FiOWEwZTZhMDY5NTE3NDhhM2IwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.ubGqGiEJo0lRgmrlaxRr-zkxNKdxE042v864lZL8N84" width="90%"></img>

+ **개발 사용**

# Case Study
+ **웹크롤링**
  + www.tripadvisor.co.kr 를 웹크롤링

# Conclusion
+ **개발 어플리케이션 문제점**
  + 높은 AI 의존도
     + 개발 어플리케이션의 주요 부분 중 여행지 특성 지표화와 AI 챗봇 시스템은 해당 AI 기업의 데이터 저쟝율에 따라 정확도가 달라진다.
       웹크롤링을 통해 얻은 여행지에 대한 정보가 AI 회사에 저장되어 있지 않다면, 사용하는 AI의 특징에 따라 사용자의 여행지 관련 질문에 답변을 하지 않거나 AI 기준에서 모르는 여행지에 대해 답변이 창조될 수도 있다.

       이를 해결하기 위해서는 저장되어 있는 모든 여행지에 대한 정보를 AI에게 질문해보고, AI의 답변을 사람이 일일이 웹크롤링으로 얻은 정보와 비교를 하며 사용할 수 있는 여행지와 없는 여행지를 검증해야한다.
       또 다른 방법으로는 AI회사에서 해당 AI에 대한 성능을 업그레이드할 때 우리나라의 모든 여행지에 대해서도 정보가 저장되기를 기다리는 것이다.

       이 두가지 모두 현재 상황으로는 해결하기에 적합한 방법이 아니므로 그 외의 적절한 해결 방법을 발견하기 전 까지 현 상황이 유지될 것이다.

# Project Outcome(대회 참가 시)
