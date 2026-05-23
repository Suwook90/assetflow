# 파일정리함 (AssetFlow)

파일정리함은 로컬 PC의 파일, 이미지, 문서를 빠르게 확인하고 정리하는 Windows용 데스크톱 도구입니다.

`파일정리함`은 사용자에게 보이는 한글 제품명이고, `AssetFlow`는 다운로드 파일명과 GitHub URL에 남겨 둔 영문 코드명입니다.

> Source code is managed privately. This public repository is for product information, screenshots, license notices, and Windows installer downloads.

## 다운로드

[Windows 설치 파일 다운로드](https://github.com/Suwook90/assetflow/releases/download/v1.1.1/AssetFlowSetup.exe)

최신 릴리스 페이지:
https://github.com/Suwook90/assetflow/releases/latest

현재 공개 버전:
https://github.com/Suwook90/assetflow/releases/tag/v1.1.1

## 주요 기능

- 파일 뷰어/이동, 이름/확장자 변경, 이미지 용량 압축, 이미지 해상도 변경, AI 업스케일링, 문서 변경, 로컬 AI 도우미
- 왼쪽 폴더 목록, 중앙 미리보기/결과 그리드, 오른쪽 대상 폴더 및 AI 에이전트 패널
- 다중 선택, 드래그 선택, `Del`, `F2`, 우클릭 메뉴, `Ctrl+휠` 아이콘 크기 조정
- JPG, PNG, WebP, HDR/HDRI, EXR, TXT, JSON, MD, CSV 등 다양한 파일 확인
- EXR depth map 흑백 미리보기, 큰 폴더 순차 로딩, 보이는 썸네일 우선 로딩
- 이름/확장자 변경 규칙, 압축 용량 기준, 해상도 프리셋, 출력 폴더 저장/덮어쓰기
- AI 업스케일링: Real-ESRGAN 기본 모델, 1K/2K/4K 제한, Sharp 후처리, ncnn/ONNX 지원 모델 설치
- 업스케일 `선택 사용` 탭에서 설치 모델 before/after 미리보기, `모델 찾기` 탭에서 지원 모델 검색/설치
- 문서 변경 모드에서 개별 편집/저장, 단어 일괄 변경/삭제, `.bak` 백업
- 선택형 AI Pack: 로컬 AI 에이전트가 모드별 작업 계획과 명령 적용을 보조

## 화면 미리보기

| 모드 선택 | 파일 뷰어/이동 |
| --- | --- |
| ![모드 선택 화면](docs/screenshots/01-launcher.png) | ![파일 뷰어와 이동 대상 패널](docs/screenshots/02-viewer.png) |

| 이름/확장자 변경 | 이미지 용량 압축 |
| --- | --- |
| ![이름과 확장자 일괄 변경](docs/screenshots/03-rename.png) | ![이미지 용량 압축](docs/screenshots/04-compress.png) |

| 이미지 해상도 변경 | AI 업스케일링 모델 선택 |
| --- | --- |
| ![이미지 해상도 변경](docs/screenshots/05-resize.png) | ![AI 업스케일링과 설치 모델 선택](docs/screenshots/06-upscale.png) |

| 업스케일 모델 찾기 | 문서 변경/AI 문서 에이전트 |
| --- | --- |
| ![OpenModelDB 기반 업스케일 모델 찾기](docs/screenshots/09-upscale-model-search.png) | ![문서 미리보기와 AI 문서 에이전트](docs/screenshots/07-document.png) |

| AI 도우미 |
| --- |
| ![로컬 AI 도우미](docs/screenshots/08-ai-agent.png) |

## 설치 안내

1. [AssetFlowSetup.exe](https://github.com/Suwook90/assetflow/releases/download/v1.1.1/AssetFlowSetup.exe)를 다운로드합니다.
2. 설치 파일을 실행합니다.
3. Windows SmartScreen 경고가 뜨면 `추가 정보` 후 실행을 선택합니다.
4. 시작 메뉴 또는 바탕화면의 `파일정리함` 바로가기로 실행합니다.

현재 설치 파일은 코드 서명 인증서로 서명되지 않았기 때문에 Windows SmartScreen 경고가 표시될 수 있습니다.

## 저장소 구성

- `Suwook90/assetflow`: 공개 다운로드/소개용 저장소입니다. 소스코드는 포함하지 않습니다.
- `Suwook90/assetflow-private`: 비공개 소스/빌드 작업용 저장소입니다.

## 라이선스

Copyright (c) 2026 Suwook90.

파일정리함(AssetFlow)은 [PolyForm Noncommercial License 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0/)으로 배포됩니다.

- 개인, 교육, 연구, 비영리 목적의 사용을 허용합니다.
- 상업적 사용은 허용하지 않으며, 상업적 사용이 필요하면 저작권자에게 별도 허가를 받아야 합니다.
- 재배포할 때는 `LICENSE`와 `NOTICE`를 함께 포함해 주세요.

SPDX-License-Identifier: `PolyForm-Noncommercial-1.0.0`
