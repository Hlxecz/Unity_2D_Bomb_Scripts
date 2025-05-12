# 💣 Unity 2D 폭탄 게임 - 핵심 스크립트 정리

이 저장소는 Unity 기반 2D 폭탄 게임 프로젝트에서 **직접 구현한 핵심 C# 스크립트 파일만 추출하여 정리한 포트폴리오용 저장소**입니다.

게임 로직의 구조화, 객체 제어 방식, 그리고 Unity 이벤트 흐름에 대한 이해를 보여주는 데 목적이 있습니다.

---

## 🧩 주요 스크립트 구성

| 파일명 | 주요 기능 |
|--------|-----------|
| `bombController.cs` | 폭탄의 생성, 타이머, 충돌 처리 |
| `coinController.cs` | 코인 획득 및 점수 증가 로직 |
| `SoundController.cs` | 효과음 재생 제어 |
| `BackgroundControl.cs` | 배경 이미지 이동 및 루프 처리 |
| `HPController.cs` | 체력 UI 표시 및 감소 처리 |
| `Display.cs` | 점수 및 상태 텍스트 표시 |
| `RobotController.cs` | 적 로봇 AI 및 이동 처리 |
| 그 외 다수 | 오브젝트 제어, 게임 이벤트 처리 등 |

> 📌 모든 스크립트는 **기능별로 분리된 구조**를 따르며,  
> Unity의 `MonoBehaviour` 생명주기 함수 (`Start()`, `Update()` 등)를 활용해 설계되었습니다.

---

## 🎯 개발 목적

- Unity 2D Physics 기반의 게임 구현 능력 표현
- 기능 단위로 나뉜 C# 스크립트 작성 역량 공유
- 포트폴리오용 깔끔한 코드만 정제하여 저장

---

## 📎 참고사항

- 본 저장소에는 `.cs` 스크립트 외 리소스/에셋/씬 파일은 포함되어 있지 않습니다.
- Unity **2022.3.13f1** 버전에서 개발 및 테스트되었습니다.
- 실제 게임 구현에서는 `Assets/` 내 여러 오브젝트들과 연동되어 동작합니다.

---

## 📨 Contact

- 📧 Email: azaz3769@gmail.com  
- 🐙 GitHub: [github.com/Hlxecz](https://github.com/Hlxecz)
