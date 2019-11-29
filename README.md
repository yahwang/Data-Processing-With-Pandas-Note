# Data-Processing-Note (with Pandas)

## 기본 사용법

- [데이터 확인](data_check.ipynb)

- [데이터 타입 정보+변환](data_type.ipynb)

- [Data Slicing ( loc, iloc, xs )](data_slicing.ipynb)  

- [조건(row, 그룹 단위)으로 데이터 검색 (+ query, filter 함수)]( query.ipynb)

- [추가 컬럼 만들기](add_column.ipynb)

- [데이터 합치기 concat & merge]( concat_and_merge.ipynb)


## 데이터 전처리

### 일반 데이터

- [데이터 중복 다루기 Unique & duplicated]( preprocessing/unique&duplicated.ipynb)

- [데이터 결측치(NA) 값 처리 방법]( preprocessing/null_value.ipynb)

- [일반적인 함수를 통한 전처리 (+ apply, map, ... )](preprocessing/general_preprocess.ipynb)

- [groupby 함수를 통한 전처리 (+ agg, transform, filter... )]( preprocessing/group_preprocess.ipynb)

- [문자열(object) 전처리]( preprocessing/object_preprocess.ipynb)

- [pivot_table - 두 개의 그룹 기준(Index와 Column)으로 계산 (+ crosstab)]( pivottable&crosstab.ipynb)  

### 시계열 데이터

- [시계열 기본 타입과 함수 (datetime, timedelta, pd.date_range, ...)]( preprocessing/time_default.ipynb)

- [시계열 데이터 프레임 활용 ( + shift)]( preprocessing/time_preprocess.ipynb)

- [누락된 날짜 확인하는 방법(추가하는 법) - 날짜가 중복되지 않는 경우]( find_nodate.ipynb)

### 시각화

- [명목(범주형) 변수 Count 시각화]( visualization/count_graph.ipynb)

- [Boxplot]( visualization/boxplot.ipynb)

### 모델 데이터 만들기

- [One-Hot-Encoding & dummy variable]( one_hot&dummy.ipynb)
  - Categorical -> Numerical : binning(bucketing) 추가 예정
