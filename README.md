#  GUYSHOUSE Project

[![guyshouse](https://images.velog.io/images/sae0428/post/681b036a-e7cb-4b90-bc34-0f72026aba47/%EB%82%A8%EC%9D%98%EC%A7%91.JPG)](https://youtu.be/F6Sg-UZp1NY)

## 🎇 팀명 : 남의집

> 취향 공유 커뮤니티 서비스 [남의집](https://naamezip.com/)을 모티브로 제작하게 된 남의집(GUYSHOUSE) 팀의 백엔드 레포지토리 입니다.
> 짧은 프로젝트 기간동안 개발에 집중해야 하므로 디자인/기획 부분만 클론했습니다.

## 📅 개발 기간 및 개발 인원

- 개발 기간 : 2021/12/13 ~ 2021/12/24
- 개발 인원 <br/>
 👨‍👧‍👦 **Front-End** 3명 : [김상훈](https://github.com/Ho0on), [김태영](https://github.com/Moro-yong), [황성재](https://github.com/seongjae0325
)<br/>
- [Front-end github 링크](https://github.com/wecode-bootcamp-korea/27-2nd-GuysHouse-frontend)<br/>
 👨‍👧‍👦 **Back-End** 3명 : [고민혁](https://github.com/MinhyukK0), [박세용](https://github.com/se-yong
), [유민혁](https://github.com/MinHyeouk
)<br/>
- [Back-end github 링크](https://github.com/wecode-bootcamp-korea/27-2nd-GuysHouse-backend)

## 🎬 프로젝트 구현 영상

[![Video Label](http://img.youtube.com/vi/F6Sg-UZp1NY/0.jpg)](https://www.youtube.com/watch?v=F6Sg-UZp1NY=0s)





## ⚙ 적용 기술
- **Front-End** : JavaScript(ES6), React.js, StyledComponent, HTML5/CSS3
- **Back-End** : Django(Pyhton 3.8), Myql5.7, AWS(EC2, S3, RDS), Bcrypt / JWT
- **Common** : Git, Github, Slack, Trello, Postman, Notion

## 🗜 [데이터베이스 Diagram(클릭 시 해당 링크로 이동합니다)](https://dbdiagram.io/d/61b6b6908c901501c0ecdb28)

## 💻 구현 기능
### BACKEND
#### 고민혁

> 호스트 프로그램 등록
- 호스트가 프로그램을 등록하는 API 작성 (AWS(EC2,S3)기술 사용)
- 호스트가 등록한 프로그램들을 조회하는 API 작성
- 호스트 정보 조회 API 작성

> 예약페이지
- 프로그램 예약 시 심사 질문을 보여주는 API 작성
- 프로그램 심사질문에 답변시 저장하는 API 작성

> 서버배포
- AWS(EC2, RDS)
- gunicorn


#### 박세용

> 메인페이지 API 구현

- 메인페이지에서 전체 프로그램들의 목록을 전달하는 로직을 구현하였습니다.
- 각 카테고리 마다 그에 맞는 조건을 할당하고 카테고리중복선택이 가능한 로직을 구현하였습니다.
- 카테고리가 선택되어있는 상태에서도 필터초기화를 통하여 카테고리가 초기화되고 전체 프로그램을 다시 반환하는 로직을 구현하였습니다.

> 프로그램 상세페이지 구현

- 상세페이지에서 알맞는 데이터를 프론트 단에 전달하는 로직을 구현하였습니다.

### 유민혁

> 소셜 로그인
- KakaoAPI를 통한 social login / signup을 구현했습니다.
- 우리 서비스에 필요로 하는 회원정보만을 kakao로부터 response받습니다.

> 호스트 등록하기
- 일반 유저가 호스트로 등록을 하면 host_token이 발행됩니다.
- 이를 통해 관리자페이지나 프로그램 등록페이지에 접근 할 수 있습니다.

## ❗ Reference
- 이 프로젝트는 [남의집](https://naamezip.com/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 모두는 copyright free 사이트들의 이미지들을 취합 및 canva 에서 직접 제작한 이미지들로 제작되었습니다.
