# 👋 안녕하세요, AI 엔지니어 장효성입니다.

현재 AI 모델의 효율적인 서빙과 최적화, 그리고 RAG 기술을 활용한 지식 기반 시스템 구축에 깊은 관심을 가지고 공부하고 있는 취업 준비생입니다. 단순한 모델 개발을 넘어, 시스템 전체의 파이프라인을 설계하고 문제를 해결하는 과정에서 즐거움을 느낍니다.

---

### 🛠 Tech Stacks

| Category | Technologies |
| :--- | :--- |
| **AI & ML** | `LLM`,`RAG`|
| **language** | `Python`|
| **Tools** | `Git`, `LangGraph`, `Langfuse` , 'LangChain' , 'LlamaIndex'  |

---

### 🚀 Featured Projects

#### 1️⃣ [Boostcamp AI Tech] Open-Domain Question Answering
* **Description:** 한국어 MRC(Machine Reading Comprehension) 대회 환경에서 형태소 분석기(Kiwi), 개체명 인식(GLiNER), 지식 그래프(유의어 확장)를 결합한 Hybrid Retrieval과 추출 모델 및 생성 모델을 조합한 Compound AI Reader 시스템을 구축하여 정답 추출 성능(EM)을 극대화함.
* **Key Achievements:** * 
    * Retrieval : 97.5% (Top-5 Recall), 98.75% (Top-10 Recall)
    * Result : 71.11 % (EM) 81.68% (F1 Score)
* **Link:** [https://github.com/boostcampaitech8/pro-nlp-mrc-nlp-05/tree/develop]

#### 2️⃣ [Boostcamp AI Tech] 수능형 문제 풀이 Agent RAG
* **Description:** 수능형(지문·문항·선지 기반) 객관식 문제에서 외부 지식 필요 여부를 판별하고, 필요 시 Wikipedia API 기반 web 검색&reranking을 통해 근거를 수집하여 정답 선택의 일관성과 정확도를 향상시키는 Agent 파이프라인 설계
* **Key Achievements:**
    * LangGraph 기반 라우터 RAG 설계
    * Accuracy : 80.68 % -> 82.20 %
* **Link:** [https://github.com/boostcampaitech8/pro-nlp-generationfornlp-nlp-05/tree/feature/ver-1/src_ver1/web_wiki]

#### 3️⃣ [Personal Project] Korean Domain-Specific Reranker PEFT
* **Description:** AI-Hub 금융/법률 데이터를 활용하여 한국어에 특화된 Reranker 모델을 PEFT(LoRA) 기법으로 파인튜닝. 하드 네거티브 마이닝과 오답 사례 집중 보강을 통해 검색 정확도를 극대화함.
* **Key Achievements:**
    * Hit@1 Accuracy: 0.90 -> 0.96 (6%p 상승)
    * Fast Vector Search 기반 하드 네거티브 채굴 및 효율적인 증분 학습 파이프라인 구축
* **Link:** [https://github.com/hyos0415/reranker-peft-project]

#### 4️⃣ 뉴스 아레나(News Arena): 지능형 뉴스 RAG & PGI 파이프라인
* **Description:** 뉴스 RSS 수집부터 하이브리드 검색(Elasticsearch + ChromaDB), Neo4j 기반 지식 그래프 분석까지 결합된 엔드투엔드 뉴스 지능 엔진
* **Tech:** Apache Airflow, PostgreSQL, Elasticsearch, ChromaDB, Neo4j, LlamaIndex, LangChain
* **Focus:**
- **엔드투엔드 파이프라인 자동화**: Airflow를 활용하여 수집, 정제, 메타데이터 추출, 하이브리드 스토어 동기화 자동화 구축
- **하이브리드 RAG (RRF)**: BM25와 Dense Vector 검색을 RRF 알고리즘으로 결합하여 **Context Precision 1.0** 달성
- **지식 그래프 엔진**: PGI(Property Graph Index)를 활용한 **육각형 분석 2.0 (Hexagonal Metrics)** 지표 산출 기술 구현
- **팩트체크 시나리오**: 사용자 기사 초안을 기존 지식 베이스와 격리 대조하여 사실 모순(Contradiction) 및 신규 지식 탐지
- **Link :** [https://github.com/hyos0415/KAG_LlamaIndex]
---

### ✍️ Recent Interests & Learning
"단순한 명령 수행을 넘어, 자율적으로 문제를 분해하고 루프를 돌며 최적의 해를 찾는 'AI Agent' 구축에 집중합니다."

* **🔄 Recursive Language Models**: 복잡한 태스크를 하위 단위로 재귀적으로 분해하고, 자기 피드백을 통해 결과물을 정제하는 에이전트 워크플로우 설계

* **🧠 Graph RAG**: 비정형 데이터 간의 관계를 구조화하여, 에이전트가 단편적인 검색을 넘어 논리적 맥락을 파악할 수 있는 지식 베이스 구축

* **🏗️ Data Pipeline for Agents**: 에이전트가 실시간 정보를 지속적으로 학습하고 활용할 수 있도록 RSS, Web Scraping 기반의 자동화된 데이터 파이프라인(ETL) 최적화

* **🛠️ Agentic Workflow**: 유연한 도구 호출(Tool use)과 오류 자가 수정(Self-correction) 메커니즘을 통한 신뢰성 높은 자율 에이전트 아키텍처 연구

---

### 📫 Contact Me
* **Email:** [jhsyo768@gmail.com]

---

<!--
**hyos0415/hyos0415** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
