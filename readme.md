# Streamlit 간단한 계산기 (Simple Calculator)

Streamlit을 활용하여 두 정수와 연산자를 입력받아 결과를 출력하는 직관적이고 단순한 웹 기반 계산기 애플리케이션입니다.

---

## 📌 주요 기능
- **직관적인 UI**: 정수 및 연산자를 각 줄별로 입력받는 간단한 웹 인터페이스
- **사칙연산 지원**: `+`, `-`, `*`, `/` 연산 처리
- **예외 처리 및 에러 메시지 지원**:
  - 정수가 아닌 값 입력 시 안내 메시지 출력 (`ValueError` 처리)
  - 지원하지 않는 연산자 입력 시 오류 메시지 출력
  - `0`으로 나누기 예외 처리

---

## 🛠️ 설치 및 실행 방법

### 1. 레포지토리 클론 또는 파일 다운로드
프로젝트 파일을 준비합니다.

### 2. 가상환경 생성 및 활성화 (선택)
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS / Linux
python -m venv venv
source venv/bin/activate
```

### 3. 의존성 패키지 설치
`requirements.txt`에 기록된 패키지를 설치합니다.
```bash
pip install -r requirements.txt
```

### 4. Streamlit 앱 실행
```bash
streamlit run app.py
```
> **참고**: 실행 후 브라우저가 자동으로 열리며 `http://localhost:8501`에서 앱을 확인할 수 있습니다.

---

## 📁 프로젝트 구조
```text
.
├── app.py           # Streamlit 메인 계산기 코드
├── requirements.txt # 의존성 패키지 목록
└── README.md        # 프로젝트 설명 문서
```