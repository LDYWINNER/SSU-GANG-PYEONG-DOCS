# SSU-GANG-PYEONG-DOCS

## Code repo
- Backend: https://github.com/LDYWINNER/SSU-GANG-PYEONG-BACKEND
- Frontend: https://github.com/LDYWINNER/SSU-GANG-PYEONG-APP
- Data processing: https://github.com/LDYWINNER/SUNYTIME_CourseList_to_MongoDB

## 프로젝트 objective
- mvp로 출시한 웹 서비스인 쑤니타임 유저들을 상대로 한 설문조사 결과(필요한 신기능, 불편했던 점, 쑤니타임의 강약점 등)를 토대로 유저들의 니즈에 더 맞는 모바일 앱 서비스로 개편함
- SUNYTIME docs: https://github.com/LDYWINNER/SUNYTIME-DOCS 

## 프로젝트 디테일
- 쑤강평은 2023년 4월에 출시한 쑤니타임에서 디벨롭시켜서 기존 팀원들과 함께 개발한 iOS & Android 모바일 앱서비스
- 기본 서비스 로직은 쑤니타임을 따르지만 유저 피드백을 반영하여, 수업별 게시판을 개발하여 같은 수업을 듣는 학생들간의 소통을 돕고, 수업 시간표를 직관적으로 볼 수 있는 UI 추가, 수업 시간표와 연동되는 투두리스트 기능을 개발하여 다른 대학생 커뮤니티 앱들과 차별화시킴
- iOS 버전: 2024년 3월에 iOS 앱스토어에 출시하여 현재까지 운영중
- Android 버전: 구글 플레이 스토어에 출시하기 전 배타 테스터들과 테스팅 진행중

## 진행상황
- 2024년 5월초 기준 150명이 넘는 유저와 500개가 넘는 수강평을 수집하는데에 성공함

## 기술 스택
### Backend:
- express(nodejs)
- mongodb atlas
- jsonwebtoken
- nodemailer
### Frontend:
- React Native
- swr
- zustand
- react-hook-form
- react-navigation
- shopify restyle
- date-fns & moment
### Data processing:
- pymongo
- tabula
- pandas
