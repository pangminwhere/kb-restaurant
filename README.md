# kb-restaurant

## 요구사항

- ID와 비밀번호로 로그인하여 사용자를 식별한다.
- 매일 추천하는 메뉴를 메인, 에피타이저, 음료 별로 두가지씩 추천한다.
- 사용자는 주문할 메뉴의 번호와 수량을 각각 여러개 입력할 수 있어야 한다.
- 사용자가 주문을 완료하면 영수증과 결제 금액을 출력해야 한다.
- 사용자가 여태까지 총 주문한 내역과 가격을 조회할 수 있어야 한다.

## 메뉴

```
<메인>
티본스테이크(55,000), 바비큐립(54,000), 해산물파스타(35,000), 크리스마스파스타(25,000)

<사이드>
양송이수프(6,000), 타파스(5,500), 시저샐러드(8,000), 초코케이크(15,000), 아이스크림(5,000)

<음료>
제로콜라(3,000), 레드와인(60,000), 샴페인(25,000), 화이트와인(80,000)
```

## 로그인 입출력 형식

```
로그인을 진행해주세요.

사용자 ID:
dh1010a

사용자 PW:
1234

<< 인증에 성공하였습니다 >>

// === 실패 시 ==//

<< !!!!!인증에 실패하였습니다. 다시 시도하세요 >>

로그인을 진행해주세요.

....
```

## 주문 입출력 형식

```
안녕하세요! KB 식당입니다.
오늘의 추천메뉴를 알려드릴게요!

<메인 메뉴>
해산물파스타, 레드와인

<사이드>
양송이수프

<음료>
레드와인

주문하실 메뉴를 메뉴와 개수를 알려 주세요. (e.g. 해산물파스타-2,레드와인-1,초코케이크-1)
타파스-1,제로콜라-1

<주문 메뉴>
타파스 1개
제로콜라 1개

<총 결제 금액>
8,500원
```
