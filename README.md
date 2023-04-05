# Introduction-to-machine-learning-data-preprocessing

## 데이터분석에서 중요한것

### 1. 데이터 구조(타입) 확인할것

### 2. 변수가 어떤값으로 나올지 모르면 print 해본다.

### 3. 데이터 분석할때 어떤조건을 정렬되고 나서 또 조건을 걸어서 보고자 할때: 
       변수[] 등 판다스_인덱스, 판다스_데이터 프레임, 판다스_시리즈, 넘파이_어레이, 리스트, 튜플등 꼭 확인할것

### 4. 해당 변수.메서드를 걸었을때 데이터구조와 결과값을 예상해야 한다.
.columns
.tolist()
.isnull()

### 5. 해당 열에 데이터 타입이 오브젝트인데 안에 숫자형하고 같이 있는 경우도 고려해야 한다.

### 6. 데이터 전처리 조건 처리 방식은 실행 --> 저장 -> 실행 -> 저장으로 누적되면서 전처리하는 것이다.

### 7. 헷갈리는거 axis = 0 , 1

concat에서 axis = 0 수직으로 결합 가로(행)을 위아래로 합치는거 열의 수가 같아야 한다. 
           axis = 1 수평으로 결합 세로(열)을 옆으로 합치는거 행의 수가 같아야 한다. 

drop axis = 0  행
     axis = 1  열
     
isnull()  axis = 0  열
          axis = 1  행
     

     
