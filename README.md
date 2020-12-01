# Seoul-commercial-business-analysis
# 서울 상가업종 분석
# 문제정의
서울에 어떠한 업종이 있는지 확인하고 업종별로 어느 지역이 많이 분포되어 있는지 확인한다.   
학원가가 많다는 대치동에 정말로 학원이 많이 있는지 확인한다.   
   
# 데이터수집
데이터는 공공데이터 포털을 통해 얻었다.   
공공데이터 포털은 공공데이터를 한 곳에서 제공하는 통합 창구로 쉽고 편리하게 공공데이터를 얻을 수 있다.   
   
수집한 데이터:   
상가업소정보_201912_01.csv

# 데이터전처리
수집한 데이터에 결측치와 이상치가 없었다.
    
# 데이터 모델링
부산과 서울중 서울로 모델링   
서울에 있는 업종중 음식, 부동산, 학문/교육, 의료 업종으로 모델링   
각 업종에서 상권업종소분류명으로 다시 한번 모델링   
구별 학원수 비교를 위해 학원-입시를 조건으로 시군구명으로 모델링   
동명 학원수 비교를 위해 학원-입시를 조건으로 법정동명으로 모델링   

# 시각화 및 탐색(서울의 지역별, 업종 종류별 순위)
## 서울 업종 종류별 순위
![서울에 많은 업종](https://user-images.githubusercontent.com/59160781/100754708-bd0fc780-342e-11eb-879b-ea904aab3418.PNG)
   
## 서울 음식 업종 지역별 순위
![서울에 음식 업종](https://user-images.githubusercontent.com/59160781/100754829-db75c300-342e-11eb-8423-e0339c327605.PNG)
   
## 강남구 음식 업종 종류별 순위
![강남구 음식 업종](https://user-images.githubusercontent.com/59160781/100754896-edeffc80-342e-11eb-9a8b-48b790741c5e.PNG)
   
## 서울 부동산 업종 지역별 순위
![서울에 부동산 업종](https://user-images.githubusercontent.com/59160781/100754962-006a3600-342f-11eb-80fc-18bfb0fd01ee.PNG)
   
## 강남구 부동산 업종 종류별 순위
![강남구 부동산 업종](https://user-images.githubusercontent.com/59160781/100754996-0d872500-342f-11eb-8c27-f81830046810.PNG)
   
## 서울 학문/교육 업종 지역별 순위
![서울에 학문 업종](https://user-images.githubusercontent.com/59160781/100755086-242d7c00-342f-11eb-93a6-58418161be55.PNG)
   
## 강남구 학문/교육 동별 순위
![대치동](https://user-images.githubusercontent.com/59160781/100755187-42937780-342f-11eb-8ed7-db2cf43a84c9.PNG)

## 강남구 학문/교육 업종 종류별 순위
![강남구 학업 업종](https://user-images.githubusercontent.com/59160781/100755248-52ab5700-342f-11eb-863b-fe107b3821e9.PNG)
   
## 서울 의료 업종 지역별 순위
![서울에 의료 업종](https://user-images.githubusercontent.com/59160781/100755288-5f2faf80-342f-11eb-9c7b-de515cd642b1.PNG)
   
## 강남구 의료 업종 종류별 순위
![강남구 의료 업종](https://user-images.githubusercontent.com/59160781/100755342-6e166200-342f-11eb-97f8-8eaccb448b4d.PNG)

# 시각화 및 탐색(서울 학문/교육 분석)
## 서울 학문/교육 업종 종류별 순위
![서울에 학문 소분류명](https://user-images.githubusercontent.com/59160781/100755598-b170d080-342f-11eb-8b9e-09bf7429c16f.PNG)
   
## 강남구 학문/교육 동별 순위
![서울에 학문 동명2](https://user-images.githubusercontent.com/59160781/100755443-871f1300-342f-11eb-8128-de7c11740425.PNG)
   
## 서울 학문/교육 지도
![서울 지도](https://user-images.githubusercontent.com/59160781/100755951-0e6c8680-3430-11eb-83bc-ff092a89d853.PNG)










