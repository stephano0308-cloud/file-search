# file-search 업로드 안내

이 저장소에는 `Docufinder-main(2).zip` 파일이 업로드되어 있습니다.

## 실행 방법

### 1) ZIP 다운로드 후 압축 해제
- GitHub에서 `Docufinder-main(2).zip` 파일을 다운로드
- 압축 해제 후 프로젝트 루트로 이동

### 2) 개발 실행
```bash
pnpm install
pnpm tauri:dev
```

### 3) 프론트엔드만 실행
```bash
pnpm install
pnpm dev
```

### 4) 배포 빌드
```bash
pnpm install
pnpm tauri:build
```

## 요구 사항
- Windows 10/11
- Node.js 22 LTS
- pnpm 10
- Rust 1.92+
- Visual Studio Build Tools 2022

## package.json 기준 주요 스크립트
- `pnpm dev`
- `pnpm tauri:dev`
- `pnpm tauri:build`
- `pnpm run download-model`
- `pnpm run download-vcredist`
- `pnpm run bundle-kordoc`
