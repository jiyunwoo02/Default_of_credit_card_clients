# Default_of_credit_card_clients

본 프로젝트는 default of credit card clients.csv 파일을 이용하여 의사결정나무 분석을 수행하였습니다.

1.1 (데이터 수집 및 전처리)
- 아래 data repository에서 원하는 dataset 선택 (변수가 15개 이상, 그리고 실제 label이 있는 데이터 선정)
  https://archive.ics.uci.edu/ml/datasets.php
- 데이터에 대해서 이해한대로 설명
- 전처리 진행

1.2 의사결정나무 구축 및 실험비교
- 의사결정나무를 구축하고, 가지치기(pruning phase)를 적용하기 전/후 실험결과를 비교

1.3 의사결정나무 학습모델 가시화 및 설명 
- 의사결정나무를 sklearn, graphviz 등을 이용해 가시화 하고, 해당 diagram을 다양하게 해석

1.4 의사결정나무의 특징 코멘트
- 본 실험을 수행하면서 느낀 의사결정나무의 특징에 대해서 기술
예시. 결측치에 예민한가? 이상치에 민감한가? 학습데이터에 과적합 문제가 있는가? 가지치기는 어느 정도 해야 하지? 등
