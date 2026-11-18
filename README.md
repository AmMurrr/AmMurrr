<h1 align="center">Artem Muratov</h1>

<p align="center"><strong>Junior Python Backend Developer</strong> · Moscow</p>

<p align="center">I build Python backend projects. I'm especially interested in AI tools and how asynchronous services behave when something goes wrong.</p>

<p align="center">
  <a href="https://t.me/rlasarl"><img src="https://img.shields.io/badge/Telegram-246B92?style=for-the-badge&amp;logo=telegram&amp;logoColor=white" alt="Contact me on Telegram"></a>
  <a href="mailto:gribvsevid@gmail.com"><img src="https://img.shields.io/badge/Email-55428B?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Contact me by email"></a>
</p>

<p align="center"><em>Open to junior Python backend roles</em></p>

## Selected projects

### [Lost Items](https://github.com/AmMurrr/Lost_items) · Semantic search for metro lost property

A FastAPI service and Telegram bot that let users search for a lost item by description. PostgreSQL filters records by station and date, and pgvector ranks the matches using text embeddings from a local model.


### [Report CLI](https://github.com/AmMurrr/report_cli) · Extensible CSV reporting

A Python command-line tool that reads YouTube metrics from multiple CSV files and generates a report. It discovers new report types automatically, so adding one requires no changes to the CLI.


### [AutoDrill Research](https://github.com/AmMurrr/AutoDrillResearch) · Pronunciation assessment

My thesis project compares two ways to score pronunciation: MFCC features aligned with dynamic time warping, and wav2vec 2.0 embeddings. A Streamlit app lets users try both approaches.


## Contributions

- **[aio-pika #748](https://github.com/mosquito/aio-pika/pull/748)** · Proposed a fix for `connect()` and `reconnect()` calls that can hang when a RabbitMQ connection closes. Added regression tests. **Open**
- **[pydoclint #329](https://github.com/jsh9/pydoclint/pull/329)** · Proposed passing per-function state explicitly through docstring checks while preserving existing diagnostics. **Open**
- **[agreemod_v2 #70](https://github.com/Insomnia-IT/agreemod_v2/pull/70)** · Added configurable log rotation for the app and its workers, with settings passed through Docker Compose. **Merged**

## Stack

- **Backend** · Python, FastAPI, Django, asyncio, RabbitMQ, gRPC, 
- **Databases** · PostgreSQL, MongoDB, Redis,  Alembic, SQLAlchemy
- **Tooling** · pytest, Ruff, Docker, Git, uv, Linux
- **LLMs & Retrieval**: vLLM, Instructor, Docling, RAG, Qdrant, pgvector
