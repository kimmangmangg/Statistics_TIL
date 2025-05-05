# 통계학 4주차 정규과제

📌통계학 정규과제는 매주 정해진 분량의 『*데이터 분석가가 반드시 알아야 할 모든 것*』 을 읽고 학습하는 것입니다. 이번 주는 아래의 **Statistics_4th_TIL**에 나열된 분량을 읽고 `학습 목표`에 맞게 공부하시면 됩니다.

아래의 문제를 풀어보며 학습 내용을 점검하세요. 문제를 해결하는 과정에서 개념을 스스로 정리하고, 필요한 경우 추가자료와 교재를 다시 참고하여 보완하는 것이 좋습니다.

4주차는 `2부. 데이터 분석 준비하기`를 읽고 새롭게 배운 내용을 정리해주시면 됩니다.


## Statistics_4th_TIL

### 2부. 데이터 분석 준비하기
### 10. 데이터 탐색과 시각화



## Study Schedule

|주차 | 공부 범위     | 완료 여부 |
|----|----------------|----------|
|1주차| 1부 p.2~56     | ✅      |
|2주차| 1부 p.57~79    | ✅      | 
|3주차| 2부 p.82~120   | ✅      | 
|4주차| 2부 p.121~202  | ✅      | 
|5주차| 2부 p.203~254  | 🍽️      | 
|6주차| 3부 p.300~356  | 🍽️      | 
|7주차| 3부 p.357~615  | 🍽️      | 

<!-- 여기까진 그대로 둬 주세요-->

# 10. 데이터 탐색과 시각화

```
✅ 학습 목표 :
* EDA의 목적을 설명할 수 있다.
* 주어진 데이터셋에서 이상치, 누락값, 분포 등을 식별하고 EDA 결과를 바탕으로 데이터셋의 특징을 해석할 수 있다.
* 공분산과 상관계수를 활용하여 두 변수 간의 관계를 해석할 수 있다.
* 적절한 시각화 기법을 선택하여 데이터의 특성을 효과적으로 전달할 수 있다.
```
<!-- 새롭게 배운 내용을 자유롭게 정리해주세요.-->

## 1. 데이터 탐색
- **데이터 분석의 중요성** <br>데이터의 형태와 분포, 이상치 등을 탐색하는 것이 중요하며, 이는 ML 모델링의 성능에 큰 영향을 미친다.<br>
- **탐색적 데이터 분석(EDA)** <br>데이터의 특성을 파악하고, 이상치를 식별하며, 데이터의 품질을 향상시키기 위한 과정.<br><br>
<img width="877" alt="Image" src="https://github.com/user-attachments/assets/b79d4bd3-0078-4003-ab4d-22bf364def0b" /><br><br>

## 2. EDA와 데이터 분석
- **EDA의 목적** <br>데이터 파악을 효율적으로 하기 위해 시각화를 사용하며, 분석 결과를 효과적으로 전달하는 것이 목표.<br>
<img width="866" alt="Image" src="https://github.com/user-attachments/assets/50b2d5ca-5825-46a9-904e-ff9a39594e13" /><br>
- **시각화 기법** <br>시간 시각화, 범주 시각화, 분포 시각화, 관계 시각화, 공간 시각화 등 다양한 방법이 존재.<br><br>

## 3. 엑셀을 활용한 EDA
- **샘플 데이터 분석** : 엑셀을 사용하여 데이터를 샘플링하고, 변수의 특성을 직접 확인하는 방법.<br>
- **피벗 테이블** : 지점별 상황, 고객 등록별 평균 등을 확인하기 위한 도구로 사용.<br><br>

## 4. 탐색적 데이터 분석 실습
- **Python 라이브러리 활용** : pandas, seaborn, matplotlib 등을 사용하여 데이터 분석을 수행.<br>
- **데이터 불러오기 및 확인** : 데이터셋을 불러와서 기초 통계량과 데이터 분포를 확인.<br><br>

## 5. 공분산과 상관성 분석
- **공분산** <br>두 분산의 관계를 나타내며, 양의 상관관계와 음의 상관관계를 식별.<br>
<img width="928" alt="Image" src="https://github.com/user-attachments/assets/35c4206f-dfa7-405b-a10d-043005dc31fa" /><br>
<img width="863" alt="Image" src="https://github.com/user-attachments/assets/4bcef7dd-a0df-433c-a5f2-ab627c6bdbe3" /><br>
<img width="840" alt="Image" src="https://github.com/user-attachments/assets/2daa6dad-5ce3-4f27-b329-949234c3c43d" /><br>
- **상관계수** <br>변수 간의 상관성을 수치화하여 비교할 수 있도록 함.<br><br>
<img width="857" alt="Image" src="https://github.com/user-attachments/assets/c6eae5a6-dcb1-4647-b56a-835d700243f6" /><br>
<img width="876" alt="Image" src="https://github.com/user-attachments/assets/fff4f04f-a3be-464b-ad2f-191e514deaed" /><br>
<img width="867" alt="Image" src="https://github.com/user-attachments/assets/7bcd6fed-cbaa-45e8-8400-0bbc1c6b0b52" /><br><br>

