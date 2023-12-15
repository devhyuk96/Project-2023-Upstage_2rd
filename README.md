# Project-2023-Upstage_2rd# 💊 Second Project : Exploring Risk Factors for Liver Disease: Hepatitis B, Hepatitis C, Cirrhosis


## Abstract
> 간과 관련된 질병에 대해 탐색하고 각 병과 관련이 있는 요인을 검증해보기.

<h2> 👪 Team </h2>

> Name : URSA(우루사)

<h3> 👪 Members </h3>
<table>
  <tr>
    <td> <div align=center> 👑 </div> </td>
    <td> <div align=center>  1 </div> </td>
    <td> <div align=center>  2 </div> </td>
    <td> <div align=center>  3 </div> </td>
  </tr>
  <tr>
    <td> <div align=center> <b>김도연</b> </div> </td>
    <td> <div align=center> <b>서상혁</b> </div> </td>
    <td> <div align=center> <b>김다운</b> </div> </td>
    <td> <div align=center> <b>신동혁</b> </div> </td>
  </tr>
  <tr>
    <td> <img alt="Github" src ="https://github.com/Daw-ny/Upstage_02nd_Proj/assets/76687996/8d57d084-1d8c-4306-8765-b8d05cd1fc73" width="200" height="300"/> </td>
    <td> <img alt="Github" src ="https://github.com/Daw-ny/Upstage_02nd_Proj/assets/76687996/a7be969c-b5ad-4f14-9dd9-cb72640c49a3" width="200" height="300"/> </td>
    <td> <img alt="Github" src ="https://github.com/Daw-ny/Upstage_02nd_Proj/assets/76687996/37f278cf-3c62-44ca-a49d-6a7799078b4c" width="200" height="300"/> </td>
    <td> <img alt="Github" src ="https://github.com/Daw-ny/Upstage_02nd_Proj/assets/76687996/cbd0651a-4d70-41d8-aad3-b654c42f16e2" width="200" height="300"/> </td>
  </tr>
  <tr>
    <td> <div align=center> <a href="https://github.com/d-yeon"> <img alt="Github" src ="https://img.shields.io/badge/Github-181717.svg?&style=plastic&logo=Github&logoColor=white"/> </div> </td>
    <td> <div align=center> <a href="https://github.com/S-RSH"> <img alt="Github" src ="https://img.shields.io/badge/Github-181717.svg?&style=plastic&logo=Github&logoColor=white"/> </div> </td>
    <td> <div align=center> <a href="https://github.com/Daw-ny"> <img alt="Github" src ="https://img.shields.io/badge/Github-181717.svg?&style=plastic&logo=Github&logoColor=white"/> </div> </td>
    <td> <div align=center> <a href="https://github.com/HyeokHam"> <img alt="Github" src ="https://img.shields.io/badge/Github-181717.svg?&style=plastic&logo=Github&logoColor=white"/> </td>
  </div> </tr>
</table>

<h3> 🛑 Role & Rule </h3>

> ### Ground Rule
> - 데이터의 이해를 돕기 위해 관련 자료를 찾아보고 공유하며 데이터 활용도를 높이기 위해 Code Book을 다같이 직접 작성하고 정의하였다.
> - 회의를 통해 각자의 역할을 정하고 다음 회의까지 진행된 상황을 공유하여 서로의 피드백을 듣고 필요한 부분은 수정하였다.
> - 휴식시에는 꼭 다같이 쉴것.


