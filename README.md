# 2022_Summer_DA7

2022 CUAI 하계 컨퍼런스 DA 7팀 repository

<br/>

## Topic
LPAY 등급 예측을 통한 롯데 멤버스 고객 대상 개인화 마케팅 전략 제시



<br/>

## Team Member 
 
• [**강영훈**] - 중앙대학교 경영학과  
• [**김소은**] - 중앙대학교 응용통계학과   
• [**원민재**] - 중앙대학교 경영학과   

<br/>

## Background of Study     
코로나 19 및 스마트 폰을 통한 비대면 금융거래의 보편화 현상은 현재 간편 결제 시장의 성장을 불러일으켰다. 실제로 한국은행의 보도자료에 따르면 체크카드를 포함한 간편결제 서비스의 이용현황에서 이용 건수는 2016년 210만건 대비 2020년 1454만건으로 1244만건 증가하였고, 이용금액 또한 645 억원에서 4492 억원으로 3807억원 증가하였다.   

해당 간편결제 시장의 성장에 따라서 기존의 유통 산업에서도 ‘특정 생태계를 조성해 재화나 서비스 이용 시 다른 선택을 제한하게 종속 시켜 재구매를 촉진시키는 락인 효과 및 빅데이터 확보를 통한 신사업 확장을 위한 간편결제 서비스를 확대하고 경쟁력을 갖추려는 시도를 하고있다. 

롯데멤버스 또한 L.Pay간편결제 서비스 런칭 및 금융서비스(썸뱅크)와의 연계를 통해 충성 고객 확보 및 서비스 경쟁력 확충 등의 사업 확장을 진행하고 있으나, 해당 서비스의 경쟁력이 동종 업계 대비 저조한 편이며  유통/제휴사 결제 이력이 있는 유저 중 LPAY 결제 이력이 없는 유저가 대다수이고 온라인 매체에서의 LPAY 결제 금액 비중이 현저히 낮은 편이다.



<br/>

## Research Objective

LPAY 결제의 활성화를 통해 ARPU 증대, 락인효과 등을 촉진시키기 위해 머신러닝과 데이터 분석을 통해 개인의 LPAY RFM 등급을 예측하고 이에 대응한 개인화 마케팅 전략을 제안하고자 한다.


 <br/>
 
 ## Result 
 

<img width="571" alt="image" src="https://user-images.githubusercontent.com/79828628/184786443-8554f610-cab2-426c-8aac-e8f4a7f9b00a.png">

#### Classification matric
<img width="571" alt="image" src="https://user-images.githubusercontent.com/79828628/184786511-66d2d987-e349-4679-8c0b-f110188a52cb.png">

<br/>

##  Expectation effectiveness

롯데멤버스의 제공 데이터의 Unique 고객 수는 총 29,874 명이고 LPAY 미가입 유저 중 LPAY 1등급 예측 유저 총 683 명이다. 따라서, 제공 데이터 기준으로 1등급 예측 유저 / 전체 표본=  683 / 29,874 = 2.29 %이다.  

이와 같은 수치를 롯데 멤버스 홈페이지에서 발췌한 롯데멤버스의 연간 이용회원 수에 적용하면 롯데 멤버스 전체 이용 유저 = 2,100만 명이고 전체 유저 X 1등급 예측 유저 비율 = 2,100 만명 X 2.29% = 480,900 명이다. 따라서 1등급 예측 유저 LPAY 전환 시 기존 LPAY 가입 유저 대비 9.61 % 확보 효과가 발생할 것으로 추산한다.   

또한 롯데 멤버스 제공 데이터 기준 고객 당 월 평균 소비금액을 Lpay 전환시 기대되는 Lpay 월 전환 금액으로 추산하면 전체 1등급 예측 유저 수 X 전환 시 기대되는 LPAY 월 전환 금액 = 480,900 명 X 298,847 (원) 으로 총 143억 가량이 Lpay 전환 결제액으로 증가할 것으로 추산할 수 있다.  

기존 0등급 (Lpay 미 이용) 유저의 제휴/유통사 이용수가 2 ~ 4회이고, 기존 1등급 유저의 제휴/유통사 이용수 가 6 ~ 8회인 점을 고려하였을 때, LPAY 전환 시 평균적으로 2~4 개의 제휴사 / 유통사를 추가로  이용하게 유도하는 효과를 발생하여 충성 고객 확보에 용이할 것이다.  

결론적으로 LPAY 미가입 유저에 대한 예측 등급별 타겟팅 마케팅을 이용한 가입 전환을 통해서 LPAY 결제액과 매출액 및 충성 고객 수 상승에 기여 할 수 있다.













