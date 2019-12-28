# 아동 발달 장애 분류 알고리즘
두브레인의 Drag Data를 활용하여 아동의 발달 장애 여부를 분류하는 알고리즘 및 코드</b>

## 실행 순서
Json_Parser : JSON파일을 DB서버에 적재하는 과정<br>
Normal Data Generator : DB에서 정상 발달 아동들의 데이터를 추출 후, 전처리 및 파생변수 생성<br>
Abnormal Data Generator : DB에서 발달 장애 아동들의 데이터를 추출 후, 전처리 및 파생변수 생성<br>
Normal Abnormal Classification : 두 아동 그룹의 데이터로 Deep learning 진행 후 결과 확인<br>
