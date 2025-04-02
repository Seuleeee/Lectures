# Building an AI-Powered Blog Writing Assistant with RAG

이 강의에서는 RAG(Retrieval-Augmented Generation) 기술을 활용하여 AI 기반 블로그 작성 도우미를 개발하는 방법을 배웁니다. 최신 Python 개발 도구와 AI 기술을 결합하여 실용적인 애플리케이션을 만들어보세요.

## 🎯 학습 목표

- RAG 시스템의 기본 개념과 구현 방법 이해
- UV를 활용한 현대적인 Python 개발 환경 구축
- LangChain과 FAISS를 사용한 기본적인 RAG 시스템 구현
- 웹 크롤링을 통한 데이터 수집 및 전처리
- 임베딩과 검색 시스템 구축
- Streamlit을 활용한 사용자 인터페이스 개발
- 고급 주제: 로컬 LLM과 벡터 데이터베이스 활용

## 📚 커리큘럼

### 0. 개발 환경 설정
- UV: Rust로 작성된 초고속 Python 패키지 관리자
- 프로젝트 구조 설정 및 의존성 관리

### 1. RAG 기초
- LangChain과 VectorDB(ChromaDB)를 활용한 기본 RAG 시스템 구축
- LLM 통합 및 기본 프롬프트 작성

### 2. 데이터 수집 및 처리
- 웹 크롤링을 통한 데이터 수집
- 데이터 전처리 및 정제

### 3. RAG 시스템 구현
- 데이터 임베딩 생성
- 검색 시스템 구축
- 프롬프트 엔지니어링
- 블로그 글 자동 생성

### 4. 사용자 인터페이스
- Streamlit을 활용한 웹 인터페이스 개발
- 사용자 경험 최적화

### 5. 고급 주제
- Ollama를 활용한 로컬 LLM 구현
- Milvus 벡터 데이터베이스 활용
- Docker를 통한 애플리케이션 컨테이너화

## 🛠 기술 스택

- Python 3.12+
- UV (패키지 관리자)
- LangChain
- ChromaDB
- Sentence Transformers
- Streamlit
- Docker
- Ollama
- Milvus

## 🚀 시작하기

1. 저장소 클론
```bash
git clone [repository-url]
cd Tutorials/RAG
```

2. 개발 환경 설정
```bash
pip install uv
uv venv .venv
source .venv/bin/activate
```

3. Package 설치
```bash
uv lock
uv sync
```

## 📝 프로젝트 구조

```
RAG/
├── pyproject.toml      # 프로젝트 설정 및 의존성
├── src/               # 소스 코드
└── README.md          # 프로젝트 문서
```

## 🤝 Contact

- E-Mail : bryantjo1224@gmail.com
- LinkedIn : https://www.linkedin.com/in/hanseul-jo-446528301/

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요. 