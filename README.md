# my-first-project

## 프로젝트 소개

`my-first-project`는 개발 워크플로우를 익히고 실험하기 위한 첫 번째 프로젝트입니다.
저장소 구조 잡기, 브랜치 전략, 커밋과 풀 리퀘스트 흐름 등 협업의 기본을 연습하는 것을 목표로 합니다.

주요 목표:

- 프로젝트 초기 설정과 문서화 연습
- Git 기반 협업 흐름(브랜치, 커밋, PR) 익히기
- 이후 기능을 점진적으로 추가할 수 있는 기반 마련

## 설치 방법

### 사전 요구 사항

- [Git](https://git-scm.com/) 2.30 이상
- 프로젝트에서 사용할 언어 런타임 (예: Node.js, Python 등 — 코드가 추가되면 이 항목을 갱신하세요)

### 저장소 클론

```bash
git clone https://github.com/blackmirror6170-pixel/my-first-project.git
cd my-first-project
```

### 의존성 설치

아직 코드가 추가되지 않아 설치할 의존성이 없습니다.
코드가 추가되면 사용하는 도구에 맞춰 아래와 같은 명령을 여기에 적어 주세요.

```bash
# 예시: Node.js 프로젝트인 경우
npm install

# 예시: Python 프로젝트인 경우
pip install -r requirements.txt
```

## 사용법

### 실행

프로젝트 코드가 추가되면 실행 명령을 여기에 정리합니다.

```bash
# 예시: Node.js 프로젝트인 경우
npm start

# 예시: Python 프로젝트인 경우
python main.py
```

### 개발 흐름

1. `main` 브랜치에서 작업용 브랜치를 만듭니다.

   ```bash
   git checkout -b feature/작업-이름
   ```

2. 변경 사항을 커밋합니다.

   ```bash
   git add .
   git commit -m "변경 내용을 설명하는 메시지"
   ```

3. 원격 저장소에 푸시하고 풀 리퀘스트를 엽니다.

   ```bash
   git push -u origin feature/작업-이름
   ```

## 라이선스

라이선스는 아직 정해지지 않았습니다. 필요에 따라 `LICENSE` 파일을 추가해 주세요.
