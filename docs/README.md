
# 기능 구현 목록
g
## 💻 1. 컴퓨터 난수 생성 기능 
### 기능 순서
    - 1~9의 숫자중 하나의 숫자 생성
    - 기존에 생성한 숫자를 제외한 수 생성 x 2

## 🧑‍💻 2. 사용자 난수 입력 기능
### 기능 순서
    - 숫자 입력 
    - 숫자가 1~9의 숫자만 있는지 체크
    - 숫자의 중복 체크
    - 3자리의 숫자인지 체크

## 💯 3. 생성한 숫자와 입력받은 숫자 비교 기능
### 기능 순서
    - 생성한 숫자에 입력받은 숫자가 있는지 체크
    - 동일한 숫자가 존재하면 해당 인덱스가 같은지 체크
    - 해당 데이터로 BALL과 STRIKE기록

## ♾️ 4. 게임 종료 및 재시작 기능
### 기능 순서
    - STRIKE가 3개면 다음 문구 출력
       "3개의 숫자를 모두 맞히셨습니다! 게임 종료"
       "게임을 새로 시작하려면 1, 종료하려면 2를 입력하세요."
    - 사용자의 입력이 1이면 컴퓨터의 난수 재생성 
    - 사용자의 입력이 2이면 프로그램 종료

## ⛔ 5. 예외 처리 기능
    - 사용자의 난수가 조건을 만족하지 않으면 "[ERROE]" 를 throw문을 사용해 예외 발생 후 프로그램 종료


  

