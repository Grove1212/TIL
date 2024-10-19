# Class
## 생성자
- 생성자 만드는 법 : 주, 보조 생성자, 
  - init 역할 : 클래스가 초기화될 때 실행됨


# Data class
- 특징
  - 상속 불가
  - val 또는 var로 선언
  - abstract, open, sealed, inner 붙일 수 없음
  - 1개 이상의 프로퍼티를 가지고 있음
  - equals(), toString(), hashCode()에 오버라이드 구현 가능
  - copy 또한 가능
  - 데이터 분해와 대입 가능
