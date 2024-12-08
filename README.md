# 2023 DATA, ai 분석 경진대회 
### 🍎 사과 품질 예측 모델 개발 & 프로그램 구축 🍏

본선 진출, 상위 10% 

## 🌳Introduction

 본 대회는 사과 종류(후지/홍로)별로 사과 품질 예측 모델과 사용자별 사과 품질 분석 AI 모델을 개발
한다. 사과 품질 예측 모델은 데이터 분석을 통해 사과의 품질을 예측하고 사과의 품질에 영향
을 미친 요인 등을 알려주는 모델이다. 이 과정에서 요인분석과 상관분석 기법을 활용하여 차원을 축소함과 동시에 품질에 영향을 주는 주요 기상 변수를 추출한다.
사용자별 사과 품질 분석 AI 모델은 사용자가 사과를 심을 때부터 수확 전까지의 기상 데이터를 기입하면, 해당 사과의 품질을 결정하는 주요 기상 데이터를 자동으로 분석하여 현재 사과의 상태를 예측하고 개선 방향을 제공한다. 
해당 모델을 개발하기 위해 필요한 전처리와 성능 개선 단계를 거쳐 진행한다.


## 문제 선택 이유

사과가 세계적으로 많이 재배되고 소비되는 중요한 작물 중 하나이며, 기후 변화와 관련하여 사과의 품질에 큰 영향을 미치기 때문이다. 또한, 1)국립원예특작
과학원 온난화대응농업연구소의 연구결과에 따르면 기후 변화의 영향을 가장 많이 받는 과일
은 사과이며, 오는 2050년대에는 강원도 일부 산지에서만 사과를 재배할 수 있을 것이라고 예
측되고 있다. 이러한 상황에서 사과 생산에 대한 대응 방안이 필요하다고 생각했으며, 사과 품
질 예측을 통해 이를 해결하고자 한다.

사과의 품질과 기후 요소들 간의 상관관계를 파악한다면, 농가들은 더욱 효율적인 생산 방법
을 도입하고 농작물 관리에 있어 더 나은 결정을 내릴 수 있을거라 생각한다. 또한, 소비자들
은 예측 가능한 품질의 사과를 구매함으로써 만족도가 향상되며, 이는 사과 시장에 긍정적인
영향을 끼칠 것이다. 따라서 해당 문제는 농가와 소비자 모두에게 다양한 이점을 제공할 수 있

## 💾 Dataset

- 기상 데이터 : 기상청 API 이용 (지역별 기상 데이터)
- 타겟데이터는 농촌진흥청 자료를 활용하여 품질 기준을 계산한 후 생성.

## 📑Project Summary

![image](https://github.com/user-attachments/assets/adc3f043-03ca-4a9a-b41c-f8f28d96bb14)

