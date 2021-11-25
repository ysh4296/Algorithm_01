# Matrix factorization

### 1. 배경  
방탈출 카페가 성행함에 따라 영업을 돕는 여러가지 부가서비스가 생겨났다.
그중 우리가 주목한 부분은 방탈출 카페 추천 서비스이다.
방탈출 카페를 이용하는 고객들의 만족도는 난이도, 분위기, 활동성등 여러가지 요인에 의해 영향을 받을 수 있다.
따라서 단순히 전체적인 평가의 평균이 추천의 기준이 될 수 없기 때문에 유저개개인을 위한 추천기능이 필요하다.
  
### 2. 목표
  - 방탈출 카페끼리 비교를 좀더 명확한 방식으로 할 수 있다.
      
  - 기본적인 만족도 예상 및 탈출 성공,실패를 동시에 제공하여 합리적인 선택을 가능하게 한다.
  
  - 취향에 맞춘 방탈출 카페 추천을 통해 **유저**의 방탈출 이용의 만족도를 높인다.

### 3. 구현방법
  - [**전국방탈출**](https://www.roomescape.co.kr/theme/detail.php?theme=578) 리뷰를 통한 서울 지역 방탈출 데이터 분석
  - Matrix factorization을 통한 추천 최적화
  - Latent Factor Collaborate Filtering을 이용한 추천 시스템 알고리즘 구축
  - Django 및 파이썬 + html을 통한 추천 사이트 구축

### 4. 구현
  - [**탈출 성공 가능성 학습**](https://github.com/ysh4296/Machine_Running_Tutorials/blob/main/MatrixFactorization/Escape_recommand.ipynb)

  - [**유저 체감 난이도 학습**](https://github.com/ysh4296/Machine_Running_Tutorials/blob/main/MatrixFactorization/difficulty_recommand.ipynb)
