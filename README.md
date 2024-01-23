
# Alphabet_Recognition_CNN

<br><br>
### 주요 설명
---
1. **데이터 수집**
    + [Kaggle Alphabet Dataset](https://www.kaggle.com/datasets/sachinpatel21/az-handwritten-alphabets-in-csv-format)<br>

2. **데이터 정보**
    + 크롤링 때 장르 부분에 추출 이상 발견
    ```
    my_frame.shape
    ```
    + 장르 컬럼 값 조건 변경
    ```
    my_frame.info()
    ```
    + 장르 컬럼 값 공백 제거
    ```
    my_frame.isnull().sum()
    ```
    0        0<br>
    0.1      0<br>
    0.2      0<br>
    0.3      0<br>
    0.4      0<br>
            ..<br>
    0.644    0<br>
    0.645    0<br>
    0.646    0<br>
    0.647    0<br>
    0.648    0<br>
    Length: 785, dtype: int64
3. **시각화 처리**
    + 한글 폰트 설정 : from matplotlib import font_manager, rc
    + 사용한 시각화 방법 : bar, pie, word cloud<br><br>
    [연도별 장르 변화, 2005 vs 2022 장르 비교](https://github.com/LeeSeolHee/Melon_Chart_Analysis/blob/master/genre_comparison.py)<br>
    [연도별 인기 가수 변화](https://github.com/LeeSeolHee/Melon_Chart_Analysis/blob/master/Singer_frequency.py)<br><br>
4. **포트폴리오 자료**<br>
    + [빅데이터 처리 프로젝트 PPT](https://github.com/LeeSeolHee/Melon_Chart_Analysis/blob/master/프로젝트ppt.pdf)
   


