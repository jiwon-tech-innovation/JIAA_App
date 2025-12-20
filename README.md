예상 디렉토리 구조

```
JIAA_Project/                # 프로젝트 최상위 폴더
├── client_flutter/              # [Flutter] 데스크톱 애플리케이션
│   ├── lib/                     # Dart 소스 코드
│   ├── macos/                   # macOS 네이티브 코드 (Swift/Live2D SDK)
│   ├── windows/                 # Windows 네이티브 코드 (C++/Win32 API)
│   └── assets/                  # Live2D 모델 및 이미지 리소스
├── server_spring/               # [Spring Boot] 메인 백엔드 서버
│   ├── src/                     # Java 소스 코드
│   ├── build.gradle             # 빌드 설정
│   └── Dockerfile               # 스프링 서버 이미지 빌드 파일
├── server_fastapi/              # [FastAPI] AI/음성 처리 서버
│   ├── app/                     # Python 소스 코드 (Whisper, TTS 로직)
│   ├── requirements.txt         # 파이썬 라이브러리 목록
│   └── Dockerfile               # AI 서버 이미지 빌드 파일
└── README.md                    # 프로젝트 문서 및 기획서
```
