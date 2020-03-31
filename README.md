# Data-Processing-Note (with Pandas)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yahwang/Data-Processing-With-Pandas-Note/master/?urlpath=lab)

## 기본 사용법

- [데이터 로딩](data_load.ipynb) 

- [데이터 확인](data_check.ipynb)

- [데이터 타입 정보+변환](data_type.ipynb)

  - [Numeric 데이터 타입 최적화](optimize_numeric.ipynb)

- [컬럼 다루기 (추가, 삭제, ...)](treat_column.ipynb)

- [데이터 Slicing ( loc, at, xs )](data_slicing.ipynb)  

- [데이터 Filtering ( Query ) ]( query.ipynb)

- [데이터 정렬 (순위)]( sort_data.ipynb)

- [데이터 합치기 concat & merge]( concat_and_merge.ipynb)

- [일반적인 함수를 통한 전처리 ( apply, map, ... )](processing/general_preprocess.ipynb)

- [groupby 함수를 통한 전처리 (+ WINDOW FUNCTION 기능 )]( processing/group_preprocess.ipynb)

- [pivot_table - 두 개의 그룹 기준(Index와 Column)으로 계산 (+ crosstab)]( pivottable&crosstab.ipynb)

## 데이터 처리

### 코드 최적화

- [최적화 Tip 간단 정리](optimization/tip_summary.ipynb)

- [단순 연산 처리 최적화](optimization/simple_calculus.ipynb)

- [유용한 numpy 함수 정리](optimization/numpy_functions.ipynb)

### 일반 데이터

- [데이터 중복 다루기 Unique & duplicated]( processing/unique&duplicated.ipynb)

- [데이터 결측치(NA) 값 처리 방법]( processing/null_value.ipynb)

- [데이터 mapping ( 치환 ) 방법]( processing/data_mapping.ipynb)

- [두 데이터프레임의 차이 비교 ( 데이터 검증에 활용 )](processing/merge_diff.ipynb)  

### 문자열 데이터

- [문자열(object) 전처리]( processing/object_preprocess.ipynb)

- [정규식(Regular Expression) 처리]( processing/regular_expression.ipynb)

### 시계열 데이터

- [시계열 기본 타입과 함수 (datetime, timedelta, pd.date_range, ...)]( preprocessing/time_default.ipynb)

- [시계열 데이터 컬럼 활용 ( + shift)]( processing/time_preprocess.ipynb)

- [누락된 날짜 확인하는 방법(추가하는 법) - 날짜가 중복되지 않는 경우]( processing/find_nodate.ipynb)

### 시각화

- [명목(범주형) 변수 Count 시각화]( visualization/count_graph.ipynb)

- [Boxplot]( visualization/boxplot.ipynb)

### 모델 데이터 만들기

- [One-Hot-Encoding & dummy variable]( one_hot&dummy.ipynb)
  - Categorical -> Numerical : binning(bucketing) 추가 예정
