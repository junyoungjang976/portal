# Portal (부성티케이 업무 포털)

## 개요
부성티케이의 각 업무 시스템으로 연결하는 메인 포털 페이지입니다.

## 기술 스택
- **구조**: 정적 HTML/CSS
- **폰트**: Noto Sans KR (Google Fonts)
- **배포**: GitHub Pages 또는 정적 호스팅

## 프로젝트 구조
```
portal/
├── index.html    # 메인 포털 페이지
├── images/       # 로고 및 이미지 파일
└── .gitignore
```

## 주요 기능
- 부성티케이 브랜드 로고 표시
- 각 업무 시스템으로의 링크 제공
- 반응형 디자인

## 연결된 시스템
- asms (A/S 관리 시스템)
- sales-pipeline (영업 파이프라인)
- field-check (현장 진단)
- order-tracker (발주 추적)
- hvac-mentor (HVAC 진단)
- equipment-manager (장비 관리)

## 로컬 개발
```bash
# 정적 파일이므로 브라우저에서 직접 열거나
# Live Server 등 사용
npx serve .
```

## 수정 시 주의사항
- 단순 HTML/CSS 파일이므로 직접 수정
- 빌드 과정 없음
