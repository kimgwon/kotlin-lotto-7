# kotlin-lotto-precourse
## 입력
`camp.nextstep.edu.missionutils.Console`의 `readLine()을 활용
- [ ] `구입금액을 입력해 주세요.` 로또 구입 금액을 입력받는다.
- [ ] `당첨 번호를 입력해 주세요.` 당첨 번호를 입력 받는다. 쉼표를 기준으로 구분한다.
- [ ] `보너스 번호를 입력해 주세요.` 보너스 번호를 입력받는다.

## Lotto
- 변수1 `번호 리스트`
- 변수2 `당첨 금액`
- 함수1 번호 정렬해서 번호 리스트에 저장
- 함수2 번호가 몇 개 맞는지 체크해서 저장

## LottoController
- [ ] 로또 발매 (1,000원당 1장). `camp.nextstep.edu.missionutils.Randoms`의 `pickUniqueNumbersInRange()`를 활용.
- [ ] 수익률 계산

## LottoConstant
- 1등: 6개 번호 일치 / 2,000,000,000원
- 2등: 5개 번호 + 보너스 번호 일치 / 30,000,000원
- 3등: 5개 번호 일치 / 1,500,000원
- 4등: 4개 번호 일치 / 50,000원
- 5등: 3개 번호 일치 / 5,000원

## 출력
- [ ] `$num개를 구매했습니다.` 발행한 로또 수량 및 번호를 출력한다. 로또 번호는 오름차순으로 정렬하여 보여준다.
- [ ] `당첨 통계` 당첨 내역을 출력한다.
- [ ] `총 수익률 $profitRate` 수익률을 출력한다.

## 예외
- [ ] 구입 금액은 숫자만 가능하다.
- [ ] 로또 구입 금액이 1,000원 단위로 나누어 떨어지지 않는 경우 예외 처리한다.
- [ ] 당첨 번호는 숫자여야 한다. 
- [ ] 당첨 번호는 6개여야 한다.
- [ ] 보너스 번호는 숫자여야 한다.
- [ ] 보너스 번호는 1개여야 한다.
- [ ] 로또 번호는 1~45 사이의 숫자여야 한다.