<table>
  <tr>
    <td> <div align=center> <b> 이름 </b> </div> </td>
    <td> <div align=center> <b> 역할 </b> </div> </td>
  </tr>
  <tr>
    <td> <div align=center> <b> 김도연 </b> </div> </td>
    <td> <b>EDA </b>(데이터 별 결측치 및 이상치 탐색, 분포 확인)</br> <b>파생변수 </b>(Hepatitis B 감염환자 여부 생성) </br> <b>간 관련자료 </b>(각 변수의 의학적 설명과 작성치의 기준 확립)</br><b>코드북작성 </b>(데이터 확립을 위한 코드북 작성) </td>
  </tr>
  <tr>
    <td> <div align=center> <b> 서상혁 </b> </div> </td>
    <td> <b>EDA </b>(데이터 별 결측치 및 이상치 탐색, 분포 확인)</br> <b>데이터 크롤링과 병합 </b>(hepatitis B와 관련된 변수 수집 및 병합) </br><b>코드 및 데이터 정리 </b>(활용한 코드 및 데이터 정리 및 취합)</br><b>코드북작성 </b>(데이터 확립을 위한 코드북 작성) </td>
  </tr>
  <tr>
    <td> <div align=center> <b> 김다운 </b> </div> </td>
    <td> <b>EDA </b>(데이터 별 결측치 및 이상치 탐색, 분포 확인)</br> <b>데이터 분석 </b>(로지스틱 적합결과 출력 및 정리, Tukey의 사후검정 실행)</br><b>도표 생성 </b>(기초통계량 산출 및 결과물 도표 생성)</br><b>코드북작성 </b>(데이터 확립을 위한 코드북 작성) </td>
  </tr>
  <tr>
    <td> <div align=center> <b> 신동혁 </b> </div> </td>
    <td> <b>EDA </b>(데이터 별 결측치 및 이상치 탐색, 분포 확인)</br> <b>시각화 그래프 결합 </b>(유사한 속성의 그래프를 하나로 묶어 간편히 보일 수 있도록 출력)</br><b>데이터 크롤링과 병합 </b>(hepatitis B와 관련된 변수 수집 및 병합)</br><b>코드 및 데이터 정리 </b>(활용한 코드 및 데이터 정리 및 취합) </td>
  </tr>
</table>

<h3> 📽️ Project Intro </h3>

<table>
  <tr>
    <td> <div align=center> <b> Subject </b> </div> </td>
    <td> 간에 관련된 질병인 Hepatitis B, C와 Cirrhosis에 대해 EDA를 진행하고 이에 파생되는 가설 검증 </td>
  </tr>
  <tr>
    <td> <div align=center> <b> Processing </b> </div> </td>
    <td> 1. 데이터의 각 칼럼이 어떤 의미를 갖는지 확인하고 각 칼럼의 분포 및 결측, 이상치 존재여부 확인 </br>
  2. 데이터 맞춤 전처리 및 이상치 대치 이후 기초통계량을 확인하고 병의 진행 집단별로 분석 가설을 세우고 적합한 방법으로 검증
  </td>
  </tr>
  <tr>
    <td> <div align=center> <b> Develop Enviroment </b> </div> </td>
    <td> <tt>Tool</tt>: Jupyter Notebook, VS Code, Microsoft Excel</td>
  </tr>
  <tr>
    <td> <div align=center> <b> Communication Enviroment </b> </div> </td>
    <td> <tt>Notion</tt>: EDA프로젝트를 위한 역할분담, 아이디어 브레인 스토밍, 프로젝트 관련 회의 내용 기록 </br> <tt>SLACK, Zoom, Offline Meeting</tt>: 실시간 대면/비대면 회의 </td>
  </tr>
</table>

<h3> 📆 Project Procedure </h3>

>  자세한 진행 내용은 [11조 URSA](https://www.notion.so/11-e525c7c651aa46c5954548eb2cad2e29?pvs=4)에서 확인하실 수 있습니다.

<h3> 📂 Project Structure </h3>

> - Code
>> 01_project_eda.ipynb
>> - cirrhosis 관련 데이터 탐색과 간단한 heatmap 코드가 포함되어 있습니다.
>>
>> 02_Cirrhoisi_detail.ipynb
>> - 본격적으로 각 변수의 분포를 확인하고 ANOVA, Tukey's HSD를 진행하였습니다.
>>
>> 03_cancer.ipynb
>> - cancer 데이터를 활용하여 plotly animation figure을 생성하였습니다.
>>
>> 04_hepatitis.ipynb
>> - hepatitis B에 대해 변수의 분포와 관계에 대해 확인하고 logistic regression을 적합하였습니다.
>>
>> 05_codebook.ipynb
>> - 코드북을 쉽게 만들기 위해 사용했습니다.
>>
>> 06_hepatitis_c.ipynb
>> - 기초통계량 표를 만들기 위해 활용하였습니다.
