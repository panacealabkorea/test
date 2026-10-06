# Holo AI Camera CMD 사용자 매뉴얼 제작 자료

이 폴더는 전체 개발 프로젝트를 전달하지 않고도 제3자 또는 다른 Agent가 사용자 매뉴얼을 제작할 수 있도록 구성한 전달 패키지다.

## 먼저 읽을 문서

1. `CONTEXT_MEMORY.md`: 현재 APK의 확정된 기능과 작업 이력
2. `USER_GUIDE_SOURCE.md`: 사용자 매뉴얼 본문으로 재가공할 수 있는 원고
3. `ASSET_INDEX.md`: 이미지와 참고 문서의 용도
4. `DOCUMENT_TASK_BRIEF.md`: 문서 제작자에게 전달할 작업 지시서

## 폴더 구성

- `assets/screenshots`: 실제 앱 화면 캡처
- `assets/reference`: 기존 HTML 설명서와 기능 참고 문서
- `release`: 최신 User Demo APK와 빌드 보고서

## 문서 제작 원칙

- 최신 사실은 `CONTEXT_MEMORY.md`를 우선한다.
- 기존 HTML의 오래된 내용은 그대로 복사하지 않는다.
- 현재 AI Camera 명령은 “문서를 읽어줘”, “화면을 설명해줘”이다.
- “영상을 분석해줘”는 현재 UI에서 삭제된 과거 명령이다.
- IMAGE AI 기본 선택은 Google API이다.
- 사용자에게 API 키, 내부 서버 주소, 개발 경로를 노출하지 않는다.
- AI 설명은 안전을 보장하는 기능이 아니며 보행·의료·비상 판단을 대체하지 않는다고 명시한다.

## 기준 릴리스

- 패키지: `com.aide.gtm.demo.holoaicameracmd.userdemo`
- 버전: `0.1.20261006_112808`
- 사용기한: 2026-10-31까지
- 대상 구성: Android 기기 + GTM300 USB-C 영상/카메라/오디오 장치

