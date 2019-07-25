# Data-Processing-Note (with Pandas)

- [기초](https://github.com/yahwang/Data-Processing-Note/tree/master/basic.ipynb)
  - 타입 (+ astype)

- EDA
  - [data slicing ( loc, iloc, xs )](https://github.com/yahwang/Data-Processing-Note/tree/master/data_slicing.ipynb)  
  - [데이터 중복 다루기 Unique & duplicated](https://github.com/yahwang/Data-Processing-Note/tree/master/duplicated.ipynb)
  - [데이터 결측치(NA) 값 처리 방법](https://github.com/yahwang/Data-Processing-Note/tree/master/null_value.ipynb)
    - [누락된 날짜 확인하는 방법(추가하는 법) - 날짜가 중복되지 않는 경우](https://github.com/yahwang/Data-Processing-Note/tree/master/find_nodate.ipynb)
  - [데이터 합치기 concat & merge](https://github.com/yahwang/Data-Processing-Note/tree/master/concat&merge.ipynb)
  - Value 전처리 방법
    - [일반적인 함수를 통한 전처리 (+ apply, map, ... )](https://github.com/yahwang/Data-Processing-Note/tree/master/preprocessing/general_preprocess.ipynb)
    - [groupby 함수를 통한 전처리 (+ agg, transform, filter... )](https://github.com/yahwang/Data-Processing-Note/tree/master/preprocessing/group_preprocess.ipynb)
    - [문자열(object) 전처리](https://github.com/yahwang/Data-Processing-Note/tree/master/preprocessing/object_preprocess.ipynb)
    - 시계열(datetime) 전처리
      - [시계열 기본 타입과 함수 (datetime, timedelta, pd.date_range, ...)](https://github.com/yahwang/Data-Processing-Note/tree/master/preprocessing/time_default.ipynb)
      - [시계열 데이터 프레임 활용 ( + shift)](https://github.com/yahwang/Data-Processing-Note/tree/master/preprocessing/time_preprocess.ipynb)
  - [Query - 조건(row, 그룹 단위)으로 데이터 검색 (+ query, filter)](https://github.com/yahwang/Data-Processing-Note/tree/master/query.ipynb)
  - [pivot_table - 두 개의 그룹 기준(Index와 Column)으로 계산 (+ crosstab)](https://github.com/yahwang/Data-Processing-Note/tree/master/pivottable&crosstab.ipynb)  

- Tips
  - [Make your Pandas apply functions faster using Parallel Processing](https://towardsdatascience.com/make-your-own-super-pandas-using-multiproc-1c04f41944a1)

- 시각화
  - [명목(범주형) 변수 Count 시각화](https://github.com/yahwang/Data-Processing-Note/tree/master/visualization/count_graph.ipynb)
  - [Boxplot](https://github.com/yahwang/Data-Processing-Note/tree/master/visualization/boxplot.ipynb)
- 모델링
  - [One-Hot-Encoding & dummy variable](https://github.com/yahwang/Data-Processing-Note/tree/master/one_hot&dummy.ipynb)
  - Categorical -> Numerical : binning(bucketing) 추가 예정
