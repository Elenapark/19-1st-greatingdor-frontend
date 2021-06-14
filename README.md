# 그리팅몰 클론 프로젝트 소개

---

## 프로젝트 소개

- 팀명: Greatingdor
- 설명: 건강식 식단 및 식자재 판매 플랫폼인 그리팅몰(greating mall) 사이트 클론 프로젝트
- 그리팅몰 original website (https://www.greating.co.kr)

![](https://images.velog.io/images/elena_park/post/09c32465-1e57-4c15-9ce9-6af103b0010b/%EA%B7%B8%EB%A6%AC%ED%8C%85%EB%AA%B0%20original%20main.png)

## 프로젝트 전체 구현 영상 

https://www.youtube.com/watch?v=N_5u4KgBaC0

## 개발 기간

- 21.04.12 ~ 21.04.23 (11일)

## 개발 인원

- 프론트엔드: 박성은 박세리 이명진
- 백엔드: 이서진 이윤형 함경재

## 프론트엔드 기술스택

- JavaScript(ES6)
- React.JS
- React-Router
- Sass
- HTML, CSS

## 협업도구

- Git, Github : 버전관리 및 협업
- Trello : 일정 관리
- Slack : 비대면 소통

## 프론트엔드 주요 구현 사항

1. 로그인 페이지 (박세리)

- 로그인 기능 : 서버로부터 회원가입이 된 회원 정보를 받아온 뒤 로그인 구현
  ![](https://images.velog.io/images/elena_park/post/25ce9678-de9f-4871-afa1-06fb07373b60/%EB%A1%9C%EA%B7%B8%EC%9D%B8.gif)

2. 회원가입 페이지 (박세리)

- 회원가입 기능 : fetch에 post로 회원 정보를 서버에 보내고 서버에 성공적으로 전달이 되는 경우 success라는 message가 뜨며 로그인 페이지로 이동
  ![회원가입](https://user-images.githubusercontent.com/60565155/116185430-91cea180-a75c-11eb-885d-b4c8fad2a98c.gif)

3. 메인 상품 리스트 페이지 (이명진)

- 광고 배너 제작 : 광고 배너 코드 구현
- 제품 카드 제작 : 상세페이지로의 연결 및 제품 간략 정보를 담은 제품 카드 구현
- 제품 카테고리 필터 기능 : 제품 종류를 토대로 필터가 되는 기능 구현
- 제품 페이지네이션 기능 : 제품 수량이 많을 경우 페이지 넘버를 통해 이전, 다음 페이지를 탐색할 수 있는 페이지네이션 기능 구현
  ![](https://images.velog.io/images/elena_park/post/3ebcabf7-59e4-49ae-8bb1-26a378f43277/%EA%B4%91%EA%B3%A0%EB%B0%B0%EB%84%88.gif)
  ![카테고리_Trim](https://user-images.githubusercontent.com/60565155/116186258-3b626280-a75e-11eb-8559-b1dda404d20b.gif)
  ![페이지네이션](https://user-images.githubusercontent.com/60565155/116187048-c132dd80-a75f-11eb-9792-9ad0310a40ad.gif)

4. 공용 컴포넌트 구현 (박성은)

- Navbar : 카테고리 및 검색창 드롭다운 구현, 검색창 아이템 다중선택 구현 (검색 기능 추가 구현 예정)
- Footer : 외부 링크 연결

![네브바](https://user-images.githubusercontent.com/60565155/116176075-75c30400-a74c-11eb-9740-53ed8f09f0ee.gif)

5. 상품 상세 페이지 (박성은)

- 동적 라우팅 이용하여 상품 리스트에서 클릭한 아이템에 해당하는 data 호출하여 상세페이지 구현
- 장바구니, 구매하기 클릭 시 옵션 모달창 생성 및 수량 증감 구현
- 상세페이지 하단 메뉴 탭 구현 및 각 탭에 해당하는 data 출력 (상품정보,교환/반품 탭에서는 우선 클릭 제품의 id 번호를 반영한 이미지를 임시로 사용하였음. 추후 이미지 변경 적용 예정)
- 상품후기, 상품문의 리스트 드롭다운 구현 (페이지네이션 추가 구현 예정)
![상세](https://user-images.githubusercontent.com/60565155/116176110-87a4a700-a74c-11eb-925c-276c5c8b7ebf.gif)

## 각 팀원 블로그

- 박성은 : https://velog.io/@elena_park
- 박세리 : https://velog.io/@moripark32
- 이명진 : https://velog.io/@ljo094822

## References

이 프로젝트는 그리팅몰 사이트를 참고하여 학습 목적으로 진행된 프로젝트입니다.
