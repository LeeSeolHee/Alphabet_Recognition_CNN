
# Alphabet_Recognition_CNN

<br><br>
### 주요 설명
---
1. **데이터 수집**
    + [Kaggle Alphabet Dataset](https://www.kaggle.com/datasets/sachinpatel21/az-handwritten-alphabets-in-csv-format)<br>

2. **데이터 정보**
    + 구조
    ```
    my_frame.shape
    
    (372450, 785)
    ```
    + 정보
    ```
    my_frame.info()
    
    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 372450 entries, 0 to 372449
    Columns: 785 entries, 0 to 0.648
    dtypes: float32(785)
    memory usage: 1.1 GB
    ```
    + null값 확인
    ```
    my_frame.isnull().sum()
    
    0        0
    0.1      0
    0.2      0
    0.3      0
    0.4      0
            ..
    0.644    0
    0.645    0
    0.646    0
    0.647    0
    0.648    0
    Length: 785, dtype: int64
    ```

   


