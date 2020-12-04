# Virtual_Environment_Process_Analysis 
제품 공정에 대한 가상 데이터 분석 

## 가상 환경 분석 
Flexsim 소프트웨어를 이용해 EGR Cooler 제품의 조립공정 시뮬레이션 모델을 만든 후 그 과정에서 생성되는 데이터들을 활용해 머신러닝 분류 알고리즘에 학습시켜 OEE를 항샹시키는 데에 활용할 수 있도록 한다.
  ### 개발 순서
  1. EGR Cooler를 제작하는 공정에 대하여 순서 및 공정 요소를 선정
  2. Flexsim 소프트웨어를 이용하여 EGR Cooler 조립 공정을 제작
  3. 일정 시간을 설정하여 해당 시간의 제품 데이터를 excel 파일로 저장
  4. 저장된 excel 파일을 이용하여 python 머신러닝 분류 알고리즘에서 데이터의 상관관계를 분석
