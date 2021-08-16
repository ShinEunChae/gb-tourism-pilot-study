## 프로젝트 소개
  ### 주제
    경북 도내 관광지/관광기업 탐색 및 분석  
    여기서는 문경시와 안동시 두 개 지역을 임의로 택하여 진행
  
  
  ### 내용
    1. Selenium을 활용하여 네이버 블로그 포스팅의 관련 데이터 크롤링
   ![Animation](https://user-images.githubusercontent.com/68213799/129530707-71365e16-50d9-4526-b1eb-2549395f0dc9.gif)
    
    2. konlpy 라이브러리의 okt 형태소 분석기를 사용, 명사 추출  
    3. wordcloud로 핵심 키워드 탐색
   ![wordcloud](https://user-images.githubusercontent.com/68213799/129531870-82d6a4fc-73cf-47ca-a350-71971f799767.png)
    
    4. 3의 결과를 바탕으로 임의로 관광지/관광기업 선정  
    5. 선정한 관광지들에 대하여 심화 분석 진행  
    6. folium 라이브러리를 활용하여 지도상에 시각화  
   ![gif_folium](https://user-images.githubusercontent.com/68213799/129533727-4bb95fb5-294f-4c1d-b010-e63661841a57.gif)
  
  
  ### 결과
    역사와 전통이 담긴 여행  
    패러글라이딩, 사격 등 다양한 레저스포츠 체험 역시 인기  
    코로나 바이러스로 인한 피로감으로 '힐링' 테마 여행의 증가  
    다소 접근성이 떨어지는 숙소  
  
  
  ### 향후 분석 계획
    타 sns 데이터를 크롤링하여 부족한 데이터와 빈약한 키워드 보충  
    키워드 간 연관성 분석으로 분석 정교화
