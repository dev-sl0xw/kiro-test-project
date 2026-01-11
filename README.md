# 테크이노베이션 기업 소개 웹사이트

3계층 아키텍처 개념을 적용한 확장 가능한 기업 소개 웹사이트입니다.

## 프로젝트 개요

이 프로젝트는 현대적인 웹 아키텍처 패턴을 적용하여 구축된 기업 소개 웹사이트입니다. 단일 HTML 파일로 시작하여 점진적으로 확장 가능한 구조로 설계되었습니다.

## 아키텍처 설계

### 3계층 구조 적용
- **프레젠테이션 계층**: 사용자 인터페이스 (헤더, 네비게이션, 스타일링)
- **애플리케이션 계층**: 비즈니스 로직 (콘텐츠 구조, 상호작용)
- **데이터 계층**: 정보 저장 (연락처, 회사 정보, 서비스 데이터)

### 주요 특징
- **반응형 디자인**: 모바일부터 데스크톱까지 최적화
- **모던 CSS**: Flexbox, Grid, 그라데이션, 애니메이션 활용
- **시맨틱 HTML**: 접근성과 SEO 최적화
- **확장 가능한 구조**: 향후 기능 추가를 위한 모듈화된 설계

## 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: 모던 스타일링 (Grid, Flexbox, Transitions)
- **JavaScript**: 기본 상호작용 (스무스 스크롤)
- **한국어 지원**: UTF-8 인코딩, 한글 폰트 최적화

## 프로젝트 구조

```
kiro-test-project/
├── .git/                 # Git 버전 관리
├── .kiro/                # Kiro 설정 및 가이드
│   └── steering/         # 프로젝트 가이드라인
├── README.md             # 프로젝트 문서
└── index.html            # 메인 웹페이지
```

## 실행 방법

### 로컬 개발 서버
```bash
# Python 사용
python -m http.server 8000

# Node.js 사용
npx serve .

# 또는 브라우저에서 직접 열기
open index.html
```

### 브라우저 접속
- 로컬: `http://localhost:8000`
- 파일: `file:///path/to/index.html`

## 향후 확장 계획

### Phase 1: 정적 사이트 최적화
- [ ] SEO 메타태그 추가
- [ ] 이미지 최적화
- [ ] 성능 개선

### Phase 2: 동적 기능 추가
- [ ] 연락처 폼 구현
- [ ] 포트폴리오 갤러리
- [ ] 블로그 섹션

### Phase 3: 백엔드 통합
- [ ] CMS 연동 (WordPress/Headless CMS)
- [ ] 데이터베이스 연결
- [ ] API 개발

### Phase 4: 고급 기능
- [ ] 다국어 지원
- [ ] 관리자 대시보드
- [ ] 분석 도구 연동

## 보안 고려사항

- HTTPS 적용 필수
- 입력 데이터 검증
- XSS 방지
- CSRF 토큰 적용 (동적 기능 추가 시)

## 성능 최적화

- 이미지 lazy loading
- CSS/JS 압축
- CDN 활용
- 캐싱 전략

## 기여 방법

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 라이선스

MIT License - 자세한 내용은 LICENSE 파일을 참조하세요.

---

**테크이노베이션** - 혁신적인 기술 솔루션으로 미래를 만들어갑니다.