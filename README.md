# java-racingcar-precourse

# 구현할 기능 목록

## 1. 입력 기능
### 1.1 자동차 이름 입력
- [ ] 쉼표(,)로 구분된 자동차 이름 입력 받기
- [ ] 자동차 이름 유효성 검증
    - [ ] 이름 길이 5자 이하 검증
    - [ ] 빈 값 검증
    - [ ] 공백 값 검증

### 1.2 시도 횟수 입력
- [ ] 시도 횟수 입력 받기
- [ ] 시도 횟수 유효성 검증
    - [ ] 숫자값 검증
    - [ ] 양수 검증

## 2. 자동차 경주 기능
### 2.1 자동차 생성
- [ ] 입력받은 이름으로 자동차 객체 생성
- [ ] 자동차 초기 위치 설정

### 2.2 자동차 이동
- [ ] 무작위 값 생성 (0-9)
- [ ] 전진 조건 확인 (값 >= 4)
- [ ] 자동차 위치 업데이트

## 3. 출력 기능
### 3.1 실행 결과 출력
- [ ] 각 차수별 실행 결과 출력
- [ ] 자동차별 위치 표시 (-로 표현)
- [ ] 이름과 위치 정보 함께 출력

### 3.2 우승자 출력
- [ ] 최종 우승자 선정
    - [ ] 가장 멀리 이동한 거리 계산
    - [ ] 동일 거리의 자동차 확인
- [ ] 우승자 이름 출력 (쉼표로 구분)

## 4. 예외 처리
### 4.1 입력값 예외 처리
- [ ] 자동차 이름 예외 처리
    - [ ] 이름 길이 초과 예외
    - [ ] 빈 값 예외
    - [ ] 공백 값 예외
- [ ] 시도 횟수 예외 처리
    - [ ] 숫자가 아닌 값 예외
    - [ ] 0 또는 음수 예외

## 5. 테스트
### 5.1 단위 테스트
- [ ] 자동차 생성 테스트
- [ ] 자동차 이동 테스트
- [ ] 이름 유효성 검증 테스트
- [ ] 시도 횟수 유효성 검증 테스트

### 5.2 통합 테스트
- [ ] 전체 게임 진행 테스트
- [ ] 우승자 선정 테스트
- [ ] 예외 상황 테스트
