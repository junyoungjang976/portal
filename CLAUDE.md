# Portal - Claude 작업 지침

## 프로젝트 개요
부성티케이 업무 포털 (정적 HTML/CSS)

## 작업 방식

### 필수 절차
1. 어떤 파일을 수정할지 먼저 목록으로 보여주고 승인 받기
2. 변경 범위를 최소화 - 요청한 기능만 수정
3. 수정 후 "이것만 바꿨고, 다른 건 안 건드렸다" 확인 메시지 출력

### 금지 사항
- 승인 없이 파일 수정 금지
- "이왕 하는 김에" 식의 추가 수정 금지
- 코드 정리/리팩토링 임의 수행 금지

### 배포/커밋 규칙
- 배포, push, commit은 내가 "작업 끝났다" 또는 "수정 완료"라고 말할 때 물어보고 진행
- 그 전까지는 브라우저에서 직접 확인

## 기술 스택
- **구조**: 정적 HTML/CSS
- **폰트**: Noto Sans KR (Google Fonts)
- **배포**: GitHub Pages 또는 정적 호스팅

## 프로젝트 구조
```
portal/
├── index.html    # 메인 포털 페이지
├── images/       # 로고 및 이미지 파일
│   ├── busung-logo.png
│   └── infrakitchen-logo-kr.png
└── .gitignore
```

## 연결된 시스템
- **ASMS**: A/S 관리 시스템 (asms-two.vercel.app)
- **Sales Pipeline**: 영업 대시보드 (sales-pipeline-sandy.vercel.app)
- **Field Check**: 현장 진단 (field-check.vercel.app)
- **Order Tracker**: 발주 추적 (order-tracker-iota.vercel.app)
- **HVAC Mentor**: AI 냉동공조 멘토 (hvac-mentor.vercel.app)
- **Equipment Manager**: 장비 관리 (equipment-manager-app.vercel.app)

## 로컬 개발
```bash
# 정적 파일이므로 브라우저에서 직접 열거나
# Live Server 등 사용
npx serve .
```

## 수정 시 주의사항
- 단순 HTML/CSS 파일이므로 직접 수정
- 빌드 과정 없음
