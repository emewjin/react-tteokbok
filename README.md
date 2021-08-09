# Team tteokbok.com

> ## 😎 Our Website : http://tteokbok.com/
> 😢 지금은 서버가 켜져있지 않아 데이터를 받을 수 없어요. 이용에 불편을 드려 죄송합니다.
>
> ## 📎 Route Path
>
> - / : 메인페이지
> - /detail/:id : 상세페이지
> - /project-start : 프로젝트 등록페이지
> - /profile : 마이페이지

## 💬 프로젝트 설명
창작자는 자신만의 아이디어를 프로젝트로 소개하고, 후원자는 관심있는 프로젝트를 검색/정렬/필터링 하여 펀딩할 수 있는 텀블벅 사이트를 모티브로 삼았습니다.
떡볶닷컴은 한국의 분식을 세계로 알리자는 뜻을 담아, 분식을 주제로 한 창의적인 프로젝트 펀딩 사이트입니다.

## 🎯 프로젝트 목적
- 리액트 함수형 컴포넌트, hooks를 이용하는 데 익숙해지기
- 스타일드 컴포넌트를 통해 css in js를 이용해보고 css/scss와 비교해보기
- 배포까지 진행해보기

[📎 프로젝트 후기](https://velog.io/@1703979/%ED%85%80%EB%B8%94%EB%B2%85-%ED%81%B4%EB%A1%A0-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%ED%9B%84%EA%B8%B0)

## 👫 팀원

- FE 3인: [노선경(PM)](https://velog.io/@celline1637), [송가람](https://velog.io/@sgr2134), [임유진](https://emewjin.github.io/)
- BE 2인: [이승무](https://goback.oopy.io/), [최준식](https://velog.io/@junsikchoi) ([BE Reop](https://github.com/wecode-bootcamp-korea/20-2nd-tteokbokcom-backend))

## 📅 프로젝트 기간

2021.05.23~2021.06.04

## 🔧 사용된 기술이예요

- FE : React Hooks, React Router, Styled-Component, Lodash
- BE : Django, Docker, MY SQL
- Common : KAKAO social login, AWS(EC2,RDS, S3), RESTful API

## 👩🏻‍🌾 제가 담당한 구현 사항이예요

**공통**
- context api를 이용한 state 관리. [(좀 더 상세한 내용은 📎 이 글을 참고해주세요)](https://emewjin.github.io/react/contextapi)
- 스타일드 컴포넌트의 변수 및 공통 세팅 사항 작성
- 모바일 중심의 반응형 디자인 구현
- AWS S3를 이용한 정적 웹 배포 + Github Action을 이용한 자동 배포

**[프로젝트 등록 view](https://github.com/emewjin/react-tteokbok/tree/master/src/pages/ProjectStart)**
- 두 개의 탭에 각각 다른 입력 폼을 그려내고 다양한 데이터를 입력받음
- 입력받은 데이터를 FormData로 감싸 서버로 POST
- 각 탭의 항목이 모두 작성되었는지 검사해 UI로 표현
- keyword 입력 항목에서의 유효성 검사 등을 진행

**[프로젝트 리스트 (메인 화면)](https://github.com/emewjin/react-tteokbok/tree/master/src/pages/Main)**
- 다중 filter, sorting 기능 구현
- filter, sorting, search 값에 맞는 쿼리스트링을 구성해 서버에 data 요청, 뷰에 그려냄
- PATCH http 메소드로 프로젝트에 대한 좋아요 기능 구현
- 메인, 마이페이지에서 공통으로 사용할 수 있는 [프로젝트 카드 컴포넌트](https://github.com/emewjin/react-tteokbok/tree/master/src/components/ProjectCard) 구현

## 🤝🏻 프로젝트 협업은 이렇게 진행됐어요
- 매일 짧고 굵게, Daily Scrum을 통해 현재의 blocker, 어제 한 일, 오늘 할 일을 있는 그대로 담백하게 공유
- 프로젝트 본격 시작 전, 모든 팀원과 함께 사용자의 이용 흐름에 맞춰 선택과 집중할 사이트 구성 요소 선정
- 매주 월요일에 진행되는 Sprint를 통해서 마감일정에 맞춰 남은 작업을 확인하고 일정 조율 및 피드백
- 팀원별 작업 현황, 백엔드와의 데이터 구조 소통을 위해 Trello를 활용

## 🚨 Reference
- 이 프로젝트는 텀블벅 사이트를 참조하여 학습목적으로 만들었습니다. 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 직접 찍거나 unsplash에서 공유받은 Free 이미지이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
- 이 프로젝트에서 사용한 로고, 커서 이미지는 직접 제작한 것으로 외부인이 사용할 수 없습니다.
