# ✅ To-Do 리스트

> 작성일: 2026년 10월 26일

> 이 README는 실습을 완성한 뒤, 배포 직전 단계에서 작성합니다. 자세한 실습 절차는 [guide.md](./guide.md)를 참고하세요.

## 소개

Tailwind CSS CDN과 Vanilla JavaScript로 만든 브라우저 기반 투두리스트입니다. 할 일 추가·수정·삭제, 시작·마감 일시 관리, 완료 상태 관리, 오늘/완료 필터, 정렬 및 진행률 확인을 지원합니다. 데이터는 브라우저의 `localStorage`에 저장됩니다.

## 어떻게 만들었나요

PRD를 기준으로 Tailwind CSS Play CDN을 사용해 반응형 화면을 구성하고, 별도의 JavaScript 프레임워크 없이 상태와 동작을 구현했습니다.

## Bootstrap vs Tailwind

이 브랜치는 Tailwind CSS 버전입니다. Bootstrap 버전과 화면 및 HTML 유틸리티 클래스 구성을 비교할 때 이 섹션을 작성하세요.

## 실행 방법

`index.html`을 브라우저에서 열어 실행합니다. Tailwind CSS Play CDN을 불러오기 위해 인터넷 연결이 필요합니다. 할 일은 현재 브라우저의 `localStorage`에 저장됩니다. Play CDN은 개발·학습 용도이며, 실제 운영 배포에는 빌드된 CSS 사용을 권장합니다.

GitHub Pages에 배포할 때는 저장소 설정의 Pages에서 배포 브랜치와 폴더를 선택하세요.

## 커스터마이징한 부분

모바일에서 탭을 가로로 스크롤할 수 있도록 했으며, 입력 글자 수와 필터별 항목 수를 표시합니다. 저장소 오류와 잘못된 저장 데이터는 사용자에게 안내합니다.
