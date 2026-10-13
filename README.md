# BreakDown Beta

> **“‘이거 해줘’를, 누가 무엇을 언제 할지로 바꿉니다.”**

BreakDown(중간관리자)의 **Windows x64 공개 베타 배포 전용 저장소**입니다.

이 저장소에는 소스코드를 공개하지 않습니다. 실제 제품 소스는 별도의 private repository에서 관리하며, 여기에는 공개 베타 다운로드와 릴리스 정보만 제공합니다.

## Current beta

## 공개 다운로드

- Release: https://github.com/zsefv945-commits/breakdown-beta-releases/releases/tag/v0.1.0-beta.1
- Windows ZIP: https://github.com/zsefv945-commits/breakdown-beta-releases/releases/download/v0.1.0-beta.1/BreakDown_BETA_001.zip
- SHA-256: `a7106eb8a141a7af16c6084ee3424b7935b88c08a55428c7828679f6842973c6`


- Version: `v0.1.0-beta.1`
- Platform: Windows x64
- Distribution: portable ZIP
- Cloud AI: **OFF**
- External task execution: **없음**
- Installer: 없음
- Code signing: 없음

## 사용 방법

1. `BreakDown_BETA_001.zip`을 다운로드합니다.
2. 새 폴더에 압축을 풉니다.
3. 루트의 `START_BETA.bat`를 더블클릭합니다.
4. 브라우저에서 `http://127.0.0.1:3000`이 열립니다.
5. 처음이면 회원가입 후 워크스페이스/회사 맥락을 설정합니다.
6. 모호한 업무지시를 입력합니다.
7. UNKNOWN 항목이 있으면 실제 값을 확인해 수정합니다.
8. 최종 결과를 확정합니다.

첫 사용은 실제 회사 기밀 대신 **합성 또는 비식별 데이터** 사용을 권장합니다.

## 현재 제한사항

- Windows x64 전용
- 정식 installer 아님
- 코드 서명 없음
- 자동 업데이트 없음
- Mac/Linux/모바일 미지원
- Cloud AI는 비활성화 상태로 배포
- 외부 Slack/Notion/Trello/Kakao/이메일 등을 자동 실행하지 않음
- 베타 단계이므로 사용성·제품가치는 계속 검증 중

## 무결성 확인

공개 ZIP의 SHA-256은 `SHA256SUMS.txt`와 Release 설명에 함께 제공합니다.

현재 승인된 release candidate SHA-256:

`a7106eb8a141a7af16c6084ee3424b7935b88c08a55428c7828679f6842973c6`

## 개인정보 / 회사정보

이 베타는 로컬 `127.0.0.1`에 바인딩되며, Cloud AI는 기본적으로 꺼져 있습니다.

초기 공개 베타에서는 실제 회사 기밀정보 대신 합성/비식별 데이터를 사용해 주세요.

## 피드백

실행 실패, 저장/복원 문제, UNKNOWN 처리 문제, 사용성 불편 및 기능 요청은 이 저장소의 Issues에 남겨 주세요.

---

**BreakDown Beta는 정식 상용제품이 아닙니다.**
