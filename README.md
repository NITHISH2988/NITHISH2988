# Hi, I'm Nithish

I'm a third-year B.Tech Computer Science student building practical experience in AI/ML engineering. I like understanding how training, evaluation, retrieval, and serving fit together—not just calling a model API.

## Interests

- Classical machine learning and experiment design
- Deep learning and computer vision with PyTorch
- NLP, transformer inference, and model serving
- Retrieval-augmented generation and local inference
- Reproducible Python systems, testing, and MLOps foundations

## Selected projects

I'm building these four projects to understand different parts of the ML stack. Their current implementations are in open **draft release-candidate PRs**, so they remain under review.

### [House Price Lab](https://github.com/NITHISH2988/house-price-lab)

I use this project to compare a mean baseline, Ridge, and Random Forest with preprocessing inside cross-validation pipelines. The recorded metrics come from deterministic synthetic data, not a real housing market.

- [Draft release candidate](https://github.com/NITHISH2988/house-price-lab/pull/1)
- Stack: Python, pandas, scikit-learn, FastAPI, pytest

### [Vision Bench](https://github.com/NITHISH2988/vision-bench)

I built an inspectable PyTorch training and evaluation path for a compact CNN and a randomly initialized ResNet-18. I haven't verified a full-dataset benchmark or CUDA run.

- [Draft release candidate](https://github.com/NITHISH2988/vision-bench/pull/1)
- Stack: Python, PyTorch, torchvision, scikit-learn metrics

### [Review Sentiment API](https://github.com/NITHISH2988/review-sentiment-api)

I compare a TF-IDF/logistic-regression baseline with optional pretrained transformer inference, then serve predictions through FastAPI. There's no bundled review corpus or claimed real-corpus score.

- [Draft release candidate](https://github.com/NITHISH2988/review-sentiment-api/pull/1)
- Stack: Python, scikit-learn, FastAPI, Hugging Face Transformers (optional)

### [StudyBuddy RAG](https://github.com/NITHISH2988/studybuddy-rag)

I'm exploring local document Q&A with dense retrieval, SQLite persistence, source records, retrieval metrics, and optional Ollama integration. Citations show which passages were retrieved; they don't prove every generated claim is supported.

- [Draft release candidate](https://github.com/NITHISH2988/studybuddy-rag/pull/1)
- Stack: Python, FastAPI, Sentence Transformers, NumPy, SQLite, Ollama (optional)

## Tools I've used across these projects

Python · JavaScript · HTML/CSS · SQL/SQLite · PyTorch · scikit-learn · FastAPI · pandas · NumPy · pytest · Ruff · GitHub Actions · Docker · Ollama

## Currently learning

I'm continuing to learn about model evaluation and data quality, PyTorch internals, retrieval evaluation, reliable model serving, and practical MLOps. I care about measured improvements and being clear about what an experiment does—and doesn't—show.
