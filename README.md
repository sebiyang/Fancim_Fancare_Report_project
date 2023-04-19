# Fancim_Fancare_Report_project 팬케어 보고서 프로젝트 

## 서비스 소개 💜

Fancim 은 크리에이터와 팬이 소통할 수 있는 어플리케이션으로, 메시지 보내기, 후원하기, 선물하기 등의 활동이 가능한 어플임. 해당 서비스는 크리에이터들의 더 편안하고 안정적인 셀럽활동을 위한 " 보고서" 로, 셀럽과 팬의 해당 월 활동 지표, 팬 등급 분류 등 셀럽의 앱 활동을 측정한 내역들이 담겨있는 보고서임. 해당 서비스는 로그 데이터를 바탕으로 후원 금액, 반응 속도, 충성심 등을 정량화해 셀럽의 당월 활동 지표와 팬의 등급을 대쉬보드 형태로 가공해 매월 메일링하는 서비스에서 사용되었음. 



## 개발과정 👩‍💻

- 구글 빅쿼리를 통해 데이터를 추출, 필요한 컬럼 생성
- 데이터 전처리, 통계학적 근거를 통한 점수화 체계 생성
- 데이터 모델링, 비지도학습 모델 5가지를 비교해 적합한 모델 선정
- 셀럽별로 VIP 팬, 잠재 VIP 팬, 일반팬, 이탈가능팬, 이탈팬 5가지 등급으로 팬을 분류 
- tableau 를 이용해 이를 자동화 시각화, 셀럽에게 월단위로 제공 
- 추후 앱 내에서 셀럽이 팬 등급을 확인할 수 있게하는 인앱서비스 런칭 예정


## 파일 요약 📂

- "Fancare_Report_page0-2" 는 태블로에서 시각화가 이루어질 주요 KPI 를 추출하고 가공하는 과정임
- "Fancare_Report_page3" 는 태블로에서 시각화가 이루어질 팬의 등급 분류와 자동 코멘트를 생성하는 과정임 



## Introduction to Services 💜

Fancim is an application that allows creators and fans to communicate, and it is an application that allows activities such as sending messages, sponsoring, and giving gifts. The service is a "fan care report" for creators' more comfortable and stable celebrity activities, which includes details of celebrities' app activities such as monthly activity indicators and fan rating classification. The service was used in a service that quantifies sponsorship amount, response speed, and loyalty based on log data, processes celebrities' monthly activity indicators and fans' ratings in the form of dashboards and mails them every month. 



## Development process 👩‍💻

- Extract data and generate required columns through Google Big Query
- Data preprocessing, generating scoring schemes based on statistical evidence
- Data modeling, selecting the right model by comparing five unsupervised learning models
- VIP fans, potential VIP fans, general fans, breakaway fans, and breakaway fans are classified into five categories by celebrity 
- Automation visualization using tableau and monthly delivery to celebrities 
- In the future, an in-app service will be launched to allow celebrities to check their fan ratings within the app


## File Summary 📂

- "Fancare_Report_page0-2" is the process of extracting and processing the key KPIs to be visualized in the tablo
- "Fancare_Report_page3" is the process of generating rating and automatic comments for fans that will be visualized in the tableau
