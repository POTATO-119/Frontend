# Frontend

React + Vite + TypeScript 팀 협업 프로젝트

## 기술 스택

- React 18 + TypeScript
- Vite
- ESLint + Prettier + Husky

## 시작하기

```bash
# 1. 의존성 설치
npm install

# 2. 환경변수 설정
cp .env.example .env.local
# .env.local 파일을 열어 실제 값 입력

# 3. 개발 서버 실행
npm run dev
```

## 브랜치 전략

```
main        ← 배포용 (항상 안정)
develop     ← 통합 개발 브랜치
  feature/* ← 기능 개발
  fix/*     ← 버그 수정
  chore/*   ← 설정/의존성
```

## 커밋 컨벤션

```
feat(scope): 새로운 기능
fix(scope): 버그 수정
chore(scope): 설정 변경
style(scope): 스타일 수정
refactor(scope): 리팩토링
docs(scope): 문서 수정
test(scope): 테스트
```

## 스크립트

| 명령어 | 설명 |
|--------|------|
| `npm run dev` | 개발 서버 실행 |
| `npm run build` | 프로덕션 빌드 |
| `npm run lint` | ESLint 검사 |
| `npm run lint:fix` | ESLint 자동 수정 |
| `npm run format` | Prettier 포맷 적용 |

## 환경변수

`.env.example` 참고. 실제 키는 `.env.local`에 입력 (절대 커밋 금지).
