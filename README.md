# Git Graph VS Code Extension Fork

이 저장소는 [원본 Git Graph 소스](https://github.com/mhutchie/vscode-git-graph)를 기반으로 한 개인 포크입니다.

## Fork Changes

### 1.30.3 - 2026-10-29

* 커밋 상세 화면(Commit Details View) 높이가 낮을 때 우측 컨트롤 바의 아이콘(변경 파일 목록 복사 등)이 잘리지 않도록 최소 높이 및 스크롤 처리를 개선했습니다.
* 변경 파일 목록 복사 시 파일 정렬 순서가 화면의 파일 트리/리스트 정렬 순서와 일치하도록 개선했습니다.
* 웹뷰 번들 패키징 스크립트의 비동기 경쟁 조건 및 OS별 줄바꿈 처리 문제를 수정하고, ESLint 줄바꿈 강제 규칙을 완화했습니다.
* CI 아티팩트 업로드 및 GitHub Release 자동화 워크플로를 정비했습니다.

### 1.30.2 - 2026-09-11

* 파일 변경 watcher가 삭제된 일반 파일 경로를 저장소 삭제 경로로 오인하지 않도록 수정했습니다.
* 확장 활성화 후 파일을 열거나 변경할 때 `파일경로/파일명.git` 형태의 잘못된 Git 경로를 계속 찾다가 콘솔 오류가 발생할 수 있던 문제를 방지했습니다.
* 위 동작을 검증하는 `RepoManager` 회귀 테스트를 추가했습니다.

### 1.30.1 - 2026-09-11

* 커밋 상세 화면에 변경된 파일 목록을 클립보드로 복사하는 `Copy Changed File List to Clipboard` 기능을 추가했습니다.
* 내부 빌드 툴체인(TypeScript, ESLint, Jest)을 최신 버전으로 업그레이드했습니다.
* GitHub 아바타 URL을 잘못 조합하던 잠재적 버그를 수정했습니다.

## Original Source

원본 프로젝트의 전체 기능 설명, 사용법, 설정 문서는 아래 링크에서 확인할 수 있습니다.

* [mhutchie/vscode-git-graph](https://github.com/mhutchie/vscode-git-graph)
