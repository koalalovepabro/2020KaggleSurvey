# 2020 Kaggle Machine Learning & Data Science Survey
## 1. Data
[kaggle_survey_2020_responses.csv](https://github.com/koalalovepabro/2020KaggleSurvey/blob/master/kaggle_survey_2020_responses.csv)  
23,859명의 캐글 사용자를 대상으로 2020년 10월 일주일간 실시한 머신러닝과 데이터사이언스 관련 설문조사 데이터

## 2. What I learn through this analysis
Data Scientist를 꿈꾸고있는 나에게 무척 흥미로운 데이터였기에 분석을 해 보았다.  
전 세계 캐글 사용자의 머신러닝 및 데이터사이언스에 관한 설문 응답내용을 통해  
Data Science를 공부하는 사람들 또는 Data Scientist들의 관심사와 Data Science 분야의 트렌드를 파악하고 이해할 수 있었으며, 질문별 응답 내용과 빈도 분석을 통해 캐글러의 관심사와 인구통계학적 정보를 확인할 수 있었다.  
질문별 응답내용과 빈도수 분포를 파악해보고 시각화시켜서 비교해 보았다.  

### [ 예시 ] 질문내용과 여러 질문을 결합해서 확인할 수 있는 내용들 
**🧐 캐글러는 주로 어느 지역에 살고 어떤 직업군에 종사하고 있을까?**  
![img](img_06.png)
![img](img_05.png)

**🧐 캐글러의 성별과 연령대는 어떻게 될까?**  
**🧐 연령대별 성별 비율은 어떻게 달라질까?**  
![img](img_01.png)

**🧐 캐글러의 임금은 어느정도일까?**  
![img](img_02.png)

**🧐 국가별 임금의 차이는 어느정도일까?**  
![img](img_03.png)
![img](img_04.png)

**🧐 캐글 유저는 주로 어떤 언어와 어떤 개발도구를 사용할까?**  
![img](img_07.png)
![img](img_10.png)

**🧐 성별에 따라 사용하는 언어에 차이가 있을까?**  
![img](img_08.png)

**🧐 입문 언어를 추천한다면 어떤 언어를 추천할까?**    
![img](img_09.png)

## 3. What I did in this analysis
- 총 39개의 질문이 있기 때문에 각 질문의 응답내용을 확인하고 시각화 하는데에 반복작업이 필요했는데, 질문 번호만 넘겨주면 알아서 빈도수를 분석하는 함수를 만들어서 같은 작업을 반복하는 것을 줄였다. 
- 질문별 각 응답내용의 빈도 분포를 `seaborn countplot`, `seaborn barplot`으로 시각화하는 함수를 만들어서 마찬가지로 반복작업을 줄였다.

## 4. Reference
[CORAZZON님의 노트북](https://www.kaggle.com/corazzon/how-to-use-pandas-filter-in-survey-eda)