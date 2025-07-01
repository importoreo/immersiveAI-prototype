# Immersive AI App

모던하고 반응형인 AI 경험 생성 플랫폼의 React 애플리케이션입니다.

## 🚀 주요 기능

- **홈 피드**: 추천 경험들과 트렌딩 콘텐츠
- **경험 생성**: Visual Story, Interactive World, AI Character 생성
- **발견**: 다양한 경험 탐색 및 검색
- **채팅**: 개인 메시지 및 커뮤니티 채팅
- **프로필**: 사용자 프로필 및 경험 관리

## 🛠 기술 스택

- **React 18** - 최신 React 기능 활용
- **TypeScript** - 타입 안전성 보장
- **Tailwind CSS** - 유틸리티 퍼스트 CSS 프레임워크
- **Lucide React** - 모던 아이콘 라이브러리
- **Vite** - 빠른 개발 서버 및 빌드 도구

## 📱 주요 개선사항

### 1. 성능 최적화
- `useMemo`와 `useCallback`을 활용한 불필요한 리렌더링 방지
- 컴포넌트 분리로 재사용성 향상
- 이미지 최적화 및 지연 로딩

### 2. 접근성 개선
- ARIA 라벨 및 역할 추가
- 키보드 네비게이션 지원
- 스크린 리더 호환성

### 3. 타입 안전성
- 엄격한 TypeScript 타입 정의
- 인터페이스 기반 컴포넌트 설계
- 유틸리티 타입 활용

### 4. 사용자 경험
- 부드러운 애니메이션 및 전환 효과
- 반응형 디자인
- 직관적인 네비게이션

## 🏗 프로젝트 구조

```
src/
├── components/          # 재사용 가능한 컴포넌트
│   ├── common/         # 공통 컴포넌트 (Button, Modal, Icon 등)
│   ├── experience/     # 경험 관련 컴포넌트
│   ├── icons/          # 커스텀 아이콘
│   └── navigation/     # 네비게이션 컴포넌트
├── pages/              # 페이지 컴포넌트
├── types/              # TypeScript 타입 정의
├── utils/              # 유틸리티 함수
├── data/               # Mock 데이터
└── styles/             # 스타일 파일
```

## 🚀 시작하기

### 필수 요구사항
- Node.js 16.0 이상
- npm 또는 yarn

### 설치 및 실행

```bash
# 의존성 설치
npm install

# 개발 서버 실행
npm start

# 프로덕션 빌드
npm run build

# 테스트 실행
npm test
```

## 🎨 디자인 시스템

### 색상 팔레트
- **Primary**: Blue-Purple 그라디언트
- **Secondary**: Pink-Red 그라디언트
- **Accent**: Cyan-Blue 그라디언트
- **Background**: 다크 그라디언트

### 컴포넌트
- **Button**: Primary, Secondary, Ghost 변형
- **Modal**: 다양한 크기와 스타일
- **Card**: 호버 효과와 그라디언트 배경
- **Icon**: 커스텀 SVG 아이콘

## 📱 반응형 디자인

- **모바일 우선**: 393px 너비 기준
- **태블릿**: 768px 이상 지원
- **데스크톱**: 1024px 이상 지원

## 🔧 개발 가이드라인

### 코드 스타일
- TypeScript 엄격 모드 사용
- 함수형 컴포넌트와 Hooks 활용
- 의미있는 변수명과 함수명
- 주석과 문서화

### 컴포넌트 설계
- 단일 책임 원칙
- Props 인터페이스 정의
- 재사용 가능한 구조
- 접근성 고려

### 상태 관리
- 로컬 상태는 useState
- 복잡한 상태는 useReducer
- 전역 상태는 Context API

## 🧪 테스트

```bash
# 단위 테스트
npm test

# 커버리지 리포트
npm test -- --coverage

# E2E 테스트 (추후 추가 예정)
npm run test:e2e
```

## 📦 배포

```bash
# 프로덕션 빌드
npm run build

# 정적 파일 서빙
npm run serve
```

## 🤝 기여하기

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 🙏 감사의 말

- [React](https://reactjs.org/) - 훌륭한 UI 라이브러리
- [Tailwind CSS](https://tailwindcss.com/) - 유틸리티 퍼스트 CSS
- [Lucide](https://lucide.dev/) - 아름다운 아이콘
- [TypeScript](https://www.typescriptlang.org/) - 타입 안전성

---

**개발자**: Senior Front-End Developer  
**버전**: 1.0.0  
**최종 업데이트**: 2024년 1월
