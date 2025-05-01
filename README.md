📱 프로젝트 소개
이 프로젝트는 플러터를 사용하여 개발된 모바일 애플리케이션입니다.

🛠️ 개발 환경
- Flutter: 3.x.x
- Dart: 3.x.x
- IDE: Android Studio / VS Code

🏗️ 프로젝트 구조

lib/

├── main.dart

├── models/

├── screens/

├── widgets/

├── services/

└── utils/

🚀 시작하기
1. 플러터 환경 설정
bashflutter pub get

2. 앱 실행
bashflutter run

🔄 Git 컨벤션
브랜치 전략
- main: 안정적인 코드
- dev: 개발 중인 코드
- TB-{이슈번호}: 특정 이슈에 대한 개발 브랜치 (예: TB-01)

**커밋 메시지 컨벤션**
커밋 메시지는 다음 형식을 따릅니다:
{이슈번호} {태그}: {내용}
예시:
TB-01 Feat: add new feature

**태그 종류**
- Feat: 새로운 기능을 추가할 경우
- Fix: 버그를 고친 경우
- Design: CSS 등 사용자 UI 디자인 변경
- Style: 코드 포맷 변경, 세미 콜론 누락, 코드 수정이 없는 경우
- Refactor: 프로덕션 코드 리팩토링
- Comment: 필요한 주석 추가 및 변경
- Docs: 문서를 수정한 경우
- Test: 테스트 추가, 테스트 리팩토링(프로덕션 코드 변경 X)
- Rename: 파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우
- Remove: 파일을 삭제하는 작업만 수행한 경우

##📝 PR(Pull Request) 작성 가이드
**PR 제목 형식**
[{이슈번호}] {태그}: {간략한 설명}
**PR 본문 템플릿**
markdown## 📝 PR 설명 (PR Description)

### 🔹 요약 설명 (Summary)
[변경 사항에 대한 간략한 설명]

### 🔎 세부 내용 (Details)
[구현 내용에 대한 자세한 설명]

### 🔄 변경 유형 (Type(s) of Changes)
- [ ] 🐛 Bug fix (버그 수정)
- [ ] ✨ New feature (새로운 기능 추가)
- [ ] 🛠️ Enhancement (기능 개선/최적화/리팩토링)
- [ ] 📖 Documentation (문서 추가/수정)
- [ ] 🛰️ Other (please specify): [기타 변경 사항]

### 📸 스크린샷 (Screenshots) [선택사항]
[UI 변경이 있는 경우 변경 전/후 스크린샷]

### 📋 테스트 체크리스트 (Test Checklist)
- [ ] 로컬에서 테스트 완료
- [ ] 유닛 테스트 통과
- [ ] 코드 리뷰 요청
⚙️ 배포 프로세스

dev 브랜치에서 개발 완료
PR 검토 및 승인
main 브랜치로 병합
릴리스 태그 생성

📚 추가 문서

API 문서
위젯 가이드
상태 관리

👥 기여자

개발자 이름 : 봄IN

📄 라이선스
이 프로젝트는 MIT 라이선스를 따릅니다.
