예상 디렉토리 구조

jia-app/ (Monorepo)
├── apps/
│   ├── jia-web/          # Next.js (프론트엔드)
│   ├── jia-admin/        # 관리자 대시보드 (React)
│   ├── jia-main-api/     # 메인 백엔드 (Nest.js / Spring Boot)
│   └── jia-ai-worker/    # K8s 감시 및 AI 처리 서버
├── libs/
│   ├── shared-types/     # 프론트와 백엔드가 같이 쓰는 타입/DTO
│   ├── ui-components/    # 프론트엔드 공통 UI 컴포넌트
│   └── common-utils/     # 공통 유틸리티 함수
├── package.json
└── turborepo.json        # 빌드 최적화 설정
