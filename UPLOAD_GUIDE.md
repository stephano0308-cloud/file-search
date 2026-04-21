# file-search 저장소 업로드 메모

업로드 파일: `Docufinder-main(2).zip`

## 실행 방법
### 1) 개발 실행
```bash
pnpm install
pnpm tauri:dev
```

### 2) 프론트엔드만 실행
```bash
pnpm install
pnpm dev
```

### 3) 배포 빌드
```bash
pnpm install
pnpm tauri:build
```

## 요구사항
- Windows 10/11
- Node.js 22 LTS
- pnpm 10
- Rust 1.92+
- Visual Studio Build Tools 2022

## package.json 기준 주요 스크립트
- `dev`: Vite 개발 서버
- `tauri:dev`: Tauri 개발 모드
- `download-model`: ONNX 모델 다운로드
- `download-vcredist`: VC++ 런타임 다운로드
- `bundle-kordoc`: HWP 파서 번들
- `tauri:build`: 모델/런타임 다운로드 후 MSI 빌드
