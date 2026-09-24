# Keyboard Test

키보드 입력을 시각적으로 확인할 수 있는 웹 기반 테스트 프로그램입니다.

## 기능

- **클릭 & 키 입력** — 마우스 클릭 또는 실제 키보드 입력 시 해당 키가 즉시 강조 표시
- **입력 로그** — 최근 누른 키를 상단 스트립에 순서대로 기록 (최대 20개)
- **Modifier 뱃지** — Shift / Ctrl / Alt / Meta / CapsLock 상태를 실시간 표시
- **심플한 디자인** — 흰색 기반의 깔끔한 UI

## 실행 방법

별도 설치 없이 브라우저에서 바로 실행할 수 있습니다.

```bash
open keyboard-test.html
```

또는 로컬 서버로 실행:

```bash
python3 -m http.server 8080
# http://localhost:8080/keyboard-test.html
```

## 기술 스택

- HTML / CSS / JavaScript (순수 바닐라, 의존성 없음)
