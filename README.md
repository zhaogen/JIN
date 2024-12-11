# 1942 Style Shooting Game

## 프로젝트 개요
"1942 Style Shooting Game"은 클래식 비행 슈팅 게임을 기반으로 한 Python으로 제작된 게임입니다. 플레이어는 적기를 피하고 총알로 격추하며 점수를 쌓고 라운드를 진행합니다. 최대 3라운드로 구성되며, 라운드를 진행할수록 난이도가 점차 상승합니다.
---

## 주요 기능

### 게임 플레이
- **플레이어 컨트롤:**
  - `W`, `A`, `S`, `D` 키를 사용하여 플레이어 비행기 이동.
  - 마우스 클릭으로 적을 조준하여 총알 발사.

- **적 스폰:**
  - 라운드에 따라 적의 속도와 생성 빈도 증가.

- **라운드 진행:**
  - 각 라운드에서 일정 점수를 획득하면 다음 라운드로 이동.
  - 라운드마다 플레이어의 총알 속도가 증가.

- **게임 종료:**
  - 플레이어가 적을 너무 많이 놓치면 게임 오버.
  - 모든 라운드를 완료하면 승리.

### UI 요소
- 시작 화면: "게임 시작" 버튼을 통해 게임을 시작할 수 있음.
- HUD 표시: 점수, 라운드 진행 상황, 놓친 적의 수.
- 게임 종료 화면: 게임 결과에 따라 메시지 표시.

---

## 설치 및 실행 방법

### 요구 사항
- Python 3.8 이상
- `pygame` 라이브러리 설치

### 설치 명령
```bash
pip install pygame
```

### 실행 방법
1. 이 저장소를 클론합니다.
   ```bash
   git clone <repository-url>
   ```
2. 프로젝트 디렉토리로 이동합니다.
   ```bash
   cd <repository-folder>
   ```
3. 게임을 실행합니다.
   ```bash
   python main.py
   ```

---

## 게임 스크린샷
![image](https://github.com/user-attachments/assets/0bf21477-2f6b-4199-995e-13052590eb11)


---

## 파일 구조
```
project-folder/
│
├── main.py           # 게임 메인 코드
├── README.md         # 프로젝트 설명
└── LICENSE           # 라이선스 정보
```

---

## 참고자료/Reference
- 본 프로젝트는 [Pygame 공식 문서](https://www.pygame.org/docs/)를 참고하여 제작되었습니다.

---

## 라이선스
이 프로젝트는 [MIT 라이선스](./LICENSE)를 따릅니다. 자세한 내용은 LICENSE 파일을 참조하세요.

---