## 6. 시간 시각화
- **시계열 데이터** <br>시간의 흐름에 따른 데이터 변화를 선그래프나 막대그래프로 표현.<br>
- **이동평균** <br>데이터의 트렌드를 파악하기 위해 사용되는 방법.<br><br>
<img width="883" alt="Image" src="https://github.com/user-attachments/assets/e4757913-2422-42f8-a7d2-2f36a35592b7" /><br><br>

## 7. 비교 시각화
- **히트맵** <br>그룹과 비교 요소가 많을 때 이를 효과적으로 시각화할 수 있는 방법.<br>
- **방사형 차트** <br>여러 그룹의 여러 변수를 시각적으로 비교.<br>
- **평행 좌표 그래프** <br>업계 현황 파악 및 새로운 전략의 비교우위 표현위한 방법.(전략 캔버스)<br>방사형 차트에서 사용했던 데이터셋을 평행 좌표 그래프로 시각화<br><br>
<img width="706" alt="Image" src="https://github.com/user-attachments/assets/f5266ea3-e41b-4f6e-b9df-7992c6030ae8" /><br>
<img width="676" alt="Image" src="https://github.com/user-attachments/assets/9523c06b-e3bf-46f4-b864-1c0ebb6ea1aa" /><br><br>

## 8. 분포 시각화
- **히스토그램** <br>데이터의 분포를 시각적으로 표현하여 이해를 돕는 도구.<br>
- **파이차트 및 도넛차트** <br>구성 요소들의 비율을 시각적으로 표현.<br>
- **트리맵 차트** <br>계층적 데이터를 직사각형으로 표현하여, 각 영역의 크기가 데이터의 크기를 나타냄.
- **와플차트** <br>작은 정사각형으로 구성된 차트로, 각 정사각형이 데이터의 비율을 나타냄.<br><br>
<img width="850" alt="Image" src="https://github.com/user-attachments/assets/295c35ae-0ac5-4f63-abe6-d0e2004c4c55" /><br><br>

## 9. 관계 시각화
- **산점도** <br>두 개의 연속형 변수 간의 관계를 나타내며, R&D 비용과 수익 간의 관계를 시각화.<br>
- **버블 차트** <br>마케팅 비용과 관리 비용을 추가하여 시각화. 마케팅 비용은 범위의 크기로, 관리 비용은 색상으로 표현.<br><br>
<img width="873" alt="Image" src="https://github.com/user-attachments/assets/1b5d619a-c670-476c-b3ed-fdaaa76b652c" /><br><br>

## 10. 공간 시각화
- **지도 시각화** <br>서울 스타벅스 지점과 미국 주별 실업률을 지도 위에 시각화. folium과 plotly를 사용하여 다양한 지도 형태와 데이터를 표현.<br>
- **커넥션맵** <br>서울과 각국 수도 간의 연결을 시각화하여 지리적 관계를 표현.<br><br>
<img width="855" alt="Image" src="https://github.com/user-attachments/assets/eb3bba8a-c3f5-4b77-b98d-1a190df02d59" /><br><br>


## 11. 박스 플롯
- **기본 박스 플롯** <br>데이터의 분포 및 변화를 시각적으로 표현. 중앙값, 사분위수, 이상치를 통해 데이터의 특성 파악에 사용.<br>
- **그룹별 박스 플롯** <br>State 변수를 사용하여 뉴욕, 캘리포니아, 플로리다의 수익을 비교.<br><br>
<img width="879" alt="Image" src="https://github.com/user-attachments/assets/80e97771-cc90-4e4b-9d4c-e049853b09f6" /><br>


<br>
<br>

# 확인 문제

## 문제 1.
> **🧚 공분산과 상관계수의 차이점에 대해 간단히 설명하세요.**

```
공분산은 서로 공유하는 분산을 뜻하고, 두 분산의 관계를 나타낸다. 따라서 공분산 값은 두 변수의 공통적인 분산의 정도를 나타내며, 부호에 따라 양의 상관관계, 음의 상관관계, 0의 상관관계를 의미한다.<br>
하지만 공분사나 값이 상관성의 정도를 나타내지는 못하는데, 이러한 상관성의 정도를 보여주는 것이 상관계수이다.

```

## 문제 2.
> **🧚 다음 데이터 분석 목표에 적합한 시각화 방법을 보기에서 모두 골라 연결해주세요.**

> 보기: 산점도, 선그래프, 막대그래프, 히스토그램, 박스플롯

(a) 변수의 분포 확인   
(b) 두 변수 간의 관계 확인   
(c) 집단별 평균 비교   
(d) 시계열 데이터 분석

<!--중복 가능-->

```
(a) 히스토그램, 박스플롯 
(b) 산점도  
(c) 막대그래프, 박스플롯  
(d) 선그래프, 막대그래프
```


### 🎉 수고하셨습니다.
